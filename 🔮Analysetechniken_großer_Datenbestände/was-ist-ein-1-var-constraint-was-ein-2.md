## Note
nid: 1608984946255
model: Basic-d7a3e
tags: 08_constrained_ar
markdown: false

### Front
<p>Was ist ein <b>1-var constraint</b>, was ein <b>2-var
constraint</b>?

### Back
<ul style="letter-spacing: normal; text-indent: 0px; 
 text-transform: none; white-space: normal; word-spacing: 0px;">
  <li style="font-weight: 400;">
    <p>1-var: Constraint, das nur eine Seite der Regel (L oder R)
    einschränkt.
  <li style="">
    <p style="">2-var: constraint bezüglich beider Seiten (L und
    R). <b>Beispiel:</b> <i style="font-weight: 400;">sum(LHS)
    <= min(RHS) ^ max(RHS) < 5 * sum(LHS)</i>
</ul>
<div>
  <i>Man arbeitet hier mit Association Rules</i> \(A \implies B\)!
  \(A\) ist dann LHS und \(B\) ist RHS. Im Beispiel oben fällt vom
  Himmel, worauf sich LHS z. B. Preis bezieht.
</div>
