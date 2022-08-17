## Note
nid: 1627643879582
model: Basic-d7a3e
tags: 04_uebung, 04_uebung_rs
markdown: false

### Front
Welche Kommunikationsoperationen unterstützt MPI?

### Back
<div>
<div><ul>
<li><strong>Senden:</strong> MPI_Send</li>
<li><strong>Senden:</strong> (nicht blockierend) MPI_Isend</li>
<li><strong>Gepuffert:</strong> MPI_Bsend, MPI_Ibsend</li>
<li><strong>ready/synchron:</strong> MPI_Rsend, MPI_Ssend, MPI_Irsend, MPI_Issend</li>
<li><strong>empfangen:</strong> MPI_Recv, MPI_Irecv</li>
<li><b>kombiniert:</b> MPI_Sendrecv</li>
</ul>
</div></div>
