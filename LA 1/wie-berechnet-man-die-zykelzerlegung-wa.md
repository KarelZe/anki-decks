## Note
nid: 1582214970546
model: LaTeX
tags: Eigene
markdown: false

### Front
Wie berechnet man die Zykelzerlegung? Wann kommutieren einzelne Zykel?

### Back
\textbf{Beispiel}<div>
</div><div>$a=\left(\begin{array}{lll}
{1} & {2} & {3} \\
{3} & {1} & {2}
\end{array}\right) \quad b=\left(\begin{array}{lll}
{1} & {2} & {3} \\
{3} & {2} & {1}
\end{array}\right)$
</div><div>
</div><div>$\begin{aligned}
a \cdot b &=\left(\begin{array}{lll}
{1} & {3} & {2}
\end{array}\right)\left(\begin{array}{ll}
{1} & {3}
\end{array}\right) \\
&=\left(\begin{array}{ll}
{1} & {2}
\end{array}\right)
\end{aligned}$
</div><div>
</div><div>$\begin{aligned}
b \cdot a &=\left(\begin{array}{ll}
{1} & {3}
\end{array}\right)\left(\begin{array}{lll}
{1} & {3} & {2}
\end{array}\right) \\
&=(1)\left(\begin{array}{ll}
{2} & {3}
\end{array}\right)
\end{aligned}$</div><div>
</div><div>Benachbarte Zykel, welche dieselben Zahlen enthalten, kommutieren nicht und dürfen nicht vertauscht werden.\\</div><div>
</div><div>\textbf{Methodik 1:}</div><div>
</div><div>Man nimmt als $1,2,3$ und schaut was die Zyklen damit machen. Zuerst werden sie in den rechten Zykel eingesetzt, dann wird geschaut, was der Linke damit macht.\\
</div><div>
</div><div>\textbf{Methodik 2:}</div><div>
</div><div>% Siehe z. B. <a href="https://youtu.be/rAkv8MphcmE">https://youtu.be/rAkv8MphcmE</a></div><div>
</div><div>Bei mehreren Zyklen finde ich es intutiver zuerst die Tabellenform aufzustellen und dann daraus den Zykel ablesen. </div>
