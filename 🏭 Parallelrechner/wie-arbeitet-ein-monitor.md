## Note
nid: 1602347323691
model: Basic-b122e-20a86
tags: Eigene
markdown: false

### Front
Wie arbeitet ein Monitor?

### Back
<ul>
  <li>Ein Monitor ist ein Modul (eine Klasse), in dem die von
  Prozessen gemeinsam genutzten Daten und ihre Zugriffsprozeduren
  zu einer Einheit zusammengeführt sind.
  <li>Zugriffsprozeduren mit kritischen Abschnitten heißen
  Monitor-Operationen
  <li>Monitor kann auch Zugriffsprozeduren ohne kritische
  Abschnitte enthalten.
  <li>Die Monitoroperationen werden unter wechselseitigem
  Ausschluss definiert. Es sind keine Synchronisationsanweisungen
  im Code notwendig. Synchronisierungsprimitive werden bei
  Übersetzung des Monitors eingefügt.
  <li>Bei Benutzung des Monitors sorgt der Monitor dafür, dass eine
  Monitoroperation nur von einem Prozess ausgeführt wird. Wird eine
  Monitorprozedur bereits von einem Prozess verwendet, so wird der
  Prozess blockiert.
</ul>
