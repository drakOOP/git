# Git
![Git logo](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.svg)
Git je distribuirani sistem za kontrolu verzija. Prati promene u bilo kom skupu datoteka, i obično se koristi za koordinaciju rada između programera koji zajedno razvijaju izvorni kod tokom razvoja softvera. Njegovi ciljevi uključuju brzinu, integritet podataka i podršku za distribuirane, nelinearne tokove posla (hiljade paralelnih grana koje rade na različitim sistemima).
# Git konfiguracija
Komanda `git config` je pogodna funkcija koja se koristi za postavljanje vrednosti Git konfiguracije na globalnom ili lokalnom nivou projekta. Ovi nivoi konfiguracije odgovaraju `.gitconfig` tekstualnim datotekama. Izvršavanje `git config`-a će izmeniti tekstualnu datoteku konfiguracije.
```
git config --global user.email "your_email@example.com
```
# Osnovne git komande
* `git init` - Kreira prazno git skladište ili ponovo inicijalizuje već postojeće
* `git clone` - Klonira skladište u novi direktorijum
* `git add` - Dodaje fajl u _staging area_
* `git status` - Prikazuje sve fajlove koji treba da budu priloženi (engl. _commit_)
* `git diff` - Prikazuje sve razlike u fajlovima koji nisu još priloženi i onih koji su sačuvani
* `git commit` - Sačuvaj promene u skladište
* `git notes` - Dodaj ili proveri beleške objekta
* `git restore` - Vraća skladište u neko stanje iz prošlosti
