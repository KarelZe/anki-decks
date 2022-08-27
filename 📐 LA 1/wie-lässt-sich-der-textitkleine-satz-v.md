## Note
nid: 1583055512095
model: LaTeX-deb4a
tags: Eigene
markdown: false

### Front
Wie lässt sich der \textit{kleine Satz von Fermat} beweisen?

### Back
<div>% Aus der Übung für Mathematiker </div><div>% <a href="https://de.wikibooks.org/wiki/Beweisarchiv:_Zahlentheorie:_Elementare_Zahlentheorie:_Kleiner_Satz_von_Fermat">https://de.wikibooks.org/wiki/Beweisarchiv:_Zahlentheorie:_Elementare_Zahlentheorie:_Kleiner_Satz_von_Fermat</a></div><div>
</div>\textbf{Beh:} Für $0 \neq x \in \mathbb{F}_{p}:=\mathbb{Z} / p \mathbb{Z}$ gilt $x^{p-1}=[1]$.<div>
</div><div>\textbf{Bew:}\\  Sei $\mathbb{F}_p$ ein Körper, dann gilt $|\mathbb{F}_{p}| = p$. <span>Für die multiplikative Gruppe auf dem endlichen Körper $\mathbb{F}$ gilt: $|\mathbb{F}_{p}^{*}| = p-1$.\\</span></div><div>
</div><div>Sei im Weiteren $a \in <span>\mathbb{F}_{p}^{*}</span><span>$.\\</span></div><div>
</div><div>% <a href="https://de.wikipedia.org/wiki/Ordnung_eines_Gruppenelementes">https://de.wikipedia.org/wiki/Ordnung_eines_Gruppenelementes</a></div><div>
</div><div><div>Aus dem \textit{Satz von Lagrange} folgt, dass die Ordnung jedes Elements einer endlichen Gruppe ein Teiler von $G$ ist (siehe seperate Karteikarte).\\</div><div>
</div><div>Definiere also $k = \operatorname{ord}(a) | p-1 \implies \exists h \in \mathbb{N}$ mit $p-1 = k * h$
</div><div>
</div></div><div>$\implies a^{p-1} = a^{kh} = <span>{</span><span>a^{k</span><span>}</span><span>}</span><span>^{h} = [1]^h = [1]$. \\</span></div><div><span>
</span></div><div>Dies gilt, weil $<span>{</span><span>a^{k</span><span>}</span><span>}</span><span>$ genau $\operatorname{id}$ entspricht.</span></div>
