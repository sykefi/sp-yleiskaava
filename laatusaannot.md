---
layout: "default"
description: ""
id: "laatusaannot"
status: "Ehdotus"
---
# Laatusäännöt
Nämä laatusäännöt laajentavat Kaavatietomallin [yleisiä laatusääntöjä](../../looginenmalli/laatusaannot.html).

## Yleiset säännöt

{% include common/clause_start.html type="req" id="prof-yk/arvot" %}
Ellei tarkemmin ole määritetty, ```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="rec" id="sov-yk/suos-asiakirja" %}
Mikäli kaavakohteeseen liittyen on laadittu jokin suunnitelma, selvitys, raportti tai muu asiakirja, on suositeltavaa linkittää se kaavamääräykseen ```liittyvaAsiakirja```-assosiaation avulla.
{% include common/clause_end.html %}

{% include common/tip.html content="Kaavakohde voidaan linkittää toisiin ```Kaavakohteisiin``` assosiaation ```liittyvaKohde``` arvojen avulla." %}