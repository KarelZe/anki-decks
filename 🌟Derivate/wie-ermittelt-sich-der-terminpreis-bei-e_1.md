## Note
nid: 1618261600336
model: Basic-d7a3e
tags: 02_forwards_futures, checklater
markdown: false

### Front
Wie ermittelt sich der <b>Terminpreis</b> bei einer <b>Anleihe</b>?

### Back
<table class="table table-striped table-bordered"> <thead> <tr> <th></th> <th>\(t=0\)</th> <th>\(T=T\)</th> </tr> </thead> <tbody> <tr> <td>Kauf Anleihe</td> <td>\(-S(0)\)
</td><td>\(S(T)\)</td> </tr> <tr> <td>Kreditaufnahme</td> <td>\(+S(0)\)</td> <td>\(S(0)(1+r)^T\)</td> </tr> <tr> <td>PF</td><td>\( 0\)</td><td><table><tbody><tr><td>\( S(T)-S(0)(1+r)^T\)</td></tr></tbody></table></td> </tr> <tr> <td>Forward long</td> <td>\(0\)</td><td><table><tbody><tr><td>\( S(T)-f(0,T) + C_T\)</td></tr></tbody></table>
</td> </tr> </tbody> </table>

\(f(0,t) = S(0)(1+r)^T - C_T\)<div>
</div><div>Basis = \(f(0,T)  - K(0) = S(0)(1+r)^T - C_T - K(0) = (K(0) + C_0) (1+r)^T -C^T - K(0) =(K(0) + C_0) r T - (C_T - C_0)\)</div><div>
</div><div>1. Term sind Haltekosten, zweiter Term Halteerträge.</div>
