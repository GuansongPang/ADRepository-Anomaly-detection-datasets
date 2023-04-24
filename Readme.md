# ADRepository: Real-world anomaly detection datasets

In this repository, we provide a continuously updated collection of popular real-world datasets used for anomaly detection in the literature. Some of the datasets are converted from imbalanced classification datasets, while the others contain real anomalies.

This repository is created to serve as an extension to the datasets presented in our recent survey paper on deep anomaly detection. If you use the datasets below, you may cite the survey paper or the specific papers in the following sections to acknowledge the use. 
```bibtex
@article{pang2021deep,
  title={Deep learning for anomaly detection: A review},
  author={Pang, Guansong and Shen, Chunhua and Cao, Longbing and Hengel, Anton Van Den},
  journal={ACM Computing Surveys (CSUR)},
  volume={54},
  number={2},
  pages={1--38},
  year={2021},
  publisher={ACM New York, NY, USA}
}
```

**A continuously updated repository for SOTA deep anomaly detection implementation is made publicly available at https://github.com/GuansongPang/SOTA-Deep-Anomaly-Detection**

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

Detailed introduction of these datasets and some performance benchmarks can be found in the DevNet paper. Source code of DevNet is available at [here](https://github.com/GuansongPang/deviation-network). 
```bibtex
@inproceedings{pang2019deep,
  title={Deep anomaly detection with deviation networks},
  author={Pang, Guansong and Shen, Chunhua and van den Hengel, Anton},
  booktitle={Proceedings of the 25th ACM SIGKDD international conference on knowledge discovery \& data mining},
  pages={353--362},
  year={2019}
}
```

## Categorical Datasets

14 widely-used categorical datasets for anomaly detection are available at the [Categorical data](https://github.com/GuansongPang/anomaly-detection-datasets/tree/main/categorical%20data) folder. The basic statistics of these datasets are shown below. 

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
```bibtex
@inproceedings{pang2016outlier,
  title={Outlier detection in complex categorical data by modelling the feature value couplings},
  author={Pang, Guansong and Cao, Longbing and Chen, Ling},
  booktitle={IJCAI International Joint Conference on Artificial Intelligence},
  year={2016}
}

@inproceedings{xu2018exploring,
  title={Exploring a high-quality outlying feature value set for noise-resilient outlier detection in categorical data},
  author={Xu, Hongzuo and Wang, Yongjun and Cheng, Li and Wang, Yijie and Ma, Xingkong},
  booktitle={Proceedings of the 27th ACM International Conference on Information and Knowledge Management},
  pages={17--26},
  year={2018}
}

@article{pang2021homophily,
  title={Homophily outlier detection in non-IID categorical data},
  author={Pang, Guansong and Cao, Longbing and Chen, Ling},
  journal={Data Mining and Knowledge Discovery},
  pages={1--62},
  year={2021},
  publisher={Springer}
}
```

## Video Datasets
Two popular weakly supervised video anomaly detection datasets, including ShanghaiTech Campus and UCF-Crime, are added to the [video data](https://github.com/GuansongPang/anomaly-detection-datasets/tree/main/video%20data) folder. The sources are features extracted using I3D backbone rather than raw data. Weakly supervised video anomaly detection assumes the availability of the video-level labels and aims at detecting frame-level anomalies. They can also be re-organized and used for semi-supervised settings that the training data contains normal videos only. More information about the datasets can be found in the following papers.
```bibtex
@inproceedings{sultani2018real,
  title={Real-world anomaly detection in surveillance videos},
  author={Sultani, Waqas and Chen, Chen and Shah, Mubarak},
  booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition},
  pages={6479--6488},
  year={2018}
}

@inproceedings{tian2021weakly,
  title={Weakly-supervised Video Anomaly Detection with Robust Temporal Feature Magnitude Learning},
  author={Tian, Yu and Pang, Guansong and Chen, Yuanhong and Singh, Rajvinder and Verjans, Johan W and Carneiro, Gustavo},
  booktitle={Proceedings of the IEEE/CVF international conference on computer vision},
  year={2021}
}
```

## Image Datasets
We add 14 publicly available image datasets with real anomalies from diverse application domains, including **defect detection**, **novelty detection** in rover-based planetary exploration, **lesion detection** in medical images, and **anomaly segmentation** in autonomous driving scenes. See [image data](https://github.com/GuansongPang/anomaly-detection-datasets/tree/main/image%20data) for more details. These datasets are used to evaluate a wide range of detection models in different settings (e.g., **open-set anomaly detection** and **out-of-distribution semantic segmentation**) in the following paper:
```bibtex
@article{pang2021explainable,
  title={Explainable Deep Few-shot Anomaly Detection with Deviation Networks},
  author={Pang, Guansong and Ding, Choubo and Shen, Chunhua and Hengel, Anton van den},
  journal={arXiv preprint arXiv:2108.00462},
  year={2021}
}

@inproceedings{ding2022catching,
  title={Catching Both Gray and Black Swans: Open-set Supervised Anomaly Detection},
  author={Ding, Choubo and Pang, Guansong and Shen, Chunhua},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={7388--7398},
  year={2022}
}

@article{tian2021pixel,
  title={Pixel-wise Energy-biased Abstention Learning for Anomaly Segmentation on Complex Urban Driving Scenes},
  author={Tian, Yu and Liu, Yuyuan and Pang, Guansong and Liu, Fengbei and Chen, Yuanhong and Carneiro, Gustavo},
  journal={arXiv preprint arXiv:2111.12264},
  year={2021}
}

@article{chan2021segmentmeifyoucan,
  title={Segmentmeifyoucan: A benchmark for anomaly segmentation},
  author={Chan, Robin and Lis, Krzysztof and Uhlemeyer, Svenja and Blum, Hermann and Honari, Sina and Siegwart, Roland and Salzmann, Mathieu and Fua, Pascal and Rottmann, Matthias},
  journal={arXiv preprint arXiv:2104.14812},
  year={2021}
}
```

## Graph Datasets
16 real-world datasets for graph-level anomaly detection are added. Basic statistics of these datasets are as follows. See [graph data](https://github.com/GuansongPang/ADRepository-Anomaly-detection-datasets/tree/main/graph%20data) for more detail.

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

The datasets were used and made available by the authors of the following paper.
```bibtex
@inproceedings{ma2022deep,
  title={Deep Graph-level Anomaly Detection by Glocal Knowledge Distillation},
  author={Ma, Rongrong and Pang, Guansong and Chen, Ling and van den Hengel, Anton},
  booktitle={The Fifteenth ACM International Conference on Web Search and Data Mining},
  year={2022}
}
```

4 real-world graph datasets for node-level anomaly detection are added. Basic statistics of these datasets are as follows. See [graph data](https://github.com/GuansongPang/ADRepository-Anomaly-detection-datasets/tree/main/graph%20data) for more detail.

Dataset| #Dim. | #Nodess|#Avg. Degree|#Anomalies|#Ratio
------------ |------------ | ------------- |------------ | ------------- |------------ 
YelpRes|8,000|5,012|41.79|250|0.0499
YelpHotel|8,000|4,322|23.55|250|0.0578
YelpNYC|10,000|21,040|78.81|1,000|0.0475
Amazon|10,000|18,601|28.30|726|0.0390

The datasets were used and made available by the authors of the following paper.
```bibtex
@article{ding2021cross,
  title={Cross-domain graph anomaly detection},
  author={Ding, Kaize and Shu, Kai and Shan, Xuan and Li, Jundong and Liu, Huan},
  journal={IEEE Transactions on Neural Networks and Learning Systems},
  volume={33},
  number={6},
  pages={2406--2415},
  year={2021},
  publisher={IEEE}
}

@inproceedings{wang2023cross,
  title={Cross-Domain Graph Anomaly Detection via Anomaly-aware Contrastive Alignment},
  author={Wang, Qizhou and Pang, Guansong and Salehi, Mahsa and Buntine, Wray and Leckie, Christopher},
  booktitle={AAAI},
  year={2023}
}
```

## Time Series Datasets

Anomaly detection on time series data is one of the most active research directions in the anomaly detection community. Some commonly-used datasets are as follows:  
- ASD   https://github.com/zhhlee/InterFusion  
- SMD   https://github.com/NetManAIOps/OmniAnomaly  
- SWAT  https://itrust.sutd.edu.sg/itrust-labs_datasets  
- WaQ   https://www.spotseven.de/gecco/gecco-challenge  
- DSADS https://github.com/zhangyuxin621/AMSL  
- Epilepsy https://github.com/boschresearch/NeuTraL-AD/  

These datasets are from the paper below; check the paper for more detail.
```bibtex
@article{xu2022deep,
  title={Calibrated One-class Classification for Unsupervised Time Series Anomaly Detection},
  author={Xu, Hongzuo and Wang, Yijie and Jian, Songlei and Liao, Qing and Wang, Yongjun and Pang, Guansong},
  journal={arXiv preprint arXiv:2207.12201},
  year={2022}
}
```

There are some concerns on the use of these popular datasets. Check out the below paper for more detail and the recommended datasets therein at [here](https://compete.hexagon-ml.com/practice/competition/39/).
```bibtex
@article{wu2021current,
  title={Current time series anomaly detection benchmarks are flawed and are creating the illusion of progress},
  author={Wu, Renjie and Keogh, Eamonn},
  journal={IEEE Transactions on Knowledge and Data Engineering},
  year={2021},
  publisher={IEEE}
}
```

See the [time series data](https://github.com/GuansongPang/ADRepository-Anomaly-detection-datasets/tree/main/time%20series%20data) folder for any update of this section.


