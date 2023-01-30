---
layout: "default"
description: ""
id: "yhdyskuntateknisen-huollon-alue"
status: "Ehdotus"
---
# Kaavamääräyslajit - yhdyskuntateknisen huollon alue
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/ymparistoteknisenHuollonAlue>

## Pohjavedenottamo
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0913>

{% include common/clause_start.html type="req" id="prof-yk/vaat-pohjavedenottamo-maar" %}
Ilmaisee, että kaavakohde kuvaa pohjavedenottamon välittömän ympäristön.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-pohjavedenottamo-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-pohjavedenottamo-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Pohjavedenottamon lähisuoja-alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0914>

{% include common/clause_start.html type="req" id="prof-yk/vaat-pohjavedenottamo-lahisuoja-alue-maar" %}
Ilmaisee, että kaavakohde kuvaa pohjavedenottamon lähisuoja-alueen.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-pohjavedenottamo-lahisuoja-alue-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-pohjavedenottamo-lahisuoja-alue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/question.html content="Voidaanko tästä määrätä mitään yleiskaavassa, vai onko vesilain ja muiden maankäyttöpäätösten asia?" %}