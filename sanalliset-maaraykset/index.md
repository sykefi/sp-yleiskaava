---
layout: "default"
description: ""
id: "sanalliset-maaraykset"
status: "Ehdotus"
---
# Sanallisten kaavamääräysten luokittelu
{:.no_toc}

{:toc}

Sanallisilla kaavamääräyksillä tarkoitetaan kaavamääräystä, jolle ei ole annettu Kaavamääräyksen ```laji```-tietoa, vaan   ```arvo```-attribuutille {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %}.

{% include common/clause_start.html type="req" id="sp-yk/vaat-sanallisten-luokittelu" %}
Sanalliset kaavamääräykset on annotoitava [Sanallisen määräyksen laji](<http://uri.suomi.fi/codelist/rytj/RY_Sanallisen_Kaavamaarayksen_Laji/>) -koodein.
{% include common/clause_end.html %}

{% include common/tip.html content="Sanallisten kaavamääräysten luokittelun avulla mahdollistetaan sisällöltään usein hyvin vaihtelevien sanallisten kaavamääräysten älykäs etsittävyys ja luokiteltavuus. Tyypillisesti seikat, joita ei voida pelkin koodiarvoin kuvata, liittyvät esimerkiksi kaavakohteen toteutustapaan tai jonkin ilmiön erityiseen huomiomiseen." %}

### Yleismääräys
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Sanallisen_Kaavamaarayksen_Laji/code/yleismaarays>

{% include common/clause_start.html type="req" id="sp-yk/vaat-yleismaarays" %}
[Yleismääräys](http://uri.suomi.fi/codelist/rytj/RY_Sanallisen_Kaavamaarayksen_Laji/code/yleismaarays)-koodin avulla annotoidaan {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavamaarays" title="Kaavamääräyksiä"%}, jotka liittyvät suoraan {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaava" title="Kaavaan"%}.
{% include common/clause_end.html %}
