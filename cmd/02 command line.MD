## commandline


open een commandline/terminal


## waar zit ik?

Kijk even goed in welke directory je nu zit in de commandline
- kijk naar wat er voor de `>` staat

* dit is belangrijk, als je verkeerd zit kan je fouten maken!

- kijk met `dir (windows) / ls (mac)` wat er in de huidige `current working directory` zit

## navigeren

- kijk waar je nu bent, onthoudt of schrijf dit op
- gebruik nu het `cd ..` commando om 1 directory richting de root te gaan
- ga nu weer terug naar de eerste directory

## navigeren

- gebruik het `cd /` commando 
* (cd=changedirectory spatie /=ga_naar_root)
- waar ben je nu?
* c:\? (windows) \? (mac/linux)
* dat is de root

## directory maken

we gaan nu een directory maken. Dat moet wel op een goede plek.
Niet op de root.

- ga terug naar jouw `home`/`gebruiker` directory. gebruik `cd`
- lukt dat niet? start een nieuwe commandprompt (laat de andere even open om straks te laten zien). 
* controlleer of je nu goed zit
```
mkdir
```

- type nu `mkdir newDirectory` in
- gebruik `dir/ls` om te kijken of je de nieuwe directory ziet
- ga nu die directory in met `cd`

## directory verwijderen

- we zitten nu in newDirectory (check dat!)
- is die leeg? (`dir`)
- mooi! ga 1 directory richting de root (`cd ..`)

om een directory weg te gooien met `rmdir` moet die leeg zijn.

- type rmdir `newDirectory`
* het kan dat het systeem vraagt of je het zeker wil doen, kies Ja/Yes
- gelukt? check het met `dir/ls`


## directory met files

- maak een nieuwe directory met de naam `volMetFiles`
- ga `volMetFiles` in met `cd`
- maak een nieuwe file aan:
* windows `notepad test.txt`
* mac `touch test.txt`
- check het met `dir/ls`


## nu weggooien

- ga 1 directory richting de root (`cd ..`)
- type rmdir `volMetFiles`
* werkt dat?
- nee! gebruik nu het commando:
* windows `rmdir /s volMetFiles`
* mac `rm -r volMetFiles`
- nu wel gelukt? check het met `dir/ls` 


## Directory boom maken

voor al het schoolwerk hebben we een directory nodig.
ga naar jouw `homedirectory`, dus waar je documenten, music, videos etc staan
* de locatie wordt: `c:\users\JOUWNAAM\OneDrive Mediacollege\Ma`
* gebruik `cd "OneDrive Mediacollege"` omdat er een spatie in de naam staat

- maak `OneDrive Mediacollege` een `Ma` directory aan (`mkdir`)
- maak de volgende `directory tree` aan:


![boom.PNG](boom.PNG)

## bestandjes maken


notepad test.txt

echo "hello textfile" >> test.txt 
type test.txt

## Extensies & verborger bestanden

