## Note
nid: 1589720442947
model: Basic-d7a3e
tags: 02_Architectural_Viewpoints, architecture
markdown: false

### Front
Was versteht man unter einem v<i>iew type</i>?

### Back
<div>
  Ausschnitt des Meta-Models (Teilmenge der Klassen eines
  Meta-Modells), die sichtbar sind.
</div>
<div><img src=
"paste-62a879e564c945f5f7787a5a08721b1f48c9b84c.jpg"></div>
<div>
  <div>
    Ein <b>View Type</b> definiert eine Menge an Meta-Klassen,
    dessen Instanzen ein View anzeigen kann (instance-of
    Beziehung). Ein <i><b>view type</b></i> can mehrere
    <i>viewpoints</i> bedienen und ein viewpoint mehrere <i>view
    types</i>.
  </div>
</div>
<div>
  View ist ein Modell, der konform ist zu dem Meta-Modell des View
  Types. Der view ist eine Menge an tatsächlichen Elementen und
  Ihren Elementen. Auf Modellebene entspricht es damit einem
  <i>view type</i> angewendet auf ein Modell.
</div>
<div>
  <div>
    <div>
      Das <b>view type</b> meta-model definiert projezierte
      Eigenschaften von views (z. B. Anzeige Lieder mit Größe der
      Dateien), wohingegen die <b>view instance</b> die
      <b>Auswahl-Eigenschaften</b> definiert (z. B Liedliste von
      John Doe).
    </div>
  </div>
  <div>
    Ein <b>view point</b> ist spezifisch für bestimmte Stakeholder
    und definiert (defines Beziehung) ein betimmtes Belang. (z. B.
    der des DB-Admins)
  </div>
</div>
