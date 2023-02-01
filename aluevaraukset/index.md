---
layout: "default"
description: ""
id: "aluevaraukset"
status: "Ehdotus"
---
# Kaavamääräyslajit - aluevaraukset

<!-- Kommentti / Ilpo: Raporttiinkin viitaten - halutaanko eroon erillisistä aluevaraus / alueen käyttötarkoitus jne termeistä eri kaavatasojen välillä? Nyt tässä vanha oletus pohjalla -->

{% include common/clause_start.html type="req" id="sov-yk/vaat-aluemainen-aluevaraus" %}
Yleiskaavan aluevaraus on [Kaavakohde](dokumentaatio/#kaavakohde)-luokan objekti, jonka ```geometria```-attribuutin kuvaama geometria on aluemainen.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sov-yk/vaat-aluevaraus-maar" %}
Yleiskaavan aluevaraus liittyy assosiaatiolla ```maarays``` yhteen tai useampaan sellaiseen [Kaavamaarays](dokumentaatio/#kaavamaarays)-luokan objektiin, jonka ```laji```-attribuutin arvo on jokin [Kaavamääräys](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays)-koodiston arvoista, joka sisältyy määrityshierarkioihin  ```Käyttötarkoitus``` ja ```Yleiskaava```.
{% include common/clause_end.html %}