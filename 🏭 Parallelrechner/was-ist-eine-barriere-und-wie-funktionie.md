## Note
nid: 1592488718945
model: Basic-b122e-20a86
tags: 3_5_synchronisation
markdown: false

### Front
Was ist eine <b>Barriere</b> und <b>wie</b> funktioniert sie?

### Back
Eine Barriere ist ein Synchronisationspunkt für mehrere Prozesse.
<div>
  Eine Barriere wird als Barrieren-Variable angelegt und muss vor
  dem ersten Benutzen initialisiert werden. Eine
  <b>init-barrier</b> Anweisung weist der Barrieren-Variable die
  Zahl der Prozesse zu, auf die gewartet werden soll.
</div>
<div>
  Eine wait-barrier-Anweisung muss dann von jedem dieser Prozesse
  ausgeführt werden. Dabei wird die Prozessanzahl aus der
  Initialisierung dekrementiert und der Prozess suspendiert, sofern
  die Prozessanzahl noch größer als Null ist.
</div>
<div>
  Wenn der letzte Prozess an der Barriere angekommen ist, dann
  werden alle wartenden Prozesse wieder aufgenommen und die
  Barriere wird wieder auf den Initialwert zurückgesetzt.
</div>
