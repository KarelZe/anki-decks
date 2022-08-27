## Note
nid: 1627555330291
model: Basic-d7a3e-4ce08
tags: 04_uebung, 10_verbindungsstrukturen_klausur, checklater, klausur, rs::04_uebung, rs::10_verbindungsstrukturen, ultra
markdown: false

### Front
Woraus setzt sich die <b>Latenz</b> eines <b>Verbindungsnetzes</b>
zusammen?

### Back
<div>
  <div>
    <ol>
      <li><strong>Sender overhead:</strong> Zeit für
      Zusammenstellen des Pakets und Ablegen im Sendepuffer
      <li><strong>Time of flight:</strong> Zeit, um ein Bit von der
      Quelle ans Ziel zu senden.
      <li><strong>Transmission time:</strong> Zusätzliche Zeit, die
      benötigt wird, um alle übrigen Bits eines Pakets zu
      übertragen, nachdem erstes Bit beim Empfänger ist.
      <li><strong>Routing time:</strong> Zeit, um den Weg
      aufzusetzen, bevor ein Teil des Pakets übertragen werden
      kann.
      <li><strong>Switching time:</strong> Abhängig der
      Switching-Strategie
      <li><strong>Receiver overhead:</strong> Ablegen von
      Verwaltungsinformationen und Weiterleiten des Pakets aus dem
      Empfangspuffer.
    </ol>
  </div>
</div>
