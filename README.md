# Schema, vecka 5
###### JavaScript, vecka 4 av 8

## Introduktion

I den här modulen kommer vi fokusera på två viktiga områden: formulärvalidering och felhantering. Genom att kombinera dessa lär vi oss inte bara att säkerställa att användaren fyller i korrekta data, utan även att hantera de fel som kan uppstå på ett strukturerat sätt. Felhantering är ett centralt koncept inom all programmering och en nyckel för att bygga robusta applikationer.

Utöver detta kommer vi dyka ner i localStorage, webbläsarens inbyggda lösning för att spara data lokalt. Det ger oss möjlighet att simulera interaktion med en databas, något som blir väldigt användbart längre fram. Dessutom introducerar vi konceptet med brancher i Git, vilket är ett viktigt steg mot ett säkrare och mer organiserat arbetssätt i era projekt.

## Mål för veckan:

1. Förstå hur man interagerar med formulär i kod
2. Förstå vikten av formulärvalidering
3. Förstå hur felhantering fungerar
4. Förstå hur vi kan använda localStorage för att lagra data
5. Förstå hur vi samarbetar kring kod genom att använda oss av branscher i Git


## Resurser

### Presentationer

* [LocalStorage](https://docs.google.com/presentation/d/1fI4zTguh_n9q76UcEC0ML74yfMQLvPejixN2Jo0KPMM/edit?usp=sharing)
* [Git Workflow](https://github.com/Santosnr6/Git-Flow/)

### Inspelade föreläsningar

**LIVE**

* [Formulärvalidering, felhantering och localStorage, 27 jan](https://funet.sharepoint.com/:v:/s/FrontendutvecklareYH-Fe24Karlstad-Arvika/Ed32jqPt_lBIvr757DaQQjcB8-Idb-XaB55v8KxTByaMog?e=JwmOaN) - med Karlstad
* [LIA med Kristina, 27 jan](https://funet-my.sharepoint.com/:v:/g/personal/jesper_nyberg_folkuniversitetet_se/EWuz7fsCHRtDlvS9wxBPKD4BPhtsbiRwfBOrZqu23XFXGA?e=bQZVdH&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) - gemensam
* [Formulärvalidering, felhantering och localStorage - fördjupning, 27 jan](https://funet-my.sharepoint.com/:v:/g/personal/jesper_nyberg_folkuniversitetet_se/EctdI4KJbXhJuAZTVPhedvgBOpjlf_BVPZpi-ZULeSjcmg?e=GIzA8z&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) - gemensam
* [Git Workflow, 28 jan](https://funet.sharepoint.com/:v:/s/FrontendutvecklareYH-Fe24Distans/ETy1K9TLOWZJoJz2IA2jvbMBy_Zykp5Xe6yqnrzq12T2ag?e=wyqLDS&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) - med distans
* [Git Workflow, 28 jan](https://funet.sharepoint.com/:v:/s/FrontendutvecklareYH-Fe24Karlstad-Arvika/EVcekMnsd1ZLqBPtSRMYeOcBwfWX3bC5d0NlEwo1XP74Kg?e=ASL9sD&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) - med Karlstad
* [Genomgång av gruppexamination](https://funet.sharepoint.com/:v:/s/FrontendutvecklareYH-Fe24Distans/EYg4HpFVOXdBl5opQsMWepoBq-ySN94JHYVgnkX9IIwoeQ?e=e1iImq&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

**Förinspelat** (för distansklassen)

* [Formulärvalidering och Felhantering](https://vimeo.com/1049960188/d039d2f672)
* [LocalStorage](https://vimeo.com/805239004)
* [Git Workflow](https://vimeo.com/906686286/9a91ea5b62)

### Lektionsrepon

* [27 jan](https://github.com/fu-javascript-fe24/week-5-lecture-27-jan) - gemensam
* [28 jan](https://github.com/fu-javascript-fe24/week-5-lecture-28-jan) - distans
* [29 jan](https://github.com/fu-javascript-fe24/week-5-lecture-29-jan) - Karlstad

### Filmer


### Länkar
* [LocalStorage MDN Documentation](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)

### Övningar 

* [Login Bootcamp](https://github.com/fu-javascript-fe24/week-5-exercise-login-bootcamp)
* [Tic Tac Toe](https://github.com/fu-javascript-fe24/code-review-tic-tac-toe)
* [Workshop: Git Flow](https://github.com/fu-javascript-fe24/week-5-workshop-git-flow)
* [Gruppexamination](https://github.com/fu-javascript-fe24/exam-group-catching-pokemon)






