## Note
nid: 1628143992168
model: Basic-d7a3e
tags: 07_multi_threading, checklater, klausur
markdown: false

### Front
Was unterscheidet <b>Cycle-by-Cycle Interleaving</b> (feingranulares Multithreading) von <b>Block Interleaving </b><i style="">(grobgranulares multithreading)</i>?

### Back
<div>
  <div>
    <ul>
      <li><strong>Cycle-by-Cycle Interleaving:</strong> Wechselt
      Kontext mit jedem Prozessortakt. Eine Anzahl von
      Kontrollfäden ist auf dem Prozessor geladen. Ein
      Hardware-Scheduler wählt in jedem Takt einen der
      “ausführbaren” Threads aus. Von diesem wird der nächste
      Befehl in die Befehls-Pipeline gestellt. In
      aufeinanderfolgenden Takten werden andere Kontrollfäden
      gewählt.
      <li><strong>Block-Interleaving:</strong> Ausführen
      aufeinanderfolgender der Befehle eines Threads, solange bis
      Ereignis eintritt, das zum Warten zwingt z. B. Cache-Miss.
      Kontextwechselereignis führt dann zu Thread-Wechsel.
    </ul>
  </div>
</div>
