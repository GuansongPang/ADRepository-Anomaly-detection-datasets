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

# Image Datasets
We add 9 publicly available image datasets with real anomalies from diverse application domains, including defect detection, novelty detection in rover-based planetary exploration, and lesion detection in medical images. See [image data](https://github.com/GuansongPang/anomaly-detection-datasets/tree/main/image%20data) for more details. These datasets are used to evaluate a wide range of detection models in different settings in the following paper:
```bibtex
@article{pang2021explainable,
  title={Explainable Deep Few-shot Anomaly Detection with Deviation Networks},
  author={Pang, Guansong and Ding, Choubo and Shen, Chunhua and Hengel, Anton van den},
  journal={arXiv preprint arXiv:2108.00462},
  year={2021}
}
```


