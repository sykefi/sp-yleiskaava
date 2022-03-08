---
layout: "default"
description: ""
id: "kehittamisperiaatteet"
status: "Ehdotus"
---
# Kaavamääräyslajit - kehittämisperiaatteet
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/04>

Ryhmittelyotsikko, vain [alakoodeja](../../looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar) käytetään.

1. 
{:toc}

## Yhdyskuntarakenteen laajenemissuunta
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0401>

{% include clause_start.html type="req" id="prof-yk/vaat-yhdyskuntarakenteen-laajenemissuunta-arvot" %}
```arvo```-attribuutin mahdolliset arvot ovat seuraavat:
* Yksi [NumeerinenArvo](../../looginenmalli/dokumentaatio/#numeerinenarvo) tai yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali), joka kertoo yhdyskuntarakenteen laajenemissuunnan asteina (```deg```). Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava [Real](../../looginenmalli/dokumentaatio/#real)-rajapinta.
* Nolla tai useampi [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), jotka viittaavat koodiston KaavamääraysLaji koodin [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/01) alakoodeihin, ja joiden avulla voidaan kuvata laajenevan yhdyskuntarakenteen käyttötarkoitukset.

Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-yhdyskuntarakenteen-laajenemissuunta-geometria" %}
[Kaavakohteen](../../looginenmalli/dokumentaatio/#kaavakohde), johon liittyy Yhdyskuntarakenteen laajenemissuunta -lajin kaavamääräys, ```geometria```-attribuutin arvon tulee olla pistemäinen, ja sen tulee sijaita paikassa, josta yhdyskuntarakenne laajenee ```arvo```-attribuutin osoittamaan suuntaan.  
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-yhdyskuntarakenteen-laajenemissuunta-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Yhdyskuntarakenteen mahdollinen laajenemisalue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0402>

{% include clause_start.html type="req" id="prof-yk/vaat-yhdyskuntarakenteen-laajenemisalue-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), jotka viittaavat koodiston KaavamääraysLaji koodin [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/01) alakoodeihin, ja joiden avulla voidaan kuvata laajenevan yhdyskuntarakenteen käyttötarkoitukset. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-yhdyskuntarakenteen-laajenemisalue-geometria" %}
[Kaavakohteen](../../looginenmalli/dokumentaatio/#kaavakohde), johon liittyy Yhdyskuntarakenteen mahdollinen laajenemisalue -lajin kaavamääräys, ```geometria```-attribuutin arvon tulee olla aluemainen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-yhdyskuntarakenteen-laajenemissuunta-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Alueen eheyttämis- tai tiivistämistarve
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0403>

{% include clause_start.html type="req" id="prof-yk/vaat-alueen-eheyttamis-tiivistamistarve-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jonka sisällä kaupunkirakennetta on tarpeen eheyttää tai tiivistää.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-alueen-eheyttamis-tiivistamistarve-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.  Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-alueen-eheyttamis-tiivistamistarve-geometria" %}
[Kaavakohteen](../../looginenmalli/dokumentaatio/#kaavakohde), johon liittyy Alueen eheyttämis- tai tiivistämistarve -lajin kaavamääräys, ```geometria```-attribuutin arvon tulee olla aluemainen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-alueen-eheyttamis-tiivistamistarve-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Ohjeellinen tai vaihtoehtoinen tielinjaus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0404>

{% include clause_start.html type="req" id="prof-yk/vaat-ohjeellinen-vaihtoehtoinen-tielinjaus-maar" %}
Ilmaisee, että kaavakohde kuvaa tielinjauksen, jonka sijainti on ohjeellinen tai joka on vaihtoehtoinen toisen kaavassa esitetyn tielinjauksen kanssa.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-ohjeellinen-vaihtoehtoinen-tielinjaus-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.  Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-ohjeellinen-vaihtoehtoinen-tielinjaus-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-ohjeellinen-vaihtoehtoinen-tielinjaus-liittyva-kohde" %}
[Kaavakohteen](../../looginenmalli/dokumentaatio/#kaavakohde), johon liittyy Ohjeellinen tai vaihtoehtoinen tielinjaus -lajin kaavamääräys, ja joka kuvaa yhden tai useamman toisen tielinjauksen kanssa vaihtoehtoista tielinjausta, assosiaation ```liittyvaKohde``` tulee viitata näitä vaihtoehtoisia tielinjauksia kuvaaviin Kaavakohteisiin. Assosiaation ```rooli```-attribuutin arvon tulee ilmaista, että liittyvä kohde on vaihtoehtoinen." %}
{% include clause_end.html %}

{% include question.html content="Tielinjaus-määräyksestä tulisi voida päätellä tien toiminnallinen luokitus, jota voidaan käyttää esim. kaavan visualisoinnissa. Tulisiko tätä varten lisätä lisätiedon laji 'Toiminnallinen luokka' ja koodisto 'Maanteiden ja katujen toiminnallinen luokitus', jossa esimerkiksi arvot 'Valtatie', 'Kantatie' ja 'Seututie', 'Yhdystie', 'Pääkatu', 'Alueellinen kokoojakatu', 'Paikallinen kokoojakatu', 'Tonttikatu' ks. [Väyläverkoston yhtenäinen luokittelu kunnossapidon suunnittelua varten](https://julkaisut.vayla.fi/pdf3/lts_2012-10_vaylaverkoston_yhtenainen_web.pdf) (Liikenneviraston tutkimuksia ja selvityksiä 10-2012) ja [Katupoikkileikkausten suunnitteluohjeet](https://www.hel.fi/hel2/ksv/Aineistot/Liikennesuunnittelu/Autoilu/katu1.pdf) (Helsingin kaupunki, Kaupunkisuunnitteluviraston Liikennesuunnitteluosasto 2001), sekä toinen lisätiedon laji 'Ajoratojen lukumäärä', jolle tässä NumeerinenArvo tai NumeerinenArvovali?" %}

## Tieliikenteen yhteystarve
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0405>

{% include clause_start.html type="req" id="prof-yk/vaat-tieliikenteen-yhteystarve-maar" %}
Ilmaisee, että kaavakohde kuvaa tieliikenteen yhteystarpeen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-tieliikenteen-yhteystarve-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.  Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-tieliikenteen-yhteystarve-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include question.html content="Tieliikenteen yhteystarve -määräyksestä tulisi voida päätellä tien toiminnallinen luokitus, jota voidaan käyttää esim. kaavan visualisoinnissa. Tulisiko tätä varten lisätä lisätiedon laji 'Toiminnallinen luokka' ja koodisto 'Maanteiden ja katujen toiminnallinen luokitus', jossa esimerkiksi arvot 'Valtatie', 'Kantatie' ja 'Seututie', 'Yhdystie', 'Pääkatu', 'Alueellinen kokoojakatu', 'Paikallinen kokoojakatu', 'Tonttikatu' ks. [Väyläverkoston yhtenäinen luokittelu kunnossapidon suunnittelua varten](https://julkaisut.vayla.fi/pdf3/lts_2012-10_vaylaverkoston_yhtenainen_web.pdf) (Liikenneviraston tutkimuksia ja selvityksiä 10-2012) ja [Katupoikkileikkausten suunnitteluohjeet](https://www.hel.fi/hel2/ksv/Aineistot/Liikennesuunnittelu/Autoilu/katu1.pdf) (Helsingin kaupunki, Kaupunkisuunnitteluviraston Liikennesuunnitteluosasto 2001), sekä toinen lisätiedon laji 'Ajoratojen lukumäärä', jolle tässä NumeerinenArvo tai NumeerinenArvovali?" %}

## Joukkoliikenteen kehittämiskäytävä tai yhteystarve
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0406>

{% include clause_start.html type="req" id="prof-yk/vaat-joukkoliikenteen-yhteystarve-maar" %}
Ilmaisee, että kaavakohde kuvaa joukkoliikenteen kehittämiskäytävän tai yhteystarpeen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-joukkoliikenteen-yhteystarve-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-joukkoliikenteen-yhteystarve-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Kevyen liikenteen yhteystarve
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0407>

{% include clause_start.html type="req" id="prof-yk/vaat-kevyen-liikenteen-yhteystarve-maar" %}
Ilmaisee, että kaavakohde kuvaa kevyen liikenteen yhteystarpeen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-kevyen-liikenteen-yhteystarve-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-kevyen-liikenteen-yhteystarve-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Johdon, putken tai linjan yhteystarve
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0408>

{% include clause_start.html type="req" id="prof-yk/vaat-johdon-putken-linjan-yhteystarve-maar" %}
Ilmaisee, että kaavakohde kuvaa johdon, putken tai linjan yhteystarpeen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-johdon-putken-linjan-yhteystarve-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-johdon-putken-linjan-yhteystarve-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include question.html content="Tarvitaanko koodistoon perustuva luokittelu johtoille, putkille ja linjoille?" %}

## Viheryhteystarve
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0409>

{% include clause_start.html type="req" id="prof-yk/vaat-viheryhteystarve-maar" %}
Ilmaisee, että kaavakohde kuvaa viheryhteystarpeen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-viheryhteystarve-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-viheryhteystarve-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Virkistyksen yhteystarve
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0410>

{% include clause_start.html type="req" id="prof-yk/vaat-virkistyksen-yhteystarve-maar" %}
Ilmaisee, että kaavakohde kuvaa virkistyksen yhteystarpeen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-virkistyksen-yhteystarve-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-virkistyksen-yhteystarve-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Julkisen virkistyksen kehittämistarve
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0411>

{% include clause_start.html type="req" id="prof-yk/vaat-julkisen-virkistyksen-kehittamistarve-maar" %}
Ilmaisee, että kaavakohde kuvaa julkisen virkistyksen kehittämistarpeen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-julkisen-virkistyksen-kehittamistarve-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-julkisen-virkistyksen-kehittamistarve-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Kävely-ympäristön kehittämistarve
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0412>

{% include clause_start.html type="req" id="prof-yk/vaat-kavely-ympariston-kehittamistarve-maar" %}
Ilmaisee, että kaavakohde kuvaa kävely-ympäristön kehittämistarpeen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-kavely-ympariston-kehittamistarve-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-kavely-ympariston-kehittamistarve-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Kaupunkikuvallinen kehittämistarve
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0413>

{% include clause_start.html type="req" id="prof-yk/vaat-kaupunkikuvallinen-kehittamistarve-maar" %}
Ilmaisee, että kaavakohde kuvaa kaupunkikuvallisen kehittämistarpeen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-kaupunkikuvallinen-kehittamistarve-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-kaupunkikuvallinen-kehittamistarve-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Meluntorjuntatarve
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0414>

{% include clause_start.html type="req" id="prof-yk/vaat-meluntorjuntatarve-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolla esiintyy siinä määrin melua, että siitä voi aiheutua merkittävää haittaa. Meluntorjunta tulee huomioida alueen käyttöä ja rakentamista suunniteltaessa.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-meluntorjuntatarve-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), jolla kuvataan melun tyyppiä ja haitallisuutta. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-meluntorjuntatarve-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Ympäristö- tai maisemavaurion korjaustarve
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0415>

{% include clause_start.html type="req" id="prof-yk/vaat-ymparisto-maisemavaurion-korjaustarve-maar" %}
Ilmaisee, että kaavakohde kuvaa ympäristö- ja maisemavaurion korjaustarpeen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-ymparisto-maisemavaurion-korjaustarve-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-ymparisto-maisemavaurion-korjaustarve-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Terveyshaitan poistamistarve
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0416>

{% include clause_start.html type="req" id="prof-yk/vaat-terveyshaitan-korjaustarve-maar" %}
Ilmaisee, että kaavakohde kuvaa terveyshaitan korjaustarpeen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-terveyshaitan-korjaustarve-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-terveyshaitan-korjaustarve-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Uusi tai olennaisesti muuttuva alue 
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0418>

{% include clause_start.html type="req" id="prof-yk/vaat-uusi-olennaisesti-muuttuva-alue-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, joka kaavan vaikutuksesta muuttuu olennaisesti toisenlaiseksi.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-uusi-olennaisesti-muuttuva-alue-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-uusi-olennaisesti-muuttuva-alue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Pienin toimenpitein kehitettävä alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0419>

{% include clause_start.html type="req" id="prof-yk/vaat-pienin-toimenpitein-keh-alue-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, joka kaavan kehitetään ohjausvaikutuksella pienin toimenpitein.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-pienin-toimenpitein-keh-alue-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-pienin-toimenpitein-keh-alue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Virkistyskohde
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/1006>

{% include clause_start.html type="req" id="prof-yk/vaat-virkistyskohde-maar" %}
Ilmaisee, että kaavakohde kuvaa yleiseen virkistyskäyttöön tarkoitetun pienimuotoisen alueen tai kohteen.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-virkistyskohde-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-virkistyskohde-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include question.html content="Löytyisikö tälle parempi yläluokka?" %}

## Muu kehittämisperiaate
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0421>

{% include clause_start.html type="req" id="prof-yk/vaat-muu-kehittamisperiaate-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka kuvaa kaavamääräyksen.  Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-yk/vaat-muu-kehittamisperiaate-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}