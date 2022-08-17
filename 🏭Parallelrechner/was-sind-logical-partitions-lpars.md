## Note
nid: 1589394959329
model: LaTeX
tags: 
markdown: false

### Front
Was sind Logical Partitions (LPARs)?

### Back
<div>
  <ul>
    <li>Eine Methode, um aus logischen Ressourcen (Prozessoren,
    Speicher, IO Slots) phsysikalischen Maschinen zu schaffen
    <li>Volle Flexibilität mit gleichzeitiger voller Isolation
    (vgl. virtuelle Maschine)
    <li>Auf jeder LPAR wird eine volle Kopie des Betriebssystems
    AIX/Linux ausgeführt
    <li>Eine LPAR ist vergleichbar zu einem ThinNode in der RS/6000
    <li>LPARs können entsprechend ihrer Funktionen gruppiert, z.
    B.:
      <ul>
        <li><b>Compute Partitionen</b> für parallele Anwendungen
        <li><b>Login Partitionen</b> für für interaktiven
        Benutzer-Login, Programm-Entwicklung, Daten-Management,
        usw.
        <li><b>I/O Partitionen</b> für Fastplatten-I/O und das
        Global Parallel File System (GPFS)
        <li><b>TSM Partitionen</b> für Band-I/O und Backup mit
        hierarchical storage management (HSM)
      </ul>
  </ul>
</div>
<div><img src=
"paste-3eec5600a893a6805a08ebd427bd8fb1342ffef1.jpg"></div>
