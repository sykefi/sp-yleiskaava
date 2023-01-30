---
layout: "default"
description: ""
id: "rakentaminen"
status: "Ehdotus"
---
# Kaavamääräyslajit - rakentaminen
{:.no_toc}

*Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/02>

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

1. 
{:toc}

## Rakennusala
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0201>

{% include common/clause_start.html type="req" id="prof-yk/vaat-rakennusala-maar" %}
Ilmaisee, että kaavakohteen alue on rakennusala. Mikäli rakennusaloja on määritelty jonkin suuremman kaavakohteen alueen sisälle, tulee rakennukset suuremman kaavakohteen alueella rakentaa siten, että ne sijoittuvat kokonaan jokin rakennusalan sisälle.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-rakennusala-arvot" %}
```arvo```-attribuutin mahdolliset arvot ovat seuraavat:
* Nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} jotka kuvaa rakennusalalle rakennettavaksi tarkoitetun rakennuksen lajin viittaamalla koodistoon [Rakennusluokitus 2018](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712).
* Nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-rakennusala-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Rakennuspaikka
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/rakennuspaikka>
{% include common/clause_start.html type="req" id="prof-yk/vaat-rakennuspaikka-lisatiedot" %}
```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#lisatieto" title="Lisatieto" %} jonka laji on [Käyttötarkoituskohdistus](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/kayttotarkoituskohdistus), jolla on täsmälleen yksi ```arvo``` lajia {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} joka viittaa johonkin [Rakennusluokitus 2018](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712)-koodiston koodiin. Mikäli vähintään yksi lisätieto on annettu, saa rakennuspaikkaan rakentaa vain lisätietojen avulla rajattuja rakennustyyppejä. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

Esimerkkejä:<br>
```Asunnon rakennuspaikka``` voidaan määritellä käyttötarkoituskohdistus-lisätiedon  Rakennusluokituksen 2018:n mukaisella arvolla [Asuinrakennukset](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712/code/01).

```Loma-asunnon rakennuspaikka``` voidaan määritellä käyttötarkoituskohdistus-lisätiedon  Rakennusluokituksen 2018:n mukaisella arvolla [Vapaa-ajan asuinrakennukset](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712/code/02).

```Saunan rakennuspaikka``` voidaan määritellä käyttötarkoituskohdistus-lisätiedon  Rakennusluokituksen 2018:n mukaisella arvolla [Saunarakennukset](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712/code/1910).


## Maatalouden talouskeskuksen rakennuspaikka
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0206>

{% include common/clause_start.html type="req" id="prof-yk/vaat-mtk-rakennuspaikka-maar" %}
Ilmaisee, että kaavakohteen geometria kuvaa paikkaa, jolla on tai johon voidaan rakentaa tilan päärakennuksen ja sen yhteydessä olevien talousrakennusten muodostama kokonaisuus.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-mtk-rakennuspaikka-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-mtk-rakennuspaikka-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}


## Sallittu kokonaiskerrosala
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0207>

{% include common/clause_start.html type="req" id="prof-yk/vaat-sallittu-kerrosala-arvot" %}
```arvo```-attribuutin mahdolliset arvot ovat seuraavat:
* Yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvovali" title="NumeerinenArvovali" %} joka kertoo sallitun rakentamiseen kokonaismäärän kerrosneliömetreinä (```k-m2```) sen kaavakohteen aluella, johon kaavamääräys on liitetty. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta.
* Nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.
{% include common/clause_end.html %}


{% include common/clause_start.html type="req" id="prof-yk/vaat-sallittu-kerrosala-lisatiedot" %}
```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#lisatieto" title="Lisatieto" %} jonka laji on [Käyttötarkoituksen osuus kerrosalasta](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_YK/code/01), jolla on täsmälleen kaksi arvoa:
* Yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvovali" title="NumeerinenArvovali" %} jotka kertovat sallitun tiettyyn käyttötarkoitukseen kohdistettavan kerroalan määrän koko sallitusta kerrosalasta joko kerrosneliömetreinä (```k-m2```) tai prosentteina (```%```). Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta.
* Yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} joka viittaa KaavamääraysLaji-koodiston koodin [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/01) johonkin alakoodiin.
{% include common/clause_end.html %}

Mikäli sallittua rakentamisen määrää ei ole jaoteltu käyttötarkoituksittain, ei lisätietoja käytetä.

## Tehokkuusluku
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/tehokkuusluku>

Tehokkuusluku-koodin avulla voidaan ilmaista aluetehokkuus, korttelitehokkuus ja tonttitehokkuus, riippuen siitä, mille kaavakohteelle tehokkuusluku-koodi on osoitettu.

{% include common/clause_start.html type="req" id="prof-yk/vaat-tehokkuusluku-arvot" %}
```arvo```-attribuutin arvona saa esiintyä joko yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvovali" title="NumeerinenArvovali" %} jotka kertovat rakennustehokkuden, eli alueen rakennusten yhteenlasketun kerrosalan suhteessa alueen pinta-alaan, sen kaavakohteen aluella, johon kaavamääräys on liitetty. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta. Ilmaistaan tehokkuuslukuna ```e```, yksikkönä ```k-m2/m2```. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-vaat-tehokkuusluku-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Sallittujen rakennuspaikkojen lukumäärä
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0211>

{% include common/clause_start.html type="req" id="prof-yk/vaat-rakennuspaikkojen-maara-arvot" %}
```arvo```-attribuutin arvona saa esiintyä yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} joka kertoo sallitun rakennuspaikkojen enimmäismäärän sen kaavakohteen aluella, johon kaavamääräys on liitetty. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#integer" title="Integer" %}-rajapinta. Yksikköä ei käytetä. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-rakennuspaikkojen-maara-lisatiedot" %}
```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#lisatieto" title="Lisatieto" %} jonka laji on [Käyttötarkoituskohdistus](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_YK/code/02), jolla on täsmälleen yksi ```arvo``` lajia {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} joka viittaa johonkin [Rakennusluokitus 2018](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712)-koodiston koodiin. Mikäli vähintään yksi lisätieto on annettu, koskee rakennuspaikkojen lukumäärä vain lisätietojen avulla rajattuja rakennustyyppejä. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/question.html content="Pitäisikö poistaa otsikosta 'Sallittujen', AK-koodistossa on 'Rakennuspaikkojen lukumäärä" %}

## Rakennuspaikan vähimmäiskoko
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0212>

{% include common/clause_start.html type="req" id="prof-yk/vaat-rak-paik-koko-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} joka kertoo kaavakohteen alueen rakennuspaikkojen vähimmäiskoon neliömetreinä (```m2```). Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-rak-paik-koko-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Sallittu tuulivoimaloiden määrä
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0213>

{% include common/clause_start.html type="req" id="prof-yk/vaat-tuulivoimaloiden-maara-arvot" %}
```arvo```-attribuutin arvona saa esiintyä joko yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvovali" title="NumeerinenArvovali" %} jotka kertovat tuulivoimaloiden enimmäismäärän sen kaavakohteen aluella, johon kaavamääräys on liitetty. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#integer" title="Integer" %}-rajapinta. Yksikköjä ei käytetä. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-yk/vaat-tuulivoimaloiden-maara-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}