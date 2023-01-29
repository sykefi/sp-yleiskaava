---
layout: "default"
description: ""
id: "yhdyskuntateknisen-huollon-alue"
status: "Ehdotus"
---
# Kaavamääräyslajit - yhdyskuntateknisen huollon alue
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/ymparistoteknisenHuollonAlue>

## Johto, putki tai linja
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0901>

{% include common/clause_start.html type="req" id="prof-yk/vaat-johto-putki-linja-maar" %}
Ilmaisee, että kaavakohde kuvaa johdon, putken tai linjan keskilinjan tai välittömän ympäristön.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-johto-putki-linja-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-johto-putki-linja-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/question.html content="Pitäisikö muuttaa muotoon 'Muu johto, putki tai linja'? Nyt hieman epäselvää milloin käytettävä tarkempia määräyksiä (esim. sähkölinja tai kaasulinja. Vai haetaako tällä kenties yhdistelmälinjoja? Mikäli kyseessä yleinen, tarkemmin määrittelemätön johto, putki tai linja, niin pitäisi olla hierarkiassa yksityiskohtaisten yläkoodina." %}

## Sähkölinja
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0902>

{% include common/clause_start.html type="req" id="prof-yk/vaat-sahkojohto-maar" %}
Ilmaisee, että kaavakohde kuvaa sähköjohdon keskilinjan tai välittömän ympäristön.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-sahkojohto-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-sahkojohto-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Kaasulinja
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0903>

{% include common/clause_start.html type="req" id="prof-yk/vaat-kaasujohto-maar" %}
Ilmaisee, että kaavakohde kuvaa sähköjohdon keskilinjan tai välittömän ympäristön.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-kaasujohto-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-kaasujohto-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Vesi- tai jätevesitunneli
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0904>

{% include common/clause_start.html type="req" id="prof-yk/vaat-vesitunneli-maar" %}
Ilmaisee, että kaavakohde kuvaa vesi- tai viemäritunnelin keskilinjan tai välittömän ympäristön.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-vesitunneli-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-vesitunneli-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Vesijohto tai siirtoviemäri
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0905>

{% include common/clause_start.html type="req" id="prof-yk/vaat-vesijohto-siirtoviemari-maar" %}
Ilmaisee, että kaavakohde kuvaa vesijohdon tai siirtoviemärin keskilinjan tai välittömän ympäristön.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-vesijohto-siirtoviemari-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-vesijohto-siirtoviemari-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}


## Kaukolämpölinja
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0906>

{% include common/clause_start.html type="req" id="prof-yk/vaat-kaukolampolinja-maar" %}
Ilmaisee, että kaavakohde kuvaa kaukolämpölinjan keskilinjan tai välittömän ympäristön.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-kaukolampolinja-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-kaukolampolinja-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Kaukokylmälinja
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0907>

{% include common/clause_start.html type="req" id="prof-yk/vaat-kaukokylmalinja-maar" %}
Ilmaisee, että kaavakohde kuvaa kaukokylmalinjan keskilinjan tai välittömän ympäristön.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-kaukokylmalinja-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-kaukokylmalinja-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Hulevesien hallinta-alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0908>

{% include common/clause_start.html type="req" id="prof-yk/vaat-hulevesien-hallinta-alue-maar" %}
Ilmaisee, että kaavakohde kuvaa hulevesien määrälliseen ja/tai laadulliseen hallintaan varatun alueen.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-hulevesien-hallinta-alue-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-hulevesien-hallinta-alue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Hulevesien hallinnan kannalta merkittävä alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0909>

{% include common/clause_start.html type="req" id="prof-yk/vaat-hulevesien-hallinta-merkittava-alue-maar" %}
Ilmaisee, että kaavakohde kuvaa hulevesien hallinnan kannalta merkittävän alueen.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-hulevesien-hallinta-merkittava-alue-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-hulevesien-hallinta-merkittava-alue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Hulevesien purkuoja tai reitti
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0910>

{% include common/clause_start.html type="req" id="prof-yk/vaat-hulevesien-purkuoja-reitti-maar" %}
Ilmaisee, että kaavakohde kuvaa hulevesien purkuojan keskilinjan tai välittömän ympäristön.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-hulevesien-purkuoja-reitti-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-hulevesien-purkuoja-reitti-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/question.html content="Koodistossa 'Hulevesien purkuoja/-reitti', kumpi pidetään?" %}

## Hulevesien viivytysalue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0911>

{% include common/clause_start.html type="req" id="prof-yk/vaat-hulevesien-viivytysalue-maar" %}
Ilmaisee, että kaavakohde kuvaa hulevesien viivytyslaueen, jonka sisällä hulevesien virtausta viivytetään, pidätetään tai niitä imeytetään maaperään.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-hulevesien-viivytysalue-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-hulevesien-viivytysalue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Hulevesien käsittelytapa
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0912>

{% include common/clause_start.html type="req" id="prof-yk/vaat-hulevesien-kasittelytapa-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka kuvaa miten hulevesiä tulee käsitellä alueella, johon kaavamääräys kohdistuu. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-hulevesien-kasittelytapa-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/question.html content="Tässä potentiaalia käsittelytapaa kuvaavalle koodistolle?" %}

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