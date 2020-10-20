# Anomaly Detection Datasets

In this respository, we provide a continuously updated collection of popular real-world datasets used for anomaly detection in the literature. Some of the datasets are converted from imbalanced classification datasets, while the others contain real anomalies.

## Numerical Datasets

Seven datasets from the KDD19 paper - DevNet - are available at the [DevNet_datasets](https://github.com/GuansongPang/anomaly-detection-datasets/tree/main/numerical%20data/DevNet%20datasets) folder in this repository. The basic statistics of these datasets are shown below.

Dataset | Data size | Dimensionality
------------ |------------ | -------------
donors| 619,326 |10
census| 299,285 |500
fraud| 284,807 |29
celeba| 202,599| 39
backdoor| 95,329| 196
campaign| 41,188| 62
thyroid| 7,200 |21

Detailed introduction of these datasets can be found in the DevNet paper
>Pang, G., Shen, C., & van den Hengel, A. (2019, July). Deep anomaly detection with deviation networks. In Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (pp. 353-362).

## Categorical Datasets

14 widely-used categorical datasets for anomaly detection are available at the [Categorical data](https://github.com/GuansongPang/anomaly-detection-datasets/tree/main/categorical%20data) folder.

Dataset   | Data size | Dimensionality| Anomaly class 
------------ |------------ | -------------|------------ 
bank | 41,188 | 10 | yes 
census | 299,285 | 33 | 50K+ 
AID362 | 4,279 | 114 | active 
w7a | 49,749 | 300 | yes 
CMC | 1,473 | 8   | child>10 
APAS | 12,695 | 64  | train 
CelebA | 202,599  | 39 | bald 
Chess | 28,056 | 6 | zero 
AD | 3,279 | 1,555 | ad. 
Solar-flare | 1,066 | 11  | F  
Probe | 64,759 | 6 | attack 
U2R | 60,821 | 6 | attack 
R10 | 12,897  | 100| corn 
CoverType | 581,012  | 44 | cottonwood 

Detailed introduction of these datasets and some state-of-the-art performance benchmark can be found in the following papers:

>Pang, G., Cao, L., & Chen, L. (2016, January). Outlier detection in complex categorical data by modelling the feature value couplings. In IJCAI International Joint Conference on Artificial Intelligence.

>Pang, G., Cao, L., Chen, L., & Liu, H. (2016, December). Unsupervised feature selection for outlier detection by modelling hierarchical value-feature couplings. In 2016 IEEE 16th International Conference on Data Mining (ICDM) (pp. 410-419). IEEE.

>Pang, G., Cao, L., Chen, L., & Liu, H. (2017). Learning homophily couplings from non-IID data for joint feature selection and noise-resilient outlier detection. In 26th International Joint Conference on Artificial Intelligence, IJCAI 2017 (pp. 2585-2591). International Joint Conferences on Artificial Intelligence.
