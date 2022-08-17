## Note
nid: 1642409727789
model: Basic-02d89
tags: 05_bewertung, checklater
markdown: false

### Front
Wie lautet die Black-Scholes Formel für <b>europäische Calls</b>
und <b>Puts</b>?

### Back
\(\begin{aligned} C^{e}(t) &=S(t) N\left(d_{1}\right)-X e^{-r(T-t)} N\left(d_{1}-\sigma \sqrt{T-t}\right) \\ \text { mit } d_{1} &=\frac{\ln (S / X)+\left(r+\sigma^{2} / 2\right)(T-t)}{\sigma \sqrt{T-t}} \end{aligned}\)

\(\begin{aligned} P^{e}(t)=& X e^{-r(T-t)} N\left(-d_{1}+\sigma \sqrt{T-t}\right)-S(t) N\left(-d_{1}\right) \\ & \text { mit } d_{1} \text { wie oben } \end{aligned}\)
