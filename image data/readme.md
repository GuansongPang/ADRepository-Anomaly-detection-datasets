# Image datasets
Below are the links to access 9 publicly available image datasets with real anomalies from diverse application domains. 

## Defect detection datasets
These include five benchmarks for identifying visual defects or micro-cracks on different object surfaces: 
- [MVTec AD](https://tinyurl.com/mvtecad)
- [AITEX](https://tinyurl.com/aitex-defect)
- [SDD](https://tinyurl.com/KolektorSDD)
- [ELPV](https://tinyurl.com/elpv-crack)
- [Optical](https://tinyurl.com/optical-defect)

## Novelty detection in rover-based planetary exploration
A benchmark for detecting novel observations from large-scale observations on the surface of planets (such as Mars) in rover-based planetary exploration: 
- [Mastcam](https://tinyurl.com/mastcam)

## Lesion detection in medical images
Three medical imaging benchmarks for detecting lesions on colonoscopy/MRI/CT images: 
- [Hyper-Kvasir](https://tinyurl.com/hyper-kvasir)
- [BrainMRI](https://tinyurl.com/brainMRI-tumor)
- [HeadCT](https://tinyurl.com/headCT-tumor)

**The original sources of these datasets can be found by clicking the dataset name. A preproceesed version of each of these datasets can be found at [this Github repository](https://github.com/Choubo/deviation-network-image), and more details about these preprocessed versions can be found in the following paper:**
```bibtex
@article{pang2021explainable,
  title={Explainable Deep Few-shot Anomaly Detection with Deviation Networks},
  author={Pang, Guansong and Ding, Choubo and Shen, Chunhua and Hengel, Anton van den},
  journal={arXiv preprint arXiv:2108.00462},
  year={2021}
}
```

## Out-of-distribution/anomaly semantic segmentation 
There have been a few commonly used datasets for anomaly/out-of-distribution segmentation in autonomous urban driving scenes:
- [Fishyscapes](https://paperswithcode.com/sota/anomaly-detection-on-fishyscapes-1?p=pixel-wise-energy-biased-abstention-learning)
- [Lost and Found](https://paperswithcode.com/sota/anomaly-detection-on-lost-and-found?p=pixel-wise-energy-biased-abstention-learning)
- [Road Anomaly](https://paperswithcode.com/sota/anomaly-detection-on-road-anomaly?p=pixel-wise-energy-biased-abstention-learning)
- [Fishyscapes L&F](https://paperswithcode.com/sota/anomaly-detection-on-fishyscapes-l-f?p=pixel-wise-energy-biased-abstention-learning)
- [Segment Me If You Can](https://segmentmeifyoucan.com/)

```bibtex
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
