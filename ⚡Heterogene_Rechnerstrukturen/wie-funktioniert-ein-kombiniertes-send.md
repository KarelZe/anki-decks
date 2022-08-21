## Note
nid: 1613930090334
model: Basic-b122e
tags: 06_mpi_openmp
markdown: false

### Front
Wie funktioniert ein kombiniertes <b>Send & Receive</b> bei <b>MPI</b>?

### Back
<div>
  <div>
    <ul>
      <li><em>MPI_Sendrecv( &sendbuf, sendcount, sendtype,
      dest, sendtag, &recvbuf, recvtype, soruce, recvtag, comm,
      &status)</em>
      <li>Entspricht der Funktion von MPI_Send und MPI_Recv in
      parallelen Threads
      <li>Beide Puffer müssen definiert werden
      <li>Sendet eine Nachricht und verschickt eine
      Empfangsnachricht vor dem Blockieren.
      <li>Blockiert bis der Anwendungspuffer des Senders wieder
      frei ist und der Anwendungspuffer des Empfängers die
      empfangene Nachricht enthält.
    </ul>
  </div>
</div>
