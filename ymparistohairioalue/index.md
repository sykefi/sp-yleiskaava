---
layout: "default"
description: ""
id: "ymparistohairioalue"
status: "Ehdotus"
---
# Kaavamääräyslajit - ympäristöhäiriöalue
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/ymparistohairioAlue>

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

1. 
{:toc}

## Pilaantunut maa-alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/pilaantunutMaaAlue>

{% include common/clause_start.html type="req" id="prof-yk/vaat-pilaantunut-maa-alue-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa, esimerkiksi lisätietoa pilaantumisen laadusta. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="rec" id="prof-ak/suos-pilaantunut-maa-alue-liittyva-asiakirja" %}
Mikäli pilaantumiseen liittyen on laadittu selvitys on suositeltavaa linkittää se kaavamääräykseen ```liittyvaAsiakirja```-assosiaation avulla.
{% include common/clause_end.html %}

## Tulvariskialue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/tulvariskiAlue>

{% include common/clause_start.html type="req" id="prof-yk/vaat-tulvavaara-alue-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-tulvavaara-alue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Meritulvavaara-alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/1003>

{% include common/question.html content="Termi: onko sama kuin merenrannikon tulvariskialue vai alue, jolla vallitsee tulvariski riippumatta alueen vahinkopotentiaalista?" %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-meritulvavaara-alue-maar" %}
Ilmaisee, että kaavakohde kuvaa meren rannikolla sijaitsevan alueen, jolla on tunnistettu tulvimisvaara.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-meritulvavaara-alue-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-meritulvavaara-alue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Hulevesitulvariskialue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/hulevesitulvariskiAlue>

{% include common/clause_start.html type="req" id="prof-yk/vaat-hulevesitulvavaara-alue-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

## Valuma-alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/1005>

> Vesistöalue on alue, josta kaikki pintavalunta virtaa puron, järven, joen tai suistoalueen kautta mereen. Valuma-alueella tarkoitetaan tietyn uomaverkoston kohdan yläpuolista, vedenjakajan rajaamaa aluetta, joka määritellään tavallisesti järven luusuaan, jokien yhtymäkohtaan, valtakunnan rajalle tai meren rantaan. Valuma-alueella voidaan tarkoittaa myös vesistöaluetta.
(SYKE, [Tulvasanasto](https://www.ymparisto.fi/fi-FI/Vesi/Tulviin_varautuminen/Tulvasanasto))

{% include common/clause_start.html type="req" id="prof-yk/vaat-valuma-alue-maar" %}
Ilmaisee, että kaavakohde kuvaa tietyn uomaverkoston kohdan yläpuolista, vedenjakajan rajaamaa aluetta, joka määritellään tavallisesti järven luusuaan (laskukohta, josta järven lasku-uomana toimiva joki saa alkunsa), jokien yhtymäkohtaan, valtakunnan rajalle tai meren rantaan.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-valuma-alue-arvot" %}
```arvo```-attribuutin arvona saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), jolla annetaan sen vesistökohteen nimi, jonka valuma-alueesta on kysymys. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-valuma-alue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="rec" id="prof-yk/suos-valuma-alue-lahtotietokohde" %}
Kaavakohteen, johon valuma-alue -lajin kaavamääräys on liitetty, ```liittyvanLahtotietokohteenTunnus```-attribuutin käyttämistä valuma-alueen vesistökohteeseen viittamiseen suositellaan, mikäli kyseinen vesistökohde on osa kaavan lähtötietoaineistoja.
{% include common/clause_end.html %}

## Vaara-alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0603>

{% include common/clause_start.html type="req" id="prof-yk/vaat-vaara-alue-maar" %}
Ilmaisee, että kaavakohteen kuvaa alueen, joilla liikkuminen on turvallisuussyistä rajoitettu tai sitä on tarkoitus rajoittaa.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-vaara-alue-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), jotka kuvaavat vaaran luonteen ja sen vaikutukset alueen käyttömahdollisuuksiin.  Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-vaara-alue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Melualue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/1007>

{% include common/clause_start.html type="req" id="prof-yk/vaat-melualue-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), jolla kuvataan melun tyyppiä ja haitallisuutta. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-melualue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/question.html content="Miksi melualue on kaavamääräys? Pitäisikö melualueiden olla osa lähtötietoaineistoja?" %}

## Suojavyöhyke
**Koodi**: <http://uri.suomi.fi/codelist/rytj/
{% include common/clause_start.html type="req" id="prof-yk/vaat-suojavohyke-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), jotka kuvaavat alueiden käytön reunaehtoja tai suojavaikutuksen lisäämistä.  Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-suojavohyke-lisatiedot" %}
* ```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#lisatieto" title="Lisatieto" %} jonka laji on [Poisluettava käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_YK/code/04), ja jonka ```arvo```-attribuutin arvoina on yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} jotka viittaavat koodiston KaavamääraysLaji koodin [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/01) alakoodeihin. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}