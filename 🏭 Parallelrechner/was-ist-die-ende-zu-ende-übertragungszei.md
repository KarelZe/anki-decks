## Note
nid: 1588777971904
model: LaTeX-deb4a
tags: 2_parallelrechner
markdown: false

### Front
Was ist die Ende-zu-Ende Übertragungszeit? Aus welchen Komponenten setzt sie sich zusammen?

### Back
<div>Time(n) = overhead + routing delay + channel occupancy + contention
delay</div><b><div><b>\begin{enumerate}</b></div><div><b>\item \textbf{</b><b>Overhead:</b><b style="background-color: rgb(255, 255, 255);"> }</b><span>Zeit, um Nachrichten in und aus dem Netzwerk zu bekommen</span></div></b><b>\item \textbf{</b><b>Routing delay:</b><b>} </b>In jedem Netzwerkbauteil erfährt die Nachricht eine
Verzögerung
<b>\item \textbf{</b><b>Channel occupancy:</b><b>}</b> Zeit, um n Bytes über einen Netzwerkkanal zu
übertragen, $( n+n_e )/b$
\begin{enumerate}
<div>\item $b$ ist die Bandbreite des Netzwerkkanals
\item $n_e$ sind die Anzahl Bytes des Netzwerkprotokolls
\end{enumerate}</div><div>\item \textbf{<span>Contention delay:</span><span>} Zeit, in der die Nachricht in jedem Netzwerkbauteil</span></div><div>blockiert wird, bis der nächste Netzwerkkanal frei ist
\begin{enumerate}
<div><span>\item Tritt auf, wenn zwei Pakete den gleichen Netzwerkkanal benutzen</span>
</div><div>möchten
\item Lösungen: im Netzwerkbauteil puffern, alternative Route verwenden,
Nachricht löschen</div><div>\end{enumerate}</div><div>\end{enumerate}</div></div>
