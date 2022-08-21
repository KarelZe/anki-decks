## Note
nid: 1637234409327
model: Basic-02d89
tags: 03_data_lakes
markdown: false

### Front
Explain what <b>Apache Hadoop YARN</b> is?

### Back
<div>YARN splits the responsiblities of managing resources and job schedule monitoring into several nodes.
</div><div>
</div><div>There is a global Resource Manger and per-application Master Manager.
</div><div>
</div><div>The Resource Manager is the ultimate authority that shares resources among all the applications in the system.</div><div>
</div><div>The node manager is responsible for observing resource utilization etc. and reporting it to the Resource Master.</div><div>
</div><div>The Resource Manger and the Node Manager form the data computation framework.
<div>
</div></div><div><img src="paste-21862ac8a239849559de8603b76d7c20ff484d3b.jpg">
</div>
