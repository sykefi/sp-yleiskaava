---
layout: "default"
description: ""
id: "koodistot"
status: "Ehdotus"
---
# Koodistot

## Vuorovaikutustapahtuman laji
{% include common/clause_start.html type="req" id="prof-yk/vaat-vuorovaikutustapahtuman-laji" %}
Luokan {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#abstraktivuorovaikutustapahtumanlaji" title="AbstraktiVuorovaikutustapahtumanLaji" %} sijaan tulee käyttää tarkentavaa luokkaa {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavanvuorovaikutustapahtumanlaji" title="KaavanVuorovaikutustapahtumanLaji" %}.
{% include common/clause_end.html %}

## Käsittelytapahtuman laji
{% include common/clause_start.html type="req" id="prof-yk/vaat-kasittelytapahtuman-laji" %}
Luokan [AbstraktiKasittelytapahtumanLaji](../../looginenmalli/dokumentaatio/#abstraktikasittelytapahtumanlaji) sijaan tulee käyttää tarkentavaa luokkaa [KaavanKasittelytapahtumanLaji](../../looginenmalli/dokumentaatio/#kaavankasittelytapahtumanlaji).
{% include common/clause_end.html %}

## Kaavakohdelaji
[AbstraktiKaavakohdelaji](../../looginenmalli/dokumentaatio/#abstraktikaavakohdelaji)-koodisto on varattu tulevaisuuden käyttöön. Tässä tietomalliin versiossa ei määritellä yleiskaavakohtaista koodistoa kaavakohdelajeille.

{% include common/clause_start.html type="req" id="prof-yk/vaat-kaavakohdelaji" %}
[Kaavakohde](../../looginenmalli/dokumentaatio/#kaavakohde)-luokan ```laji```-attribuuttia ei saa käyttää informaation välittämiseen. Mikäli sille on annettu ei-tyhjä arvo, se tulee jättää huomiotta.  
{% include common/clause_end.html %}

## Kaavoitusteema
{% include common/clause_start.html type="req" id="prof-yk/vaat-kaavoitusteema" %}
Luokan [AbstraktiKaavoitusteema](../../looginenmalli/dokumentaatio/#abstraktikaavoitusteema) sijaan tulee käyttää tarkentavaa luokkaa [KaavoitusteemaYleiskaava](../../looginenmalli/dokumentaatio/#kaavoitusteemayleiskaava).
{% include common/clause_end.html %}

## Kaavamääräyslaji
{% include common/clause_start.html type="req" id="prof-yk/vaat-kaavamaarayslaji" %}
Luokan [AbstraktiKaavamaaraysLaji](../../looginenmalli/dokumentaatio/#abstraktikaavamaarayslaji) sijaan tulee käyttää tarkentavaa luokkaa [KaavamaaraysLajiYleiskaava](../../looginenmalli/dokumentaatio/#kaavamaarayslajiyleiskaava).
{% include common/clause_end.html %}

## Kaavamääräyksen lisätiedon laji
{% include common/clause_start.html type="req" id="prof-yk/vaat-kaavamaarayksen-lisatieton-laji" %}
Luokan [AbstraktiLisatiedonLaji](../../looginenmalli/dokumentaatio/#abstraktilisatiedonlaji) sijaan tulee käyttää tarkentavaa luokkaa [LisatiedonLajiYleiskaava](../../looginenmalli/dokumentaatio/#lisatiedonlajiyleiskaava).
{% include common/clause_end.html %}