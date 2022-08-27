## Note
nid: 1628400767116
model: Basic-d7a3e-4ce08
tags: checklater, klausur
markdown: false

### Front
Erklären Sie anhand der 5-stufigen RISC-Pipeline der Vorlesung, warum Pipelining zu Parallelität auf Befehlsebene führt.

### Back
Die in der Vorlesung angesprochene Pipeline besteht aus den 5 Phasen IF-ID-EX-MA-WB. Jede dieser Phasen kann gleichzeitig angestoßen werden und müssen nicht notwendigerweise den gleichen Befehl abarbeiten. Das ermöglicht das parallele Verarbeiten von maximal 5 Befehlen gleichzeitig, sobald die Pipeline gefüllt ist.
