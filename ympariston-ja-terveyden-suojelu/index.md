---
layout: "default"
description: ""
id: "ympariston-ja-terveyden-suojelu"
status: "Ehdotus"
---
# Kaavamääräyslajit - ympäristön ja terveyden suojelu
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/10>

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

1. 
{:toc}

## Pilaantunut maa-alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/1001>

{% include common/clause_start.html type="req" id="prof-yk/vaat-pilaantunut-maa-alue-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolla on ihmisen toiminnan seurauksena haitallisia aineita siinä määrin, että niistä aiheutuu haittaa tai merkittävä riski ympäristölle tai terveydelle, viihtyisyyden vähentymistä tai muuta niihin verrattavissa olevaa haittaa.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-pilaantunut-maa-alue-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa, esimerkiksi lisätietoa pilaantumisen laadusta. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-pilaantunut-maa-alue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="rec" id="prof-ak/suos-pilaantunut-maa-alue-liittyva-asiakirja" %}
Mikäli pilaantumiseen liittyen on laadittu selvitys on suositeltavaa linkittää se kaavamääräykseen ```liittyvaAsiakirja```-assosiaation avulla.
{% include common/clause_end.html %}

{% include common/question.html content="Miksi pilaantunut maa-alue on kaavamääräys? Pitäisikö pilaantuneiden maa-alueiden olla osa lähtötietoaineistoja? SYKEn MATTI-järjestelmä?" %}

## Tulvavaara-alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/1002>

{% include common/question.html content="Termi: onko sama kuin tulvariskialue vai alue, jolla vallitsee tulvariski riippumatta alueen vahinkopotentiaalista?" %}

> Tulvariskialue on (maantieteellinen) alue, jolle tulvavaara aiheuttaa vahinkoriskin, ts. alue, jolla vallitsee tulvavaara ja jolla on sellainen vahinkopotentiaali (haavoittuvuus) että tulva aiheuttaisi vahinkoja. Merkittävällä tulvariskialueella tarkoitetaan tulvariskilainsäädännön mukaisesti nimettyä, tulvariskien alustavan arvioinnin perusteella tunnistettua aluetta.
(SYKE, [Tulvasanasto](https://www.ymparisto.fi/fi-FI/Vesi/Tulviin_varautuminen/Tulvasanasto))

{% include common/clause_start.html type="req" id="prof-yk/vaat-tulvavaara-alue-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolla on tunnistettu tulvimisvaara.
{% include common/clause_end.html %}

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


## Hulevesitulvavaara-alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/1004>

{% include common/question.html content="Termi: onko sama kuin hulevesien tulvariskialue vai alue, jolla vallitsee tulvariski riippumatta alueen vahinkopotentiaalista?" %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-hulevesitulvavaara-alue-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolla on tunnistettu hulevesistä johtuva tulvimisvaara.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-hulevesitulvavaara-alue-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-hulevesitulvavaara-alue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
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


## Melualue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/1007>

{% include common/clause_start.html type="req" id="prof-yk/vaat-melualue-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolla esiintyy siinä määrin melua, että siitä voi aiheutua merkittävää haittaa.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-melualue-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), jolla kuvataan melun tyyppiä ja haitallisuutta. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-melualue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/question.html content="Miksi melualue on kaavamääräys? Pitäisikö melualueiden olla osa lähtötietoaineistoja?" %}

## Pohjavesialue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/1008>

{% include common/clause_start.html type="req" id="prof-yk/vaat-pohjavesialue-maar" %}
Ilmaisee, että kaavakohde kuvaa pohjavesialueen.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-pohjavesialue-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), jolla annetaan sen vesistökohteen nimi, jonka valuma-alueesta on kysymys. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-pohjavesialue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="rec" id="prof-yk/suos-pohjavesivalue-alue-lahtotietokohde" %}
Kaavakohteen, johon pohjavesialue-lajin kaavamääräys on liitetty, ```liittyvanLahtotietokohteenTunnus```-attribuutin käyttämistä lähtötietoaineiston pohjavesialue-kohteeseen viittamiseen suositellaan.
{% include common/clause_end.html %}


## Muu ympäristönsuojeluun liittyvä määräys
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/1011>

{% include common/clause_start.html type="req" id="prof-yk/vaat-muu-ymparistonsuojelu-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka kuvaa kaavamääräyksen. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-muu-ymparistonsuojelu-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}