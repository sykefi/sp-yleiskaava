---
layout: "default"
description: ""
id: "yleismaaraykset"
status: "Ehdotus"
---
# Kaavamääräyslajit - yleismääräykset
{:.no_toc}

<!-- Kommentti / Ilpo: Näistä käydään aktiivista säätöä vielä koodisto-, tietomalli yms tietomallin osalta, esim. yleiskaavan oikeusvaikutteisuuden kuvaaminen. Pakko täsmentää vasta kun se keskustelu käyty. Koodistoviittauksia ei ole siten vielä päivitetty. -->

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/08>

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

## Yleismääräys
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0801>

{% include common/clause_start.html type="req" id="sp-yk/vaat-yleismaarays-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka kuvaa kaavamääräyksen. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-yk/vaat-yleismaarays-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Yleiskaavan käyttö rakennusluvan myöntämisen perusteena
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/rakennusluvanPeruste>

Rakennuslupa rakennuksen rakentamiseen voidaan MRL:n [137 §:n](https://www.finlex.fi/fi/laki/ajantasa/1999/19990132#L19P137) 1 momentissa säädetyn estämättä myöntää, jos oikeusvaikutteisessa yleiskaavassa on erityisesti määrätty kaavan tai sen osan käyttämisestä rakennusluvan myöntämisen perusteena. Määräys ei voi koskea aluetta, jolla maankäytön ohjaustarve edellyttää asemakaavan laatimista. Edellytyksenä on lisäksi, että yleiskaava ohjaa riittävästi rakentamista ja muuta maankäyttöä kyseisellä alueella.

{% include common/clause_start.html type="req" id="sp-yk/vaat-yk-kaytto-rakennusluvan-perusteena-maar" %}
Ilmaisee, että {% include common/moduleLink.html moduleId="kaavatiedot" path="dokumentaatio/#kaavakohde" title="Kaavakohde" %} kuvaa alueen, jolle kohdistuvan rakennusluvan myöntämisessä voidaan käyttää yleiskaavaa myöntämisen perusteena.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-yk/vaat-yk-kaytto-rakennusluvan-perusteena-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-yk/vaat-yk-kaytto-rakennusluvan-perusteena-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}