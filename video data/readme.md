Below are the links to access two popular weakly supervised video anomaly detection (WSVAD) datasets, including ShanghaiTech Campus and UCF-Crime. The sources are features extracted using I3D backbone rather than raw data. Weakly supervised video anomaly detection assumes the availability of the video-level labels and aims at detecting frame-level anomalies. They can also be re-organized and used for semi-supervised settings that the training data contains normal videos only.

## ShanghaiTech Campus
- [Training dataset](https://drive.google.com/drive/folders/1z-CQPpVtTyfZyPKZdv2hZ-h2oMF6s8ep?usp=sharing)
- [Test dataset](https://drive.google.com/drive/folders/1L71Qa0gao6aLVhSjL0H-u2khmTRKcmQs?usp=sharing)

## UCF-Crime dataset
- [Training dataset](https://drive.google.com/drive/folders/1_6FVnHYpThVd2p93wjnbNs9g1ZuaUSTp?usp=sharing)
- [Test dataset](https://drive.google.com/drive/folders/1QCBTDUMBXYU9PonPh1TWnRtpTKOX-fxr?usp=sharing)

The datasets are made available at [the RTFM repo](https://github.com/tianyu0207/RTFM) for reproducibility of the RTFM method in the following ICCV 2021 paper. Please refer to the paper and the original repo for more information of the original datasets.
```bibtex
@inproceedings{tian2021weakly,
  title={Weakly-supervised Video Anomaly Detection with Robust Temporal Feature Magnitude Learning},
  author={Tian, Yu and Pang, Guansong and Chen, Yuanhong and Singh, Rajvinder and Verjans, Johan W and Carneiro, Gustavo},
  booktitle={Proceedings of the IEEE/CVF international conference on computer vision},
  year={2021}
}
```

## XD-Violence dataset

Another popular WSVAD dataset is XD-Violence, having a set of 4,754 untrimmed videos (and audia signals) with a total duration of 217 hours. The dataset is released in the following paper:
```bibtex
@inproceedings{wu2020not,
  title={Not only look, but also listen: Learning multimodal violence detection under weak supervision},
  author={Wu, Peng and Liu, Jing and Shi, Yujia and Sun, Yujia and Shao, Fangtao and Wu, Zhaoyang and Yang, Zhiwei},
  booktitle={Computer Vision--ECCV 2020: 16th European Conference, Glasgow, UK, August 23--28, 2020, Proceedings, Part XXX 16},
  pages={322--339},
  year={2020},
  organization={Springer}
}
```

A detailed introduction to the dataset and its download link are given at [https://roc-ng.github.io/XD-Violence/](https://roc-ng.github.io/XD-Violence/).
