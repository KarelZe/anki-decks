## Note
nid: 1638099391600
model: Basic-02d89
tags: 04_optionen, checklater
markdown: false

### Front
Wie lautet die <b>untere Wertgrenze</b> für <b>Calls</b>? (W4;5)

### Back
\(C^{e} \geq \max \left(0,
S(0)-X(1+r)^{-T}-D(1+r)^{-t_{1}}\right)\) \(C^{a} \geq \max
\left(C^{e}, S(0)-X\right)\) <b>Intuition:</b> Beweis durch
Strategie aus Reverse Covered Call (Basiswert Short + Call long) +
Mittelanlage. Für amerikanische Optionen Beweis analog. Möglich,
weil Call long ist. Ggf. kann man Wertgrenze noch verschärfen. Ob
aber tatsächlich \(S(0)-X>S(0)-X(1+r)^{-T}-D(1+r)^{-t_{1}}\)
gilt, hängt von \(D\) ab.
