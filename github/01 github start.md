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
