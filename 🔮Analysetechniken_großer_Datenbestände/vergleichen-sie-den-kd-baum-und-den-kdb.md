## Note
nid: 1632657756103
model: Basic-d7a3e
tags: 03_raeumliche_index_strukturen, checklater
markdown: false

### Front
Vergleichen Sie den <b>kd-Baum</b> und den <b>kdB-Baum</b>.

### Back
<ul>
  <li>Physischer Knoten enthält mehrere logische Regionen
  <li>Physische Knoten nicht mehr pro Split-Dimension
  <li>kdB-Baum enthält pro physischem Knoten genau eine
  Speicherseite, dadurch effizienter Zugriff.
  <li>Physischer Knoten kann mehrere logische Regionen enthalten
  (nicht mehr nur unbedingt aus einer Split-Dimension)
  <li>Abstand von Daten zu Wurzelknoten immer gleich, da
  balanciert.
  <li>In einem kd-Baum haben die Knoten die Splitdimensionen
  dargestellt, hier stellen die Knoten jetzt verschiedenen
  logischen Regionen dar.
</ul>
