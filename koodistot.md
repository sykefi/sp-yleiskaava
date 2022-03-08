---
layout: "default"
description: ""
id: "koodistot"
status: "Ehdotus"
---
# Koodistot

## Vuorovaikutustapahtuman laji
{% include common/clause_start.html type="req" id="prof-yk/vaat-vuorovaikutustapahtuman-laji" %}
Luokan {% include common/moduleLink moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#abstraktivuorovaikutustapahtumanlaji" title="AbstraktiVuorovaikutustapahtumanLaji" %} sijaan tulee käyttää tarkentavaa luokkaa {% include common/moduleLink moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavanvuorovaikutustapahtumanlaji" title="KaavanVuorovaikutustapahtumanLaji" %}.
{% include clause_end.html %}

## Käsittelytapahtuman laji
{% include clause_start.html type="req" id="prof-yk/vaat-kasittelytapahtuman-laji" %}
Luokan [AbstraktiKasittelytapahtumanLaji](../../looginenmalli/dokumentaatio/#abstraktikasittelytapahtumanlaji) sijaan tulee käyttää tarkentavaa luokkaa [KaavanKasittelytapahtumanLaji](../../looginenmalli/dokumentaatio/#kaavankasittelytapahtumanlaji).
{% include clause_end.html %}

## Kaavakohdelaji
[AbstraktiKaavakohdelaji](../../looginenmalli/dokumentaatio/#abstraktikaavakohdelaji)-koodisto on varattu tulevaisuuden käyttöön. Tässä tietomalliin versiossa ei määritellä yleiskaavakohtaista koodistoa kaavakohdelajeille.

{% include clause_start.html type="req" id="prof-yk/vaat-kaavakohdelaji" %}
[Kaavakohde](../../looginenmalli/dokumentaatio/#kaavakohde)-luokan ```laji```-attribuuttia ei saa käyttää informaation välittämiseen. Mikäli sille on annettu ei-tyhjä arvo, se tulee jättää huomiotta.  
{% include clause_end.html %}

## Kaavoitusteema
{% include clause_start.html type="req" id="prof-yk/vaat-kaavoitusteema" %}
Luokan [AbstraktiKaavoitusteema](../../looginenmalli/dokumentaatio/#abstraktikaavoitusteema) sijaan tulee käyttää tarkentavaa luokkaa [KaavoitusteemaYleiskaava](../../looginenmalli/dokumentaatio/#kaavoitusteemayleiskaava).
{% include clause_end.html %}

## Kaavamääräyslaji
{% include clause_start.html type="req" id="prof-yk/vaat-kaavamaarayslaji" %}
Luokan [AbstraktiKaavamaaraysLaji](../../looginenmalli/dokumentaatio/#abstraktikaavamaarayslaji) sijaan tulee käyttää tarkentavaa luokkaa [KaavamaaraysLajiYleiskaava](../../looginenmalli/dokumentaatio/#kaavamaarayslajiyleiskaava).
{% include clause_end.html %}

## Kaavamääräyksen lisätiedon laji
{% include clause_start.html type="req" id="prof-yk/vaat-kaavamaarayksen-lisatieton-laji" %}
Luokan [AbstraktiLisatiedonLaji](../../looginenmalli/dokumentaatio/#abstraktilisatiedonlaji) sijaan tulee käyttää tarkentavaa luokkaa [LisatiedonLajiYleiskaava](../../looginenmalli/dokumentaatio/#lisatiedonlajiyleiskaava).
{% include clause_end.html %}