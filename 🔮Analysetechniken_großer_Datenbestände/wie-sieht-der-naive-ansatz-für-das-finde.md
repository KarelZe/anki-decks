## Note
nid: 1608984941819
model: Basic-d7a3e
tags: 06_association_rules
markdown: false

### Front
<p>Wie sieht der <b>naive Ansatz</b> für das Finden von Multi-Level
Assocation Rules aus? Wie der optimierte?

### Back
<div><strong>Naiv</strong></div>
<ul>
<li data-line="625">Jedes Level wird nacheinander durchlaufen.</li><li data-line="625">Unperformant, weil viele Scans über DB notwendig.</li>
</ul>
<p data-line="627"><strong>optimiert</strong></p>
<ul>
<li data-line="629">Erzeugung von z. B. \(L[i, 1]\) (\(i\) = Tiefe in Hierarchie) für alle Levels mit einem Scan.</li>
<li data-line="630">Wenn Item angetroffen wird, werden mehrere Zähler inkrementiert (für jedes Level einer).</li>
<li data-line="631">Erzeugung des \(k\)-Itemsets (für \(k > 1\)) gleich wie bei normalem Apriori. D. h. man macht \(k\) viele Scans über DB für \(k\)-große frequent itemsets.</li>
</ul>
