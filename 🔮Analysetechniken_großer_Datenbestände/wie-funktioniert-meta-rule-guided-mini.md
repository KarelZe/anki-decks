## Note
nid: 1608984945824
model: Basic-d7a3e
tags: 08_constrained_ar, checklater, ultra
markdown: false

### Front
<p><span>Wie funktioniert <em>Meta-Rule Guided Mining</em> anhand
eines Beispiels?</span>

### Back
<p><span>

</span></p><ul style="font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px"><li><i>student(name, sno, status, major, gpa, birth_date, birth_place, address)</i></li><li><i>course(cno, title, dept)</i></li><li><i>grading(sno, cno, instructor, semester, grade)</i></li></ul><p style="font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">Finde alle Regeln der Form: <i>major (s: student, x) ^ Q(s, y) => R(s, z) </i>from student where birth_place = "Canada" in relevance to major, gpa, status, address</p><ul style="font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px"><li>major ist Attribut aus Relation Student</li><li>Q, R sind Platzhalter für Attributnamen aus Relation / Variable für Prädikate S z. B. birthdate oder gpa.</li><li>Prädikate sind Variablen, die mit Attributen aus der betrachteten Datenbank instanziiert werden während des Minings.</li><li>Kleinbuchstaben sind Platzhalter für Attributwert</li></ul><div>Man hat damit sowohl einen Data Constraint als auch einen Rule-Constraint, weil:</div><ul><li>birth_place = 'Canada' (<b>Data Constraint</b>)</li><li>Zwei Prädikate auf der linken Seite der Regel. (<b>Rule Constraint</b>)</li></ul><p style="letter-spacing: normal; text-indent: 0px; text-transform: none; white-space: normal; word-spacing: 0px;"><b>Gefundene Regel:</b></p><p style="font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px"><i>major(s, "Science") ^ gpa(s, "Excellent") => status(s, "Graduate")</i> (60 %)</p>

<p></p>
