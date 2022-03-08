---
layout: "default"
description: ""
id: "rajoitukset"
status: "Ehdotus"
---
# Kaavamääräyslajit - rajoitukset
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/05>

Ryhmittelyotsikko, vain [alakoodeja](../../looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar) käytetään.

1. 
{:toc}

## Rakentamisrajoitus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0501>

{% include common/clause_start.html type="req" id="prof-yk/vaat-rakentamisrajoitus-maar" %}
Ilmaisee, että kaavakohteen alueella ei saa rakentaa niin, että vaikeutetaan yleiskaavan toteutumista.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-rakentamisrajoitus-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.  Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-rakentamisrajoitus-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/question.html content="Pitääkö tätä voida rakenteistaa, vai riittääkö teksti? Esim. lisätä käyttötarkoituskohdistus tai pois luettava käyttötarkoitus?" %}

## Määräaikainen rakentamisrajoitus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0502>

{% include common/clause_start.html type="req" id="prof-yk/vaat-maara-aikainen-rakentamisrajoitus-maar" %}
Ilmaisee, että kaavakohde on rakennustoimintaan tarkoitetun alue, jonka käyttö on kielletty enintään viiden vuoden aikana muuhun rakentamiseen kuin maatalouden ja muiden siihen verrattavien elinkeinojen tarpeita varten.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-maara-aikainen-rakentamisrajoitus-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä joko
* yksi [NumeerinenArvo](../../looginenmalli/dokumentaatio/#numeerinenarvo), joka kuvaa sen kaavan hyväksymisestä alkavan ajanjakson pituuden, jona aikana käyttö on kielletty. Numeerisen arvon  on toteutettava [Integer](../../looginenmalli/dokumentaatio/#integer)-rajapinta. Yksikkönä vuosi (```v```), tai kuukausi (```kk```) tai
* yksi [Ajanhetkiarvo](../../looginenmalli/dokumentaatio/#ajanhetkiarvo), joka kuvaa päivämäärän, johon saakka käyttö on kielletty.
Muun tyyppiset arvot eivät ole sallittuja.

Lisäksi ```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.

Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-maara-aikainen-rakentamisrajoitus-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/question.html content="Pitääkö tätä voida rakenteistaa, vai riittääkö teksti? Esim. lisätä käyttötarkoituskohdistus tai pois luettava käyttötarkoitus?" %}


## Toimenpiderajoitus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0503>

{% include common/clause_start.html type="req" id="prof-yk/vaat-toimenpiderajoitus-maar" %}
Ilmaisee, että kaavakohteen alueella ei saa suorittaa maisemaa muuttavaa toimenpidettä ilman maisematyölupaa.
{% include common/clause_end.html %}

Maisematyölupa, ks. [MRL 128 §](https://www.finlex.fi/fi/laki/ajantasa/1999/19990132#L18P128).

{% include common/clause_start.html type="req" id="prof-yk/vaat-toimenpiderajoitus-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.  Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-toimenpiderajoitus-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Rakennuksen purkamisrajoitus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0504>

{% include common/clause_start.html type="req" id="prof-yk/vaat-purkamisrajoitus-maar" %}
Ilmaisee, että kaavakohteen alueella olevia rakennuksia tai niiden osia ei saa purkaa ilman purkamislupaa.
{% include common/clause_end.html %}

Rakennuksen purkamislupa, ks. [MRL 127 §](https://www.finlex.fi/fi/laki/ajantasa/1999/19990132#L18P127).

{% include common/clause_start.html type="req" id="prof-yk/vaat-purkamisrajoitus-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.  Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-purkamisrajoitus-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}