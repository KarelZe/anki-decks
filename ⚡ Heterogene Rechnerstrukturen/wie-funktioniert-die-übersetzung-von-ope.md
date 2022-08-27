## Note
nid: 1604950442232
model: Basic-d7a3e-4ce08
tags: het_rs::09_programmierung
markdown: false

### Front
<p>Wie funktioniert die Übersetzung von <b>OpenCL-Code</b>

### Back
<p>- Kein spezieller Compiler für die Anwendung notwendig (C++ Code
kann z. B. mit gcc übersetzt werden. OpenCL Headerfiles müssen
eingebunden werden.)
<p>- Compiler für Kernel-Code in Bibliothek enthalten
<p>- Kernel-Code wird i. d. R. als String in der Anwendung
mitgeführt
<p>- String wird an Bibliothek übergeben und zur Laufzeit (JIT) für
ausgewählte Recheneinheit übersetzt.
<p><img src="12YNqaohJ29FfTiuTvcJ.png" style="width: 366px;">
