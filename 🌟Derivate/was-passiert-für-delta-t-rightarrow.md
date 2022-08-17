## Note
nid: 1642942484289
model: Basic-02d89
tags: 05_bewertung, checklater
markdown: false

### Front
Was passiert für \(\Delta t \rightarrow 0\) bei der Ito-Formel? Betrachte Verhalten der Terme im Verhältnis zu \(\Delta t\)

### Back
\(\begin{array}{lll}\frac{(\Delta t)^{2}}{\Delta t}=\Delta t & \rightarrow 0 & \text { für } \Delta t \rightarrow 0 \\ \frac{\Delta t \Delta x}{\Delta t}=\Delta x & \rightarrow 0 & \text { für } \Delta t \rightarrow 0 \text { da } x \text { stetig } \\ \frac{\Delta t \Delta W}{\Delta t}=\Delta W & \rightarrow 0 & \text { für } \Delta t \rightarrow 0 \text { da } W \text { stetig } \\ \frac{(\Delta W)^{2}}{\Delta t} & \rightarrow ? & E(\Delta W)^{2}=\operatorname{Var}(\Delta W)=\Delta t \\ & \Rightarrow \frac{E(\Delta W)^{2}}{\Delta t} \rightarrow 1\end{array}\)
