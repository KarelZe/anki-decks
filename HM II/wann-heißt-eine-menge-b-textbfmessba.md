## Note
nid: 1591514681551
model: LaTeX
tags: Integration_im_R_n
markdown: false

### Front
Wann heißt eine Menge $B$ \textbf{messbar}? Was ist dann der \textbf{Inhalt} von $B$?

### Back
Es sei $B \subseteq \mathbb{R}^{n}$ beschränkt.\\
<div>
  Wähle ein kompaktes Intervall $I$ mit $B \subseteq I$.\\
</div>
<div>
  Es sei $Z$ eine Zerlegung von $I$ mit den Teilintervallen $I_{1},
  \ldots, I_{m}$.\\
</div>
<div>
  Damit folgt für die \textbf{Untersumme}: \[ s_{c_{B}}(Z)=\sum_{j:
  I_{j} \subseteq B}\left|I_{j}\right|. \]\\
</div>
<div>
  Damit folgt für die \textbf{Obersumme}:
</div>
<div>
  \[ S_{c_{B}}(Z)=\sum_{j: I_{j} \cap B \neq 0}\left|I_{j}\right|.
  \]\\
</div>
<div>
  Wir setzen $\underline{v}(B):=s_{c_{B}}$ (innerer Inhalt von $B$)
</div>
<div>
  $\bar{v}(B):=S_{c_{B}}$ (äußerer Inhalt von $B$)
</div>
<div>
  Die Menge $B$ heißt messbar $(\mathrm{mb}): \Longleftrightarrow
  c_{B} \in R(I) .$ In diesem Fall ist \[
  \underline{v}(B)=\bar{v}(B)=\int_{I} c_{B}(x) d x \] und \[
  |B|:=\int_{I} c_{B}(x) d x \] heißt der Inhalt von $B$.
</div>
