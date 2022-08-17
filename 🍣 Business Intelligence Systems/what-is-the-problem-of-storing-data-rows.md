## Note
nid: 1637231148138
model: Basic-02d89
tags: 03_data_lakes
markdown: false

### Front
What is the problem of storing <b>data rows</b> sequentially in <b>memory</b>?<div>
</div><div><img src="paste-7a917adba2e99a14419b25a7dcbb895bc2008dfc.jpg">
</div>

### Back
This type of organization performs well for the manipulation of a
single data set (i. e. row)
<div><img src=
"paste-b4edc3c722e02bb37911babd11d5a67973b01740.jpg"></div>
<div>
  It performs poorly when data is accessed in the same colums (e.
  g. summization), as many pointer movements in memory are
  required, bank conflicts arise and non-continous blocks of memory
  are loaded.
  <div><img src=
  "paste-9e54f199b399f8949793576a685f3c37c3485296.jpg"></div>
</div>
