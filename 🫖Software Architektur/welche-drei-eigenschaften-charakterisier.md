## Note
nid: 1637403861387
model: Einfach
tags: 02_Architectural_Viewpoints, architecture
markdown: false

### Vorderseite
Welche drei <b>Eigenschaften </b>charakterisieren eine <b>Komponente </b>nach C. Szyperski?

### Rückseite
<ul><li><em>Unit of independent deployment</em> (Komponente muss getrennt sein von Umgebung um unabhängig deploybar zu sein)</li><li><em>Unit of third party composition</em> (Um zusammensetzbar zu sein, mit anderen Komponenten, muss Komponente hinsichtlich Implementierung abgeschlossen sein.)</li><li><em>has no persistent state</em> (Komponente kann nicht unterschieden werden von ihren Kopien. Da sie keinen persistenten Zustand hat, kann man sie in System laden, aber es ist nicht sinnvoll dies mehrmalig zu tun. Persistent nur auf Instanz- nicht auf Typebene)</li></ul><div></div>
