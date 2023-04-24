# Graph datasets
Graph anomaly detection may include the detection of abnormal nodes, edges, or graphs. This repository collects relevant datasets for these tasks.

## Graph-level anomaly detection
Below are sixteen publicly available real-world graph-level anomaly detection datasets used by GLocalKD, a method published in WSDM'22 and released at https://github.com/RongrongMa/GLocalKD. The basic 
statistics of the datasets are given in the table below. To download the datasets, please refer to the GLocalKD repository.

Dataset| #Graphs|#Avg. Nodes|#Avg. Edges
------------ |------------ | ------------- |------------ 
PROTEINS_full|1,113|39.06|72.82
ENZYMES|600|32.63|62.14
AIDS|2,000|15.69|16.2
DHFR|467|42.43|44.54
BZR|405|35.75|38.36
COX2|467|41.22|43.45
DD|1,178|284.32|715.66
NCI1|4,110|29.87|32.3
IMDB|1,000|19.77|96.53
REDDIT|2,000|429.63|497.75
HSE|8,417|16.89|17.23
MMP|7,558|17.62|17.98
p53|8,903|17.92|18.34
PPAR-gamma|8,451|17.38|17.72
COLLAB|5,000|74.49|2,457.78
hERG|655|26.48|28.79

## Node-level anomaly detection

Below are four real-world graph datasets for node-level anomaly detection. Basic statistics of these datasets are as follows. They are used in cross-domain graph anomaly detection and released at https://github.com/QZ-WANG/ACT.

Dataset| #Dim. | #Nodess|#Avg. Degree|#Anomalies|#Ratio
------------ |------------ | ------------- |------------ | ------------- |------------ 
YelpRes|8,000|5,012|41.79|250|0.0499
YelpHotel|8,000|4,322|23.55|250|0.0578
YelpNYC|10,000|21,040|78.81|1,000|0.0475
Amazon|10,000|18,601|28.30|726|0.0390

