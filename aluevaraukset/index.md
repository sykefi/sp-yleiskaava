---
layout: "default"
description: ""
id: "aluevaraukset"
status: "Ehdotus"
---
# Kaavamääräyslajit - aluevaraukset

{% include common/clause_start.html type="req" id="sov-yk/vaat-aluemainen-aluevaraus" %}
Yleiskaavan aluevaraus on [Kaavakohde](dokumentaatio/#kaavakohde)-luokan objekti, jonka ```geometria```-attribuutin kuvaama geometria on aluemainen.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sov-yk/vaat-aluevaraus-maar" %}
Yleiskaavan aluevaraus liittyy assosiaatiolla ```maarays``` yhteen tai useampaan sellaiseen [Kaavamaarays](dokumentaatio/#kaavamaarays)-luokan objektiin, jonka ```laji```-attribuutin arvo on jokin [Kaavamääräys](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays)-koodiston arvoista, joka sisältyy määrityshierarkioihin  ```Käyttötarkoitus``` ja ```Yleiskaava```.
{% include common/clause_end.html %}