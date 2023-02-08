---
layout: "default"
description: ""
id: "lisatiedot"
status: "Ehdotus"
---

# Kaavamääräyksen lisätiedot
{:.no_toc}

## Merkittävyys
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/merkittavyys>

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

Merkittävyys-lisätiedon alakoodien avulla voidaan täsmentää kaavamääräyksen kuvaaman maankäytön tai sen perusteena olevien arvojen merkittävyyttä, maantieteellisin laajuuksin kuvattuna.

Esimerkkejä:<br>
* ``` Maakunnallisesti arvokas maisema-alue``` voidaan muodostaa liittämällä kaavakohteeseen määräys [Maisemallisesti arvokas alue](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/maisemallisestiArvokasAlue) sekä lisätieto [Maakunnallinen](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/maakunnallinen).

* ```Alueverkon pyöräilyreitti``` voidaan muodostaa liittämällä kaavakohteeseen määräys [Pyöräilyreitti](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/pyorailyReitti) sekä lisätieto [Alueellinen](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/alueellinen). Vastaavasti ```Seutuverkon pyöräilyreitti``` voidaan muodostaa vaihtamalla lisätieto koodiin [Seudullinen](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/seudullinen).

## Tarve
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/tarve>

Yleiskaavoissa käytetään paljon jotakin tunnistettua tarvetta kuvaavia kaavamääräyksiä. Tällaiset muodostetaan [Kaavamääräys](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays)-koodien ja [Tarve](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/tarve)-luokan lisätietokoodien yhdistelminä.

Esimerkkejä:<br>
* ```Johdon, putken tai linjan yhteystarve``` voidaan muodostaa liittämällä kaavakohteeseen määräys [Johto, putki tai linja](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/JohtoPutkiTaiLinja) sekä lisätieto [tarve](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/tarve). 

* ```Viheryhteystarve``` voidaan muodostaa liittämällä kaavakohteeseen määräys [Ekologinen yhteys](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/ekologinenYhteys) sekä lisätieto [tarve](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/tarve). Samoin esim. ```virkistysyhteystarve``` voidaan kuvata koodien [Ulkoilu- tai virkistysreitti](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/ulkoiluTaiVirkistysReitti) ja [tarve](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/tarve) yhdistelmänä.

* Erityyppiset ```tieliikenteen yhteystarpeet``` saadaan kuvattua väylän toiminnallista luokkaa parhaiten kuvaavan määräyskoodin (esim. [Valtatie](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/valtaTie)) ja lisätiedon [tarve](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/tarve) yhdistelmänä.

## Ympäristömuutoksen laji
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/ymparistomuutoksenLaji>

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

Ympäristömuutoksen laji -ryhmän lisätietokoodein voidaan täsmentää, miten kaavamääräyksen kuvaama maankäyttö eroaa suhteessa kaavan laadinnan ajanhetkellä olemassa olevaan, kaavakohteen alueella sijaitsevaan maankäyttöön.

Esimerkkejä:

* Määräys [Valtatie](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/valtaTie) + lisätieto [Uusi](<http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/uusi>) = ```Uusi valtatie```.

* Määräys [Asuinpientaloalue](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/asuinpientaloAlue) + lisätieto [Pienin toimenpitein kehitettävä](<http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/pieninToimenpiteinKehitettava>) = ```Pienin toimenpitein kehitettävä asuinpientaloalue```.

## Tyyppi
Kaavamääräyksen tarkempi tyypittely. Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

### Poisluettava käyttötarkoitus
Kaavamääräyksen ```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#lisatieto" title="Lisatieto" %} jonka laji on [Poisluettava käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_YK/code/04), ja jonka ```arvo```-attribuutin arvoina on yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} jotka viittaavat [Kaavamääräys](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays)-koodiston koodeihin, jotka sisältyvät ```Käyttötarkoitus```-määrityshierarkiaan. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

Poisluettavat käyttötarkoituslajit tulee valita siten, että ne kohdistuvat ```arvo```-attribuuttien avulla valittuun yleispiirteisempään joukkoon käyttötarkoituksia pois lukien niistä osan.

Esimerkkejä: 
* [Toimitilojen alue](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/toimitilojenAlue) pois lukien [Tuotantorakennusten alue](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/tuotantorakennustenAlue).

* [Suojavyöhyke](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/toimitilojenAlue) pois lukien [Erityisryhmien asuinrakennusten alue](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/erityisryhmienAsuinrakennustenAlue).

### Reservialue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/reserviAlue>

{% include common/clause_start.html type="req" id="sp-yk/vaat-reservialue" %}
Alustavaa tai ehdollista maankäyttöä kuvaavaa [Reservialue](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/reserviAlue)-lisätietoa käytetään kaavamääräyksille, joilla kuvataan alueen käyttötarkoitusta, eli ns. [Aluevarauksille](../laatusaannot.md).
{% include common/clause_end.html %}

{% include common/tip.html content="Reservialue-koodin avulla voidaan ohjata myös kaavan esitystapaa (ns. r-päätteisten aluevarausten nimiöiden kuvaamiseen)." %}

### Vaihtoehtoinen
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/vaihtoehtoinen>

Esimerkkejä
* ```Vaihtoehtoinen tielinjaus``` voidaan kuvata tien toiminnallista luokkaa kuvaavan kaavamääräyksen, esim. [Valtatie](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/valtatie) ja lisätiedon [vaihtoehtoinen](<http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/vaihtoehtoinen>) yhdistelmällä.

{% include common/tip.html content="```Ohjeelliset tielinjaukset``` ja vastaavat ohjeelliset kaavamääräykset muodostetaan Kaavakohteen ```sijainninSitovuus``` -attribuutin arvon ```Ohjeellinen``` avulla." %}

{% include common/clause_start.html type="rec" id="sp-yk/suos-vaihtoehtoinen-liittyva-kohde" %}
{% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavakohde" title="Kaavakohteen" %}, johon liittyy lisätieto vaihtoehtoinen, assosiaation ```liittyvaKohde``` tulee viitata näiden vaihtoehtoista maankäyttöä kuvaaviin Kaavakohteisiin. Assosiaation ```rooli```-attribuutin arvon tulee ilmaista, että liittyvä kohde on vaihtoehtoinen." %}
{% include common/clause_end.html %}