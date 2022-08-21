## Note
nid: 1608984948038
model: Basic-d7a3e
tags: 08_constrained_ar
markdown: false

### Front
<p>Was ist <b>Anti-Monotonizität</b>? Geben Sie <b>Definition</b>
und <b>Intuition</b> an.

### Back
<p><b>Definition</b>:</p><p>Ein single-variable Constraint ist anti-monoton gdw. für alle Mengen \(S\), \(S'\) gilt: \(S\supseteq S^{\prime} \& S\) erfüllt \(C \Rightarrow S\) ' erfüllt \(C\).
</p><p><b>Intuition</b></p><p>Wenn \(S'\) Bedingung z. B. Min nicht erfüllt, braucht man mit Apriori Obermengen von \(S'\) nicht mehr betrachten.
</p><p><b>Beispiel:</b></p><p><span>

Constraint: </span>\(\min(S) >= 5\)</p><p><span> 

</span></p><p>\(S’ = \left\{7, 11, 21\right\}\)
</p><p>Auch alle Teilmengen sind größer als 5.</p><p><b>Weiteres Beispiel:</b></p><p>\(\max(S) = v\)<span> ist teilweise anti-monton. (Eigentlich nein.)</span></p><p>Wenn \(\max \left(S^{\prime}\right)>v:\) Man braucht \(S\) nicht mehr betrachten.
Wenn \(\max \left(S^{\prime}\right)<v:\) Das gilt nicht.<span>
</span></p><p><span><b>Weitere Beispiele:</b></span></p><p><img src="paste-2d1fd60a353275f461a8408417e2d1e82081a10b.jpg"><span>
</span></p>
