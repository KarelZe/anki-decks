## Note
nid: 1628144091346
model: Basic-d7a3e-4ce08
tags: 07_multi_threading
markdown: false

### Front
Erklären Sie <b>Cycle-by-Cyle Interleaving</b> <i>(fine-grain
multithreading).</i>

### Back
Wechselt Kontext mit jedem Prozessortakt. Eine Anzahl von Kontrollfäden 
ist auf dem Prozessor geladen. ein Hardware-Scheduler wählt in jedem 
Takt einen der “ausführbaren” Threads aus. Von diesem wird der nächste 
Befehl in die Befehls-Pipeline gestellt. In aufeinanderfolgenden Takten 
werden andere Kontrollfäden gewählt.
