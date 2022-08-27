## Note
nid: 1602355176634
model: Basic-b122e-20a86
tags: 5_1_mpi
markdown: false

### Front
Worin unterscheiden sich <b>blockierende</b> und nicht
<b>blockierende Operationen</b>?

### Back
<ul>
  <li>Operationen sind lokale Aktivitäten wie Senden und Empfangen
  einer Botschaft
  <li>
    <strong>blockierend</strong>
    <ul>
      <li>Beim blockierenden Senden / Empfangen wird Senderroutine
      erst verlassen, wenn die Botschaft beim Empfänger angekommen
      ist.
      <li>Bei <strong>synchronem Senden</strong> wird die
      Senderroutine erst verlassen, wenn Botschaft beim Empfänger
      angekommen ist.
      <li>Bei <strong>asynchronem Senden</strong> wird die
      Senderroutine verlassen, sobald die Nachricht
      <strong>vollständig</strong> verschickt wurde.
      <li>Beim Empfang wird Empfangsroutine erst verlassen, wenn
      die Daten vollständig im Anwendungspuffer stehen.
    </ul>
  <li>
    <strong>nicht blockierend</strong>
    <ul>
      <li>Nicht blockierende Operation stößt Kommunikation an, kehr
      dann sofort zurück d. h. verlässt die Routine und erlaubt
      einem Prozess andere Arbeit durchzuführen.
      <li>Prozess muss bei Beendigung einer nicht-blockierenden
      Operation warten (oder evtl. einen Test auf Beendigung
      durchführen)
      <li>Alle nicht-blockierenden Operationen sollten mit einer
      Wait-/ Testoperation umgesetzt werden.
      <li>Eine nicht-blockierende Operation mit einer zugehörigen
      wait-Routine entspricht einer blockierenden Operation.
    </ul>
</ul>
