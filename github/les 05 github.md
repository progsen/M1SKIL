## github oefeningen


## account maken

heb je nog geen account? doe dan deze stappen:

- ga naar https://github.com
- click op sign up
- vul je voornaam of alias in
- gebruik je Ma email adres

- kies voor de free version
- je hoeft verder niets aan te vinken, click gewoon op doorgaan

## repository maken


- log in op github, nu zie je ongeveer:

![githubmain.png](githubmain.png)

- click op de `new` knop

![new](new.png)

- nu zie je de `create repository` pagina

![repo](repo.png)

* vul als repository naam `les_github` in
* zet `public` aan
* vink `add a readme file` aan

- click nu op `create repository`


## naar je PC/Laptop halen

Dit doen we met `git clone`

Daarvoor hebben we de `url` van de repository nodig:
- click op de groene knop `code`
- kopieer de link die je dan ziet staan 
    * ziet er ongeveer zo uit: https://github.com/YOURNAME/REPONAME.git

![repolink](repolink.png)

- ga nu naar je school map van dit vak
- open een `cmd` in die map
- type `git clone ` en plak daar de repository link achter
- druk op `enter`

* je krijgt nu een nieuwe map, die dezelfde naam heeft als jou repository

## File aanpassen

- open de `README.md` file die in de nieuwe map staat 
- voeg text toe: `github leren kennen`
- sla de file op
- Maak nu een `commit` met git (add, commit -m ..)
* vergeet niet met `git status` tussentijds te controlleren

## Lokaal.. en nu?

nu moeten we naar onze github pushen.

laten we dat proberen:
- type `git push` (in je directory met de readme.md file op jou pc)

* Nu krijg je een `login` scherm

![signin](signin.png)

## token settings page

we hebben een token nodig:

- ga naar je github in je browser.
- click op je account icoon
- click op settings

![settings.png](settings.png)

- links staat een menu, click op `developer settings`

![devset](devset.png)


- click op `personal access tokens`
- click nu op `tokens (classic)`

![token.png](token.png)

- click nu op generate token

- click op generate classic token
![classic.png](classic.png)


## token maken

nu kunnen we een token gaan maken:

- vul een naam voor het token in bv (`pushing`)
- Zet de `expiration` op `no expiration` voor nu
- vink de `repo` aan

![newtoken.png](newtoken.png)

- als dat goedstaat kan je op `generate token` clicken `onderaan` de pagina

- `LET OP!!!` je krijgt nu je token te zien. Dit is 1 keer!
- sla het token op, bijvoorbeeld in een `wachtwoord manager`

![1time.png](1time.png)

## EINDELIJK!

nu kunnen we inloggen en pushen:

![login.png](login.png)

- click op token
- plak je token 
- click op sign in

* zie je dat je `push` nu doorgaat?
- controleer het in je `repository` op `github`
- daar zie je nu 2 commits

## Andere studenten

- clone nu de repository van een andere student naar je pc toe
- maak een aanpassing in de `readme.md`
- wat gebeurt er nu?

* dit klopt!

## inleveren

lever nu je github account link in in de assignment die je gekregen hebt


## Extra leesvoer:

### Github Docs
https://docs.github.com/en

### Personal Acces Tokens
https://en.wikipedia.org/wiki/Personal_access_token

### Github acces tokens:
https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token
