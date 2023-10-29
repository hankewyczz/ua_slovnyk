
Forked from [dmklinger/ukrainian](https://github.com/dmklinger/ukrainian)

Goal:
- Searchable Ukrainian dictionary (UA -> EN), with declensions
  - Translations for words галицького діалекту
  - Definitions for роди, відмінки (What does each one mean?)
  
  -  Optional:
    - Dictionary entries in Ukrainian as well (scrape Slovnyk.ua?)
      -  Online-search? If internet access is present, draw from Slovnyk as well?
      -   Clickable links (if the entry has a word for which we have a definition, link it)
      -   Programattic declensions? [(start here)](https://en.wikipedia.org/wiki/Ukrainian_grammar#First_declension)
- Offline mobile (and desktop) version
  - Look into SingleFile for saving a webpage to IOS



> Made because I was a little annoyed by the dearth of resources for Ukrainian learners. All data scraped from wiktionary and [dbnary](http://kaiko.getalp.org/about-dbnary/), which helpfully provides many, many definitions for words that do not have entries yet in Wiktionary. Forms filled in from [here](https://lcorp.ulif.org.ua/dictua/dictua.aspx), where a match was found.
>
> To get the data yourself run `main.py` in `etl/`. Requires a lot of time and a decent amount of RAM.
