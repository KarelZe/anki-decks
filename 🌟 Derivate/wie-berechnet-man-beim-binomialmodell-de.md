## Note
nid: 1641819861603
model: Basic-02d89-e0e22
tags: 05_bewertung, derivate::05_bewertung
markdown: false

### Front
Wie berechnet man beim <b>Binomialmodell </b>den Wert einer <b>amerikanischen Option</b>? Beschreiben Sie das ungefähre Vorgehen.

### Back
<b>Intuition:</b>
<ol><li>Man bestimmt die Ausübungswerte der Option in \(T\)</li><li>Man führt Standard-Rückwärtsrekursion durch für \(t < T\).</li><li>Man nimmt an jedem Knoten das Maximum aus Ausübungswert und dem Wert aus Rückwärtssubstitution z. B. bei europäischem Put \(P^{e}\left(t_{0}\right)\)</li></ol>\(P_{x}(t)^{i}=\max \left(\text { Wert bei Ausübung in } t, \frac{1}{1+r}\left(q P_{x}(t+1)^{i+1}+(1-q) P_{x}(t+1)^{i}\right)\right)\)

<b>Beispiel:</b>
<img src="paste-8f191e9ed70f22362c829a734a278a1920700ad3.jpg">
