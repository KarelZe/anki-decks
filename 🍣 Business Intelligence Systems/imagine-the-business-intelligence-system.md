## Note
nid: 1638007624041
model: Basic-02d89
tags: 02_dwh_dm, 06_provisioning_bis
markdown: false

### Front
Imagine the business intelligence system for car retailers would hold data from 300000 retailers, each selling 2000 cars a year, resulting in 600 million datasets. Assuming an attribute item size of 20 Byte per stored "car type":

Determine the compression factor that the implementation of a dictionary encoding would provide.

### Back
\(300,000 \times 2,000=600,000,000\)

Compression Factor:
\((11.176 \text{~GB}) /(0.559 \text{~GB})=19.999\)
