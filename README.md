# Diabetic-Retinopathy-Detection

If you have any problems, suggestions or improvements, please submit the issue or PR.

## Contents
* [Datasets](#datasets)
* [Papers](#papers)
* [Codes](#codes)

## Datasets

| Dataset                   | Time     | Images |  Format   |  Camera  |  Resolution |  FOV  | Institudes | Tasks |
|---------------------------|----------|--------|-----------|----------|-------------|-------|------------| ----- |
| [DDR](https://github.com/nkicsl/DDR-dataset) | 2019 | 13673 | jpg | Topcon, Nikon, Canon | / | 45° | Nankai | DR grading / Lesion segmentation/detection |
| [DeepDRiD](https://isbi.deepdr.org/index.html) | 2019 | 2256 | jpg | TOPCON | 1956×1934 | / | SDCSP | DR grading / Quality assessment|
| [Kaggle](https://www.kaggle.com/c/diabetic-retinopathy-detection/) | 2015 | 88k | jpeg | / | / | 50° | EyePACS | DR grading |
| [Messidor](http://www.adcis.net/en/third-party/messidor/) | 2014 | 1200 | tiff | Topcpn TRC NW6 | 1440x960,<br>2240x1488,<br>2304x1536 | 45° | ADCIS | DR & DME grading |
| [IDRiD](https://ieee-dataport.org/open-access/indian-diabetic-retinopathy-image-dataset-idrid) | 2018 | 516/81 | jpg | Kowa VX-10α | 4288x2848 | 50° | CESIP | DR & DME grading / Typical DR lesions & optic disc detection / Optic disc and fovea center location |
| [APTOS](https://www.kaggle.com/c/aptos2019-blindness-detection) | 2019 | 13k | png | / | / | / | / | DR grading |
| [DIARETDB0](https://www.it.lut.fi/project/imageret/diaretdb0/index.html) | 2007 | 130 | jpg | / | 1500x1152 | 50° | / | DR lesions finding |
| [DIARETDB1](https://www.it.lut.fi/project/imageret/diaretdb1/index.html) | 2007 | 89 | jpg | / | 1500x1152 | 50° | / | DR lesions detection |
| [ROC](http://webeye.ophth.uiowa.edu/ROC/) | 2007 | 100 | jpg | / | 768×576,<br>1058x1061,<br>1386×1391 | 45° | / | Microaneurysms detection  |
| [E-ophtha-EX](http://www.adcis.net/en/third-party/e-ophtha/) | 2013 | 82 | jpeg | / | 2533x1696 | 45° | ADCIS | Exudates detection |
| [E-ophtha-MA](http://www.adcis.net/en/third-party/e-ophtha/) | 2013 | 381 | jpeg | / | 2533x1696 | 45° | ADCIS | Microaneurysms detection |

## Papers
<!-- 
- Unsupervised Visual Representation Learning by Context Prediction.
  [[pdf]](https://arxiv.org/abs/1505.05192)
  [[code]](http://graphics.cs.cmu.edu/projects/deepContext/)
  - Doersch, Carl and Gupta, Abhinav and Efros, Alexei A. *ICCV 2015*
-->
### 

- Diabetic Retinopathy Detection using Ensemble Machine Learning
[[pdf]](https://ieeexplore.ieee.org/document/9491645) : interesting comparison between using as training IDRID+Messidor-2 and classifying with Messidor Maybe preprocessing can be useful

- Diabetic Retinopathy Detection using Ensemble Machine Learnin  [[pdf]](https://arxiv.org/pdf/2106.12545.pdf)


### Pre-processing

- Pre-processing Image using Brightening, CLAHE and RETINEX
  [[pdf]](https://arxiv.org/pdf/2003.10822v1.pdf)
  [[code]](https://github.com/TsaiZinan/CoDER_Project_Code/blob/master/Preprocessing.py)

### Survey

- Applications of Deep Learning in Fundus Images: A Review
  [[pdf]](https://arxiv.org/abs/2101.09864)
  [[code]](https://github.com/nkicsl/Fundus_Review)
  - Tao Li, Wang Bo, Chunyu Hu, Hong Kang, Hanruo Liu, Kai Wang, Huazhu Fu. *MIA 2021*

- IDRiD: Diabetic Retinopathy – Segmentation and Grading Challenge
  [[pdf]](https://www.sciencedirect.com/science/article/pii/S1361841519301033)
  [[code]](https://idrid.grand-challenge.org/Challenge_Proceedings/)
  - Prasanna Porwal, Samiksha Pachade, Manesh Kokare. *MIA 2020*
  
- Computerised approaches for the detection of diabetic retinopathy using retinal fundus images: a survey
  [[pdf]](https://link.springer.com/content/pdf/10.1007%2Fs10044-017-0630-y.pdf)
  - Toufique Ahmed Soomro, Junbin Gao, Tariq Khan. *Pattern Anal Applic 2017*
  
- Computer-aided diagnosis of diabetic retinopathy: A review
  [[pdf]](https://www.sciencedirect.com/science/article/abs/pii/S0010482513002862)
  - Muthu Rama Krishnan Mookiah, U. Rajendra Acharya, Chua Kuang Chua. *Computers in Biology and Medicine 2013*


### DR Grading

- A deep learning system for detecting diabetic retinopathy across the disease spectrum
  [[pdf]](https://www.nature.com/articles/s41467-021-23458-5?utm_source=other&utm_medium=other&utm_content=null)
  [[code]](https://zenodo.org/badge/latestdoi/334570111)
  - Ling Dai, Liang Wu, Huating Li, Chun Cai, Qiang Wu, et al. *Nature Communication 2021*


- Multi-Task Learning for Diabetic Retinopathy Grading and Lesion Segmentation
  [[pdf]](https://www.researchgate.net/publication/342540041_Multi-Task_Learning_for_Diabetic_Retinopathy_Grading_and_Lesion_Segmentation)
  - Alex Foo, Wynne Hsu, Mong Li Lee, Gilbert Lim, Tien Yin Wong. *IAAI 2020*

- A Benchmark for Studying Diabetic Retinopathy: Segmentation, Grading, and Transferability
  [[pdf]](https://arxiv.org/pdf/2008.09772.pdf)
  [[code]](https://csyizhou.github.io/FGADR/)
  - Yi Zhou, Boyang Wang, Lei Huang, Shanshan Cui, Ling Shao. *TMI 2020*

- CABNet: Category Attention Block for Imbalanced Diabetic Retinopathy Grading
  [[pdf]](https://ieeexplore.ieee.org/document/9195035/)
  [[code]](https://github.com/he2016012996/CABnet)
  - Along He, Tao Li , Ning Li, Kai Wang, and Huazhu Fu. *TMI 2020*
  
- Collaborative learning of semi-supervised segmentation and classification for medical images
  [[pdf]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhou_Collaborative_Learning_of_Semi-Supervised_Segmentation_and_Classification_for_Medical_Images_CVPR_2019_paper.pdf)
  - Yi Zhou, Xiaodong He, Lei Huang. *CVPR 2019*
  
- CANet: Cross-disease Attention Network for Joint Diabetic Retinopathy and Diabetic Macular Edema Grading
  [[pdf]](https://arxiv.org/abs/1911.01376)
  [[code]](https://github.com/xmengli999/CANet)
  - Xiaomeng Li, Xiaowei Hu, Lequan Yu. *TMI 2019*
  
- Zoom-in-Net: Deep Mining Lesions for Diabetic Retinopathy Detection
  [[pdf]](https://arxiv.org/abs/1706.04372)
  - Zhe Wang, Yanxin Yin, Jianping Shi. *MICCAI 2018*
  
- A Framework for Identifying Diabetic Retinopathy Based on Anti-noise Detection and Attention-Based Fusion
  [[pdf]](https://link.springer.com/chapter/10.1007/978-3-030-00934-2_9)
  - Zhiwen Lin, Ruoqian Guo, Yanjie Wang. *MICCAI 2018*

- Development and Validation of a Deep Learning Algorithm for Detection of Diabetic Retinopathy in Retinal Fundus Photographs 
  [[pdf]](https://jamanetwork.com/journals/jama/fullarticle/2588763)
  - Varun Gulshan, Lily Peng, Marc Coram. *JAMA 2016*

- Grader Variability and the Importance of Reference Standards for Evaluating Machine Learning Models for Diabetic Retinopathy
  [[pdf]](https://www.aaojournal.org/article/S0161-6420(17)32698-2/fulltext)
  - Jonathan Krause, Varun Gulshan, Ehsan Rahimy. *Ophthalmology 2018*

- Using a Deep Learning Algorithm and Integrated Gradients Explanation to Assist Grading for Diabetic Retinopathy
  [[pdf]](https://www.aaojournal.org/article/S0161-6420(18)31575-6/fulltext)
  - Rory Sayres, Ankur Taly, Ehsan Rahimy. *Ophthalmology 2018*

- BIRA-NET: BILINEAR ATTENTION NET FOR DIABETIC RETINOPATHY GRADING
  [[pdf]](https://arxiv.org/pdf/1905.06312.pdf)
  - Ziyuan Zhao, Kerui Zhang, Xuejie Hao, Jing Tian. *ICIP 2019*
  
- SUNET: A LESION REGULARIZED MODEL FOR SIMULTANEOUS DIABETIC RETINOPATHY AND DIABETIC MACULAR EDEMA GRADING
  [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9098673)
  - Zhi Tu, Shenghua Gao, Kang Zhou, Xianing Chen, Jiang Liu. *ISBI 2020* 

### Segmentation
- Joint Optic Disc and Cup Segmentation Based on Multi-label Deep Network and Polar Transformation
  [[pdf]](https://arxiv.org/pdf/1801.00926.pdf)
  - Huazhu Fu, Jun Cheng, Yanwu Xu, Damon Wing Kee Wong, Jiang Liu, and Xiaochun Cao. *TMI 2017*

- Boundary and Entropy-driven Adversarial Learning for Fundus Image Segmentation
  [[pdf]](https://pubmed.ncbi.nlm.nih.gov/30871687/)
  - Shujun Wang1, Lequan Yu, Kang Li, Xin Yang, Chi-Wing Fu1, Pheng-Ann Heng. *MICCAI 2019*
  
- LESION-AWARE SEGMENTATION NETWORK FOR ATROPHY AND DETACHMENT OF PATHOLOGICAL MYOPIA ON FUNDUS IMAGES
  [[pdf]](https://ieeexplore.ieee.org/document/9098669)
  - Yan Guo, Rui Wang, Xia Zhou, Yang Liu, Lilong Wang. *ISBI 2020*
  
- Attention Guided Network for Retinal Image Segmentation
  [[pdf]](https://arxiv.org/pdf/1907.12930.pdf)
  - Zhang, Shihao，Fu, Huazhu，Yan, Yuguang，Zhang, Yubing，Wu, Qingyao，Yang, Ming，Tan, Mingkui，Xu, Yanwu. *MICCAI 2019*

- A coarse-to-fine deep learning framework for optic disc segmentationin fundus images
  [[pdf]](https://www.sciencedirect.com/science/article/pii/S1746809419300229?via%3Dihub)
  - Wang, Lei，Liu, Han，Lu, Yaling，Chen, Hang，Zhang, Jian，Pu, Jiantao. *BSPC*
  
- DoFE: Domain-oriented Feature Embedding for Generalizable Fundus Image Segmentation on Unseen Datasets
  [[pdf]](https://ieeexplore.ieee.org/document/9098673)
  - Shujun Wang，Lequan Yu，Kang Li，Xin Yang，Pheng-Ann Heng. *TMI 2019*
  
- Joint segmentation and classification of retinal arteries/veins from fundus images
  [[pdf]](https://pubmed.ncbi.nlm.nih.gov/30871687/)
  - Fantin Girard, Conrad Kavalec, Farida Cheriet. *artmed*
  
- CE-Net: Context Encoder Network for 2D Medical Image Segmentation
  [[pdf]](https://arxiv.org/pdf/1903.02740.pdf)
  - Zaiwang Gu, Jun Cheng, Huazhu Fu, Kang Zhou, Huaying Hao, Yitian Zhao, Tianyang Zhang, Shenghua Gao and Jiang Liu. *TMI2019*
  
- Patch-based Output Space Adversarial Learning for Joint Optic Disc and Cup Segmentation
  [[pdf]](https://ieeexplore.ieee.org/document/9098673)
  - Shujun Wang, Lequan Yu, Xin Yang, Chi-Wing Fu, Pheng-Ann Heng. *TMI 2019*
  
  
## Codes
- [[Team o_O](https://github.com/sveitser/kaggle_diabetic)] Team o_O solution for the Kaggle Diabetic Retinopathy Detection Challenge

- [[EyeNet](https://github.com/gregwchase/eyenet)] Identifying diabetic retinopathy using convolutional neural networks
