## Note
nid: 1627643879582
model: Basic-d7a3e-4ce08
tags: 04_uebung, rs::04_uebung
markdown: false

### Front
Welche Kommunikationsoperationen unterstützt MPI?

### Back
<div>
  <div>
    <ul>
      <li><strong>Senden:</strong> MPI_Send
      <li><strong>Senden:</strong> (nicht blockierend) MPI_Isend
      <li><strong>Gepuffert:</strong> MPI_Bsend, MPI_Ibsend
      <li><strong>ready/synchron:</strong> MPI_Rsend, MPI_Ssend,
      MPI_Irsend, MPI_Issend
      <li><strong>empfangen:</strong> MPI_Recv, MPI_Irecv
      <li><b>kombiniert:</b> MPI_Sendrecv
    </ul>
  </div>
</div>
