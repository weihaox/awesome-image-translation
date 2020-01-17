# Awesome Image-to-image Translation Paper [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of resources on Image Translation.

## Contributing

If you think I have missed out on something (or) have any suggestions (papers, implementations and other resources), feel free to [pull a request](https://github.com/xiaweihao/awesome-image-translation/pulls)

Feedback and contributions are welcome!

## Table of Contents
- [Tutorials](#tutorials)
- [Supervised](#supervised)
- [Unsupervised](#unsupervised)
  * [General](#general)
  * [Attention-Examplar-Guided](#attention-examplar-guided)
  * [Disentanglement](#disentanglement)
  * [Many-to-many](#many-to-many)
- [Applications](#applications)
  * [Attribute-Editing](#attribute-editing)
  * [Video](#video)
  * [Data Augmentation](#data-augmentation)
  * [Model-Compression-and-Pruning](#model-compression-and-pruning)
  * [Adversarial-Examples](#adversarial-examples)
  * [Imbalanced Data](#imbalanced-data)
  * [Few-Shot](#few-shot)
  * [Image-Synthesis](#image-synthesis)
  * [Retargeting-and-3D-Vision](#retargeting-and-3d-vision)
- [Chronological Order](#conference)
- [Datasets](#datasets)

## Tutorials

[Unpaired Image-to-Image Translation.](http://efrosgans.eecs.berkeley.edu/CVPR18_slides/CycleGAN.pptx) CVPR Tutorial on GANs (2018)

[On Image-to-Image Translation.](https://people.csail.mit.edu/junyanz/talks/image_translation.pptx) Stanford, MIT, Facebook, CUHK, SNU (2017)

## Supervised

**pix2pix: Image-to-Image Translation with Conditional Adversarial Networks.** <br>
*[Phillip Isola](http://web.mit.edu/phillipi/), [Jun-Yan Zhu](http://people.csail.mit.edu/junyanz/), [Tinghui Zhou](https://people.eecs.berkeley.edu/~tinghuiz/), [Alexei A. Efros](https://people.eecs.berkeley.edu/~efros/).*<br>
CVPR 2017. [[PDF](https://arxiv.org/abs/1611.07004)] [[Github](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)]

**BicycleGAN: Toward Multimodal Image-to-Image Translation.**<br>
*Jun-Yan Zhu, Richard Zhang, Deepak Pathak, Trevor Darrell, Alexei A. Efros, Oliver Wang, Eli Shechtman.*<br>
NeurIPS 2017. [[PDF](https://arxiv.org/abs/1711.11586)] [[Github](https://github.com/junyanz/BicycleGAN)]

**High-Resolution Image Synthesis and Semantic Manipulation with Conditional GANs.**<br>
*Ting-Chun Wang, Ming-Yu Liu, Jun-Yan Zhu, Andrew Tao, Jan Kautz, Bryan Catanzaro.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1711.11585)] [[Github](https://github.com/NVIDIA/pix2pixHD)]

**Geometry Guided Adversarial Facial Expression Synthesis.**<br>
*Lingxiao Song, Zhihe Lu, Ran He, Zhenan Sun, Tieniu Tan.*<br>
MM 2018. [[PDF](https://arxiv.org/abs/1712.03474)]  

**TextureGAN: Controlling Deep Image Synthesis with Texture Patches.**<br>
*Wenqi Xian, Patsorn Sangkloy, Varun Agrawal, Amit Raj, Jingwan Lu, Chen Fang, Fisher Yu, James Hays.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1706.02823)] [[Github](https://github.com/janesjanes/Pytorch-TextureGAN)]

**Smart, Sparse Contours to Represent and Edit Images.** <br>
*Tali Dekel, Chuang Gan, Dilip Krishnan, Ce Liu, William T. Freeman.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1712.08232)] [[[Project](https://contour2im.github.io/)] 

**Image-to-image translation for cross-domain disentanglement.**<br>
*Abel Gonzalez-Garcia, Joost van de Weijer, Yoshua Bengio.*<br>
NeurIPS 2018. [[PDF](https://arxiv.org/abs/1805.09730)]

**MSGAN: Mode Seeking Generative Adversarial Networks for Diverse Image Synthesis.**<br>
*Qi Mao, Hsin-Ying Lee, Hung-Yu Tseng, Siwei Ma, Ming-Hsuan Yang.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1903.05628)] [[Github](https://github.com/HelenMao/MSGAN)]

**SPADE: Semantic Image Synthesis with Spatially-Adaptive Normalization.** <br>
*Taesung Park, Ming-Yu Liu, Ting-Chun Wang, Jun-Yan Zhu.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1903.07291)] [[Github](https://github.com/NVlabs/SPADE)]

**C2-GAN: Cycle In Cycle Generative Adversarial Networks for Keypoint-Guided Image Generation.** <br>
*Hao Tang, Dan Xu, Gaowen Liu, Wei Wang, Nicu Sebe, Yan Yan.*<br>
MM 2019. [[PDF](https://arxiv.org/abs/1908.00999)]

**PI-REC: Progressive Image Reconstruction Network With Edge and Color Domain.** <br>
*Sheng You, Ning You, Minxue Pan.*<br>
arxiv, 25 Mar 2019. [[PDF](https://arxiv.org/abs/1903.10146)] [[Github](https://github.com/youyuge34/PI-REC)]

## Unsupervised

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

**Art2Real: Unfolding the Reality of Artworks via Semantically-Aware Image-to-Image Translation.**<br>
*Matteo Tomei, Marcella Cornia, Lorenzo Baraldi, Rita Cucchiara.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1811.10666)] [[Github](https://github.com/aimagelab/art2real)]

**HarmonicGAN: Harmonic Unpaired Image-to-image Translation.**<br>
*Rui Zhang, Tomas Pfister, Jia Li.*<br>
ICLR 2019. [[PDF](https://arxiv.org/abs/1902.09727)]

**SDIT: Scalable and Diverse Cross-domain Image Translation.**<br> 
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

**AGUIT: Attribute Guided Unpaired Image-to-Image Translation with Semi-supervised Learning.**<br> 
*Xinyang Li, Jie Hu, Shengchuan Zhang, Xiaopeng Hong, Qixiang Ye, Chenglin Wu, Rongrong Ji.*<br>
arxiv, 29 Apr 2019. [[PDF](https://arxiv.org/abs/1904.12428)] [[Github](https://github.com/imlixinyang/AGUIT)]

### Attention-Examplar-Guided

**ContrastGAN: Generative Semantic Manipulation with Mask-Contrasting GAN.**<br>
*Xiaodan Liang, Hao Zhang, Eric P. Xing.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1708.00315)]

**DA-GAN: Instance-level Image Translation by Deep Attention Generative Adversarial Networks.**<br>
*Shuang Ma, Jianlong Fu, Chang Wen Chen, Tao Mei.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1802.06454)] 

**Attention-GAN for Object Transfiguration in Wild Images.**<br>
*Xinyuan Chen, Chang Xu, Xiaokang Yang, Dacheng Tao.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1803.06798)]

**Unsupervised Attention-guided Image to Image Translation.**<br>
*Youssef A. Mejjati, Christian Richardt, James Tompkin, Darren Cosker, Kwang In Kim.*<br>
NeurIPS 2018. [[PDF](https://arxiv.org/abs/1806.02311)] [[Github](https://github.com/AlamiMejjati/Unsupervised-Attention-guided-Image-to-Image-Translation)]

**Show, Attend and Translate: Unsupervised Image Translation with Self-Regularization and Attention.**<br>
*Chao Yang, Taehwan Kim, Ruizhe Wang, Hao Peng, C.-C. Jay Kuo.*</br>
TIP 2019. [[PDF](https://arxiv.org/abs/1806.06195)]

**InstaGAN: Instance-aware image-to-image translation.**<br>
*Zhiqiang Shen, Mingyang Huang, Jianping Shi, Xiangyang Xue, Thomas Huang.*<br>
ICLR 2019. [[PDF](https://openreview.net/pdf?id=ryxwJhC9YX)] [[Github](https://github.com/sangwoomo/instagan)] 

**INIT: Towards Instance-level Image-to-Image Translation.**<br>
*Zhiqiang Shen, Mingyang Huang, Jianping Shi, Xiangyang Xue, Thomas Huang.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1905.01744)] [[project](http://zhiqiangshen.com/projects/INIT/index.html)] 

**Mask-Guided Portrait Editing with Conditional GANs.**<br>
*Shuyang Gu, Jianmin Bao, Hao Yang, Dong Chen, Fang Wen, Lu Yuan.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1905.10346)] [[Github](https://github.com/cientgu/Mask_Guided_Portrait_Editing)]

**U-GAT-IT: Unsupervised Generative Attentional Networks with Adaptive Layer-Instance Normalization for Image-to-Image Translation.**<br>
*Junho Kim, Minjae Kim, Hyeonwoo Kang, Kwanghee Lee.*<br>
[[PDF](https://arxiv.org/abs/1907.10830)] [[TensorFlow](https://github.com/taki0112/UGATIT) or [Pytorch](https://github.com/znxlwm/UGATIT-pytorch)]

**SPA-GAN: Spatial Attention GAN for Image-to-Image Translation.**<br>
*Hajar Emami, Majid Moradi Aliabadi, Ming Dong, Ratna Babu Chinnam.*<br>
ArXiv 2019. [[PDF](https://arxiv.org/abs/1908.06616)] 

**Guided Image-to-Image Translation with Bi-Directional Feature Transformation.**<br>
*Badour AlBahar, Jia-Bin Huang.*<br>
ArXiv 2019. [[PDF](https://arxiv.org/abs/1910.11328)] [[Github](http://t.cn/Ai1beVDp)] 

**Stylizing Video by Example.**<br> 
*Ondřej Jamriška, Šárka Sochorová, Ondřej Texler, Michal Lukáč, Jakub Fišer, Jingwan Lu, Eli Shechtman, Daniel Sýkora.*<br>
SIGGRAPH 2019. [[PDF](https://dcgi.fel.cvut.cz/home/sykorad/Jamriska19-SIG.pdf)]

### Disentanglement

**XGAN: Unsupervised Image-to-Image Translation for Many-to-Many Mappings.**<br>
*Amélie Royer, Konstantinos Bousmalis, Stephan Gouws, Fred Bertsch, Inbar Mosseri, Forrester Cole, Kevin Murphy.*<br>
ICML 2018. [[PDF](https://arxiv.org/abs/1711.05139)] [[Dataset](https://google.github.io/cartoonset/)]

**ELEGANT: Exchanging Latent Encodings with GAN for Transferring Multiple Face Attributes.**<br>
*Taihong Xiao, Jiapeng Hong, Jinwen Ma.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1803.10562)] [[Github](https://github.com/Prinsphield/ELEGANT)] 

**MUNIT: Multimodal Unsupervised Image-to-Image Translation.**<br>
*Xun Huang, Ming-Yu Liu, Serge Belongie, Jan Kautz.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1804.04732)] [[Github](https://github.com/NVlabs/MUNIT)]      

**Conditional Image-to-Image Translation.** <br> 
*Jianxin Lin, Yingce Xia, Tao Qin, Zhibo Chen, Tie-Yan Liu.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1805.00251)]     

**EGSC-IT: Exemplar Guided Unsupervised Image-to-Image Translation with Semantic Consistency.** <br> 
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

**GDWTC: Image-to-Image Translation via Group-wise Deep Whitening and Coloring Transformation.** <br> 
*Wonwoong Cho, Sungha Choi, David Keetae Park, Inkyu Shin, Jaegul Choo.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1812.09912)]    

**DRIT++: Diverse Image-to-Image Translation via Disentangled Representations.**<br> 
*Hsin-Ying Lee, Hung-Yu Tseng, Qi Mao, Jia-Bin Huang, Yu-Ding Lu, Maneesh Singh, Ming-Hsuan Yang.*<br>
IJCV 2019. [[PDF](https://arxiv.org/abs/1905.01270)] [[[Project](http://vllab.ucmerced.edu/hylee/DRIT_pp/)] [[Github](https://github.com/HsinYingLee/MDMM)]

**Multi-mapping Image-to-Image Translation via Learning Disentanglement.** <br>
*Xiaoming Yu, Yuanqi Chen, Thomas Li, Shan Liu, Ge Li.*<br>
NeurIPS 2019. [[PDF](https://arxiv.org/abs/1909.07877)] [[Github](https://github.com/Xiaoming-Yu/DMIT)]               

**Flow-based Image-to-Image Translation with Feature Disentanglement.** <br> 
*Ruho Kondo, Keisuke Kawano, Satoshi Koide, Takuro Kutsuna.*<br>
NeurIPS 2019. [[PDF](http://papers.nips.cc/paper/8670-flow-based-image-to-image-translation-with-feature-disentanglement.pdf)]

### Many-to-many

**StarGAN v2: Diverse Image Synthesis for Multiple Domains.**<br> 
*Yunjey Choi, Youngjung Uh, Jaejun Yoo, Jung-Woo Ha. Clova AI Research, NAVER Corp.*<br> 
arxiv, 4 Dec 2019. [[PDF](https://arxiv.org/abs/1912.01865)] [[GitHub](http://t.cn/AieqHhyy)]

**IcGAN: Invertible Conditional GANs for image editing.**<br>
*Guim Perarnau, Joost van de Weijer, Bogdan Raducanu, Jose M. Álvarez.*<br>
NeurIPS Workshop 2016. [[PDF](https://arxiv.org/abs/1611.06355)] [[Github](https://github.com/Guim3/IcGAN)]

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

**GANimation: Anatomically-aware Facial Animation from a Single Image.**<br> 
*Albert Pumarola, Antonio Agudo, Aleix M. Martinez, Alberto Sanfeliu, Francesc Moreno-Noguer.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1807.09251)] [[Github](https://github.com/albertpumarola/GANimation)] 

**SingleGAN: Image-to-Image Translation by a Single-Generator Network using Multiple Generative Adversarial Learning.**<br>
*Xiaoming Yu, Xing Cai, Zhenqiang Ying, Thomas Li, Ge Li.*<br>
ACCV 2018. [[PDF](https://arxiv.org/abs/1810.04991)] [[Github](https://github.com/Xiaoming-Yu/SingleGAN)] 

**SMIT: Stochastic Multi-Label Image-to-Image Translation.** <br>
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


**injectionGAN: Toward Learning a Unified Many-to-Many Mapping for Diverse Image Translation.** <br>
*Wenju Xu, Shawn Keshmiri, Guanghui Wang.* <br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1905.08766)]

## Applications

### Attribute-Editing

**BeautyGAN: Instance-level Facial Makeup Transfer with Deep Generative Adversarial Network.**<br>
*Tingting Li, Ruihe Qian, Chao Dong,  Si Liu, Qiong Yan, Wenwu Zhu,  Liang Lin*<br> 
ACM MM 2018. [[PDF](https://liusi-group.com/pdf/BeautyGAN-camera-ready.pdf)] [[Github](github.com/Honlan/BeautyGAN)] [[Project](http://liusi-group.com/projects/BeautyGAN)]

**UFDN: A Unified Feature Disentangler for Multi-Domain Image Translation and Manipulation.**<br> 
*Alexander H. Liu, Yen-Cheng Liu, Yu-Ying Yeh, Yu-Chiang Frank Wang.*<br> 
NeurIPS 2018. [[PDF](https://arxiv.org/abs/1809.01361)] [[Github](https://github.com/Alexander-H-Liu/UFDN)]

**ELEGANT: Exchanging Latent Encodings with GAN for Transferring Multiple Face Attributes.** <br>
*Taihong Xiao, Jiapeng Hong, Jinwen Ma.*<br> 
ECCV 2018. [[PDF](https://arxiv.org/abs/1803.10562)] [[Github](https://github.com/Prinsphield/ELEGANT)] 

**Biphasic-GAN: Biphasic Learning of GANs for High-Resolution Image-to-Image Translation.** <br>
*Jie Cao, Huaibo Huang, Yi Li, Jingtuo Liu, Ran He, Zhenan Sun.*<br> 
ArXiv 2019. [[PDF](https://arxiv.org/abs/1904.06624)]              

**High Fidelity Face Manipulation with Extreme Pose and Expression.**<br> 
*Chaoyou Fu, Yibo Hu, Xiang Wu, Guoli Wang, Qian Zhang, Ran He.*<br> 
ArXiv 2019. [[PDF](https://arxiv.org/abs/1903.12003)] 

**Make a Face: Towards Arbitrary High Fidelity Face Manipulation.** <br>
*Shengju Qian, Kwan-Yee Lin, Wayne Wu, Yangxiaokang Liu, Quan Wang, Fumin Shen, Chen Qian, Ran He.*<br> 
ICCV 2019. [[PDF](https://arxiv.org/abs/1908.07191)]

**SliderGAN: Synthesizing Expressive Face Images by Sliding 3D Blendshape Parameters.**<br>
*Evangelos Ververas, Stefanos Zafeiriou.*<br> 
arxiv 2019. [[PDF](https://arxiv.org/abs/1908.08847)] 

**Generating High-Resolution Fashion Model Images Wearing Custom Outfits.**<br> 
*Gökhan Yildirim, Nikolay Jetchev, Roland Vollgraf, Urs Bergmann.*<br> 
Workshop on Computer Vision for Fashion, Art and Design, ICCV 2019. [[PDF](https://arxiv.org/abs/1908.09638)] 

### Video

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

**Few-shot Video-to-Video Synthesis.** <br>
*Ting-Chun Wang, Ming-Yu Liu, Andrew Tao, Guilin Liu, Jan Kautz, Bryan Catanzaro.*<br> 
ArXiv 2019. [[PDF](https://nvlabs.github.io/few-shot-vid2vid/main.pdf)] [[Project](https://nvlabs.github.io/few-shot-vid2vid/)]

### Data Augmentation

**Generative Image Translation for Data Augmentation in Colorectal Histopathology Images.** <br>
NeurIPS 2019 Machine Learning for Health Workshop. [[PDF](https://arxiv.org/abs/1910.05827)] [[Project](https://github.com/BMIRDS/HistoGAN)]

**DG-Net: Joint Discriminative and Generative Learning for Person Re-identification.** <br>
*Zhedong Zheng, Xiaodong Yang, Zhiding Yu, Liang Zheng, Yi Yang, Jan Kautz.* <br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1904.07223)] [[Github](https://github.com/NVlabs/DG-Net)]

### Model-Compression-and-Pruning

**Co-Evolutionary Compression for Unpaired Image Translation.** <br>
*Han Shu, Yunhe Wang, Xu Jia, Kai Han, Hanting Chen, Chunjing Xu, Qi Tian, Chang Xu.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1907.10804)] [[Github](https://github.com/huawei-noah/GAN-pruning)] 

### Adversarial-Examples

**Adversarial Self-Defense for Cycle-Consistent GANs.** <br>
*Dina Bashkirova, Ben Usman, Kate Saenko.*<br>
NeurIPS 2019. [[PDF](https://arxiv.org/abs/1908.01517v1)]]

### Imbalanced Data

**Elastic-InfoGAN: Unsupervised Disentangled Representation Learning in Imbalanced Data.** <br>
*Utkarsh Ojha, Krishna Kumar Singh, Cho-Jui Hsieh, Yong Jae Lee.*<br>
arxiv, 1 Oct 2019. [[PDF](https://arxiv.org/abs/1910.01112)]   

### Few-Shot

**FUNIT: Few-Shot Unsupervised Image-to-Image Translation.** <br> 
*[Ming-Yu Liu](http://mingyuliu.net/), Xun Huang, Arun Mallya, Tero Karras, Timo Aila, Jaakko Lehtinen, Jan Kautz.*<br> 
ICCV 2019. [[PDF](https://arxiv.org/abs/1905.01723)] [[Project](https://nvlabs.github.io/FUNIT/)] [[Github](https://github.com/nvlabs/FUNIT/)]

**Semi Few-Shot Attribute Translation.** <br> 
*Ricard Durall, Franz-Josef Pfreundt, Janis Keuper.*<br> 
ArXiv 2019. [[PDF](https://arxiv.org/abs/1910.03240)] 

**ZstGAN: An Adversarial Approach for Unsupervised Zero-Shot Image-to-Image Translation.** <br> 
*Jianxin Lin, Yingce Xia, Sen Liu, Tao Qin, Zhibo Chen.*<br> 
ArXiv 2019. [[PDF](https://arxiv.org/abs/1906.00184)] [[Github](https://github.com/linjx-ustc1106/ZstGAN-PyTorch)]

**MetaPix: Few-Shot Video Retargeting.** <br>
*Jessica Lee, Deva Ramanan, Rohit Girdhar.*<br> 
ICCV 2019. [[PDF](https://arxiv.org/abs/1910.04742)]] [[Project](https://motionretargeting2d.github.io)] [[Github](https://github.com/imjal/MetaPix)] 

**Few-shot Video-to-Video Synthesis.** <br>
*Ting-Chun Wang, Ming-Yu Liu, Andrew Tao, Guilin Liu, Jan Kautz, Bryan Catanzaro.*<br> 
ArXiv 2019. [[PDF](https://nvlabs.github.io/few-shot-vid2vid/main.pdf)] [[Project](https://nvlabs.github.io/few-shot-vid2vid/)]

### Image-Synthesis

**SEAN: Image Synthesis with Semantic Region-Adaptive Normalization.** <br>
*Peihao Zhu, Rameen Abdal, Yipeng Qin, Peter Wonka.*<br> 
arxiv, 28 Nov 2019. [[PDF](https://arxiv.org/abs/1911.12861)] [[Video](https://youtu.be/0Vbj9xFgoUw)]

**LostGANs: Image Synthesis From Reconfigurable Layout and Style.** <br>
*Wei Sun, Tianfu Wu.*<br>
ICCV 2019. [[PDF](https://www.arxiv-vanity.com/papers/1908.07500/)] [[Github](https://github.com/iVMCL/LostGANs)]

**Learning to Predict Layout-to-image Conditional Convolutions for Semantic Image Synthesis.** <br> 
*Xihui Liu, Guojun Yin, Jing Shao, Xiaogang Wang, Hongsheng Li.* <br>
NeurIPS 2019. [[PDF](https://arxiv.org/abs/1910.06809)]  

**Face-to-Parameter Translation for Game Character Auto-Creation.** <br> 
*Tianyang Shi, Yi Yuan, Changjie Fan, Zhengxia Zou, Zhenwei Shi, Yong Liu.*<br>
ICCV 2019. [[PDF](https://arxiv.org/pdf/1909.01064.pdf)]    

**APDrawingGAN: Face-to-Parameter Translation for Game Character Auto-Creation.** <br>
*Ran Yi, Yong-Jin Liu, Yu-Kun Lai, Paul L. Rosin.*<br>
CVPR 2019. [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/papers/Yi_APDrawingGAN_Generating_Artistic_Portrait_Drawings_From_Face_Photos_With_Hierarchical_CVPR_2019_paper.pdf) [Github](https://github.com/yiranran/APDrawingGAN)] [[Online Demo](https://face.lol)]

**Cascaded Generation of High-quality Color Visible Face Images from Thermal Captures.** <br> 
*Naser Damer, Fadi Boutros, Khawla Mallat, Florian Kirchbuchner, Jean-Luc Dugelay, Arjan Kuijper.*<br>
ArXiv 2019. [[PDF](https://arxiv.org/abs/1910.09524)] 

**CartoonGAN: Generative Adversarial Networks for Photo Cartoonization.** <br>
*Yang Chen, Yu-Kun Lai, Yong-Jin Liu.*<br>
CVPR 2018. [[PDF](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_CartoonGAN_Generative_Adversarial_CVPR_2018_paper.pdf)] [[Github](https://github.com/FlyingGoblin/CartoonGAN)] [[unofficial test](https://github.com/Yijunmaverick/CartoonGAN-Test-Pytorch-Torch)] [[unofficial pytorch](https://github.com/znxlwm/pytorch-CartoonGAN)]

### Retargeting-and-3D-Vision

**Render4Completion: Synthesizing Multi-View Depth Maps for 3D Shape Completion.** <br>
*Tao Hu, Zhizhong Han, Abhinav Shrivastava, Matthias Zwicker.* <br>
ICCV 2019 workshop on Geometry meets Deep Learning. [[PDF](https://arxiv.org/abs/1904.08366)]

**Multi-Garment Net_Learning to Dress 3D people from Images.** <br>
*Bharat Lal Bhatnagar, Garvita Tiwari, Christian Theobalt, Gerard Pons-Moll.*<br>
ICCV 2019. [[PDF](https://virtualhumans.mpi-inf.mpg.de/papers/bhatnagar2019mgn/bhatnagar2019mgn.pdf)] [[Github](https://github.com/bharat-b7/MultiGarmentNetwork)]

**Tex2Shape: Detailed Full Human Body Geometry From a Single Image.** <br>
*Thiemo Alldieck, Gerard Pons-Moll, Christian Theobalt, Marcus Magnor.* <br>
ICCV 2019. [[arxiv](https://arxiv.org/abs/1904.08645)] [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/html/Alldieck_Tex2Shape_Detailed_Full_Human_Body_Geometry_From_a_Single_Image_ICCV_2019_paper.html)] [[Github](https://github.com/thmoa/tex2shape)]

**pix2vertex: Unrestricted facial geometry reconstruction using image-to-image translation.** <br>
*Matan Sela, Elad Richardson, Ron Kimmel.* <br>
arxiv, 2017. [[PDF](https://arxiv.org/abs/1703.10131)] [[Github](https://github.com/matansel/pix2vertex)]

**Learning to Reconstruct People in Clothing from a Single RGB Camera.** <br>
*Thiemo Alldieck, Marcus Magnor, Bharat Lal Bhatnagar, Christian Theobalt, Gerard Pons-Moll.* <br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1903.05885)][[Github](https://github.com/thmoa/octopus)]

**360-Degree Textures of People in Clothing from a Single Image.** <br>
*Verica Lazova, Eldar Insafutdinov, Gerard Pons-Moll.* <br>
3DV 2019. [[PDF](https://arxiv.org/pdf/1908.07117.pdf)][[Project](http://virtualhumans.mpi-inf.mpg.de/360tex/)] 

**SelectionGAN: Multi-Channel Attention Selection GAN with Cascaded Semantic Guidance for Cross-View Image Translation.**<br>
*Hao Tang, Dan Xu, Nicu Sebe, Yanzhi Wang, Jason J. Corso, Yan Yan.*<br>
VPR 2019. [[PDF](https://arxiv.org/abs/1904.06807)] [[Github](https://github.com/Ha0Tang/SelectionGAN)]

**VR Facial Animation via Multiview Image Translation.**<br>
*Shih-En Wei, Jason Saragih, Tomas Simon, Adam W. Harley, Stephen Lombardi, Michal Perdoch, Alexander Hypes, Dawei Wang, Hernan Badino, Yaser Sheikh.*<br>
SIGGRAPH 2019. [[PDF](https://research.fb.com/publications/vr-facial-animation-via-multiview-image-translation/)]

## Conference

### ICLR 2020 
[[accepted paper list](https://openreview.net/group?id=ICLR.cc/2020/Conference)]

**U-GAT-IT: Unsupervised Generative Attentional Networks with Adaptive Layer-Instance Normalization for Image-to-Image Translation.**<br>
*Junho Kim, Minjae Kim, Hyeonwoo Kang, Kwanghee Lee.* <br>
ICLR 2020. [[PDF](https://arxiv.org/abs/1907.10830)] [[Official Tensorflow](https://github.com/taki0112/UGATIT)] [[Pytorch](https://github.com/znxlwm/UGATIT-pytorch)]

### AAAI 2020

### NeurIPS 2019 
[[accepted paper list](https://nips.cc/Conferences/2019/AcceptedPapersInitial)]

**Multi-mapping Image-to-Image Translation via Learning Disentanglement.** [[PDF](https://arxiv.org/abs/1909.07877)]<br>
*Xiaoming Yu, Yuanqi Chen, Shan Liu, Thomas Li, Ge Li.*

**Flow-based Image-to-Image Translation with Feature Disentanglement.** [[PDF](http://papers.nips.cc/paper/8670-flow-based-image-to-image-translation-with-feature-disentanglement.pdf)]<br>
*Ruho Kondo, Keisuke Kawano, Satoshi Koide, Takuro Kutsuna.*

**Explicitly disentangling image content from translation and rotation with spatial-VAE.** [[PDF](https://arxiv.org/abs/1909.11663)]<br>
Tristan Bepler, Ellen Zhong, Kotaro Kelley, Edward Brignole, Bonnie Berger.*

**Learning to Predict Layout-to-image Conditional Convolutions for Semantic Image Synthesis.** [[PDF](https://arxiv.org/abs/1910.06809)]<br>
*Xihui Liu, Guojun Yin, Jing Shao, Xiaogang Wang, Hongsheng Li.*


### ICCV 2019 
[[accepted paper list](http://openaccess.thecvf.com/ICCV2019.py)]

**Tex2Shape: Detailed Full Human Body Geometry From a Single Image.** [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/html/Alldieck_Tex2Shape_Detailed_Full_Human_Body_Geometry_From_a_Single_Image_ICCV_2019_paper.html)]<br>
*Thiemo Alldieck, Gerard Pons-Moll, Christian Theobalt, Marcus Magnor.*

**Face-to-Parameter Translation for Game Character Auto-Creation.** [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Shi_Face-to-Parameter_Translation_for_Game_Character_Auto-Creation_ICCV_2019_paper.pdf)] <br>
*Tianyang Shi, Yi Yuan, Changjie Fan, Zhengxia Zou, Zhenwei Shi, Yong Liu.*

**Learning Fixed Points in Generative Adversarial Networks: From Image-to-Image Translation to Disease Detection and Localization.** [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Siddiquee_Learning_Fixed_Points_in_Generative_Adversarial_Networks_From_Image-to-Image_Translation_ICCV_2019_paper.pdf)] <br>
*Md Mahfuzur Rahman Siddiquee, Zongwei Zhou, Nima Tajbakhsh, Ruibin Feng, Michael B. Gotway, Yoshua Bengio, Jianming Liang.*

**Interactive Sketch & Fill: Multiclass Sketch-to-Image Translation.** [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Ghosh_Interactive_Sketch__Fill_Multiclass_Sketch-to-Image_Translation_ICCV_2019_paper.pdf)] <br>
*Arnab Ghosh, Richard Zhang, Puneet K. Dokania, Oliver Wang, Alexei A. Efros, Philip H. S. Torr, Eli Shechtman.*

**Deep CG2Real: Synthetic-to-Real Translation via Image Disentanglement.** [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Bi_Deep_CG2Real_Synthetic-to-Real_Translation_via_Image_Disentanglement_ICCV_2019_paper.pdf)]<br>
*Sai Bi, Kalyan Sunkavalli, Federico Perazzi, Eli Shechtman, Vladimir G. Kim, Ravi Ramamoorthi.*

**Co-Evolutionary Compression for Unpaired Image Translation.** [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/html/Shu_Co-Evolutionary_Compression_for_Unpaired_Image_Translation_ICCV_2019_paper.html)]<br>
*Han Shu, Yunhe Wang, Xu Jia, Kai Han, Hanting Chen, Chunjing Xu, Qi Tian, Chang Xu.*

**Sym-Parameterized Dynamic Inference for Mixed-Domain Image Translation.** [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/html/Chang_Sym-Parameterized_Dynamic_Inference_for_Mixed-Domain_Image_Translation_ICCV_2019_paper.html)]<br>
*Simyung Chang, SeongUk Park, John Yang, Nojun Kwak.*

**RelGAN: Multi-Domain Image-to-Image Translation via Relative Attributes.** [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/html/Wu_RelGAN_Multi-Domain_Image-to-Image_Translation_via_Relative_Attributes_ICCV_2019_paper.html)]<br>
*Po-Wei Wu, Yu-Jing Lin, Che-Han Chang, Edward Y. Chang, Shih-Wei Liao.*

**ADSPM: Attribute-Driven Spontaneous Motion in Unpaired Image Translation.** [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/html/Wu_Attribute-Driven_Spontaneous_Motion_in_Unpaired_Image_Translation_ICCV_2019_paper.html)] [[Github](https://github.com/mikirui/ADSPM)]<br>
*Ruizheng Wu, Xin Tao, Xiaodong Gu, Xiaoyong Shen, Jiaya Jia.*

**Everybody Dance Now.** [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/html/Chan_Everybody_Dance_Now_ICCV_2019_paper.html)]<br>
*Caroline Chan, Shiry Ginosar, Tinghui Zhou, Alexei A. Efros.*

**Multimodal Style Transfer via Graph Cuts.** [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/html/Zhang_Multimodal_Style_Transfer_via_Graph_Cuts_ICCV_2019_paper.html)]<br>
*Yulun Zhang, Chen Fang, Yilin Wang, Zhaowen Wang, Zhe Lin, Yun Fu, Jimei Yang.*

**A Closed-Form Solution to Universal Style Transfer.** [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/html/Lu_A_Closed-Form_Solution_to_Universal_Style_Transfer_ICCV_2019_paper.html)]<br>
*Ming Lu, Hao Zhao, Anbang Yao, Yurong Chen, Feng Xu, Li Zhang.*

**Guided Image-to-Image Translation With Bi-Directional Feature Transformation.** [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/html/AlBahar_Guided_Image-to-Image_Translation_With_Bi-Directional_Feature_Transformation_ICCV_2019_paper.html)]<br>
*Badour AlBahar, Jia-Bin Huang.*

**Few-Shot Unsupervised Image-to-Image Translation.** [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/html/Liu_Few-Shot_Unsupervised_Image-to-Image_Translation_ICCV_2019_paper.html)]<br>
*Ming-Yu Liu, Xun Huang, Arun Mallya, Tero Karras, Timo Aila, Jaakko Lehtinen, Jan Kautz.*

**InGAN: Capturing and Retargeting the "DNA" of a Natural Image.** [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/html/Shocher_InGAN_Capturing_and_Retargeting_the_DNA_of_a_Natural_Image_ICCV_2019_paper.html)]<br>
*Assaf Shocher, Shai Bagon, Phillip Isola, Michal Irani.*

**Liquid Warping GAN: A Unified Framework for Human Motion Imitation, Appearance Transfer and Novel View Synthesis.** [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/html/Liu_Liquid_Warping_GAN_A_Unified_Framework_for_Human_Motion_Imitation_ICCV_2019_paper.html)]<br>
*Wen Liu, Zhixin Piao, Jie Min, Wenhan Luo, Lin Ma, Shenghua Gao.*

### CVPR 2019 
[[accepted paper list](http://openaccess.thecvf.com/CVPR2019.py)]

**Latent Filter Scaling for Multimodal Unsupervised Image-To-Image Translation.** [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/html/Alharbi_Latent_Filter_Scaling_for_Multimodal_Unsupervised_Image-To-Image_Translation_CVPR_2019_paper.html)]<br>
*Yazeed Alharbi, Neil Smith, Peter Wonka.*<br>

**Attention-Aware Multi-Stroke Style Transfer.** [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/html/Yao_Attention-Aware_Multi-Stroke_Style_Transfer_CVPR_2019_paper.html)]<br>
*Yuan Yao, Jianqiang Ren, Xuansong Xie, Weidong Liu, Yong-Jin Liu, Jun Wang.*<br>

**Textured Neural Avatars.** [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/html/Shysheya_Textured_Neural_Avatars_CVPR_2019_paper.html)]<br>
*Aliaksandra Shysheya, Egor Zakharov, Kara-Ali Aliev, Renat Bashirov, Egor Burkov, Karim Iskakov, Aleksei Ivakhnenko, Yury Malkov, Igor Pasechnik, Dmitry Ulyanov, Alexander Vakhitov, Victor Lempitsky.*<br>

**Homomorphic Latent Space Interpolation for Unpaired Image-To-Image Translation.** [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/html/Chen_Homomorphic_Latent_Space_Interpolation_for_Unpaired_Image-To-Image_Translation_CVPR_2019_paper.html)] [[Github](https://github.com/yingcong/HomoInterpGAN)]<br>
*[Ying-Cong Chen](https://yingcong.github.io/), Xiaogang Xu, Zhuotao Tian, Jiaya Jia.*<br>

**Multi-Channel Attention Selection GAN With Cascaded Semantic Guidance for Cross-View Image Translation.** [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/papers/Tang_Multi-Channel_Attention_Selection_GAN_With_Cascaded_Semantic_Guidance_for_Cross-View_CVPR_2019_paper.pdf)]<br>
*Hao Tang, Dan Xu, Nicu Sebe, Yanzhi Wang, Jason J. Corso, Yan Yan.*<br>

**TraVeLGAN: Image-To-Image Translation by Transformation Vector Learning.** [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/html/Amodio_TraVeLGAN_Image-To-Image_Translation_by_Transformation_Vector_Learning_CVPR_2019_paper.html)]<br>
*Matthew Amodio, Smita Krishnaswamy.*<br>

**ReversibleGANs for Memory-Efficient ImageTo Image Translation.** [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/html/van_der_Ouderaa_Reversible_GANs_for_Memory-Efficient_Image-To-Image_Translation_CVPR_2019_paper.html)]<br>
*Tycho F.A. van der Ouderaa, Daniel E. Worrall.*<br>

**Image-To-Image Translation via Group-Wise Deep Whitening-And-Coloring Transformation.** [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/html/Cho_Image-To-Image_Translation_via_Group-Wise_Deep_Whitening-And-Coloring_Transformation_CVPR_2019_paper.html)]<br>
*Wonwoong Cho, Sungha Choi, David Keetae Park, Inkyu Shin, Jaegul Choo.*<br>

**Towards Visual Feature Translation.** [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/html/Hu_Towards_Visual_Feature_Translation_CVPR_2019_paper.html)]<br>
*Jie Hu, Rongrong Ji, Hong Liu, Shengchuan Zhang, Cheng Deng, Qi Tian.*<br>

**Towards Instance-Level Image-To-Image Translation.** [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/html/Hu_Towards_Visual_Feature_Translation_CVPR_2019_paper.html)]<br>
*Zhiqiang Shen, Mingyang Huang, Jianping Shi, Xiangyang Xue, Thomas S. Huang.*<br>

**Art2Real: Unfolding the Reality of_Artworks via Semantically-Aware Image-To-Image Translation.** [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/html/Tomei_Art2Real_Unfolding_the_Reality_of_Artworks_via_Semantically-Aware_Image-To-Image_Translation_CVPR_2019_paper.html)]<br>
*Matteo Tomei, Marcella Cornia, Lorenzo Baraldi, Rita Cucchiara.*<br>

**TransGaGa：Geometry-Aware Unsupervised Image To Image Translation.** [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/html/Wu_TransGaGa_Geometry-Aware_Unsupervised_Image-To-Image_Translation_CVPR_2019_paper.html)] [[arxiv](https://arxiv.org/abs/1904.09571)] [[project](https://wywu.github.io/projects/TGaGa/TGaGa.html)]<br>
*Wayne Wu, Kaidi Cao, Cheng Li, Chen Qian, Chen Change Loy.*<br>

### ICLR 2019 
[[accepted paper list](https://openreview.net/group?id=ICLR.cc/2019/Conference)]

**InstaGAN: Instance-aware Image-to-Image Translation.** [[PDF](https://openreview.net/forum?id=ryxwJhC9YX)] [[Github](https://github.com/sangwoomo/instagan)]<br>
*Sangwoo Mo, Minsu Cho, Jinwoo Shin.* <br>

**Harmonic Unpaired Image-to-image Translation.** [[PDF](https://openreview.net/forum?id=S1M6Z2Cctm)] <br>
*Rui Zhang, Tomas Pfister, Jia Li.*<br>

**Local Image-to-Image Translation via Pixel-wise Highway Adaptive Instance Normalization.** [[PDF](https://openreview.net/forum?id=HJgTHnActQ)] <br>
*Wonwoong Cho, Seunghwan Choi, Junwoo Park, David Keetae Park, Tao Qin, Jaegul Choo.*

**EG-UNIT: Exemplar Guided Unsupervised Image-to-Image Translation with Semantic Consistency.** [[PDF](https://openreview.net/forum?id=S1lTg3RqYQ)]<br>
*Liqian Ma, Xu Jia, Stamatios Georgoulis, Tinne Tuytelaars, Luc Van Gool.*<br>

**Unsupervised one-to-many image translation.** [[PDF](https://openreview.net/forum?id=B1GIQhCcYm)]<br>
*Samuel Lavoie-Marchildon, Sebastien Lachapelle, Mikołaj Bińkowski, Aaron Courville, Yoshua Bengio, R Devon Hjelm.*<br>

**Unsupervised Image to Sequence Translation with Canvas-Drawer Networks.** [[PDF](https://openreview.net/forum?id=ByeLBj0qFQ)]<br>
*Kevin Frans, Chin-Yi Cheng.*<br>

**Unsupervised Video-to-Video Translation.** [[PDF](https://openreview.net/forum?id=SkgKzh0cY7)]<br>
*Dina Bashkirova, Ben Usman, Kate Saenko.*<br>

### AAAI 2019

**Exploiting Time-Series Image-to-Image Translation to Expand the Range of Wildlife Habitat Analysis.** [[PDF](https://www.aaai.org/ojs/index.php/AAAI/article/view/3862)]<br>
*Ruobing Zheng, Ze Luo, Baoping Yan.*<br>

**Controllable Image-to-Video Translation: A Case Study on Facial Expression Generation.** [[PDF](https://arxiv.org/abs/1808.02992)]<br>
*Lijie Fan, Wenbing Huang, Chuang Gan, Junzhou Huang, Boqing Gong.*<br>

**OT-CycleGAN: Guiding the One-to-one Mapping in CycleGAN via Optimal Transport.** [[PDF](https://arxiv.org/abs/1811.06284)] <br>
*Guansong Lu, Zhiming Zhou, Yuxuan Song, Kan Ren, Yong Yu.*<br> 

### ACM MM 2019

**C2-GAN: Cycle In Cycle Generative Adversarial Networks for Keypoint-Guided Image Generation.**[[PDF](https://arxiv.org/abs/1908.00999)] <br>
*Hao Tang, Dan Xu, Gaowen Liu, Wei Wang, Nicu Sebe, Yan Yan.* <br>

**Towards Automatic Face-to-Face Translation.**[[PDF](https://dl.acm.org/doi/10.1145/3343031.3351066)] [[Github](https://github.com/Rudrabha/LipGAN)] [[Project](http://cvit.iiit.ac.in/research/projects/cvit-projects/facetoface-translation)]<br>
*Prajwal Renukanand, Rudrabha Mukhopadhyay, Jerin Philip, Abhishek Jha, Vinay Namboodiri and C.V. Jawahar.*<br>

**Preserving Semantic and Temporal Consistency for Unpaired Video-to-Video Translation.**[[PDF](https://arxiv.org/abs/1908.07683)]<br>
*Kwanyong Park, Sanghyun Woo, Dahun Kim, Donghyeon Cho, In So Kweon.*<br>
 
**Mocycle-GAN: Unpaired Video-to-Video Translation.**[[PDF](https://arxiv.org/abs/1908.09514)]<br> 
*Yang Chen, Yingwei Pan, Ting Yao, Xinmei Tian, Tao Mei.*<br> 

### Journal 2019

**DRIT++: Diverse Image-to-Image Translation via Disentangled Representations.** <br>
*Hsin-Ying Lee, Hung-Yu Tseng, Qi Mao, Jia-Bin Huang, Yu-Ding Lu, Maneesh Singh, Ming-Hsuan Yang.* <br>
IJCV 2019. [[Project](http://vllab.ucmerced.edu/hylee/DRIT_pp/)] [[Github](https://github.com/HsinYingLee/MDMM)]

**Show, Attend and Translate: Unsupervised Image Translation with Self-Regularization and Attention.** <br>
*Chao Yang, Taehwan Kim, Ruizhe Wang, Hao Peng, C.-C. Jay Kuo.* <br>
TIP 2019. [[PDF](https://arxiv.org/abs/1806.06195)]

**AttGAN: Facial Attribute Editing by Only Changing What You Want.** <br> 
*Zhenliang He, Wangmeng Zuo, Meina Kan, Shiguang Shan, Xilin Chen.* <br>
TIP 2019. [[PDF](https://arxiv.org/abs/1711.10678)] [[Github](https://github.com/LynnHo/AttGAN-Tensorflow)]

### Others 2019

**RL-GAN: Transfer Learning for Related Reinforcement Learning Tasks via Image-to-Image Translation.** <br>
*Shani Gamrian, Yoav Goldberg.* <br>
ICML 2019. [[accepted paper list](http://proceedings.mlr.press/v97/)] [[PDF](https://arxiv.org/abs/1806.07377)] [[Supplementary PDF](http://proceedings.mlr.press/v97/fujimoto19a/fujimoto19a-supp.pdf)] [[Github](https://github.com/ShaniGam/RL-GAN)]

**VR Facial Animation via Multiview Image Translation.** <br>
*Shih-En Wei, Jason Saragih, Tomas Simon, Adam W. Harley, Stephen Lombardi, Michal Perdoch, Alexander Hypes, Dawei Wang, Hernan Badino, Yaser Sheikh.* <br>
SIGGRAPH 2019. [[PDF](https://research.fb.com/publications/vr-facial-animation-via-multiview-image-translation/)]

**Stylizing Video by Example.**<br> 
*Ondřej Jamriška, Šárka Sochorová, Ondřej Texler, Michal Lukáč, Jakub Fišer, Jingwan Lu, Eli Shechtman, Daniel Sýkora.*<br>
SIGGRAPH 2019. [[PDF](https://dcgi.fel.cvut.cz/home/sykorad/Jamriska19-SIG.pdf)]

**VR Facial Animation via Multiview Image Translation.**<br>
*Shih-En Wei, Jason Saragih, Tomas Simon, Adam W. Harley, Stephen Lombardi, Michal Perdoch, Alexander Hypes, Dawei Wang, Hernan Badino, Yaser Sheikh.*<br>
SIGGRAPH 2019. [[PDF](https://research.fb.com/publications/vr-facial-animation-via-multiview-image-translation/)]

**CartoonRenderer: An Instance-based Multi-Style Cartoon Image Translator.** <br>
*Yugang Chen, Muchun Chen, Chaoyue Song, Bingbing Ni.* <br>
International Conference on Multimedia Modeling (MMM2020). [[PDF](https://arxiv.org/abs/1911.06102)] 

**AttentionGAN: Attention-Guided Generative Adversarial Networks for Unsupervised Image-to-Image Translation.**<br>
*Hao Tang, Dan Xu, Nicu Sebe, Yan Yan.* <br>
IJCNN 2019. [[Github](https://github.com/Ha0Tang/AttentionGAN)]

**SMIT: Stochastic Multi-Label Image-to-Image Translation.** <br>
*Andrés Romero, Pablo Arbeláez, Luc Van Gool, Radu Timofte.*<br>
ICCV Workshops 2019. [[PDF](https://arxiv.org/abs/1812.03704)] [[Github](https://github.com/BCV-Uniandes/SMIT)]

**Image-to-Image Translation with Multi-Path Consistency Regularization.** <br>
*Jianxin Lin, Yingce Xia, Yijun Wang, Tao Qin, Zhibo Chen.*<br>
IJCAI 2019. [[PDF](https://arxiv.org/abs/1905.12498)]

**Asymmetric Generative Adversarial Networks for Image-to-Image Translation.** <br>
*Hao Tang, Dan Xu, Hong Liu, Nicu Sebe.*<br>
arxiv, 14 Dec 2019 (ACCV 2018 Extension) [[PDF](https://arxiv.org/abs/1912.06931)] [[GitHub](​​​https://github.com/Ha0Tang/AsymmetricGAN)]

**PPN2V: Fully Unsupervised Probabilistic Noise2Void.** <br>
*Mangal Prakash, Manan Lalit, Pavel Tomancak, Alexander Krull, Florian Jug.*<br>
arxiv, 27 Nov 2019. [[PDF](https://arxiv.org/abs/1911.12291)] [[GitHub](https://github.com/juglab/ppn2v)] [[MPI-CBG: Max-Planck Institute of Molecular Cell Biology and Genetics](https://www.mpi-cbg.de/home/)]

**PN2V:Probabilistic Noise2Void: Unsupervised Content-Aware Denoising.** <br>
*Alexander Krull, Tomas Vicar, Florian Jug.*<br>
arxiv, 3 Jun 2019. [[PDF](https://arxiv.org/abs/1906.00651)] [[Github](https://github.com/juglab/pn2v)]

**Unpaired Image Translation via Adaptive Convolution-based Normalization.** <br>
*Wonwoong Cho, Kangyeol Kim, Eungyeup Kim, Hyunwoo J. Kim, Jaegul Choo.*<br>
arxiv, 29 Nov 2019. [[PDF]( https://arxiv.org/abs/1911.13271)]

**EDIT: Exemplar-Domain Aware Image-to-Image Translation.** <br>
*Yuanbin Fu, Jiayi Ma, Lin Ma, Xiaojie Guo.* <br>
arxiv, 24 Nov 2019. [[PDF](https://arxiv.org/abs/1911.10520)] [[GitHub](http://t.cn/AigvDwW3)]

**Council-GAN: Breaking the cycle - Colleagues are all you need.** <br>
*Ori Nizan, Ayellet Tal.* <br>
arxiv, 24 Nov 2019. [[PDF](https://arxiv.org/abs/1911.10538)]

**injectionGAN: Toward Learning a Unified Many-to-Many Mapping for Diverse Image Translation.**<br>
*Wenju Xu, Shawn Keshmiri, Guanghui Wang.* <br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1905.08766)]

**Cross-Domain Cascaded Deep Feature Translation.** <br>
*Oren Katzir, Dani Lischinski, Daniel Cohen-Or.* <br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1906.01526)]

**AGUIT: Attribute Guided Unpaired Image-to-Image Translation with Semi-supervised Learning.**<br>
*Xinyang Li, Jie Hu, Shengchuan Zhang, Xiaopeng Hong, Qixiang Ye, Chenglin Wu, Rongrong Ji.*<br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1904.12428)] [[Github](https://github.com/imlixinyang/aguit)]

**CrossNet: Latent Cross-Consistency for Unpaired Image Translation.** <br>
*Omry Sendik, Dani Lischinski, Daniel Cohen-Or.*<br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1901.04530)]

### Before 2018
- pix2pix: [[Project](https://phillipi.github.io/pix2pix/)] [[Code](https://github.com/phillipi/pix2pix)] [[Paper](https://arxiv.org/pdf/1611.07004.pdf)]
- BicycleGAN: [[Code](https://github.com/junyanz/BicycleGAN)] [[Tensorflow](https://github.com/gitlimlab/BicycleGAN-Tensorflow)]
- CycleGAN: [[Project](https://junyanz.github.io/CycleGAN/)] [[CycleGAN](https://github.com/junyanz/CycleGAN)] [[pytorch-CycleGAN-and-pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)] [[Full Paper](https://arxiv.org/pdf/1703.10593.pdf)]
- DualGAN: [[Code](https://github.com/duxingren14/DualGAN)] [[Paper](https://arxiv.org/abs/1704.02510)]
- DiscoGAN: [[Code](https://github.com/carpedm20/DiscoGAN-pytorch)] [[Paper](https://arxiv.org/abs/1703.05192)]
- StarGAN: CVPR 2018. [[Code](https://github.com/yunjey/StarGAN)] [[Paper](https://arxiv.org/abs/1711.09020)]
- VAE-GAN: [[Code](http://github.com/andersbll/autoencoding_beyond_pixels)] [[Paper](https://arxiv.org/pdf/1611.07004.pdf)]
- UNIT:[[Code](https://github.com/mingyuliutw/UNIT)]
- cVAE-GAN: [[Paper](https://arxiv.org/pdf/1703.10155.pdf)]
- DTN: [[Code](https://github.com/yunjey/domain-transfer-network)] [[Paper](https://arxiv.org/abs/1611.02200)]
- FaderNets: [[Code](https://github.com/facebookresearch/FaderNetworks)] [[Paper](https://arxiv.org/abs/1706.00409)]
- IcGAN: [[Code](https://github.com/Guim3/IcGAN)] [[Paper](https://arxiv.org/abs/1611.06355)]
- GeneGAN: [[Code](https://github.com/Prinsphield/GeneGAN)] [[Paper](https://arxiv.org/abs/1705.04932)]
- Face-Age-cGAN: [[Paper](https://arxiv.org/abs/1702.01983)]
- DAGAN:  Deep Attention GAN

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

### Attribute Editing
- `CelebA`. The CelebFaces Attributes (CelebA) dataset contains 202,599 face images of celebrities, each annotated with 40 binary attributes. size 178×218. hair color (black, blond, brown),gender (male/female), and age (young/old).
- `CelebA-HQ`.
- `CelebAMask-HQ`. It is a large-scale face image dataset that has 30,000 high-resolution face images selected from the CelebA dataset by following CelebA-HQ. Each image has segmentation mask of facial attributes corresponding to CelebA. The masks of CelebAMask-HQ were manually-annotated with the size of 512×512 and 19 classes including all facial components and acessories such as skin, nose, eyes, eyebrows, ears, mouth, lip, hair, hat, eyeglass, earring, necklace, neck, and cloth.
- `RaFD`. The Radboud Faces Database (RaFD) consists of 4,824 images collected from 67 participants. Each participant makes eight facial expressions in three different gaze directions, which are captured from three different angles.
- `CMU Multi-PIE Face Database`. [[Multi-PIE](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2873597/)] A large (305GB) database of images for training facial recognition software. It consists 13 poses within ±90 degrees of 337 subjects and can be used for face frontalization experiments.
- `AFHQ`.  Released in StarGAN v2. Animal FacesHQ (AFHQ) consists of 15,000 high-quality images at 512 × 512 resolution. We collected images with
permissive licenses from the [Flickr](https://www.flickr.com/) and [Pixabay](https://pixabay.com/) websites. All images are vertically and horizontally aligned to have the eyes at the center. The low-quality images were discarded by human effort. See the [Project](https://github.com/clovaai/stargan-v2) or Paper for more details.

### Others
-`Makeup Transfer`. [[Download](http://liusi-group.com/projects/BeautyGAN)]
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
