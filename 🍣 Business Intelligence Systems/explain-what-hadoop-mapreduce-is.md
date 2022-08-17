## Note
nid: 1637234696911
model: Basic-02d89
tags: 03_data_lakes
markdown: false

### Front
Explain what <b>Hadoop MapReduce</b> is.

### Back
Map Reduce is a framework for easily writing software that processes data in parallel on a cluster of commodity hardware.<div>
</div><div>Map Reduce frameworks contains a master tracker that is responsible for starting the jobs and monitoring the slaves.</div><div>
</div><div>A Map Reduce jobs consists of the Map() and Reduce() step. </div><div>
</div><div>A Map Reduce jobs splits the data into larger chunks that are processed in parallel in the Map function.</div><div>
</div><div>The <b>map function </b>takes care of a set of key-value pairs.</div><div>Creates a set of zero or more key-value pairs.</div><div>Input and output pairs are usually different.</div><div>
</div><div>The <b>reduce function</b> is executed on each key aggregates all values according to the key.</div><div>
</div><div><img src="paste-a0df4bb554ca7eb989716ecba6b3c31dca3c6126.jpg">
</div><div>
</div>
