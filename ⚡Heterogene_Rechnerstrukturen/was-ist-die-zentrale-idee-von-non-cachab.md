## Note
nid: 1610818491256
model: Basic-b122e
tags: 04_koheraenz, 11_para_block_prozess
markdown: false

### Front
Was ist die <b>zentrale Idee</b> von <b>Non-Cachable Data</b>?
(hier bezogen auf Prozessor und Master)

### Back
<ul>
  <li>
    <div>
      Speicherbereiche, die von Prozessor und Master gemeinsam
      benutzt werden, werden von der Speicherung im Cache
      ausgeschlossen.
    </div>
  <li>
    <div>
      Adressbereich wird in Speicherverwaltungseinheit als
      "non-cacheable" gekennzeichnet.
    </div>
  <li>
    <div>
      Cache-Steuerung wird nicht aktiv bei Zugriffen auf so
      gekennzeichnete Bereiche.
    </div>
  <li>
    <div>
      Private Adressbereiche Schnittstellen und Controller sind
      non-cacheable.
    </div>
</ul>
