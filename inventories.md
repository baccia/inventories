---
layout: default
title: Inventories
redirect_from: /libraries
permalink: inventories.html
inventories:
- id: 51006826
  siglum: "A-FKsta, Akt Nr. 269"
  title: "The Feldkirch Inventory (1699)"
  rism: ""
- id: 51006872
  siglum: "B-Oa, SAO AC027 236"
  title: "The Oostende Inventory (1747)"
  rism: ""
- id: 51006870
  siglum: "CH-A Stadtarchiv, II.562c"
  title: "The 'Guldenes Buch' of the Collegium Musicum in Aarau (1710–1768p)"
  rism: ""
- id: 51006867
  siglum: "CH-BEa, B III 873"
  title: "The Berne Inventory (1697)"
  rism: ""
- id: 51006866
  siglum: "CH-BEa, OG Bern-Muenster 208"
  title: "The Berne Inventory (1761)"
  rism: ""
- id: 51006863
  siglum: "CH-Bischofszell, Museum [1743]"
  title: "The Bischofszell Inventory (1743)"
  rism: ""
- id: 51006864
  siglum: "CH-Bischofszell, Museum [1744]"
  title: "The Bischofszell Inventory (1744)"
  rism: ""
- id: 51000005
  siglum: "CH-BM, StiA Bd. 1206"
  title: "The Beromünster Inventory (1696)"
  rism: ""
- id: 51006876
  siglum: "CH-G AEG, Jur Civ F 300"
  title: "Ouvrages de musique dans la Bibliothèque de Pierre Fatio, 1707"
  rism: ""
- id: 51006823
  siglum: "CH-Lz, Pp Msc 11.4"
  title: "The St Urban Inventory (1661)"
  rism: ""
- id: 51006868
  siglum: "CH-SOa, St Leod. Prot. vol. 1"
  title: "The Inventory of St Leodegar in Schönenwerd (1622)"
  rism: ""
- id: 51006861
  siglum: "CH-W, Dep MK 303 [1660]"
  title: "The Inventory of the Winterthur Collegium Musicum (1660)"
  rism: ""
- id: 51006862
  siglum: "CH-W, Dep MK 303 [1722]"
  title: "The Inventory of the Winterthur Collegium Musicum (1722)"
  rism: ""
- id: 51006865
  siglum: "CH-Zz, AMG Archiv IV A 3"
  title: "The Zurich 'Deutsche Schule' Inventory (1698)"
  rism: ""
- id: 51006860
  siglum: "CH-Zz, AMG Archiv IV A 6"
  title: "The Zurich 'Chorherrenstube' Inventory (1698)"
  rism: ""
- id: 51006874
  siglum: "Parstorffer 1653"
  title: "Paul Parstorffer's «Indice di tutte le Opere di Musica» (Munich 1653)"
  rism: ""

---

Inventories are now catalogued in Muscat and published in RISM Online. You can see the current list of inventories in [RISM Online](https://rism.online/search?mode=sources&fq=material-content-types%3AInventory&page=1&rows=100).

### Initial database

For documentation purposes, this is the list of inventories catalogues in the original database. They all have been migrated into RISM.

<table>
  <thead>
    <tr>
      <th>Inventory siglum</th>
      <th>Title</th>
      <th>RISM</th>
    </tr>
  </thead>
  <tbody>
    {% for inventory in page.inventories %}
    <tr>
      <td>
        <a href="https://inventories.rism-ch.org/libraries/{{ inventory.id }}">
          {{ inventory.siglum }}
        </a>
      </td>
      <td>{{ inventory.title }}</td>
      <td>
        <a href="https://rism.online/sources/{{ inventory.rism}}">
          Inventory
        </a> |
        <a href="https://rism.online/sources/{{ inventory.rism}}/inventory-items">
          Content
        </a>
      </td>
    </tr>
    {% endfor %}
  </tbody>
</table>
