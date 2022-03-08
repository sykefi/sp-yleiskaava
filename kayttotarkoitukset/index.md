---
layout: "default"
description: ""
id: "kayttotarkoitukset"
status: "Ehdotus"
---
# Kaavamääräyslajit - käyttötarkoitukset

## Alueen käyttötarkoitus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/01>

Ryhmittelyotsikko, vain koodin [alakoodeja](../../looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar) käytetään.

{% include common/clause_start.html type="req" id="prof-yk/vaat-alueen-kayttotarkoitus" %}
Kaikkien yleiskaavojen tietoaineistojen sisältämien [Kaavamaarays](../../looginenmalli/dokumentaatio/#kaavamaarays)-luokan instanssien, joiden ```laji```-attribuutin arvo on jokin [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/01)-koodin alakoodi, osalta tulee noudattaa seuraavia rajoituksia:

* ```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.

* ```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi [Lisatieto](../../looginenmalli/dokumentaatio/#lisatieto), jonka laji on [Poisluettava käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_YK/code/04), ja jonka ```arvo```-attribuutin arvoina on yksi tai useampi [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), jotka viittaavat koodiston KaavamääraysLaji koodin [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/01) alakoodeihin. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

Poisluettavat käyttötarkoituslajit tulee valita siten, että ne kohdistuvat ```arvo```-attribuuttien avulla valittuun yleispiirteisempään joukkoon käyttötarkoituksia poislukien niistä osan. Esim. [Elinkeinot, työ ja tuotanto](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/0103) poislukien [Ympäristöhäiriötä aiheuttava tuotantotoiminta](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_YK/code/010313).

{% include question.html content="Tulisiko olla oma lisätiedon laji 'Käyttötarkoituksen osuus maapinta-alasta', jonka avulla voitaisiin määrätä käyttötarkoituksen jakautuminen tapauksissa, josssa kyse ei ole rakentamisesta tai kun sallittua kerrosalaa tai -tilavuutta ei määrätä kaavassa?" %}