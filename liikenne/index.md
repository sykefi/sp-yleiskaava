---
layout: "default"
description: ""
id: "liikenne"
status: "Ehdotus"
---
# Kaavamääräyslajit - liikenne
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/03>

Ryhmittelyotsikko, vain [alakoodeja](../../looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar) käytetään.

{% include question.html content="Koodistossa koodit aakkosjärjestyksessä, saman tyyppiset asiat kaukana toisistaan (esim. 'Alueverkon pyöräilyreitti' ja 'Pyöräilyn pää- tai runkoreitti', 'Seutuverkon pyöräilyreitti'). Onko muu (järjestyksellä) ryhmittely tarpeen?" %}

1.
{:toc}

## Alueverkon pyöräilyreitti
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0301>

{% include clause_start.html type="req" id="prof-yk/vaat-alueverkon-pyorailyreitti-maar" %}
Ilmaisee, että kaavakohde kuvaa alueverkon pyöräilyreitin.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-alueverkon-pyorailyreitti-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-alueverkon-pyorailyreitti-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include question.html content="Pitäisikö yleistää muotoon 'Pyöräilyverkon reitti' ja lisätä lisätiedon laji 'Toiminnallinen luokka' ja koodisto 'Pyöräilyverkon toiminnallinen luokitus', jossa arvot 'Pääverkko', 'Alueellinen verkko' ja 'Paikallinen verkko', ks. [Jalankulku- ja pyöräilyväylien suunnittelu](https://julkaisut.vayla.fi/pdf8/lo_2014-11_jalankulku_pyorailyvaylien_web.pdf) (Liikenneviraston ohjeita 11-2014)?" %}

{% include question.html content="Mikä on tämän suhde määräykseen 'Pyöräilyn pää- tai runkoreitti'? Onko 'pyöräilyn pääverkon reitti' sama asia kuin 'pyöräilyn pääreitti' tai pyöräilyn runkoreitti'?" %}

## Eritasoliittymä
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0302>

{% include clause_start.html type="req" id="prof-yk/vaat-eritasoliittyma-maar" %}
Ilmaisee, että kaavakohde kuvaa eritasolittymän.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-eritasoliittyma-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-eritasoliittyma-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Eritasoristeys ilman liittymää
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0303>

{% include clause_start.html type="req" id="prof-yk/vaat-eritasoristeys-maar" %}
Ilmaisee, että kaavakohde kuvaa eritasoristeyksen ilman littymää.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-eritasoristeys-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-eritasoristeys-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Joukkoliikenteen runkoyhteys
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0304>

{% include clause_start.html type="req" id="prof-yk/vaat-joukkoliikenteen-runkoyhteys-maar" %}
Ilmaisee, että kaavakohde kuvaa joukkoliikenteen runkoyhteyden.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-joukkoliikenteen-runkoyhteys-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-joukkoliikenteen-runkoyhteys-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Kaksiajoratainen päätie tai -katu
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0305>

{% include clause_start.html type="req" id="prof-yk/vaat-paatie-katu-maar" %}
Ilmaisee, että kaavakohde kuvaa päätien tai -kadun.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-paatie-katu-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-paatie-katu-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include question.html content="Koodistossa 'Kaksiajoratainen päätie/-katu', kumpi muutetaan?" %}

{% include question.html content="Tulisiko yleistää muotoon 'Tie tai katu', ja lisätä lisätiedon laji 'Toiminnallinen luokka' ja koodisto 'Maanteiden ja katujen toiminnallinen luokitus', jossa esimerkiksi arvot 'Valtatie', 'Kantatie' ja 'Seututie', 'Yhdystie', 'Pääkatu', 'Alueellinen kokoojakatu', 'Paikallinen kokoojakatu', 'Tonttikatu' ks. [Väyläverkoston yhtenäinen luokittelu kunnossapidon suunnittelua varten](https://julkaisut.vayla.fi/pdf3/lts_2012-10_vaylaverkoston_yhtenainen_web.pdf) (Liikenneviraston tutkimuksia ja selvityksiä 10-2012) ja [Katupoikkileikkausten suunnitteluohjeet](https://www.hel.fi/hel2/ksv/Aineistot/Liikennesuunnittelu/Autoilu/katu1.pdf) (Helsingin kaupunki, Kaupunkisuunnitteluviraston Liikennesuunnitteluosasto 2001), sekä toinen lisätiedon laji 'Ajoratojen lukumäärä', jolle tässä NumeerinenArvo tai NumeerinenArvovali?" %}

## Kevyen liikenteen reitti
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0306>

{% include clause_start.html type="req" id="prof-yk/vaat-kevyen-liikenteen-reitti-maar" %}
Ilmaisee, että kaavakohde kuvaa kevyen liikenteen (jalankulku tai pyöräily) reitin.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-kevyen-liikenteen-reitti-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-kevyen-liikenteen-reitti-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include question.html content="Kevyt liikenne terminä, jalankulku ja pyöräily erikseen?" %}

{% include question.html content="Miten suhtautuu määräykseen 'Ulkoilu- tai virkistysreitti'?" %}

{% include question.html content="Onko tavanomainen kevyen liikenteen/pyöräily/jalankulku väylä sama vai eri asia kuin tässä tarkoitettu reitti?" %}

## Laivaväylä 
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0307>

{% include clause_start.html type="req" id="prof-yk/vaat-laivavayla-maar" %}
Ilmaisee, että kaavakohde kuvaa laivaväylän.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-laivavayla-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-laivavayla-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Liikennetunneli
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0308>

{% include clause_start.html type="req" id="prof-yk/vaat-liikennetunneli-maar" %}
Ilmaisee, että kaavakohde kuvaa liikennetunnelin.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-liikennetunneli-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-liikennetunneli-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Liittymä
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0309>

{% include clause_start.html type="req" id="prof-yk/vaat-liittyma-maar" %}
Ilmaisee, että kaavakohde kuvaa liikenneliittymän.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-liittyma-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-liittyma-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Linja-autoasema / julkisen liikenteen vaihtopaikka / matkakeskus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0310>

{% include clause_start.html type="req" id="prof-yk/vaat-linja-autoas-vaihtop-matkakeskus-maar" %}
Ilmaisee, että kaavakohde kuvaa linja-autoaseman, julkisen liikenteen vaihtopaikan tai matkakeskuksen alueen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-linja-autoas-vaihtop-matkakeskus-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-linja-autoas-vaihtop-matkakeskus-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Metroasema
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0311>

{% include clause_start.html type="req" id="prof-yk/vaat-metroasema-maar" %}
Ilmaisee, että kaavakohde kuvaa metroaseman alueen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-metroasema-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-metroasema-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include question.html content="Onko tarpeenn kuvata (maanalaisen) metroaseman sisäänkäynti omana määräyksenään?" %}

## Metrolinja
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0312>

{% include clause_start.html type="req" id="prof-yk/vaat-metrolinja-maar" %}
Ilmaisee, että kaavakohde kuvaa metrolinjan.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-metrolinja-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-metrolinja-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Moottoritie tai moottoriliikennetie
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0313>

{% include clause_start.html type="req" id="prof-yk/vaat-moottoritie-maar" %}
Ilmaisee, että kaavakohde kuvaa moottoritien tai moottoriliikennetien.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-moottoritie-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-moottoritie-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include question.html content="Tulisiko yleistää muotoon 'Tie tai katu', ja lisätä lisätiedon laji 'Toiminnallinen luokka' ja koodisto 'Maanteiden ja katujen toiminnallinen luokitus', jossa esimerkiksi arvot 'Valtatie', 'Kantatie' ja 'Seututie', 'Yhdystie', 'Pääkatu', 'Alueellinen kokoojakatu', 'Paikallinen kokoojakatu', 'Tonttikatu' ks. [Väyläverkoston yhtenäinen luokittelu kunnossapidon suunnittelua varten](https://julkaisut.vayla.fi/pdf3/lts_2012-10_vaylaverkoston_yhtenainen_web.pdf) (Liikenneviraston tutkimuksia ja selvityksiä 10-2012) ja [Katupoikkileikkausten suunnitteluohjeet](https://www.hel.fi/hel2/ksv/Aineistot/Liikennesuunnittelu/Autoilu/katu1.pdf) (Helsingin kaupunki, Kaupunkisuunnitteluviraston Liikennesuunnitteluosasto 2001), sekä toinen lisätiedon laji 'Ajoratojen lukumäärä', jolle tässä NumeerinenArvo tai NumeerinenArvovali?" %}

{% include question.html content="Koodistossa 'Moottori- tai moottoriliikennetie, kumpi muutetaan?" %}

## Moottorikelkkailureitti
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0314>

{% include clause_start.html type="req" id="prof-yk/vaat-moottorikelkkailureitti-maar" %}
Ilmaisee, että kaavakohde kuvaa moottorikelkkailureitin.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-moottoritie-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-moottoritie-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Pysäkki tai seisake
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0315>

{% include clause_start.html type="req" id="prof-yk/vaat-pysakki-seisake-maar" %}
Ilmaisee, että kaavakohde kuvaa moottorikelkkailureitin.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-pysakki-seisake-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-pysakki-seisake-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include tip.html content="Pysäkin tai seisakkeen kuvaava Kaavakohde voidaan linkittää reitin tai väylän kuvaavaan Kaavakohteeseen ```liittyvaKohde```-assosiaation avulla." %}

{% include question.html content="Koodistossa 'Pysäkki/seisake, kumpi muutetaan?" %}

## Pyöräilyn pää- tai runkoreitti
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0316>

{% include clause_start.html type="req" id="prof-yk/vaat-pyorailyn-paareitti-maar" %}
Ilmaisee, että kaavakohde kuvaa pyöräilyn pää- tai runkoreitin.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-pyorailyn-paareitti-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-pyorailyn-paareitti-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include question.html content="Koodistossa 'pää-/runkoreitti', kumpi muutetaan?" %}

{% include question.html content="Ehkä tarpeeton, ks. avoin kysymys kohdassa [Alueverkon pyöräilyreitti](#alueverkon-py%C3%B6r%C3%A4ilyreitti)?" %}

## Päärata
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0317>

{% include clause_start.html type="req" id="prof-yk/vaat-paarata-maar" %}
Ilmaisee, että kaavakohde kuvaa raideliikenteen pääradan.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-paarata-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-paarata-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Raitiotie tai pikaraitiotie
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0318>

{% include clause_start.html type="req" id="prof-yk/vaat-raitiotie-pikaraitiotie-maar" %}
Ilmaisee, että kaavakohde kuvaa raitiotien tai pikaraitiotien.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-raitiotie-pikaraitiotie-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-raitiotie-pikaraitiotie-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include question.html content="Koodistossa 'Raitiotie/Pikaraitiotie', kumpi muutetaan?" %}

## Ratsastusreitti
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0319>

{% include clause_start.html type="req" id="prof-yk/vaat-ratsastusreitti-maar" %}
Ilmaisee, että kaavakohde kuvaa ratsastusreitin.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-ratsastusreitti-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-ratsastusreitti-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Rautatieasema
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0320>

{% include clause_start.html type="req" id="prof-yk/vaat-rautatieasema-maar" %}
Ilmaisee, että kaavakohde kuvaa rautatieaseman alueen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-ratsastusreitti-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-ratsastusreitti-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Seututie tai pääkatu
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0321>

{% include clause_start.html type="req" id="prof-yk/vaat-seututie-paakatu-maar" %}
Ilmaisee, että kaavakohde kuvaa seututien tai pääkadun.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-seututie-paakatu-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-seututie-paakatu-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include question.html content="Koodistossa 'Seututie/pääkatu', kumpi muutetaan?" %}

{% include question.html content="Tulisiko yleistää muotoon 'Tie tai katu', ja lisätä lisätiedon laji 'Toiminnallinen luokka' ja koodisto 'Maanteiden ja katujen toiminnallinen luokitus', jossa esimerkiksi arvot 'Valtatie', 'Kantatie' ja 'Seututie', 'Yhdystie', 'Pääkatu', 'Alueellinen kokoojakatu', 'Paikallinen kokoojakatu', 'Tonttikatu' ks. [Väyläverkoston yhtenäinen luokittelu kunnossapidon suunnittelua varten](https://julkaisut.vayla.fi/pdf3/lts_2012-10_vaylaverkoston_yhtenainen_web.pdf) (Liikenneviraston tutkimuksia ja selvityksiä 10-2012) ja [Katupoikkileikkausten suunnitteluohjeet](https://www.hel.fi/hel2/ksv/Aineistot/Liikennesuunnittelu/Autoilu/katu1.pdf) (Helsingin kaupunki, Kaupunkisuunnitteluviraston Liikennesuunnitteluosasto 2001), sekä toinen lisätiedon laji 'Ajoratojen lukumäärä', jolle tässä NumeerinenArvo tai NumeerinenArvovali?" %}

## Seutuverkon pyöräilyreitti
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0322>

{% include clause_start.html type="req" id="prof-yk/vaat-seutuverkon-pyorailyreitti-maar" %}
Ilmaisee, että kaavakohde kuvaa seutuverkon pyöräilyreitin, eli kuntaa laajemmalla alueella oleva pyöräilyn verkon, joka muodostuu eri kuntien pääverkkojen osista.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-seutuverkon-pyorailyreitti-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-seutuverkon-pyorailyreitti-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}


## Suuntaisliittymä
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0323>

{% include clause_start.html type="req" id="prof-yk/vaat-suuntaisliittyma-maar" %}
Ilmaisee, että kaavakohde kuvaa suuntaisliittymän alueen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-suuntaisliittyma-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-suuntaisliittyma-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}


## Ulkoilu- tai virkistysreitti
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0324>

{% include clause_start.html type="req" id="prof-yk/vaat-ulkoilu-virkistysreitti-maar" %}
Ilmaisee, että kaavakohde kuvaa ulkoilu- tai virkistysreitin.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-ulkoilu-virkistysreitti-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-ulkoilu-virkistysreitti-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Valta- tai kantatie
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0325>

{% include clause_start.html type="req" id="prof-yk/vaat-valta-kantatie-maar" %}
Ilmaisee, että kaavakohde kuvaa valta- tai kantatien.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-valta-kantatie-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-valta-kantatie-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include question.html content="Koodistossa 'Valtatie/kantatie', kumpi muutetaan?" %}

{% include question.html content="Tulisiko yleistää muotoon 'Tie tai katu', ja lisätä lisätiedon laji 'Toiminnallinen luokka' ja koodisto 'Maanteiden ja katujen toiminnallinen luokitus', jossa esimerkiksi arvot 'Valtatie', 'Kantatie' ja 'Seututie', 'Yhdystie', 'Pääkatu', 'Alueellinen kokoojakatu', 'Paikallinen kokoojakatu', 'Tonttikatu' ks. [Väyläverkoston yhtenäinen luokittelu kunnossapidon suunnittelua varten](https://julkaisut.vayla.fi/pdf3/lts_2012-10_vaylaverkoston_yhtenainen_web.pdf) (Liikenneviraston tutkimuksia ja selvityksiä 10-2012) ja [Katupoikkileikkausten suunnitteluohjeet](https://www.hel.fi/hel2/ksv/Aineistot/Liikennesuunnittelu/Autoilu/katu1.pdf) (Helsingin kaupunki, Kaupunkisuunnitteluviraston Liikennesuunnitteluosasto 2001), sekä toinen lisätiedon laji 'Ajoratojen lukumäärä', jolle tässä NumeerinenArvo tai NumeerinenArvovali?" %}

## Varattu joukkoliikenteelle
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0326>

{% include clause_start.html type="req" id="prof-yk/vaat-valta-kantatie-maar" %}
Ilmaisee, että kaavakohde kuvaa joukkoliikenteelle varatun alueen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-valta-kantatie-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-valta-kantatie-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}


## Varikko
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0327>

{% include clause_start.html type="req" id="prof-yk/vaat-varikko-maar" %}
Ilmaisee, että kaavakohde kuvaa varikkoalueen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-varikko-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-varikko-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Venesatama tai -valkama 
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0328>

{% include clause_start.html type="req" id="prof-yk/vaat-venesatama-valkama-maar" %}
Ilmaisee, että kaavakohde kuvaa venesataman tai valkaman.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-venesatama-valkama-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-venesatama-valkama-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include tip.html content="Venesataman tai valkaman kuvaava Kaavakohde voidaan linkittää reitin tai väylän kuvaavaan Kaavakohteeseen ```liittyvaKohde```-assosiaation avulla." %}

## Veneväylä
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0329>

{% include clause_start.html type="req" id="prof-yk/vaat-venevayla-maar" %}
Ilmaisee, että kaavakohde kuvaa veneväylän.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-venevayla-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-venevayla-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include question.html content="Tulisiko yleistää muotoon 'vesiväylä', ja lisätä lisätiedon laji 'Toiminnallinen luokka' ja koodisto 'Vesiväylän toiminnallinen luokitus', jossa arvot 'Julkinen kulkuväylä', 'yleinen paikallisväylä' ja 'Yksityinen kulkuväylä', ks. [Vesilaki 3§, Määritelmät](https://finlex.fi/fi/laki/ajantasa/2011/20110587#a587-2011)" %}

#### Yhdys-, sivu- tai kaupunkirata
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0330>

{% include clause_start.html type="req" id="prof-yk/vaat-yhdys-sivu-kaupunkirata-maar" %}
Ilmaisee, että kaavakohde kuvaa raideliikenteen yhdys-, sivu- tai kaupunkiradan.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-yhdys-sivu-kaupunkirata-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-yhdys-sivu-kaupunkirata-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include question.html content="Koodistossa 'Yhdysrataa/sivurata/kaupunkirata', kumpi muutetaan?" %}

## Yhdystie tai kokoojakatu
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0331>

{% include clause_start.html type="req" id="prof-yk/vaat-yhdystie-kokoojakatu-maar" %}
Ilmaisee, että kaavakohde kuvaa yhdystien tai kokoojakadun.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-yhdystie-kokoojakatu-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-yhdystie-kokoojakatu-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include question.html content="Koodistossa 'Yhdystie/kokoojakatu', kumpi muutetaan?" %}

{% include question.html content="Tulisiko yleistää muotoon 'Tie tai katu', ja lisätä lisätiedon laji 'Toiminnallinen luokka' ja koodisto 'Maanteiden ja katujen toiminnallinen luokitus', jossa esimerkiksi arvot 'Valtatie', 'Kantatie' ja 'Seututie', 'Yhdystie', 'Pääkatu', 'Alueellinen kokoojakatu', 'Paikallinen kokoojakatu', 'Tonttikatu' ks. [Väyläverkoston yhtenäinen luokittelu kunnossapidon suunnittelua varten](https://julkaisut.vayla.fi/pdf3/lts_2012-10_vaylaverkoston_yhtenainen_web.pdf) (Liikenneviraston tutkimuksia ja selvityksiä 10-2012) ja [Katupoikkileikkausten suunnitteluohjeet](https://www.hel.fi/hel2/ksv/Aineistot/Liikennesuunnittelu/Autoilu/katu1.pdf) (Helsingin kaupunki, Kaupunkisuunnitteluviraston Liikennesuunnitteluosasto 2001), sekä toinen lisätiedon laji 'Ajoratojen lukumäärä', jolle tässä NumeerinenArvo tai NumeerinenArvovali?" %}

## Liityntäpysäköinti
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0334>

{% include clause_start.html type="req" id="prof-yk/vaat-liityntapysakointi-maar" %}
Ilmaisee, että kaavakohde kuvaa yhdystien tai kokoojakadun.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-liityntapysakointi-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-liityntapysakointi-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include tip.html content="Liityntäpysäköinnin kuvaava Kaavakohde voidaan linkittää liittyviä tie- ja raideliikenteen reittejä ja väyliä kuvaaviin Kaavakohteisiin ```liittyvaKohde```-assosiaation arvojen avulla." %}

## Muu liikenteeseen liittyvä määräys
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0335>

{% include clause_start.html type="req" id="prof-yk/vaat-muu-liikenne-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka kuvaa kaavamääräyksen.  Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-muu-liikenne-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}
