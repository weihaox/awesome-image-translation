# awesome image-to-image translation papers 

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com) 
![GitHub contributors](https://img.shields.io/github/contributors/weihaox/awesome-image-translation)
<!-- [![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](http://commonmark.org) -->
<!-- [![Documentation Status](https://readthedocs.org/projects/ansicolortags/badge/?version=latest)](http://ansicolortags.readthedocs.io/?badge=latest) -->

A collection of resources on image-to-image translation (constantly updating). 

This repository is organized in terms of category, another one which is organized chronologically by conferences is also [available](https://github.com/xiaweihao/awesome-image-translation/blob/master/README.md). 

## Contributing

If you think I have missed out on something (or) have any suggestions (papers, implementations and other resources), feel free to [pull a request](https://github.com/xiaweihao/awesome-image-translation/pulls)

Feedback and contributions are welcome!

## Table of Contents
- [Tutorials](#tutorials)
- [Supervised](#supervised)
- [Unsupervised](#unsupervised)
  * [General](#general)
  * [Disentanglement](#disentanglement)
  * [Multi-Domain and Multi-Modal](#multi-domain-and-multi-modal)
- [Guided Image-to-image Translation](#guided-image-to-image-translation)
  * [Scene Graphs Guided](#scene-graphs-guided)
  * [Keypoint or Landmark Guided](#keypoint-or-landmark-guided)
  * [Pose and Skeleton Guided](#pose-and-skeleton-guided)
  * [Amodal Map Guided](#amodal-map-guided)
  * [Segmentation or Label Map Guided](#segmentation-or-label-map-guided)
  * [Texture Guided](#texture-guided)
  * [Text Guided](#text-guided)
  * [Mask Guided](#mask-guided)
  * [Exemplar Guided](#exemplar-guided)
  * [Attention Guided](#attention-guided)
  * [Layout or Structure Guided](#layout-or-structure-guided)
  * [Dialog Guided](#dialog-guided)
  * [Audio Guided](#audio-guided)
- [Continous Change](#continous-change)
- [Video](#video)
- [Few-Shot](#few-shot)
- [Applications](#applications)
  * [Photo Animation](#photo-animation)
  * [Image Restoration](#image-restoration)
  * [Image ynthesis](#image-synthesis)
  * [Retargeting and 3D Vision](#retargeting-and-3d-vision)
  * [Attribute Editing](#attribute-editing)
  * [Data Augmentation](#data-augmentation)
  * [Model-Compression-and-Pruning](#model-compression-and-pruning)
  * [Adversarial Examples](#adversarial-examples)
  * [Imbalanced Data](#imbalanced-data)
- [Datasets](#datasets)

## Tutorials

[Unpaired Image-to-Image Translation.](http://efrosgans.eecs.berkeley.edu/CVPR18_slides/CycleGAN.pptx) CVPR Tutorial on GANs (2018)

[On Image-to-Image Translation.](https://people.csail.mit.edu/junyanz/talks/image_translation.pptx) Stanford, MIT, Facebook, CUHK, SNU (2017)

## Supervised

**pix2pix: Image-to-Image Translation with Conditional Adversarial Networks.**</br>
*[Phillip Isola](http://web.mit.edu/phillipi/), [Jun-Yan Zhu](http://people.csail.mit.edu/junyanz/), [Tinghui Zhou](https://people.eecs.berkeley.edu/~tinghuiz/), [Alexei A. Efros](https://people.eecs.berkeley.edu/~efros/).*<br>
CVPR 2017. [[PDF](https://arxiv.org/abs/1611.07004)] [[Github](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)]

**BicycleGAN: Toward Multimodal Image-to-Image Translation.**<br>
*Jun-Yan Zhu, Richard Zhang, Deepak Pathak, Trevor Darrell, Alexei A. Efros, Oliver Wang, Eli Shechtman.*<br>
NeurIPS 2017. [[PDF](https://arxiv.org/abs/1711.11586)] [[Github](https://github.com/junyanz/BicycleGAN)]

**PI-REC: Progressive Image Reconstruction Network With Edge and Color Domain.**</br>
*Sheng You, Ning You, Minxue Pan.*<br>
arxiv, 25 Mar 2019. [[PDF](https://arxiv.org/abs/1903.10146)] [[Github](https://github.com/youyuge34/PI-REC)]

## Unsupervised

### Truly Unsupervised

**Diverse Image Generation via Self-Conditioned GANs.**. <br>
*Steven Liu, Tongzhou Wang, David Bau, Jun-Yan Zhu, Antonio Torralba.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2006.10728)] [[Project](http://selfcondgan.csail.mit.edu/)] [[Github](https://github.com/stevliu/self-conditioned-gan)]

**TUNIT: Rethinking the Truly Unsupervised Image-to-Image Translation.**<br>
*Kyungjune Baek, Yunjey Choi, Youngjung Uh, Jaejun Yoo, Hyunjung Shim.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.05734)] [[Github](https://github.com/clovaai/tunit)]

### General

**CycleGAN: Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks.**<br>
*Jun-Yan Zhu, Taesung Park, Phillip Isola, Alexei A. Efros.*<br>
ICCV 2017. [[PDF](https://arxiv.org/abs/1703.10593)] [[Github](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)]

**DiscoGAN: Learning to Discover Cross-Domain Relations with Generative Adversarial Networks.**<br>
*Taeksoo Kim, Moonsu Cha, Hyunsoo Kim, Jung Kwon Lee, Jiwon Kim.*<br>
ICML 2017. [[PDF](https://arxiv.org/abs/1703.05192)] [[Github](https://github.com/SKTBrain/DiscoGAN)]

**DualGAN: Unsupervised Dual Learning for Image-to-Image Translation.**<br>
*Zili Yi, Hao Zhang, Ping Tan, Minglun Gong.*<br>
ICCV 2017. [[PDF](https://arxiv.org/abs/1704.02510)] [[Github](https://github.com/duxingren14/DualGAN)]

**DTN: Unsupervised Cross-Domain Image Generation.**<br> 
*Yaniv Taigman, Adam Polyak, Lior Wolf.*<br>
ICLR 2017. [[PDF](https://arxiv.org/abs/1611.02200)] [Github](https://github.com/yunjey/domain-transfer-network)]

**UNIT: Unsupervised image-to-image translation networks.**<br>
*Ming-Yu Liu, Thomas Breuel, Jan Kautz.*<br>
NeurIPS 2017. [[PDF](https://arxiv.org/abs/1703.00848)] [[Github](https://github.com/mingyuliutw/UNIT)]

**DistanceGAN: One-Sided Unsupervised Domain Mapping.**<br>
*Sagie Benaim, Lior Wolf.*<br>
NeurIPS 2017. [[PDF](https://arxiv.org/abs/1706.00826)] [[Github](https://github.com/sagiebenaim/DistanceGAN)]

**TriangleGAN: Triangle Generative Adversarial Networks.**<br>
*Zhe Gan, Liqun Chen, Weiyao Wang, Yunchen Pu, Yizhe Zhang, Hao Liu, Chunyuan Li, Lawrence Carin.*<br>
NeurIPS 2017. [[PDF](https://arxiv.org/abs/1709.06548)] [[Github](https://github.com/LiqunChen0606/Triangle-GAN)]

**NAM: Non-Adversarial Unsupervised Domain Mapping.**<br>
*Yedid Hoshen, Lior Wolf.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1806.00804)] [[Github](https://github.com/facebookresearch/nam)]

**SCAN: Unsupervised Image-to-Image Translation with Stacked Cycle-Consistent Adversarial Networks.**<br>
*Minjun Li, Haozhi Huang, Lin Ma, Wei Liu, Tong Zhang, Yu-Gang Jiang.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1807.08536)] 

**GANimorph: Improved Shape Deformation in Unsupervised Image to Image Translation.**<br>
*Aaron Gokaslan, Vivek Ramanujan, Daniel Ritchie, Kwang In Kim, James Tompkin.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1808.04325)] [[Github](https://github.com/brownvc/ganimorph/)]

**OT-CycleGAN: Guiding the One-to-one Mapping in CycleGAN via Optimal Transport.**<br>
*Guansong Lu, Zhiming Zhou, Yuxuan Song, Kan Ren, Yong Yu.*<br>
AAAI 2019. [[PDF](https://arxiv.org/abs/1811.06284)] 

**HarmonicGAN: Harmonic Unpaired Image-to-image Translation.**<br>
*Rui Zhang, Tomas Pfister, Jia Li.*<br>
ICLR 2019. [[PDF](https://arxiv.org/abs/1902.09727)]

**SDIT: Scalable and Diverse Cross-Domain Image Translation.**<br> 
*Yaxing Wang, Abel Gonzalez-Garcia, Joost van de Weijer, Luis Herranz.*<br>
ACM MM, 2019. [[PDF](https://arxiv.org/abs/1908.06881)] [[Github](https://github.com/yaxingwang/SDIT)]

**CrossNet: Latent Cross-Consistency for Unpaired Image Translation.**<br>
*Omry Sendik, Dani Lischinski, [Daniel Cohen-Or](https://danielcohenor.com/publications/).*<br>
WACV 2020. [[PDF](https://arxiv.org/abs/1901.04530)] 

**Cross-Domain Cascaded Deep Feature Translation.**<br>
*Oren Katzir, Dani Lischinski, Daniel Cohen-Or.*<br>
arxiv, 4 Jun 2019. [[PDF](https://arxiv.org/abs/1906.01526)]   

**Implicit Pairs for Boosting Unpaired Image-to-Image Translation.**<br> 
*Yiftach Ginger, Dov Danon, Hadar Averbuch-Elor, Daniel Cohen-Or.*<br> 
arxiv, 15 Apr 2019. [[PDF](https://arxiv.org/abs/1904.06913)]

**Unsupervised Shape Transformer for Image Translation and Cross-Domain Retrieval.**<br> 
*Kaili Wang, [Liqian Ma](https://homes.esat.kuleuven.be/~liqianma/), Jose Oramas M., Luc Van Gool, Tinne Tuytelaars.*<br>
arxiv, 5 Dec 2018. [[PDF](http://homes.esat.kuleuven.be/~liqianma/pdf/Arxiv18_Unsupervised_shap_transformer_for_image_translation_and_cross-domain_retrieval.pdf)] 

**A Novel BiLevel Paradigm for Image-to-Image Translation.**<br> 
*Liqian Ma, Qianru Sun, Bernt Schiele, Luc Van Gool.*<br>
arxiv, 8 Apr 2019. [[PDF](http://homes.esat.kuleuven.be/~liqianma/pdf/Arxiv19_A_Novel_BiLevel_Paradigm_for_Image-to-Image_Translation.pdf)] 

**Augmented Cyclic Consistency Regularization for Unpaired Image-to-Image Translation.**<br>
*Takehiko Ohkawa, Naoto Inoue, Hirokatsu Kataoka, Nakamasa Inoue.*<br>
arxiv, 29 Feb 2020. [[PDF](https://arxiv.org/abs/2003.00187)]

**NICE: Reusing Discriminators for Encoding: Towards Unsupervised Image-to-Image Translation.**<br>
*Runfa Chen, Wenbing Huang, Binghui Huang, Fuchun Sun, Bin Fang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.00273)] [[Github](https://github.com/alpc91/NICE-GAN-pytorch)]

**Unpaired Image-to-Image Translation using Adversarial Consistency Loss.**<br>
*Yihao Zhao, Ruihai Wu, Hao Dong.*<br>
arxiv, 10 Mar 2020. [[PDF](https://arxiv.org/abs/2003.04858)]

**Optimal Unsupervised Domain Translation.**<br>
*Emmanuel de Bézenac, Ibrahim Ayed, Patrick Gallinari.*<br>
ICML 2020 Workshop on Invertible Neural Networks, Normalizing Flows, and Explicit Likelihood Models (INNF+ ).
[[PDF](https://arxiv.org/abs/1906.01292)]

**Cross-Domain Cascaded Deep Feature Translation.**<br>
*Oren Katzir, Dani Lischinski, Daniel Cohen-Or.*<br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1906.01526)]

**Towards Lifelong Self-Supervision For Unpaired Image-to-Image Translation.**<br>
*Victor Schmidt, Makesh Narsimhan Sreedhar, Mostafa ElAraby, Irina Rish.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.00161)] [[Github](https://github.com/vict0rsch/LiSS)]

**TuiGAN: Learning Versatile Image-to-Image Translation with Two Unpaired Images.**<br>
*Jianxin Lin, Yingxue Pang, Yingce Xia, Zhibo Chen, Jiebo Luo.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.04634)]

**Unpaired Image Translation via Adaptive Convolution-based Normalization.**<br>
*[Wonwoong cho](https://wonwoongcho.github.io/), Kangyeol Kim, Eungyeup Kim, Hyunwoo J. Kim, Jaegul Choo.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/1911.13271)]

**What and Where to Translate: Local Mask-based Image-to-Image Translation.**<br>
*Wonwoong Cho, Seunghwan Choi, Junwoo Park, David Keetae Park, Tao Qin, Jaegul Choo.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/1906.03598)]

### Disentanglement

**Guided Variational Autoencoder for Disentanglement Learning.**<br>
*Zheng Ding, Yifan Xu, Weijian Xu, Gaurav Parmar, Yang Yang, Max Welling, Zhuowen Tu.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.01255)]

**XGAN: Unsupervised Image-to-Image Translation for Many-to-Many Mappings.**<br>
*Amélie Royer, Konstantinos Bousmalis, Stephan Gouws, Fred Bertsch, Inbar Mosseri, Forrester Cole, Kevin Murphy.*<br>
ICML 2018. [[PDF](https://arxiv.org/abs/1711.05139)] [[Dataset](https://google.github.io/cartoonset/)]

**ELEGANT: Exchanging Latent Encodings with GAN for Transferring Multiple Face Attributes.**<br>
*Taihong Xiao, Jiapeng Hong, Jinwen Ma.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1803.10562)] [[Github](https://github.com/Prinsphield/ELEGANT)] 

**MUNIT: Multimodal Unsupervised Image-to-Image Translation.**<br>
*Xun Huang, Ming-Yu Liu, Serge Belongie, Jan Kautz.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1804.04732)] [[Github](https://github.com/NVlabs/MUNIT)]

**Image-to-Image Translation for Cross-Domain Disentanglement.**<br>
*Abel Gonzalez-Garcia, Joost van de Weijer, Yoshua Bengio.*<br>
NeurIPS 2018. [[PDF](https://arxiv.org/abs/1805.09730)]    

**Conditional Image-to-Image Translation.**</br> 
*Jianxin Lin, Yingce Xia, Tao Qin, Zhibo Chen, Tie-Yan Liu.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1805.00251)]     

**EGSC-IT: Exemplar Guided Unsupervised Image-to-Image Translation with Semantic Consistency.**</br> 
*Liqian Ma, Xu Jia, Stamatios Georgoulis, Tinne Tuytelaars, Luc Van Gool.*<br>
ICLR 2019. [[PDF](https://arxiv.org/abs/1805.11145)] [[Github](https://github.com/charliememory/EGSC-IT)]

**PairedCycleGAN: Asymmetric Style Transfer for Applying and Removing Makeup.**<br> 
*Huiwen Chang, Jingwan Lu, Fisher Yu, Adam Finkelstein.*<br>
CVPR 2018. [[PDF](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chang_PairedCycleGAN_Asymmetric_Style_CVPR_2018_paper.pdf)] 

**DRIT: Diverse Image-to-Image Translation via Disentangled Representations.**<br> 
*Hsin-Ying Lee, Hung-Yu Tseng, Jia-Bin Huang, Maneesh Kumar Singh, Ming-Hsuan Yang.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1808.00948)] [[Github](https://github.com/HsinYingLee/DRIT)]

**UFDN: A Unified Feature Disentangler for Multi-Domain Image Translation and Manipulation.**<br> 
*Alexander H. Liu, Yen-Cheng Liu, Yu-Ying Yeh, Yu-Chiang Frank Wang.*<br>
NeurIPS 2018. [[PDF](https://arxiv.org/abs/1809.01361)] [[Github](https://github.com/Alexander-H-Liu/UFDN)]

**GDWTC: Image-to-Image Translation via Group-wise Deep Whitening and Coloring Transformation.**</br> 
*Wonwoong Cho, Sungha Choi, David Keetae Park, Inkyu Shin, Jaegul Choo.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1812.09912)] [[Github](https://github.com/WonwoongCho/GDWCT)]

**DRIT++: Diverse Image-to-Image Translation via Disentangled Representations.**<br> 
*Hsin-Ying Lee, Hung-Yu Tseng, Qi Mao, Jia-Bin Huang, Yu-Ding Lu, Maneesh Singh, Ming-Hsuan Yang.*<br>
IJCV 2019. [[PDF](https://arxiv.org/abs/1905.01270)] [[[Project](http://vllab.ucmerced.edu/hylee/DRIT_pp/)] [[Github](https://github.com/HsinYingLee/MDMM)]

**Multi-mapping Image-to-Image Translation via Learning Disentanglement.**</br>
*Xiaoming Yu, Yuanqi Chen, Thomas Li, Shan Liu, Ge Li.*<br>
NeurIPS 2019. [[PDF](https://arxiv.org/abs/1909.07877)] [[Github](https://github.com/Xiaoming-Yu/DMIT)]               

**Flow-based Image-to-Image Translation with Feature Disentanglement.**</br> 
*Ruho Kondo, Keisuke Kawano, Satoshi Koide, Takuro Kutsuna.*<br>
NeurIPS 2019. [[PDF](http://papers.nips.cc/paper/8670-flow-based-image-to-image-translation-with-feature-disentanglement.pdf)]

**DosGAN: Exploring Explicit Domain Supervision for Latent Space Disentanglement in Unpaired Image-to-Image Translation.**<br>
*[Jianxin Lin](http://home.ustc.edu.cn/~linjx/), [Zhibo Chen](http://staff.ustc.edu.cn/~chenzhibo/), Yingce Xia, Sen Liu, Tao Qin, Jiebo Luo.*<br>
TPAMI 2019. [[PDF](https://arxiv.org/abs/1902.03782)] [[Github](https://github.com/linjx-ustc1106/DosGAN-PyTorch)]

### Multi-Domain and Multi-Modal

**Unsupervised multi-modal Styled Content Generation.**<br>
*Omry Sendik, Dani Lischinski, Daniel Cohen-Or.*<br>
SIGGRAPH 2020. [[PDF](https://arxiv.org/abs/2001.03640)]

**Multimodal Image Synthesis with Conditional Implicit Maximum Likelihood Estimation.**<br>
*Ke Li, Shichong Peng, Tianhao Zhang, Jitendra Malik.*<br>
IJCV 2020. [[PDF](https://arxiv.org/abs/2004.03590)]

**MSGAN: Mode Seeking Generative Adversarial Networks for Diverse Image Synthesis.**<br>
*Qi Mao, Hsin-Ying Lee, Hung-Yu Tseng, Siwei Ma, Ming-Hsuan Yang.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1903.05628)] [[Github](https://github.com/HelenMao/MSGAN)]

**GMM-UNIT: Unsupervised Multi-Domain and Multi-Modal Image-to-Image Translation via Attribute Gaussian Mixture Modeling.**<br> 
*Yahui Liu, Marco De Nadai, Jian Yao, Nicu Sebe, Bruno Lepri, Xavier Alameda-Pineda.*</br>
arxiv, 2020. [[PDF](https://arxiv.org/abs/2003.06788)

**StarGAN v2: Diverse Image Synthesis for Multiple Domains.**<br> 
*Yunjey Choi, Youngjung Uh, Jaejun Yoo, Jung-Woo Ha. Clova AI Research, NAVER Corp.*<br> 
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.01865)] [[GitHub](https://github.com/clovaai/stargan-v2)]

**Attribute-Guided Face Generation Using Conditional CycleGAN.**<br>
*Yongyi Lu, Yu-Wing Tai, Chi-Keung Tang.*<br>
ECCV 2018.  [[PDF](https://arxiv.org/abs/1705.09966)] 

**StarGAN: Uniﬁed Generative Adversarial Networks for Multi-Domain Image-to-Image Translation.**<br>
*Yunjey Choi, Minje Choi, Munyoung Kim, Jung-Woo Ha, Sunghun Kim, Jaegul Choo.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1711.09020)] [[Github](https://github.com/yunjey/StarGAN)]

**AttGAN: Facial Attribute Editing by Only Changing What You Want.**<br>
*Zhenliang He, Wangmeng Zuo, Meina Kan, Shiguang Shan, Xilin Chen.*<br>
TIP 2019. [[PDF](https://arxiv.org/abs/1711.10678)] [[Github](https://github.com/LynnHo/AttGAN-Tensorflow)]

**ComboGAN: Unrestrained Scalability for Image Domain Translation.**<br>
*Asha Anoosheh, Eirikur Agustsson, Radu Timofte, Luc Van Gool.*<br>
CVPRW 2018. [[PDF](https://arxiv.org/abs/1712.06909)] [[Github](https://github.com/AAnoosheh/ComboGAN)]  

**Augmented CycleGAN: Learning Many-to-Many Mappings from Unpaired Data.**<br>
*Amjad Almahairi, Sai Rajeswar, Alessandro Sordoni, Philip Bachman, Aaron Courville.*<br>
ICML 2018. [[PDF](https://arxiv.org/abs/1802.10151)] [[Github](https://github.com/aalmah/augmented_cyclegan)] 

**ModularGAN: Modular Generative Adversarial Networks.**<br>
*Bo Zhao, Bo Chang, Zequn Jie, Leonid Sigal.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1804.03343)] 

**SG-GAN: Sparsely Grouped Multi-task Generative Adversarial Networks for Facial Attribute Manipulation.**<br>
*Jichao Zhang, Yezhi Shu, Songhua Xu, Gongze Cao, Fan Zhong, Xueying Qin.*<br>
ACM MM 2018. [[PDF](https://arxiv.org/abs/1805.07509)] [[Github](https://github.com/zhangqianhui/Sparsely-Grouped-GAN)] 

**SingleGAN: Image-to-Image Translation by a Single-Generator Network using Multiple Generative Adversarial Learning.**<br>
*Xiaoming Yu, Xing Cai, Zhenqiang Ying, Thomas Li, Ge Li.*<br>
ACCV 2018. [[PDF](https://arxiv.org/abs/1810.04991)] [[Github](https://github.com/Xiaoming-Yu/SingleGAN)] 

**SMIT: Stochastic Multi-Label Image-to-Image Translation.**</br>
*Andrés Romero, Pablo Arbeláez, Luc Van Gool, Radu Timofte.*<br>
ICCV Workshops 2019. [[PDF](https://arxiv.org/abs/1812.03704)] [[Github](https://github.com/BCV-Uniandes/SMIT)]                                                               
**Image-to-Image Translation with Multi-Path Consistency Regularization.**<br> 
*Jianxin Lin, Yingce Xia, Yijun Wang, Tao Qin, Zhibo Chen.*<br> 
IJCAI 2019. [[PDF](https://arxiv.org/abs/1905.12498)]   

**RelGAN: Multi-Domain Image-to-Image Translation via Relative Attributes.**<br> 
*Po-Wei Wu, Yu-Jing Lin, Che-Han Chang, Edward Y. Chang, Shih-Wei Liao.*<br> 
ICCV 2019. [[PDF](https://arxiv.org/abs/1908.07269)]  

**DMIT: Multi-mapping Image-to-Image Translation via Learning Disentanglement.**<br>
*Xiaoming Yu, Yuanqi Chen, Thomas Li, Shan Liu, Ge Li.*<br> 
NeurIPS 2019. [[PDF](https://arxiv.org/abs/1909.07877)] [[Github](https://github.com/Xiaoming-Yu/DMIT)]

**ADSPM: Attribute-Driven Spontaneous Motion in Unpaired Image Translation.**<br> 
*Ruizheng Wu, Xin Tao, Xiaodong Gu, Xiaoyong Shen, Jiaya Jia.*<br> 
ICCV 2019. [[PDF](https://arxiv.org/abs/1907.01452)] [[Github](https://github.com/mikirui/ADSPM)] 

**CartoonRenderer: An Instance-based Multi-Style Cartoon Image Translator.**<br>
*Yugang Chen, Muchun Chen, Chaoyue Song, Bingbing Ni.*<br> 
International Conference on Multimedia Modeling (MMM 2020). [[PDF](https://arxiv.org/abs/1911.06102)]

**injectionGAN: Toward Learning a Unified Many-to-Many Mapping for Diverse Image Translation.**</br>
*Wenju Xu, Shawn Keshmiri, Guanghui Wang.*</br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1905.08766)]

**DCMIT: Unsupervised Multi-Domain Multimodal Image-to-Image Translation with Explicit Domain-Constrained Disentanglement.**</br>
*Weihao Xia, Yujiu Yang, Jing-Hao Xue.*</br>
Neural Networks 2020. [[PDF](https://arxiv.org/abs/1911.00622)]

## Guided Image-to-image Translation

### Scene Graphs Guided

**Semantic Image Manipulation Using Scene Graphs.**<br>
*Helisa Dhamo, Azade Farshad, Iro Laina, Nassir Navab, Gregory D. Hager, Federico Tombari, Christian Rupprecht.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.03677)]

### Texture Guided

**TextureGAN: Controlling Deep Image Synthesis with Texture Patches.**<br>
*Wenqi Xian, Patsorn Sangkloy, Varun Agrawal, Amit Raj, Jingwan Lu, Chen Fang, Fisher Yu, James Hays.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1706.02823)] [[Github](https://github.com/janesjanes/Pytorch-TextureGAN)]

**Guided Image-to-Image Translation with Bi-Directional Feature Transformation.**<br>
*Badour AlBahar, Jia-Bin Huang.*<br>
ArXiv 2019. [[PDF](https://arxiv.org/abs/1910.11328)] [[Github](http://t.cn/Ai1beVDp)] 

### Amodal Map Guided

**Self-Supervised Scene De-occlusion.**<br>
*[Xiaohang Zhan](https://xiaohangzhan.github.io/), Xingang Pan, Bo Dai, Ziwei Liu, Dahua Lin, and Chen Change Loy.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.02788)] [[Github](https://github.com/XiaohangZhan/deocclusion)] [[Project](https://xiaohangzhan.github.io/projects/deocclusion/)] [[Demo](https://www.youtube.com/watch?v=xIHCyyaB5gU)]

### Segmentation or Label Map Guided

**World-Consistent Video-to-Video Synthesis.**<br> 
*Arun Mallya, Ting-Chun Wang, Karan Sapra, Ming-Yu Liu.*<br> 
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.08509)] [[Github](https://nvlabs.github.io/wc-vid2vid/)]

**Example-Guided Image Synthesis across Arbitrary Scenes using Masked Spatial-Channel Attention and Self-Supervision.**<br>
*Haitian Zheng, Haofu Liao, Lele Chen, Wei Xiong, Tianlang Chen, Jiebo Luo.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.10024)]

**Attentive Normalization for Conditional Image Generation.**<br>
*Yi Wang, Ying-Cong Chen, Xiangyu Zhang, Jian Sun, Jiaya Jia.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.03828)]

**Edge Guided GANs with Semantic Preserving for Semantic Image Synthesis.**<br>
*Hao Tang, Xiaojuan Qi, Dan Xu, Philip H. S. Torr, Nicu Sebe.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2003.13898)] [[Github](https://github.com/Ha0Tang/EdgeGAN)]

**Local Class-Specific and Global Image-Level Generative Adversarial Networks for Semantic-Guided Scene Generation.**<br>
*[Hao Tang](http://disi.unitn.it/~hao.tang/), Dan Xu, Yan Yan, Philip H. S. Torr, [Nicu Sebe](https://scholar.google.com/citations?user=stFCYOAAAAAJ&hl=en).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.12215)] [[Github](https://github.com/Ha0Tang/LGGAN)]

**High-Resolution Image Synthesis and Semantic Manipulation with Conditional GANs.**<br>
*Ting-Chun Wang, Ming-Yu Liu, Jun-Yan Zhu, Andrew Tao, Jan Kautz, Bryan Catanzaro.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1711.11585)] [[Github](https://github.com/NVIDIA/pix2pixHD)]

**SPADE: Semantic Image Synthesis with Spatially-Adaptive Normalization.**</br>
*Taesung Park, Ming-Yu Liu, Ting-Chun Wang, Jun-Yan Zhu.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1903.07291)] [[Github](https://github.com/NVlabs/SPADE)]

**SelectionGAN: Multi-Channel Attention Selection GAN with Cascaded Semantic Guidance for Cross-View Image Translation.**<br>
*Hao Tang, Dan Xu, Nicu Sebe, Yanzhi Wang, Jason J. Corso, Yan Yan.*<br>
VPR 2019. [[PDF](https://arxiv.org/abs/1904.06807)] [[Github](https://github.com/Ha0Tang/SelectionGAN)]

**Art2Real: Unfolding the Reality of Artworks via Semantically-Aware Image-to-Image Translation.**<br>
*Matteo Tomei, Marcella Cornia, Lorenzo Baraldi, Rita Cucchiara.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1811.10666)] [[Github](https://github.com/aimagelab/art2real)]

**Mask-Guided Portrait Editing with Conditional GANs.**<br>
*Shuyang Gu, Jianmin Bao, Hao Yang, Dong Chen, Fang Wen, Lu Yuan.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1905.10346)] [[Github](https://github.com/cientgu/Mask_Guided_Portrait_Editing)]

**Semantic Bottleneck Scene Generation.**<br>
*Samaneh Azadi, Michael Tschannen, Eric Tzeng, Sylvain Gelly, Trevor Darrell, Mario Lucic.*<br>
arxiv, 2019. [[PDF](https://arxiv.org/abs/1911.11357)]

**Video Generation from Single Semantic Label Map.**<br>
*Junting Pan, Chengyu Wang, Xu Jia, Jing Shao, Lu Sheng, Junjie Yan, Xiaogang Wang.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1903.04480)] [[Github](https://github.com/junting/seg2vid)]

**Video-to-Video Synthesis.**<br>
*Ting-Chun Wang, Ming-Yu Liu, Jun-Yan Zhu, Guilin Liu, Andrew Tao, Jan Kautz, Bryan Catanzaro.*<br>
NeurIPS 2018. [[PDF](https://arxiv.org/abs/1808.06601)] [[Github](https://github.com/NVIDIA/vid2vid)]   

**Few-shot Video-to-Video Synthesis.**</br>
*Ting-Chun Wang, Ming-Yu Liu, Andrew Tao, Guilin Liu, Jan Kautz, Bryan Catanzaro.*<br> 
ArXiv 2019. [[PDF](https://nvlabs.github.io/few-shot-vid2vid/main.pdf)] [[Project](https://nvlabs.github.io/few-shot-vid2vid/)]

### Text Guided

#### Text-Guided Manipulation

**SISGAN: Semantic Image Synthesis via Adversarial Learning.**<br>
*Hao Dong, Simiao Yu, Chao Wu, Yike Guo.*<br>
ICCV 2017. [[PDF](https://arxiv.org/abs/1707.06873)] [[Github](https://github.com/woozzu/dong_iccv_2017)]

**Text-Adaptive Generative Adversarial Networks: Manipulating Images with Natural Language.**<br>
*[Seonghyeon Nam](http://snam.ml/), Yunji Kim, Seon Joo Kim.*<br>
NeurIPS 2018. [[PDF](https://arxiv.org/abs/1810.11919)] [[Github](https://github.com/woozzu/tagan)]

**Lightweight Generative Adversarial Networks for Text-Guided Image Manipulation.**<br>
*Bowen Li, Xiaojuan Qi, Philip Torr, Thomas Lukasiewicz.*<br>
NeurIPS 2020. [[PDF]()]

**ManiGAN: Text-Guided Image Manipulation.**<br>
*[Bowen Li](https://mrlibw.github.io/), [Xiaojuan Qi](https://xjqi.github.io/), Thomas Lukasiewicz, Philip H. S. Torr.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.06203)] [[Github](https://github.com/mrlibw/ManiGAN)]

**Generative Adversarial Text to Image Synthesis.**<br>
*Scott Reed, Zeynep Akata, Xinchen Yan, Lajanugen Logeswaran, Bernt Schiele, Honglak Lee.*<br>
ICML 2016. [[PDF](https://arxiv.org/abs/1605.05396)] [[Github](https://github.com/reedscot/icml2016)]

**Image-to-Image Translation with Text Guidance.**<br>
*Bowen Li, Xiaojuan Qi, Philip H. S. Torr, Thomas Lukasiewicz.*<br>
arxiv, 12 Feb 2020. [[PDF](https://arxiv.org/abs/2002.05235)]

**Neural Image Inpainting Guided with Descriptive Text.**<br>
*Lisai Zhang, Qingcai Chen, Baotian Hu, Shuoran Jiang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.03212)]

#### Text-to-Image Generation

**ControlGAN: Controllable Text-to-Image Generation.**<br>
*Bowen Li, Xiaojuan Qi, Thomas Lukasiewicz, Philip H. S. Torr.*<br>
NeurIPS 2019. [[PDF](https://papers.nips.cc/paper/8480-controllable-text-to-image-generation.pdf)] [[Github](https://github.com/mrlibw/ControlGAN)]

**RiFeGAN: Rich Feature Generation for Text-to-Image Synthesis From Prior Knowledge.**<br>
*Jun Cheng, Fuxiang Wu, Yanling Tian, Lei Wang, Dapeng Tao.*<br>
CVPR 2020. [[PDF](http://openaccess.thecvf.com/content_CVPR_2020/papers/Cheng_RiFeGAN_Rich_Feature_Generation_for_Text-to-Image_Synthesis_From_Prior_Knowledge_CVPR_2020_paper.pdf)]

**MirrorGAN: Learning Text-to-image Generation by Redescription.**<br>
*Tingting Qiao, Jing Zhang, Duanqing Xu, Dacheng Tao.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1903.05854)] [[Unofficial TensorFlow](https://github.com/taki0112/MirrorGAN-Tensorflow)]

**AttnGAN: Fine-Grained Text to Image Generation with Attentional Generative Adversarial Networks.**<br>
*Tao Xu, Pengchuan Zhang, Qiuyuan Huang, Han Zhang, Zhe Gan, Xiaolei Huang, Xiaodong He.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1711.10485)] [[Github](https://github.com/taoxugit/AttnGAN)]

**DM-GAN: Dynamic Memory Generative Adversarial Networks for Text-to-Image Synthesis.**<br>
*Minfeng Zhu, Pingbo Pan, Wei Chen, Yi Yang.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1904.01310)] [[Github](https://github.com/MinfengZhu/DM-GAN)]

**StackGAN++: Realistic Image Synthesis with Stacked Generative Adversarial Networks.**<br>
*Han Zhang, Tao Xu, Hongsheng Li, Shaoting Zhang, Xiaogang Wang, Xiaolei Huang, Dimitris Metaxas.*<br>
TPAMI 2018. [[PDF](https://arxiv.org/abs/1710.10916)] [[Github](https://github.com/hanzhanggit/StackGAN-v2)]

**StackGAN: Text to Photo-realistic Image Synthesis with Stacked Generative Adversarial Networks.**<br>
*Han Zhang, Tao Xu, Hongsheng Li, Shaoting Zhang, Xiaogang Wang, Xiaolei Huang, Dimitris Metaxas.*<br>
ICCV 2017. [[PDF](https://arxiv.org/abs/1612.03242v2)] [[Github](https://github.com/hanzhanggit/StackGAN-Pytorch)]

**CPGAN: Content-Parsing Generative Adversarial Networks for Text-to-Image Synthesis.**<br>
*Jiadong Liang, Wenjie Pei, Feng Lu.*<br>
ECCV 2020. [[PDF](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490477.pdf)] [[Github](https://github.com/dongdongdong666/CPGAN)]

**DF-GAN: Deep Fusion Generative Adversarial Networks for Text-to-Image Synthesis.**<br>
*Ming Tao, Hao Tang, Songsong Wu, Nicu Sebe, Fei Wu, Xiao-Yuan Jing.*<br>
TMM 2020. [[PDF](https://arxiv.org/pdf/2008.05865)]

**GeNeVA-GAN: Tell, Draw, and Repeat: Generating and Modifying Images Based on Continual Linguistic Instruction.**<br>
*Alaaeldin El-Nouby, Shikhar Sharma, Hannes Schulz, Devon Hjelm, Layla El Asri, Samira Ebrahimi Kahou, Yoshua Bengio, Graham W.Taylor.*<br>
ICCV 2019. [[PDF](https://arxiv.org/pdf/1811.09845v3.pdf)] [[Github](https://github.com/Maluuba/GeNeVA_datasets)]

**LeicaGAN: Learn, Imagine and Create: Text-to-Image Generation from Prior Knowledge.**<br>
*Tingting Qiao, [Jing Zhang](https://www.sydney.edu.au/engineering/about/our-people/academic-staff/jing-zhang1.html), Duanqing Xu, Dacheng Tao.*<br>
NeurIPS 2019. [[PDF](http://papers.nips.cc/paper/8375-learn-imagine-and-create-text-to-image-generation-from-prior-knowledge.pdf)] [[Github](https://github.com/qiaott/LeicaGAN)]

**HD-GAN: Photographic Text-to-Image Synthesis with a Hierarchically-nested Adversarial Network.**<br>
*Zizhao Zhang, Yuanpu Xie, Lin Yang.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1802.09178)] [[Github](https://github.com/ypxie/HDGan)]

**Adversarial Synthesis of Human Pose from Text.**<br>
*Yifei Zhang, Rania Briq, Julian Tanke, Juergen Gall.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2005.00340)]

**Semantic Object Accuracy for Generative Text-to-Image Synthesis.**<br>
*Tobias Hinz, Stefan Heinrich, Stefan Wermter.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/1910.13321)] [[Github](https://github.com/tohinz/semantic-object-accuracy-for-generative-text-to-image-synthesis)]

**3DLSN: End-to-End Optimization of Scene Layout.**<br>
*Andrew Luo, Zhoutong Zhang, Jiajun Wu, Joshua B. Tenenbaum.*<br>
CVPR 2020. [[PDF](https://jiajunwu.com/papers/3dsln_cvpr.pdf)] [[Project](http://3dsln.csail.mit.edu/)]

**CookGAN: Meal Image Synthesis from Ingredients.**<br>
*Fangda Han, Ricardo Guerrero, Vladimir Pavlovic.*<br>
WACV 2020. [[PDF](https://arxiv.org/abs/2002.11493)]

**Object-driven Text-to-Image Synthesis via Adversarial Training.**<br>
*Wenbo Li, Pengchuan Zhang, Lei Zhang, Qiuyuan Huang, Xiaodong He, Siwei Lyu, Jianfeng Gao.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1902.10740)]

**SwapText: Image Based Texts Transfer in Scenes.**<br>
*Qiangpeng Yang, Hongsheng Jin, Jun Huang, Wei Lin.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.08152)]

**Local-Global Video-Text Interactions for Temporal Grounding.**<br>
*[Jonghwan Mun](http://cvlab.postech.ac.kr/~jonghwan/), [Minsu Cho](http://cvlab.postech.ac.kr/~mcho/), [Bohyung Han](https://cv.snu.ac.kr/index.php/bhhan/).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.07514)] [[Github](https://github.com/JonghwanMun/LGI4temporalgrounding)]

**Cycle Text-To-Image GAN with BERT.**<br>
*Trevor Tsue, Samir Sen, Jason Li.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2003.12137)] [Github](https://github.com/suetAndTie/cycle-image-gan)]

**Learning Deep Representations of Fine-grained Visual Descriptions.**<br>
*Scott Reed, Zeynep Akata, Bernt Schiele, Honglak Lee.*<br>
CVPR 2016. [[PDF](https://arxiv.org/abs/1605.05395)] [[Github](https://github.com/reedscot/cvpr2016)]

### Keypoint or Landmark Guided

**ADGAN: Controllable Person Image Synthesis with Attribute-Decomposed GAN.**<br>
*[Yifang Men](https://menyifang.github.io/), [Yiming Mao](https://mtroym.github.io/), Yuning Jiang, Wei-Ying Ma, Zhouhui Lian.*<br>
CVPR 2020. [[PDF](https://menyifang.github.io/projects/ADGAN/ADGAN_files/Paper_ADGAN_CVPR2020.pdf)] [[Project](https://menyifang.github.io/projects/ADGAN/ADGAN.html)]  [[Github](https://github.com/menyifang/ADGAN)]

**AGUIT: Attribute Guided Unpaired Image-to-Image Translation with Semi-supervised Learning.**<br>
*Xinyang Li, Jie Hu, Shengchuan Zhang, Xiaopeng Hong, Qixiang Ye, Chenglin Wu, Rongrong Ji.*<br>
arxiv, 29 Apr 2019. [[PDF](https://arxiv.org/abs/1904.12428)] [[Github](https://github.com/imlixinyang/AGUIT)]

**Geometry Guided Adversarial Facial Expression Synthesis.**<br>
*Lingxiao Song, Zhihe Lu, Ran He, Zhenan Sun, Tieniu Tan.*<br>
MM 2018. [[PDF](https://arxiv.org/abs/1712.03474)] 

**C2-GAN: Cycle In Cycle Generative Adversarial Networks for Keypoint-Guided Image Generation.**</br>
*Hao Tang, Dan Xu, Gaowen Liu, Wei Wang, Nicu Sebe, Yan Yan.*<br>
MM 2019. [[PDF](https://arxiv.org/abs/1908.00999)] [[Gtihub](https://github.com/Ha0Tang/C2GAN)]

**Few-Shot Adversarial Learning of Realistic Neural Talking Head Models.**<br>
*Egor Zakharov, Aliaksandra Shysheya, Egor Burkov, Victor Lempitsky.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1905.08233)] [[Github](https://github.com/grey-eye/talking-heads)]

**Geometry Guided Adversarial Facial Expression Synthesis.**<br>
*Lingxiao Song, Zhihe Lu, Ran He, Zhenan Sun, Tieniu Tan.*<br>
MM 2018. [[PDF](https://arxiv.org/abs/1712.03474)]  

### Pose and Skeleton Guided

**Deep Spatial Transformation for Pose-Guided Person Image Generation and Animation.**<br>
*Yurui Ren, Ge Li, Shan Liu, Thomas H. Li.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.12606)] [[Github](https://github.com/RenYurui/Global-Flow-Local-Attention)]

**Pose Manipulation with Identity Preservation.**<br>
*Andrei-Timotei Ardelean, Lucian Mircea Sasu.*<br>
International Journal of Computers Communications & Control 2020. [[PDF](https://arxiv.org/abs/2004.09169)]

**Pose Guided Person Image Generation.**<br>
*Liqian Ma, Xu Jia, Qianru Sun, Bernt Schiele, Tinne Tuytelaars, Luc Van Gool.*<br>
NIPS 2017. [[PDF](https://arxiv.org/abs/1705.09368)] [[Github](https://github.com/charliememory/Pose-Guided-Person-Image-Generation)]

**Deformable GANs for Pose-based Human Image Generation.**<br>
*Aliaksandr Siarohin, Enver Sangineto, Stephane Lathuiliere, Nicu Sebe.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1801.00055)] [[Github](https://github.com/AliaksandrSiarohin/pose-gan)]

**A Variational U-Net for Conditional Appearance and Shape Generation.**<br>
*Patrick Esser, Ekaterina Sutter, Björn Ommer.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1804.04694)] [[Github](https://github.com/CompVis/vunet)]

**Progressive Pose Attention Transfer for Person Image Generation.**<br>
*Zhen Zhu, Tengteng Huang, Baoguang Shi, Miao Yu, Bofei Wang, Xiang Bai.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1904.03349)] [[Github](https://github.com/tengteng95/Pose-Transfer)]

**Everybody Dance Now.**<br>
*Caroline Chan, Shiry Ginosar, Tinghui Zhou, Alexei A. Efros.*<br>
ECCVW 2018. [[PDF](https://arxiv.org/abs/1808.07371)] [[Project](https://carolineec.github.io/everybody_dance_now/)]

**Disentangled Person Image Generation.**<br>
*[Liqian Ma](https://www.esat.kuleuven.be/psi/members/00111336), [Qianru Sun](https://qianrusun.com/), Stamatios Georgoulis, Luc Van Gool, Bernt Schiele, Mario Fritz.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1712.02621)]

### Mask Guided

**InstaGAN: Instance-aware image-to-image translation.**<br>
*Zhiqiang Shen, Mingyang Huang, Jianping Shi, Xiangyang Xue, Thomas Huang.*<br>
ICLR 2019. [[PDF](https://openreview.net/pdf?id=ryxwJhC9YX)] [[Github](https://github.com/sangwoomo/instagan)] 

**ContrastGAN: Generative Semantic Manipulation with Mask-Contrasting GAN.**<br>
*Xiaodan Liang, Hao Zhang, Eric P. Xing.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1708.00315)]

**INIT: Towards Instance-level Image-to-Image Translation.**<br>
*Zhiqiang Shen, Mingyang Huang, Jianping Shi, Xiangyang Xue, Thomas Huang.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1905.01744)] [[project](http://zhiqiangshen.com/projects/INIT/index.html)] 

### Exemplar Guided

**Controllable Descendant Face Synthesis.**<br>
*Yong Zhang, Le Li, Zhilei Liu, Baoyuan Wu, Yanbo Fan, Zhifeng Li.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2002.11376)]

**pix2pixSC: Example-Guided Style Consistent Image Synthesis from Semantic Labeling.**<br>
*Miao Wang, Guo-Ye Yang, Ruilong Li, Run-Ze Liang, Song-Hai Zhang, Peter. M. Hall, Shi-Min Hu.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1906.01314)] [[Github](https://github.com/cxjyxxme/pix2pixSC)] [[Project](http://www.liruilong.cn/projects/GuidedPix2Pix/index.html)]

**EGSC-IT: Exemplar Guided Unsupervised Image-to-Image Translation with Semantic Consistency.**</br> 
*Liqian Ma, Xu Jia, Stamatios Georgoulis, Tinne Tuytelaars, Luc Van Gool.*<br>
ICLR 2019. [[PDF](https://arxiv.org/abs/1805.11145)] [[Github](https://github.com/charliememory/EGSC-IT)]

**DA-GAN: Instance-level Image Translation by Deep Attention Generative Adversarial Networks.**<br>
*Shuang Ma, Jianlong Fu, Chang Wen Chen, Tao Mei.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1802.06454)] 

**Stylizing Video by Example.**<br> 
*Ondřej Jamriška, Šárka Sochorová, Ondřej Texler, Michal Lukáč, Jakub Fišer, Jingwan Lu, Eli Shechtman, Daniel Sýkora.*<br>
SIGGRAPH 2019. [[PDF](https://dcgi.fel.cvut.cz/home/sykorad/Jamriska19-SIG.pdf)]

### Attention Guided

**Attention-GAN for Object Transfiguration in Wild Images.**<br>
*Xinyuan Chen, Chang Xu, Xiaokang Yang, Dacheng Tao.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1803.06798)]

**Unsupervised Attention-guided Image to Image Translation.**<br>
*Youssef A. Mejjati, Christian Richardt, James Tompkin, Darren Cosker, Kwang In Kim.*<br>
NeurIPS 2018. [[PDF](https://arxiv.org/abs/1806.02311)] [[Github](https://github.com/AlamiMejjati/Unsupervised-Attention-guided-Image-to-Image-Translation)]

**Show, Attend and Translate: Unsupervised Image Translation with Self-Regularization and Attention.**<br>
*Chao Yang, Taehwan Kim, Ruizhe Wang, Hao Peng, C.-C. Jay Kuo.*</br>
TIP 2019. [[PDF](https://arxiv.org/abs/1806.06195)]

**U-GAT-IT: Unsupervised Generative Attentional Networks with Adaptive Layer-Instance Normalization for Image-to-Image Translation.**<br>
*Junho Kim, Minjae Kim, Hyeonwoo Kang, Kwanghee Lee.*<br>
ICLR 2020. [[PDF](https://arxiv.org/abs/1907.10830)] [[TensorFlow](https://github.com/taki0112/UGATIT) or [Pytorch](https://github.com/znxlwm/UGATIT-pytorch)]

**SPA-GAN: Spatial Attention GAN for Image-to-Image Translation.**<br>
*Hajar Emami, Majid Moradi Aliabadi, Ming Dong, Ratna Babu Chinnam.*<br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1908.06616)] 

### Layout or Structure Guided

**Structural-analogy from a Single Image Pair.**<br>
*Sagie Benaim, Ron Mokady, Amit Bermano, Daniel Cohen-Or, Lior Wolf.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.02222)]

**BachGAN: High-Resolution Image Synthesis from Salient Object Layout.**<br>
*[Yandong Li](https://cold-winter.github.io/), [Yu Cheng](https://sites.google.com/site/chengyu05/home), [Zhe Gan](https://www.cs.unc.edu/~licheng/), [Licheng Yu](https://www.cs.unc.edu/~licheng//), [Liqiang Wang](http://www.cs.ucf.edu/~lwang//), [Jingjing Liu](http://people.csail.mit.edu/jingl/).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.11690)] [[Github](https://github.com/Cold-Winter/BachGAN)]

**LayoutGAN: Generating Graphic Layouts with Wireframe Discriminator.**<br>
*Jianan Li, Jimei Yang, Aaron Hertzmann, Jianming Zhang, Tingfa Xu.*<br>
ICLR 2019. [[PDF](https://openreview.net/forum?id=HJxB5sRcFQ)]

**Text2Scene: Generating Compositional Scenes from Textual Descriptions.**<br>
*Fuwen Tan, Song Feng, Vicente Ordonez.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1809.01110)] [[Github](https://github.com/uvavision/Text2Image)]

**Image Generation from Layout.**<br>
*Bo Zhao, Lili Meng, Weidong Yin, Leonid Sigal.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1811.11389)]

**Generating Multiple Objects at Spatially Distinct Locations.**<br>
*Tobias Hinz, Stefan Heinrich, Stefan Wermter.*<br>
ICLR 2019. [[PDF](https://arxiv.org/abs/1901.00686)] [[Github](https://github.com/tohinz/multiple-objects-gan)]

**LostGANs: Image Synthesis From Reconfigurable Layout and Style.**<br>
*Wei Sun, Tianfu Wu.*<br>
ICCV 2019. [[PDF](https://www.arxiv-vanity.com/papers/1908.07500/)] [[Github](https://github.com/iVMCL/LostGANs)]

**Learning to Predict Layout-to-image Conditional Convolutions for Semantic Image Synthesis.**<br> 
*Xihui Liu, Guojun Yin, Jing Shao, Xiaogang Wang, Hongsheng Li.*</br>
NeurIPS 2019. [[PDF](https://arxiv.org/abs/1910.06809)]  

### Dialog Guided

**ChatPainter: Improving Text to Image Generation using Dialogue.**<br>
*Shikhar Sharma, Dendi Suhubdy, Vincent Michalski, Samira Ebrahimi Kahou, Yoshua Bengio.*<br>
ICLRW 2018. [[PDF](https://arxiv.org/abs/1802.08216)]

**Keep Drawing It: Iterative language-based image generation and editing.**<br>
*Alaaeldin El-Nouby, Shikhar Sharma, Hannes Schulz, Devon Hjelm, Layla El Asri, Samira Ebrahimi Kahou, Yoshua Bengio, Graham W.Taylor.*<br>
NIPSW 2018. [[PDF](https://arxiv.org/abs/1811.09845v1)] [[CLEVR dataset](https://github.com/facebookresearch/clevr-dataset-gen)]

**Tell, Draw, and Repeat: Generating and Modifying Images Based on Continual Linguistic Instruction.**<br>
*Alaaeldin El-Nouby, Shikhar Sharma, Hannes Schulz, Devon Hjelm, Layla El Asri, Samira Ebrahimi Kahou, Yoshua Bengio, Graham W.Taylor.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1811.09845)]

**Sequential Attention GAN for Interactive Image Editing via Dialogue.**<br>
*Yu Cheng, Zhe Gan, Yitong Li, Jingjing Liu, Jianfeng Gao.*<br>
arxiv, 2019. [[PDF](https://arxiv.org/abs/1812.08352)]

**Chat-crowd: A Dialog-based Platform for Visual Layout Composition.**<br>
*Paola Cascante-Bonilla, Xuwang Yin, Vicente Ordonez, Song Feng.*<br>
arxiv, 2018. [[PDF](https://arxiv.org/abs/1812.04081)] [[Github](https://github.com/uvavision/chat-crowd)]

**CoDraw: Collaborative Drawing as a Testbed for Grounded Goal-driven Communication.**<br>
*Jin-Hwa Kim, Nikita Kitaev, Xinlei Chen, Marcus Rohrbach, Byoung-Tak Zhang, Yuandong Tian, Dhruv Batra, Devi Parikh.*<br>
ACL 2019. [[PDF](https://arxiv.org/abs/1712.05558)] [[CoDraw Dataset](https://github.com/facebookresearch/CoDraw)]

### Audio Guided
**X2Face: A Network for Controlling Face Generation by Using Images, Audio and Pose Codes.**<br>
*Olivia Wiles, A. Sophia Koepke, Andrew Zisserman.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1807.10550)] [[Github](https://github.com/oawiles/X2Face)]

## Continous Change

**GANHopper: Multi-Hop GAN for Unsupervised Image-to-Image Translation.**<br>
*Wallace Lira, Johannes Merz, Daniel Ritchie, Daniel Cohen-Or, Hao Zhang.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2002.10102)]

**Homomorphic Latent Space Interpolation for Unpaired Image-To-Image Translation.**<br>
*[Ying-Cong Chen](https://yingcong.github.io/), Xiaogang Xu, Zhuotao Tian, Jiaya Jia.*<br>
CVPR 2019. [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/html/Chen_Homomorphic_Latent_Space_Interpolation_for_Unpaired_Image-To-Image_Translation_CVPR_2019_paper.html)] [[Github](https://github.com/yingcong/HomoInterpGAN)]

**GANimation: Anatomically-aware Facial Animation from a Single Image.**<br> 
*Albert Pumarola, Antonio Agudo, Aleix M. Martinez, Alberto Sanfeliu, Francesc Moreno-Noguer.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1807.09251)] [[Github](https://github.com/albertpumarola/GANimation)] 

## Video

**World-Consistent Video-to-Video Synthesis.**<br> 
*Arun Mallya, Ting-Chun Wang, Karan Sapra, Ming-Yu Liu.*<br> 
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.08509)] [[Github](https://nvlabs.github.io/wc-vid2vid/)]

**Line Art Correlation Matching Network for Automatic Animation Colorization.**<br>
*Zhang Qian, Wang Bo, Wen Wei, Li Hai, Liu Jun Hui.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.06718)]

**Unsupervised Multimodal Video-to-Video Translation via Self-Supervised Learning.**<br>
*Kangning Liu, Shuhang Gu, Andres Romero, Radu Timofte.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.06502)]

**Unsupervised Video-to-Video Translation via Self-Supervised Learning.**<br>
*Kangning Liu, Shuhang Gu, Radu Timofte.*<br>
2020. [[PDF](https://openreview.net/forum?id=HkevCyrFDS)]

**Video-to-Video Synthesis.**<br>
*Ting-Chun Wang, Ming-Yu Liu, Jun-Yan Zhu, Guilin Liu, Andrew Tao, Jan Kautz, Bryan Catanzaro.*<br>
NeurIPS 2018. [[PDF](https://arxiv.org/abs/1808.06601)] [[Github](https://github.com/NVIDIA/vid2vid)]   

**Everybody Dance Now.**<br>
*Caroline Chan, Shiry Ginosar, Tinghui Zhou, Alexei A. Efros.*<br>
ECCVW 2018. [[PDF](https://arxiv.org/abs/1808.07371)] [[Project](https://carolineec.github.io/everybody_dance_now/)]

**Preserving Semantic and Temporal Consistency for Unpaired Video-to-Video Translation.**<br>
*Kwanyong Park, Sanghyun Woo, Dahun Kim, Donghyeon Cho, In So Kweon.*<br>
ACM MM 2019. [[PDF](https://arxiv.org/abs/1908.07683)]

**Mocycle-GAN: Unpaired Video-to-Video Translation.**<br> 
*Yang Chen, Yingwei Pan, Ting Yao, Xinmei Tian, Tao Mei.*<br> 
ACM MM 2019. [[PDF](https://arxiv.org/abs/1908.09514)] 

**Recycle-GAN: Unsupervised Video Retargeting.**<br> 
*Aayush Bansal, Shugao Ma, Deva Ramanan, Yaser Sheikh.*<br> 
ECCV 2018. [[PDF](https://arxiv.org/abs/1808.05174)] [[Github](https://github.com/aayushbansal/Recycle-GAN)]

**Few-shot Video-to-Video Synthesis.**</br>
*Ting-Chun Wang, Ming-Yu Liu, Andrew Tao, Guilin Liu, Jan Kautz, Bryan Catanzaro.*<br> 
NeurIPS 2019. [[PDF](https://nvlabs.github.io/few-shot-vid2vid/main.pdf)] [[Project](https://nvlabs.github.io/few-shot-vid2vid/)] [[Github](https://github.com/NVlabs/few-shot-vid2vid)]

## Few-Shot

**Semi-supervised Learning for Few-shot Image-to-Image Translation.**<br>
*[Yaxing Wang](https://yaxingwang.github.io/), Salman Khan, Abel Gonzalez-Garcia, Joost van de Weijer, Fahad Shahbaz Khan.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.13853)] [[Github](https://github.com/yaxingwang/SEMIT)]

**FUNIT: Few-Shot Unsupervised Image-to-Image Translation.**</br> 
*[Ming-Yu Liu](http://mingyuliu.net/), Xun Huang, Arun Mallya, Tero Karras, Timo Aila, Jaakko Lehtinen, Jan Kautz.*<br> 
ICCV 2019. [[PDF](https://arxiv.org/abs/1905.01723)] [[Project](https://nvlabs.github.io/FUNIT/)] [[Github](https://github.com/nvlabs/FUNIT/)]

**Semi Few-Shot Attribute Translation.**</br> 
*Ricard Durall, Franz-Josef Pfreundt, Janis Keuper.*<br> 
arxiv 2019. [[PDF](https://arxiv.org/abs/1910.03240)] 

**ZstGAN: An Adversarial Approach for Unsupervised Zero-Shot Image-to-Image Translation.**</br> 
*Jianxin Lin, Yingce Xia, Sen Liu, Tao Qin, Zhibo Chen.*<br> 
arxiv 2019. [[PDF](https://arxiv.org/abs/1906.00184)] [[Github](https://github.com/linjx-ustc1106/ZstGAN-PyTorch)]

**MetaPix: Few-Shot Video Retargeting.**</br>
*Jessica Lee, Deva Ramanan, Rohit Girdhar.*<br> 
ICCV 2019. [[PDF](https://arxiv.org/abs/1910.04742)]] [[Project](https://motionretargeting2d.github.io)] [[Github](https://github.com/imjal/MetaPix)] 

**Few-shot Video-to-Video Synthesis.**</br>
*Ting-Chun Wang, Ming-Yu Liu, Andrew Tao, Guilin Liu, Jan Kautz, Bryan Catanzaro.*<br> 
arxiv 2019. [[PDF](https://nvlabs.github.io/few-shot-vid2vid/main.pdf)] [[Project](https://nvlabs.github.io/few-shot-vid2vid/)]

## Applications

### Photo Animation

**AutoToon: Automatic Geometric Warping for Face Cartoon Generation.**<br>
*Julia Gong, Yannick Hold-Geoffroy, Jingwan Lu.*<br>
WACV 2020. [[PDF](https://arxiv.org/abs/2004.02377)]

**Learning to Cartoonize Using White-box Cartoon Representations.**<br>
*Xinrui Wang, Jinze Yu.*<br>
CVPR 2020. [[PDF](https://github.com/SystemErrorWang/White-box-Cartoonization/blob/master/paper/06791.pdf)] [[Project](https://systemerrorwang.github.io/White-box-Cartoonization/)] [[Github](https://github.com/SystemErrorWang/White-box-Cartoonization)]

**AnimeGAN: A Novel Lightweight GAN For Photo Animation.**<br>
2020. [[Github](https://github.com/TachibanaYoshino/AnimeGAN)]
[[Dataset](https://github.com/TachibanaYoshino/AnimeGAN/releases/tag/dataset-1)]

**ComixGAN: Generative Adversarial Network For Transferring Images To Comics.**<br>
[[Github](https://github.com/nijuyr/comixGAN)]

**CartoonGAN: Generative Adversarial Networks for Photo Cartoonization.**<br>
*Yang Chen, Yu-Kun Lai, Yong-Jin Liu.*<br>
CVPR 2018. [[PDF](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_CartoonGAN_Generative_Adversarial_CVPR_2018_paper.pdf)] [[Pytorch](https://github.com/znxlwm/pytorch-CartoonGAN)] [[TensorFlow](https://github.com/taki0112/CartoonGAN-Tensorflow)]

### Image Restoration

**Slide-free MUSE Microscopy to H&E Histology Modality Conversion via Unpaired Image-to-Image Translation GAN Models.**<br>
*Tanishq Abraham, Andrew Shaw, Daniel O'Connor, Austin Todd, Richard Levenson.*<br>
ICMLW 2020. [[PDF](https://arxiv.org/abs/2008.08579)]

**Bringing Old Photos Back to Life.**<br>
*[Ziyu Wan](http://raywzy.com), Bo Zhang, [Dongdong Chen](http://www.dongdongchen.bid/), Pan Zhang, Dong Chen, Jing Liao, Fan Wen.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.09484)] [[Project](http://raywzy.com/Old_Photo/)]

**Reference-Based Sketch Image Colorization using Augmented-Self Reference and Dense Semantic Correspondence.**<br>
*Junsoo Lee, Eungyeup Kim, Yunsung Lee, Dongjun Kim, Jaehyuk Chang, Jaegul Choo.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2005.05207)]

**Pose Agnostic Cross-spectral Hallucination via Disentangling Independent Factors.**<br>
*Boyan Duan, Chaoyou Fu, Yi Li, Xingguang Song, Ran He.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1909.04365)]

**Learning Invariant Representation for Unsupervised Image Restoration.**<br>
*Wenchao Du, Hu Chen, Hongyu Yang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.12769)]

**Unsupervised Domain-Specific Deblurring via Disentangled Representations.**<br>
*Boyu Lu, Jun-Cheng Chen, Rama Chellappa.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1903.01594)] [[Github](https://github.com/ustclby/Unsupervised-Domain-Specific-Deblurring/)]

### Image Synthesis

**SEAN: Image Synthesis with Semantic Region-Adaptive Normalization.**</br>
*Peihao Zhu, Rameen Abdal, Yipeng Qin, Peter Wonka.*<br> 
CVPR 2020. [[PDF](https://arxiv.org/abs/1911.12861)] [[Video](https://youtu.be/0Vbj9xFgoUw)] [[Github](https://github.com/ZPdesu/SEAN)]

**Face-to-Parameter Translation for Game Character Auto-Creation.**</br> 
*Tianyang Shi, Yi Yuan, Changjie Fan, Zhengxia Zou, Zhenwei Shi, Yong Liu.*<br>
ICCV 2019. [[PDF](https://arxiv.org/pdf/1909.01064.pdf)]    

**APDrawingGAN: Face-to-Parameter Translation for Game Character Auto-Creation.**</br>
*Ran Yi, Yong-Jin Liu, Yu-Kun Lai, Paul L. Rosin.*<br>
CVPR 2019. [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/papers/Yi_APDrawingGAN_Generating_Artistic_Portrait_Drawings_From_Face_Photos_With_Hierarchical_CVPR_2019_paper.pdf)] [[Github](https://github.com/yiranran/APDrawingGAN)] [[Online Demo](https://face.lol)]

**Cascaded Generation of High-quality Color Visible Face Images from Thermal Captures.**</br> 
*Naser Damer, Fadi Boutros, Khawla Mallat, Florian Kirchbuchner, Jean-Luc Dugelay, Arjan Kuijper.*<br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1910.09524)] 

**CartoonGAN: Generative Adversarial Networks for Photo Cartoonization.**</br>
*Yang Chen, Yu-Kun Lai, Yong-Jin Liu.*<br>
CVPR 2018. [[PDF](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_CartoonGAN_Generative_Adversarial_CVPR_2018_paper.pdf)] [[Github](https://github.com/FlyingGoblin/CartoonGAN)] [[unofficial test](https://github.com/Yijunmaverick/CartoonGAN-Test-Pytorch-Torch)] [[unofficial pytorch](https://github.com/znxlwm/pytorch-CartoonGAN)]

### Retargeting and 3D Vision

**Render4Completion: Synthesizing Multi-View Depth Maps for 3D Shape Completion.**</br>
*Tao Hu, Zhizhong Han, Abhinav Shrivastava, Matthias Zwicker.*</br>
ICCV 2019 workshop on Geometry meets Deep Learning. [[PDF](https://arxiv.org/abs/1904.08366)]

**Multi-Garment Net_Learning to Dress 3D people from Images.**</br>
*Bharat Lal Bhatnagar, Garvita Tiwari, Christian Theobalt, Gerard Pons-Moll.*<br>
ICCV 2019. [[PDF](https://virtualhumans.mpi-inf.mpg.de/papers/bhatnagar2019mgn/bhatnagar2019mgn.pdf)] [[Github](https://github.com/bharat-b7/MultiGarmentNetwork)]

**Tex2Shape: Detailed Full Human Body Geometry From a Single Image.**</br>
*Thiemo Alldieck, Gerard Pons-Moll, Christian Theobalt, Marcus Magnor.*</br>
ICCV 2019. [[arxiv](https://arxiv.org/abs/1904.08645)] [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/html/Alldieck_Tex2Shape_Detailed_Full_Human_Body_Geometry_From_a_Single_Image_ICCV_2019_paper.html)] [[Github](https://github.com/thmoa/tex2shape)]

**pix2vertex: Unrestricted facial geometry reconstruction using image-to-image translation.**</br>
*Matan Sela, Elad Richardson, Ron Kimmel.*</br>
arxiv, 2017. [[PDF](https://arxiv.org/abs/1703.10131)] [[Github](https://github.com/matansel/pix2vertex)]

**Learning to Reconstruct People in Clothing from a Single RGB Camera.**</br>
*Thiemo Alldieck, Marcus Magnor, Bharat Lal Bhatnagar, Christian Theobalt, Gerard Pons-Moll.*</br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1903.05885)][[Github](https://github.com/thmoa/octopus)]

**360-Degree Textures of People in Clothing from a Single Image.**</br>
*Verica Lazova, Eldar Insafutdinov, Gerard Pons-Moll.*</br>
3DV 2019. [[PDF](https://arxiv.org/pdf/1908.07117.pdf)][[Project](http://virtualhumans.mpi-inf.mpg.de/360tex/)] 

**SelectionGAN: Multi-Channel Attention Selection GAN with Cascaded Semantic Guidance for Cross-View Image Translation.**<br>
*Hao Tang, Dan Xu, Nicu Sebe, Yanzhi Wang, Jason J. Corso, Yan Yan.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1904.06807)] [[Github](https://github.com/Ha0Tang/SelectionGAN)]

**Multi-Channel Attention Selection GANs for Guided Image-to-Image Translation.**<br>
*Hao Tang, Dan Xu, Yan Yan, Jason J. Corso, Philip H.S. Torr, Nicu Sebe.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2002.01048)]

**VR Facial Animation via Multiview Image Translation.**<br>
*Shih-En Wei, Jason Saragih, Tomas Simon, Adam W. Harley, Stephen Lombardi, Michal Perdoch, Alexander Hypes, Dawei Wang, Hernan Badino, Yaser Sheikh.*<br>
SIGGRAPH 2019. [[PDF](https://research.fb.com/publications/vr-facial-animation-via-multiview-image-translation/)]

### Attribute Editing

**Lifespan Age Transformation Synthesis.**<br>
*[Roy Or-El](https://homes.cs.washington.edu/~royorel/), [Soumyadip Sengupta](https://homes.cs.washington.edu/~soumya91/), [Ohad Fried](https://www.ohadf.com/), [Eli Shechtman](https://research.adobe.com/person/eli-shechtman/), [Ira Kemelmacher-Shlizerman](https://homes.cs.washington.edu/~kemelmi/).*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2003.09764)] [[Github](https://github.com/royorel/Lifespan_Age_Transformation_Synthesis)] [[Project](https://grail.cs.washington.edu/projects/lifespan_age_transformation_synthesis/)] [[FFHQ-Aging-Dataset](https://github.com/royorel/FFHQ-Aging-Dataset)]

**LEED: Label-Free Expression Editing via Disentanglement.**<br>
*Rongliang Wu, Shijian Lu.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.08971)]

**PA-GAN: Progressive Attention Generative Adversarial Network for Facial Attribute Editing.**<br>
*Zhenliang He, Meina Kan, Jichao Zhang, Shiguang Shan.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.05892)] [[Github](https://github.com/LynnHo/PA-GAN-Tensorflow)]

**Facial Expression Editing with Continuous Emotion Labels.**<br>
*Alexandra Lindt, Pablo Barros, Henrique Siqueira, Stefan Wermter.*<br>
FG 2019. [[PDF](https://arxiv.org/abs/2006.12210)]

**Disentangled and Controllable Face Image Generation via 3D Imitative-Contrastive Learning.**<br>
*Yu Deng, Jiaolong Yang, Dong Chen, Fang Wen, Xin Tong.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.11660)]

**High Resolution Face Age Editing.**<br>
*Xu Yao, Gilles Puy, Alasdair Newson, Yann Gousseau, Pierre Hellier.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2005.04410)] [[Github](https://github.com/InterDigitalInc/HRFAE)]

**Intuitive, Interactive Beard and Hair Synthesis with Generative Models.**<br>
*Kyle Olszewski, Duygu Ceylan, Jun Xing, Jose Echevarria, Zhili Chen, Weikai Chen, Hao Li.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.06848)]

**Lifespan Age Transformation Synthesis.**<br>
*Roy Or-El, Soumyadip Sengupta, Ohad Fried, Eli Shechtman, Ira Kemelmacher-Shlizerman.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2003.09764)]

**IcGAN: Invertible Conditional GANs for image editing.**<br>
*Guim Perarnau, Joost van de Weijer, Bogdan Raducanu, Jose M. Álvarez.*<br>
NeurIPS Workshop 2016. [[PDF](https://arxiv.org/abs/1611.06355)] [[Github](https://github.com/Guim3/IcGAN)]

**Smart, Sparse Contours to Represent and Edit Images.**</br>
*Tali Dekel, Chuang Gan, Dilip Krishnan, Ce Liu, William T. Freeman.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1712.08232)] [[[Project](https://contour2im.github.io/)] 

**AGUIT: Attribute Guided Unpaired Image-to-Image Translation with Semi-supervised Learning.**<br>
*Xinyang Li, Jie Hu, Shengchuan Zhang, Xiaopeng Hong, Qixiang Ye, Chenglin Wu, Rongrong Ji.*<br>
arxiv, 29 Apr 2019. [[PDF](https://arxiv.org/abs/1904.12428)] [[Github](https://github.com/imlixinyang/AGUIT)]

**BeautyGAN: Instance-level Facial Makeup Transfer with Deep Generative Adversarial Network.**<br>
*Tingting Li, Ruihe Qian, Chao Dong,  Si Liu, Qiong Yan, Wenwu Zhu,  Liang Lin*<br> 
ACM MM 2018. [[PDF](https://liusi-group.com/pdf/BeautyGAN-camera-ready.pdf)] [[Github](github.com/Honlan/BeautyGAN)] [[Project](http://liusi-group.com/projects/BeautyGAN)]

**UFDN: A Unified Feature Disentangler for Multi-Domain Image Translation and Manipulation.**<br> 
*Alexander H. Liu, Yen-Cheng Liu, Yu-Ying Yeh, Yu-Chiang Frank Wang.*<br> 
NeurIPS 2018. [[PDF](https://arxiv.org/abs/1809.01361)] [[Github](https://github.com/Alexander-H-Liu/UFDN)]

**ELEGANT: Exchanging Latent Encodings with GAN for Transferring Multiple Face Attributes.**</br>
*Taihong Xiao, Jiapeng Hong, Jinwen Ma.*<br> 
ECCV 2018. [[PDF](https://arxiv.org/abs/1803.10562)] [[Github](https://github.com/Prinsphield/ELEGANT)] 

**Biphasic-GAN: Biphasic Learning of GANs for High-Resolution Image-to-Image Translation.**</br>
*Jie Cao, Huaibo Huang, Yi Li, Jingtuo Liu, Ran He, Zhenan Sun.*<br> 
ArXiv 2019. [[PDF](https://arxiv.org/abs/1904.06624)]              

**High Fidelity Face Manipulation with Extreme Pose and Expression.**<br> 
*Chaoyou Fu, Yibo Hu, Xiang Wu, Guoli Wang, Qian Zhang, Ran He.*<br> 
ArXiv 2019. [[PDF](https://arxiv.org/abs/1903.12003)] 

**Make a Face: Towards Arbitrary High Fidelity Face Manipulation.**</br>
*Shengju Qian, Kwan-Yee Lin, Wayne Wu, Yangxiaokang Liu, Quan Wang, Fumin Shen, Chen Qian, Ran He.*<br> 
ICCV 2019. [[PDF](https://arxiv.org/abs/1908.07191)]

**SliderGAN: Synthesizing Expressive Face Images by Sliding 3D Blendshape Parameters.**<br>
*Evangelos Ververas, Stefanos Zafeiriou.*<br> 
arxiv 2019. [[PDF](https://arxiv.org/abs/1908.08847)] 

**Generating High-Resolution Fashion Model Images Wearing Custom Outfits.**<br> 
*Gökhan Yildirim, Nikolay Jetchev, Roland Vollgraf, Urs Bergmann.*<br> 
Workshop on Computer Vision for Fashion, Art and Design, ICCV 2019. [[PDF](https://arxiv.org/abs/1908.09638)] 

### Data Augmentation

**Generative Image Translation for Data Augmentation in Colorectal Histopathology Images.**</br>
NeurIPS 2019 Machine Learning for Health Workshop. [[PDF](https://arxiv.org/abs/1910.05827)] [[Project](https://github.com/BMIRDS/HistoGAN)]

**DG-Net: Joint Discriminative and Generative Learning for Person Re-identification.**</br>
*Zhedong Zheng, Xiaodong Yang, Zhiding Yu, Liang Zheng, Yi Yang, Jan Kautz.*</br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1904.07223)] [[Github](https://github.com/NVlabs/DG-Net)]

**Compressed Sensing using Generative Models.**</br>
*Ashish Bora, Ajil Jalal, Eric Price, Alexandros G. Dimakis.*</br>
arxiv 2017. [[PDF](https://arxiv.org/abs/1703.03208)] [[Github](https://github.com/AshishBora/csgm)]

**Person Transfer GAN to Bridge Domain Gap for Person Re-Identification.**</br>
*Longhui Wei, Shiliang Zhang, Wen Gao, Qi Tian.*</br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1711.08565)]

**Image-Image Domain Adaptation with Preserved Self-Similarity and Domain-Dissimilarity for Person Re-identification.**</br>
*Weijian Deng, Liang Zheng, Qixiang Ye, Guoliang Kang, Yi Yang, Jianbin Jiao.*</br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1711.07027)]

### Model-Compression-and-Pruning

**GAN Compression: Efficient Architectures for Interactive Conditional GANs.**<br>
*[Muyang Li](https://lmxyy.me/), Ji Lin, Yaoyao Ding, Zhijian Liu, Jun-Yan Zhu, and [Song Han](https://songhan.mit.edu/).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.08936)] [[Demo](https://tinyurl.com/r474uca)] [[Github](https://github.com/mit-han-lab/gan-compression/)]

**Co-Evolutionary Compression for Unpaired Image Translation.**</br>
*Han Shu, Yunhe Wang, Xu Jia, Kai Han, Hanting Chen, Chunjing Xu, Qi Tian, Chang Xu.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1907.10804)] [[Github](https://github.com/huawei-noah/GAN-pruning)] 

### Adversarial-Examples

**Disrupting DeepFakes: Adversarial Attacks Against Conditional Image Translation Networks and Facial Manipulation Systems.**<br>
*Nataniel Ruiz, Stan Sclaroff.*<br>
arxiv, 3 Mar 2020. [[PDF](https://arxiv.org/abs/2003.01279)]

**Adversarial Self-Defense for Cycle-Consistent GANs.**</br>
*Dina Bashkirova, Ben Usman, Kate Saenko.*<br>
NeurIPS 2019. [[PDF](https://arxiv.org/abs/1908.01517v1)]]

### Imbalanced Data

**Elastic-InfoGAN: Unsupervised Disentangled Representation Learning in Imbalanced Data.**</br>
*Utkarsh Ojha, Krishna Kumar Singh, Cho-Jui Hsieh, Yong Jae Lee.*<br>
arxiv, 1 Oct 2019. [[PDF](https://arxiv.org/abs/1910.01112)]   

## Datasets
Please cite their papers if you use the data.
### pix2pix Datasets
Some datasets can also be downloaded manually from the website or **automatically** using the following script:
```python
python download-dataset.py datasetname
```
- `facades`: 400 images from [CMP Facades dataset](http://cmp.felk.cvut.cz/~tylecr1/facade/). (31MB) 
- `sketch`: http://mmlab.ie.cuhk.edu.hk/archive/cufsf/
- `oil-chinese`: http://www.cs.mun.ca/~yz7241/dataset/
- `day-night`: http://www.cs.mun.ca/~yz7241/dataset/
- `facades`: 400 images from [CMP Facades dataset](http://cmp.felk.cvut.cz/~tylecr1/facade). [[Citation](datasets/bibtex/facades.tex)]
- `cityscapes`: 2975 images from the [Cityscapes training set](https://www.cityscapes-dataset.com). [[Citation](datasets/bibtex/cityscapes.tex)]
- `maps`: 1096 training images scraped from Google Maps
- `edges2shoes`: 50k training images from [UT Zappos50K dataset](http://vision.cs.utexas.edu/projects/finegrained/utzap50k). Edges are computed by [HED](https://github.com/s9xie/hed) edge detector + post-processing. [[Citation](datasets/bibtex/shoes.tex)]
- `edges2handbags`: 137K Amazon Handbag images from [iGAN project](https://github.com/junyanz/iGAN). Edges are computed by [HED](https://github.com/s9xie/hed) edge detector + post-processing. [[Citation](datasets/bibtex/handbags.tex)]


### CycleGAN Datasets
- `facades`: 400 images from the [CMP Facades dataset](http://cmp.felk.cvut.cz/~tylecr1/facade). [[Citation](datasets/bibtex/facades.tex)]
- `cityscapes`: 2975 images from the [Cityscapes training set](https://www.cityscapes-dataset.com). [[Citation](datasets/bibtex/cityscapes.tex)]
- `maps`: 1096 training images scraped from Google Maps.
- `horse2zebra`: 939 horse images and 1177 zebra images downloaded from [ImageNet](http://www.image-net.org) using keywords `wild horse` and `zebra`
- `apple2orange`: 996 apple images and 1020 orange images downloaded from [ImageNet](http://www.image-net.org) using keywords `apple` and `navel orange`.
- `summer2winter_yosemite`: 1273 summer Yosemite images and 854 winter Yosemite images were downloaded using Flickr API. See more details in our paper.
- `monet2photo`, `vangogh2photo`, `ukiyoe2photo`, `cezanne2photo`: The art images were downloaded from [Wikiart](https://www.wikiart.org/). The real photos are downloaded from Flickr using the combination of the tags *landscape* and *landscapephotography*. The training set size of each class is Monet:1074, Cezanne:584, Van Gogh:401, Ukiyo-e:1433, Photographs:6853.
- `iphone2dslr_flower`: both classes of images were downlaoded from Flickr. The training set size of each class is iPhone:1813, DSLR:3316.
- `KaoKore Dataset`: KaoKore is a novel dataset of face images from Japanese illustrations along with multiple labels for each face, derived from [the Collection of Facial Expressions](http://codh.rois.ac.jp/face/). [KaoKore dataset](https://github.com/rois-codh/kaokore) contains 5552 image files, each being an color (RGB) image of size 256 x 256 as well as two sets of labels gender and social status.
- `Ford Autonomous Vehicle Seasonal Dataset`: It is a challenging multi-agent seasonal dataset collected by a fleet of Ford autonomous vehicles at different days and times during 2017-18. The vehicles traversed an average route of 66 km in Michigan that included a mix of driving scenarios such as the Detroit Airport, freeways, city-centers, university campus and suburban neighbourhoods, etc. Each vehicle used in this data collection is a Ford Fusion outfitted with an Applanix POS-LV GNSS system, four HDL-32E Velodyne 3D-lidar scanners, 6 Point Grey 1.3 MP Cameras arranged on the rooftop for 360-degree coverage and 1 Pointgrey 5 MP camera mounted behind the windshield for the forward field of view. They present the seasonal variation in weather, lighting, construction and traffic conditions experienced in dynamic urban environments. To get more details about the Ford AV Dataset, please refer to the [paper](https://arxiv.org/abs/2003.07969), [github](https://github.com/Ford/AVData) or visit [the website](https://avdata.ford.com/).

### Attribute Editing
- `CelebA`. The CelebFaces Attributes (CelebA) dataset contains 202,599 face images of celebrities, each annotated with 40 binary attributes. size 178×218. hair color (black, blond, brown),gender (male/female), and age (young/old). [[Onedrive](mmlab.ie.cuhk.edu.hk/projects/CelebA.html)] [[BaiduYun](https://link.zhihu.com/?target=https%3A//pan.baidu.com/s/1eSNpdRG%23list/path%3D%252F)]
- `CelebA-HQ`. [[Homepage](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)]. There is also a Modified [h5tool.py](https://github.com/willylulu/celeba-hq-modified) to make user getting celeba-HQ easier.
- `CelebAMask-HQ`. It is a large-scale face image dataset that has 30,000 high-resolution face images selected from the CelebA dataset by following CelebA-HQ. Each image has segmentation mask of facial attributes corresponding to CelebA. The masks of CelebAMask-HQ were manually-annotated with the size of 512×512 and 19 classes including all facial components and acessories such as skin, nose, eyes, eyebrows, ears, mouth, lip, hair, hat, eyeglass, earring, necklace, neck, and cloth. The dataset can be downloaded [[here](https://github.com/switchablenorms/CelebAMask-HQ)].
- `RaFD`. The Radboud Faces Database ([RaFD](http://www.socsci.ru.nl:8180/RaFD2/RaFD?p=main)) consists of 4,824 images collected from 67 participants. Each participant makes eight facial expressions in three different gaze directions, which are captured from three different angles.
- `AFHQ`.  Released in StarGAN v2. Animal FacesHQ (AFHQ) consists of 15,000 high-quality images at 512 × 512 resolution. We collected images with
permissive licenses from the [Flickr](https://www.flickr.com/) and [Pixabay](https://pixabay.com/) websites. All images are vertically and horizontally aligned to have the eyes at the center. The low-quality images were discarded by human effort. You can downloaded using the provided [scripts](https://github.com/clovaai/stargan-v2/blob/master/download.sh). For more details, see the [Project](https://github.com/clovaai/stargan-v2) or [Paper](https://arxiv.org/abs/1912.01865).
- `CMU Multi-PIE Face Database`. [[Multi-PIE](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2873597/)] A large (305GB) database of images for training facial recognition software. It consists 13 poses within ±90 degrees of 337 subjects and can be used for face frontalization experiments.
- `APDrawing Dataset`. [[APDrawingDB](https://cg.cs.tsinghua.edu.cn/people/~Yongjin/APDrawingDB.zip)], [[Project](https://github.com/yiranran/APDrawingGAN)].
### Others
- `Makeup Transfer`. [[Download](http://liusi-group.com/projects/BeautyGAN)]
- `DeepFashion`. In-shop Clothes Retrieval Benchmark evaluates the performance of in-shop Clothes Retrieval. This is a large subset of DeepFashion, containing large pose and scale variations. It also has large diversities, large quantities, and rich annotations, including 7,982 number of clothing items, 52,712 number of in-shop clothes images, and ~200,000 cross-pose/scale pairs, Each image is annotated by bounding box, clothing type and pose type. [Download](http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion/InShopRetrieval.html)
- `AI-Generated Faces`: Free Resource of 100K Faces Without Copyright. [[Download](http://t.cn/AiEky6r3)]
- `All-Age-Faces (AAF) Database` - contains 13'322 face images (mostly Asian) distributed across all ages (from 2 to 80), including 7381 females and 5941 males. [GitHub](http://t.cn/AinOjWhK) [Paper](http://t.cn/AinOjWhY)
- `Celeb-DF`. A New Dataset for DeepFake Forensics. [[Download](http://t.cn/AimcYeUI)]
- `The Deepfake Detection Challenge (DFDC) Preview Dataset`. Facebook AI. [[PDF](https://arxiv.org/abs/1910.08854)] [[Project](http://t.cn/AiEaiHKX)].
- `Faceforensics++`. Learning to detect manipulated facial images, 2019.
- `AI Generated Diverse Photos`. [[Project](https://www.generative.photos/?ref=producthunt)]
- `t-less`. An RGB-D- Dataset for6 D Pose Estimation of Texture-less Objects.

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
