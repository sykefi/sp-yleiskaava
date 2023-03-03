---
layout: "default"
description: ""
id: "rakennuspaikka"
status: "Ehdotus"
---
# Kaavamääräykset - Rakennuspaikka

## Rakennuspaikka
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/rakennuspaikka>
{% include common/clause_start.html type="req" id="sp-yk/vaat-rakennuspaikka-lisatiedot" %}
```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#lisatieto" title="Lisatieto" %} jonka laji on [Käyttötarkoituskohdistus](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/kayttotarkoituskohdistus), jolla on täsmälleen yksi ```arvo``` lajia {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} joka viittaa johonkin [Rakennusluokitus 2018](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712)-koodiston koodiin. Mikäli vähintään yksi lisätieto on annettu, saa rakennuspaikkaan rakentaa vain lisätietojen avulla rajattuja rakennustyyppejä. Muun tyyppiset arvot eivät ole sallittuja.  
<!-- MRL 44 §, 72 § ja 77 § huomiointi -->
{% include common/clause_end.html %}

Esimerkkejä:<br>
* ```Asunnon rakennuspaikka``` voidaan määritellä käyttötarkoituskohdistus-lisätiedon Rakennusluokituksen 2018:n mukaisella arvolla [Asuinrakennukset](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712/code/01).

* ```Loma-asunnon rakennuspaikka``` voidaan määritellä käyttötarkoituskohdistus-lisätiedon Rakennusluokituksen 2018:n mukaisella arvolla [Vapaa-ajan asuinrakennukset](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712/code/02).

* ```Saunan rakennuspaikka``` voidaan määritellä käyttötarkoituskohdistus-lisätiedon Rakennusluokituksen 2018:n mukaisella arvolla [Saunarakennukset](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712/code/1910).

* ```Maatalouden talouskeskuksen rakennuspaikka``` voidaan määritellä kahden käyttötarkoituskohdistus-lisätiedon yhdistelmällä, arvoina Rakennusluokituksen 2018:n mukaiset [Asuinrakennukset](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712/code/01) ja [Maatalousrakennukset ja eläinsuojat](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712/code/14) yhdistelmällä.

{% include common/question.html content="Nykyoppaissahan näitä ei varsinaisesti edes ole. Käytännössä yleiskaavan aluevarauksen päälle on osoitettu pistemäinen kohde uudelle rakennuspaikalle. Oletuksena saaden aluevarauksen mukaisen käyttötarkoituksen. Onko tämä aiemminkin esitetty soveltamistapa ajateltu vaikeamman kautta?" %}