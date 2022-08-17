## Note
nid: 1637231312031
model: Basic-02d89
tags: 03_data_lakes
markdown: false

### Front
With storing data objects row-wise in memory we have the problem of
many pointer movements when doing aggregations over the same
column.
<div>
  How can this problem be solved?
</div>

### Back
Use of column-based database group data around attributes:
<div><img src=
"paste-a89d948f962830325a84b1bcd28337a9065199d7.jpg"></div>
<div>
  This allows for much faster data access for typical BI
  operations, as contigous blocks of memory are read:
</div>
<div><img src=
"paste-02dc7eb8d15049938a1f2162a5e9c1996ab8fc65.jpg"></div>
