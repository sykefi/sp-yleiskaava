---
layout: "default"
description: ""
id: "laatusaannot"
status: "Ehdotus"
---
# Laatusäännöt
Nämä laatusäännöt laajentavat Kaavatietomallin [yleisiä laatusääntöjä](../../looginenmalli/laatusaannot.html).

## Aluevaraukset

{% include common/clause_start.html type="req" id="sov-yk/vaat-aluevaraus-maar" %}
Yleiskaavan aluevaraus on [Kaavakohde](dokumentaatio/#kaavakohde)-luokan objekti, joka liittyy assosiaatiolla ```maarays``` yhteen tai useampaan sellaiseen [Kaavamaarays](dokumentaatio/#kaavamaarays)-luokan objektiin, jonka ```laji```-attribuutin arvo on jokin [Kaavamääräys-koodiston]((http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/01) koodeista, jolla määrityshiearkiana [Käyttötarkoitus] sekä [Yleiskaava].
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sov-yk/vaat-aluemainen-aluevaraus" %}
Yleiskaavan aluevarausten ```geometria```-attribuutin kuvaamaan geometrian tulee olla aluemainen.
{% include common/clause_end.html %}