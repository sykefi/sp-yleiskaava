---
layout: "default"
description: ""
id: "rajoitukset"
status: "Ehdotus"
---
# Kaavamääräyslajit - rajoitukset
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/maankayttorajoitukset>

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

<!-- Näistä pitää vielä miettiä tietomallin näkökulmasta missä järkevintä, määräaikainen rajoitus nyt sotkee pakkaa. -->

1. 
{:toc}

## Rakentamisrajoitus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/rakentamisrajoitus>

{% include common/clause_start.html type="req" id="prof-yk/vaat-rakentamisrajoitus-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.  Muun tyyppiset arvot eivät ole sallittuja.
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
* yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} joka kuvaa sen kaavan hyväksymisestä alkavan ajanjakson pituuden, jona aikana käyttö on kielletty. Numeerisen arvon  on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#integer" title="Integer" %}-rajapinta. Yksikkönä vuosi (```v```), tai kuukausi (```kk```) tai
* yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#ajanhetkiarvo" title="Ajanhetkiarvo" %} joka kuvaa päivämäärän, johon saakka käyttö on kielletty.
Muun tyyppiset arvot eivät ole sallittuja.

Lisäksi ```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.

Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-maara-aikainen-rakentamisrajoitus-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/question.html content="Pitääkö tätä voida rakenteistaa, vai riittääkö teksti? Esim. lisätä käyttötarkoituskohdistus tai pois luettava käyttötarkoitus?" %}

## Toimenpiderajoitus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/toimenpiderajoitus>

{% include common/clause_start.html type="req" id="prof-yk/vaat-toimenpiderajoitus-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.  Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

## Rakennuksen purkamisrajoitus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/rakennuksenPurkamisrajoitus>

{% include common/clause_start.html type="req" id="prof-yk/vaat-purkamisrajoitus-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.  Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}