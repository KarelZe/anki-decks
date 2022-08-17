## Note
nid: 1637233844040
model: Basic-02d89
tags: 03_data_lakes
markdown: false

### Front
Explain the core idea of <b>Hadoop Distributed File System</b>.

### Back
HDFS is a distributed file system to run on distributed hardware.
<div>
  HDFS is organized in a master slave architecture. A master node
  manages the name space. It stores related metadata such es
  filenames, locations. Then there are data nodes, which manage
  nodes attached to the storage, that they run.
</div>
<div>
  Data is stored in so-called files. A file internally is a stream,
  that is split into in or more blobs, that is stored in several
  nodes. HDFS is highly fault tolerant, as blocks are replicated
  over several nodes.
</div>
<div>
  The name nodes execute filesystem operations like opening files.
</div>
<div><img src=
"paste-6d55dcd13eac11be5e868dd5caf385fc84a247e7.jpg"></div>
