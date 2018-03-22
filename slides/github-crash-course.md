# GitHub

## een 'crash course' 


Ron Wardenier (bleutzinn)
Meetup "git en GitHub" 22 maart 2018

Gemaakt in Markdown met [Marp](https://yhatt.github.io/marp/) (tip)

---
# GitHub is
een plek voor software ontwikkelaars om:
- code te delen
- samen te werken

sluit optimaal aan op code onder git versiebeheer

---
# Repositories
... zijn verzamelingen van code, configuratie bestanden, documentatie, etc. wat bij elkaar een logische eenheid vormt

Bijvoorbeeld een applicatie of al het lesmateriaal van een training

git en GitHub zijn gemaakt voor tekst bestanden

---
# Public / private repositories

- GitHub free kent alleen public repositories
- BitBucket is ook gratis maar heeft wel private repo's
- GitLab is self hosted

---
# Markdown
Teksten (ReadMe en ChangeLog files maak je op in Markdown
Lijkt op BB Code en Wiki markup
Keyboard only

[Markdown zoekresultaat in searx](http://search.disroot.org/?q=markdown&categories=general&language=en-US) (tip)

---
# Samenwerking
1 repository
n developers

De repository op GitHub is de centrale moeder versie
Elke developer heeft een lokale kopie en wijzigt daarin
Wijzigingen 'vloeien' terug naar het origineel

---
# Terminologie

Forking: een kopie maken van een originele repository (GitHub)

Cloning: een lokale kopie maken van een remote repo (git)

Pull Request: ontwikkelaar biedt wijzigingen aan aan de eigenaar van de repository; het is een verzoek om die wijzigingen binnen te halen

NB Een Pull Request op je eigen remote repository heet een 'push'

---
# Branches
Gelijktijdig werken aan meerdere (op zichzelf staande) wijzigingen

Na testen kan een branch samengevoegd worden met een andere branch, vaak de 'master'

---
# Releases
Een release is een complete versie van een applicatie (of resultaat dataset)
Omvat naast de echte inhoud een Change Log en bijgewerkte documentatie
Een repo zonder release wordt gezien als (nog) niet stabiel

