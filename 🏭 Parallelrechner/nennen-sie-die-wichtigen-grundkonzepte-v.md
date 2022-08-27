## Note
nid: 1602355337667
model: Basic-b122e-20a86
tags: 5_1_mpi
markdown: false

### Front
Nennen Sie die wichtigen Grundkonzepte von MPI?

### Back
<ul>
  <li>
    <div>
      Alle Prozesse eines MPI-Programms "hängen" an dem
      Kommunikator MPI_COMM_WORLD
    </div>
  <li>
    <div>
      Jeder Prozess hat seinen eigenen Rang in einem Kommunikator
      mit den Zahlen 0 - (size -1)
    </div>
  <li>
    <div>
      Der Rang ist die Basis für parallelen Code und die Verteilung
      der Daten.
    </div>
    <ul>
      <li>int MPI_Comm_rank(MPI_Comm comm, int *rank)
      <li>int MPI_Comm_size(MPI_Comm comm, int *size)
    </ul>
    <div><img src= 
    "paste-54a1b2de1935d29a9bb336602205ea103814f300.jpg"></div>
</ul>
