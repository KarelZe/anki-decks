## Note
nid: 1633008872324
model: Basic-d7a3e
tags: 09_clustering, 09_clustering_2, checklater
markdown: false

### Front
Erklären Sie die Funktionsweise des <b>EM-Algorithmus</b>.

### Back
<div>Iteratives Vorgehen zur Lösung des Problems, dass man die Paraemter der Verteilung und die Clusterzugehörigkeiten zu einer Verteilung in einem Mixture Model ermitteln will.</div><div>
</div><div>Umfasst zwei Schritte. Initiale Belegung der Parameter \(p_{A}, \mu_{A}, \mu_{B}, \sigma_{A}^{2}, \sigma_{B}^{2}\) raten.</div><div>
<div><b>Expectation-Schritt:</b></div><div>Für jedes Datenobjekt Cluster-Wahrscheinlichkeiten \(\operatorname{Pr}[A \mid x]\) ausrechnen. ("expectation", weil erwartete Klassenzugehörigkeit) </div><div>
</div><div><b>Satz von Bayes:</b>
\(\operatorname{Pr}[A \mid x]=\frac{\operatorname{Pr}[x \mid A] \cdot \operatorname{Pr}[A]}{\operatorname{Pr}[x]}=\frac{f\left(x ; \mu_{A}, \sigma_{A}\right) \cdot p_{A}}{\operatorname{Pr}[x]}\),

wobei \(f\left(x ; \mu_{A}, \sigma_{A}\right)\) die Wahrscheinlichkeitsdichtefunktion des Clusters \(A\) ist. Nenner verschwindet wegen Normalisierung. 
</div><div>
<b>Maximization-Schritt:</b></div><div>Parameter der Cluster neu berechnen. Name, weil "maximization" des Liklihoods der Verteilungen für gegebene Daten.</div><div>
</div><div>Man schätzt die Parameter in Abhängigkeit davon, wie wahrscheinlich ein Datenobjekt zu einem Cluster gehört;</div><div>\(\operatorname{Pr}\left[A \mid x_{i}\right]=: w_{i, A}\)
</div><div>
</div><div>Wahrscheinlichkeiten wirken wie Gewichte:</div><div>\(\mu_{A}=\frac{w_{1, A} x_{1}+w_{2, A} x_{2}+\ldots+w_{n, A} x_{n}}{w_{1, A}+w_{2, A}+\ldots+w_{n, A}}\)
</div><div>
</div><div>\(\sigma_{A}^{2}=\frac{w_{1, A}\left(x_{1}-\mu_{A}\right)^{2}+w_{2, A}\left(x_{2}-\mu_{A}\right)^{2}+\ldots+w_{n, A}\left(x_{n}-\mu_{A}\right)^{2}}{w_{1, A}+w_{2, A}+\ldots+w_{n, A}},\)
</div><div>
</div><div>wobei \(w_{1, A}\) die Wahrscheinlichkeit von Instanz \(i\) ist, zu Cluster \(A\) zu gehören. </div><div>
</div><div>Man ersetzt dann die vorher geratenen Werte des kommenden Expectation Schritts durch die errechneten Werte.</div><div>
Vorgehen wiederholt sich jetzt. Man versucht overall likelihood der 5 Parameter zu maximieren. Man beendet wenn sich <b>overall likelihood</b> kaum mehr verbessert. Sie lautet allgemein:</div><div>\(\prod_{i}\left(p_{A} \cdot \operatorname{Pr}\left[x_{i} \mid A\right]+p_{B} \cdot \operatorname{Pr}\left[x_{i} \mid B\right]\right)\),</div><div>
</div><div>wobei \(p_A\) die Wahrscheinlichkeit ist, dass ich Amateur bin und \operatorname{Pr}\left[x_{i} \mid A\right] ist Wahrscheinlichkeit, dass ich Kamera zu diesem Preis kaufe. </div><div>
</div><div>Für Gaussian Mixture:
</div><div>\(\prod_{i=1}^{n}\left(N\left(x_{i} ; \mu_{\mathrm{A}}, \sigma_{\mathrm{A}}\right) p_{\mathrm{A}}+N\left(x_{i} ; \mu_{\mathrm{B}}, \sigma_{\mathrm{B}}\right) p_{\mathrm{B}}\right),\)</div><div>
</div><div>wobei es sich bei \(N\left(x_{i} ; \mu_{\mathrm{A}}, \sigma_{\mathrm{A}}\right)\) um die Wahrscheinlichkeitsdichte handelt.</div><div>
</div><div>Maximieren hier sinnvoll, den liegen viele Instanzen bereits nahe an ihrem Clustermittelpunkt z. B. \(\mu_B\) dann ist \(\operatorname{Pr}\left[x_{i} \mid B\right]\) groß, ansonsten klein.</div><div>
</div><div>Verallgemeinerung von/gleiches Prinzip wie bei k-Means. (verschieben + neuberechnen)</div></div>
