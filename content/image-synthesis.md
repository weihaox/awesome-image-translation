# Image Synthesis

## Table of Contents
- [Team](#team)
- [Restoration or Enhancement](#restoration-or-enhancement)
  * [With Exemplar](#with-exemplar)
  * [With Unpaired or Misaligned Data](#with-unpaired-or-misaligned-data)
  * [Replacing ISP](#replacing-isp)
  * [Misc](#misc)
  * [Challenge and Survey](#challenge-and-survey)
- [Diving Deep into Image Synthesis](#diving-deep-into-image-synthesis)
  * [StyleGAN-Based Method](#stylegan-based-method)
  * [Single-Image Training](#single-image-training)
  * [Misc](#misc-1)
- [DeepFake and Forensic](#deepfake-and-forensic)
- [Video Prediction and Future Prediction](#video-prediction-and-future-prediction)
- [Frame Interpolation, Extrapolation and Videos Generation](#frame-interpolation--extrapolation-and-videos-generation)
- [Free-Hand Sketch](#free-hand-sketch)
- [Image Harmonization](#image-harmonization)
- [Photorealistic Style Transfer](#photorealistic-style-transfer)
- [Soft Segmentation and Background Matting](#soft-segmentation-and-background-matting)
- [Occlusion Reasoning](#occlusion-reasoning)
- [Reciprocal Computer Vision Tasks](#reciprocal-computer-vision-tasks)

## Team

[GenForce](https://genforce.github.io): Research Initiative on Generative Modeling at CUHK.

## Image Restoration and Enhancement

### Replacing ISP

**Rendering Natural Camera Bokeh Effect with Deep Learning.**<br>
*Andrey Ignatov, Jagruti Patel, Radu Timofte.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.05698)] [[Project](http://people.ee.ethz.ch/~ihnatova/pynet-bokeh.html)] [[Everything is Better with Bokeh!  Dataset](https://competitions.codalab.org/competitions/24716)]

**PyNET: Replacing Mobile Camera ISP with a Single Deep Learning Model.**<br>
*Andrey Ignatov, Luc Van Gool, Radu Timofte.*<br>
CVPRW 2020. [[PDF](https://arxiv.org/abs/2002.05509)] [[Project](http://people.ee.ethz.ch/~ihnatova/pynet.html)] [[Official PyTorch](https://github.com/aiff22/PyNET-PyTorch)] [[Official TensorFlow](https://github.com/aiff22/PyNET)]

**DSLR-Quality Photos on Mobile Devices with Deep Convolutional Networks.**<br>
*Andrey Ignatov, Nikolay Kobyshev, Radu Timofte, Kenneth Vanhoey, Luc Van Gool.*<br>
ICCV 2017. [[PDF](https://arxiv.org/abs/1704.02470)] [[Github](https://github.com/aiff22/DPED)] [[Project](http://people.ee.ethz.ch/~ihnatova/index.html)]

**WESPE: Weakly Supervised Photo Enhancer for Digital Cameras.**<br>
*Andrey Ignatov, Nikolay Kobyshev, Radu Timofte, Kenneth Vanhoey, Luc Van Gool.*<br>
CVPRW 2018. [[PDF](https://arxiv.org/abs/1709.01118)][[Project](http://people.ee.ethz.ch/~ihnatova/wespe.html)]

**Single-Image HDR Reconstruction by Learning to Reverse the Camera Pipeline.**<br>
*[Yu-Lun Liu](https://www.cmlab.csie.ntu.edu.tw/~yulunliu/), Wei-Sheng Lai, Yu-Sheng Chen, Yi-Lung Kao, Ming-Hsuan Yang, Yung-Yu Chuang, Jia-Bin Huang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.01179)] [[Github](https://github.com/alex04072000/SingleHDR)] [[Project](https://www.cmlab.csie.ntu.edu.tw/~yulunliu/SingleHDR)]

**Deep White-Balance Editing.**<br>
*[Mahmoud Afifi](https://sites.google.com/view/mafifi), Michael S. Brown.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.01354)] [[Github](https://github.com/mahmoudnafifi/Deep_White_Balance)]

### With Exemplar

**Learning Texture Transformer Network for Image Super-Resolution.**<br>
*Fuzhi Yang, Huan Yang, Jianlong Fu, Hongtao Lu, Baining Guo.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2006.04139)] [[Github](https://github.com/FuzhiYang/TTSR)]

**Instance-aware Image Colorization.**<br>
*Jheng-Wei Su, Hung-Kuo Chu, Jia-Bin Huang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2005.10825)] [[Github](https://ericsujw.github.io/InstColorization/)] [[Project](https://ericsujw.github.io/InstColorization/)]

**Unsupervised Real Image Super-Resolution via Generative Variational AutoEncoder.**<br>
*Zhi-Song Liu, Wan-Chi Siu, Li-Wen Wang, Chu-Tak Li, Marie-Paule Cani, Yui-Lam Chan.*<br>
CVPR 2020 Workshop NTIRE. [[PDF](https://arxiv.org/abs/2004.12811)] [[Github](https://github.com/Holmes-Alan/dSRVAE)] [[NTIRE2020 Real Image Super-Resolution Challenge](https://data.vision.ee.ethz.ch/cvl/ntire20/)]

**SRTNN: Image Super-Resolution by Neural Texture Transfer.**<br>
*[Zhifei Zhang](https://zzutk.github.io/), Zhaowen Wang, Zhe Lin, Hairong Qi.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1903.00834)] [[Project](http://web.eecs.utk.edu/~zzhang61/project_page/SRNTT/SRNTT.html)] [[Github](https://github.com/ZZUTK/SRNTT)]

**CrossNet: An End-to-end Reference-based Super Resolution Network using Cross-scale Warping.**<br>
*Haitian Zheng, Mengqi Ji, Haoqian Wang, Yebin Liu, Lu Fang.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1807.10547)]

**Deep Exemplar-Based Video Colorization.**<br>
*Bo Zhang, Mingming He, Jing Liao, Pedro V. Sander, Lu Yuan, Amine Bermak, Dong Chen.*<br>
CVPR 2019. [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Deep_Exemplar-Based_Video_Colorization_CVPR_2019_paper)]

**Deep Exemplar-based Colorization.**<br>
*Mingming He, [Dongdong Chen](http://www.dongdongchen.bid/), [Jing Liao](https://liaojing.github.io/html/index.html), Pedro V. Sander, Lu Yuan.*<br>
Siggraph 2018. [[PDF](https://arxiv.org/abs/1807.06587)] [[Github](https://github.com/msracver/Deep-Exemplar-based-Colorization)]

**Progressive Color Transfer with Dense Semantic Correspondences.**<br>
*Mingming He, Jing Liao, Dongdong Chen, Lu Yuan, Pedro V Sander.*<br>
ACM TOG 2018.[[PDF](https://arxiv.org/pdf/1710.00756.pdf)]

**Recovering Realistic Texture in Image Super-resolution by Deep Spatial Feature Transform.**<br>
*[Xintao Wang](https://xinntao.github.io/), [Ke Yu](https://yuke93.github.io/), [Chao Dong](https://scholar.google.com.hk/citations?user=OSDCB0UAAAAJ&hl=en), [Chen Change Loy](http://personal.ie.cuhk.edu.hk/~ccloy/).*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1804.02815)] [[Project](http://mmlab.ie.cuhk.edu.hk/projects/SFTGAN/)] [[Github](https://github.com/xinntao/SFTGAN)] [[BasicSR](https://github.com/xinntao/BasicSR)] [[HandyViewer](https://github.com/xinntao/HandyViewer)]

**The Unreasonable Effectiveness of Texture Transfer for Single Image Super-resolution.**<br>
*Muhammad Waleed Gondal, Bernhard Schölkopf, Michael Hirsch.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1808.00043)] [[Github](https://github.com/waleedgondal/Texture-based-Super-Resolution-Network)]

**Learned Multi-View Texture Super-Resolution.**<br>
*Audrey Richard, Ian Cherabier, Martin R. Oswald, Vagia Tsiminaki, Marc Pollefeys, Konrad Schindler.*<br>
3DV 2019. [[PDF](https://arxiv.org/abs/2001.04775)]

### With Unpaired or Misaligned Data

**Unpaired Learning of Deep Image Denoising.**<br>
*Xiaohe Wu, Ming Liu, Yue Cao, Dongwei Ren, Wangmeng Zuo.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.13711)]

**Dehaze-GLCGAN: Unpaired Single Image De-hazing via Adversarial Training.**<br>
*Zahra Anvari, Vassilis Athitsos.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.06632)]

**Component Divide-and-Conquer for Real-World Image Super-Resolution.**<br>
*Pengxu Wei, Ziwei Xie, Hannan Lu, Zongyuan Zhan, Qixiang Ye, Wangmeng Zuo, Liang Lin.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.01928)] [[Github](https://github.com/xiezw5/Component-Divide-and-Conquer-for-Real-World-Image-Super-Resolution)]

**From Shadow Segmentation to Shadow Removal.**<br>
*Hieu Le, Dimitris Samaras.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.00267)] [[Github](https://www3.cs.stonybrook.edu/~cvl/projects/FSS2SR/index.html)]

**DBSN: Unpaired Learning of Deep Image Denoising.**<br>
*Xiaohe Wu, Ming Liu, Yue Cao, Dongwei Ren, Wangmeng Zuo.*<br>
ECCV 2020. [[PDF](https://github.com/XHWXD/DBSN)]

**Zero-Reference Deep Curve Estimation for Low-Light Image Enhancement.**<br>
*Chunle Guo, Chongyi Li, Jichang Guo, Chen Change Loy, Junhui Hou, Sam Kwong, Runmin Cong.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2001.06826)] [[Github](https://github.com/Li-Chongyi/Zero-DCE)]

**Unpaired Image Super-Resolution using Pseudo-Supervision.**<br>
*Shunta Maeda.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2002.11397)]

**Domain Adaptation for Image Dehazing.**<br>
*Yuanjie Shao, Lerenhan Li, Wenqi Ren, Changxin Gao, Nong Sang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2005.04668)]

**Unsupervised Real-world Low-light Image Enhancement with Decoupled Networks.**<br>
*Wei Xiong, Ding Liu, Xiaohui Shen, Chen Fang, Jiebo Luo.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2005.02818)]

**SimUSR: A Simple but Strong Baseline for Unsupervised Image Super-resolution.**<br>
*Namhyuk Ahn, Jaejun Yoo, Kyung-Ah Sohn.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.11020)]

**Weakly Aligned Joint Cross-Modality Super Resolution.**<br>
*Guy Shacht, Sharon Fogel, Dov Danon, Daniel Cohen-Or.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.09965)]

**Unsupervised Real-world Image Super Resolution via Domain-distance Aware Training.**<br>
*Yunxuan Wei, [Shuhang Gu](https://shuhanggu.github.io/), Yawei Li, Longcun Jin.*<br>
arxiv 2020. [[PDF](https://arxiv.org/pdf/2004.01178)] [[Github](https://github.com/ShuhangGu/DASR)]

**Robust Image Reconstruction with Misaligned Structural Information.**<br>
*Leon Bungert, Matthias J. Ehrhardt.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.00589)]

**Closed-loop Matters: Dual Regression Networks for Single Image Super-Resolution.**<br>
*Yong Guo, Jian Chen, Jingdong Wang, Qi Chen, Jiezhang Cao, Zeshuai Deng, Yanwu Xu, Mingkui Tan.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.07018)]

**Learning Invariant Representation for Unsupervised Image Restoration.**<br>
*Wenchao Du, Hu Chen, Hongyu Yang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.12769)]

**Meta-Transfer Learning for Zero-Shot Super-Resolution.**<br>
*Jae Woong Soh, Sunwoo Cho, Nam Ik Cho.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2002.12213)]

**EnlightenGAN: Deep Light Enhancement without Paired Supervision.**<br>
*Yifan Jiang, Xinyu Gong, Ding Liu, Yu Cheng, Chen Fang, Xiaohui Shen, Jianchao Yang, Pan Zhou, Zhangyang Wang.*<br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1906.06972)] [[Github](https://github.com/TAMU-VITA/EnlightenGAN)] [[Dataset](https://github.com/TAMU-VITA/EnlightenGAN/issues/28)] [[KinD](https://arxiv.org/abs/1905.04161)]

**Unpaired Image Enhancement Featuring Reinforcement-Learning-Controlled Image Editing Software.**<br>
*Satoshi Kosugi, Toshihiko Yamasaki.* <br>
AAAI 2020. [[PDF](https://arxiv.org/abs/1912.07833)]

**Single Image Reflection Removal Exploiting Misaligned Training Data and Network Enhancements.**<br>
*Kaixuan Wei, Jiaolong Yang, Ying Fu, David Wipf, Hua Huang.* <br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1904.00637)] [[Project](https://github.com/Vandermode/ERRNet)]

**Unpaired Image Enhancement Featuring Reinforcement-Learning-Controlled Image Editing Software.**<br>
*Kosugi, Toshihiko Yamasaki.*<br>
arxiv, 2019. [[PDF](https://arxiv.org/pdf/1912.07833.pdfSatoshi)]

**Deep Photo Enhancer: Unpaired Learning for Image Enhancement from Photographs with GANs.**<br>
*Yu-Sheng Chen, Yu-Ching Wang, Man-Hsin Kao, Yung-Yu Chuang.*<br>
CVPR 2018. [[PDF](https://www.cmlab.csie.ntu.edu.tw/project/Deep-Photo-Enhancer/CVPR-2018-DPE.pdf)] [[Supplementary Material](https://www.cmlab.csie.ntu.edu.tw/project/Deep-Photo-Enhancer/CVPR-2018-DPE-sm-compress.pdf)] [[Demo](http://www.cmlab.csie.ntu.edu.tw/project/Deep-Photo-Enhancer/)] [[Github](https://github.com/nothinglo/Deep-Photo-Enhancer)]  [[MIT-Adobe FiveK Dataset](https://data.csail.mit.edu/graphics/fivek/)] [[DSLR Photo Enhancement Dataset](http://people.ee.ethz.ch/~ihnatova/#demo)]

**PPN2V: Fully Unsupervised Probabilistic Noise2Void.**<br>
*Mangal Prakash, Manan Lalit, Pavel Tomancak, Alexander Krull, Florian Jug.*<br>
arxiv, 27 Nov 2019. [[PDF](https://arxiv.org/abs/1911.12291)] [[GitHub](https://github.com/juglab/ppn2v)] [[MPI-CBG: Max-Planck Institute of Molecular Cell Biology and Genetics](https://www.mpi-cbg.de/home/)]

**PN2V:Probabilistic Noise2Void: Unsupervised Content-Aware Denoising.**<br>
*Alexander Krull, Tomas Vicar, Florian Jug.*<br>
arxiv, 3 Jun 2019. [[PDF](https://arxiv.org/abs/1906.00651)] [[Github](https://github.com/juglab/pn2v)]

### Deep Image Prior 

**Unsupervised Hyperspectral Mixed Noise Removal Via Spatial-Spectral Constrained Deep Image Prior.**<br>
*Yi-Si Luo, Xi-Le Zhao, Tai-Xiang Jiang, Yu-Bang Zheng, Yi Chang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.09753)]

**The Hessian Penalty: A Weak Prior for Unsupervised Disentanglement.**<br>
*William Peebles, John Peebles, Jun-Yan Zhu, Alexei Efros, Antonio Torralba.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.10599)] [[Poject](https://www.wpeebles.com/hessian-penalty)] [[Github](https://github.com/wpeebles/hessian_penalty)]

**NAS-DIP: Learning Deep Image Prior with Neural Architecture Search.**<br>
*Yun-Chun Chen, Chen Gao, Esther Robb, Jia-Bin Huang.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.11713)] [[Poject](https://yunchunchen.github.io/NAS-DIP/)] [[Github](https://github.com/YunChunChen/NAS-DIP-pytorch)]

**Exploiting Deep Generative Prior for Versatile Image Restoration and Manipulation.**<br>
*Xingang Pan, Xiaohang Zhan, Bo Dai, Dahua Lin, Chen Change Loy, Ping Luo.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2003.13659)] [[Github](https://github.com/XingangPan/deepgenerative-prior)]

**Semantic Photo Manipulation with a Generative Image Prior.**<br>
*David Bau, Hendrik Strobelt, William Peebles, Jonas, Bolei Zhou, Jun-Yan Zhu, Antonio Torralba.*<br>
SIGGRAPH 2019. [[PDF](https://arxiv.org/abs/2005.07727)]

**PriorGAN: Real Data Prior for Generative Adversarial Nets.**<br>
*Shuyang Gu, Jianmin Bao, Dong Chen, Fang Wen.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.16990)]

**CDVD-TSP: Cascaded Deep Video Deblurring Using Temporal Sharpness Prior.**<br>
*Jinshan Pan, Haoran Bai, Jinhui Tang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.02501)] [[Github](https://github.com/csbhr/CDVD-TSP)]

**Attention Prior for Real Image Restoration.**<br>
*Saeed Anwar, Nick Barnes, Lars Petersson.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.13524)]

### Misc

**ChromaGAN: Adversarial Picture Colorization with Semantic Class Distribution.**<br>
*Patricia Vitoria, Lara Raad, Coloma Ballester.*<br>
WACV 2020. [[PDF](https://arxiv.org/abs/1907.09837)]

**PNEN: Pyramid Non-Local Enhanced Networks.**<br>
*Feida Zhu, Chaowei Fang, Kai-Kuang Ma.*<br>
TIP 2020. [[PDF](https://arxiv.org/abs/2008.09742)]

**ALANET: Adaptive Latent Attention Network forJoint Video Deblurring and Interpolation.**<br>
*Akash Gupta, Abhishek Aich, Amit K. Roy-Chowdhury.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2009.01005)]

**Ultra Lightweight Image Super-Resolution with Multi-Attention Layers.**<br>
*Abdul Muqeet, Jiwon Hwang, Subin Yang, Jung Heum Kang, Yongwoo Kim, Sung-Ho Bae.*<br>
ECCVW AIM2020. [[PDF](https://arxiv.org/abs/2008.12912)]

**DALE : Dark Region-Aware Low-light Image Enhancement.**<br>
*Dokyeong Kwon, Guisik Kim, Junseok Kwon.*<br>
BMVC 2020. [[PDF](https://arxiv.org/abs/2008.12493)]

**HRVGAN: High Resolution Video Generation using Spatio-Temporal GAN.**<br>
*Abhinav Sagar.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.09646)]

**Image Colorization: A Survey and Dataset.**<br>
*Saeed Anwar, Muhammad Tahir, Chongyi Li, Ajmal Mian, Fahad Shahbaz Khan, Abdul Wahab Muzaffar.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.10774)] [[Github](https://github.com/saeed-anwar/ColorSurvey)]

**Exploit Camera Raw Data for Video Super-Resolution via Hidden Markov Model Inference.**<br>
*Xiaohong Liu, Kangdi Shi, Zhe Wang, Jun Chen.*<br>
TIP 2020. [[PDF](https://arxiv.org/abs/2008.10710)]

**GAN Slimming: All-in-One GAN Compression by A Unified Optimization Framework.**<br>
*Haotao Wang, Shupeng Gui, Haichuan Yang, Ji Liu, Zhangyang Wang.*<br>
ECCV 2020. [[PDF](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490052.pdf)] [[Github](https://github.com/VITA-Group/GAN-Slimming)]

**Deep Generative Model for Image Inpainting with Local Binary Pattern Learning and Spatial Attention.**<br>
*Haiwei Wu, Jiantao Zhou, Yuanman Li.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.01031)] [[Project](https://github.com/HighwayWu/ImageInpainting)]

**Flow-edge Guided Video Completion.**<br>
*Chen Gao, Ayush Saraf, Jia-Bin Huang, Johannes Kopf.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2009.01835)] [[Project](http://chengao.vision/FGVC/)]

**SRFlow: Learning the Super-Resolution Space with Normalizing Flow.**<br>
*Andreas Lugmayr, Martin Danelljan, Luc Van Gool, Radu Timofte.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2006.14200)] [[Github](http://git.io/SRFlow)]

**Delving Deeper into Anti-aliasing in ConvNets.**<br>
*Xueyan Zou, Fanyi Xiao, Zhiding Yu, Yong Jae Lee.*<br>
BMVC 2020. [[PDF](https://arxiv.org/abs/2008.09604)] [[Github](https://maureenzou.github.io/ddac/)]

**Image Stitching and Rectification for Hand-Held Cameras.**<br>
*Bingbing Zhuang, Quoc-Huy Tran.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.09229)] [[Project](https://www.nec-labs.com/~mas/RS-APAP)]

**LIRA: Lifelong Image Restoration from Unknown Blended Distortions.**<br>
*Jianzhao Liu, Jianxin Lin, Xin Li, Wei Zhou, Sen Liu, Zhibo Chen.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.08242)]

**Single Image Super-Resolution via a Holistic Attention Network.**<br>
*Ben Niu, Weilei Wen, Wenqi Ren, Xiangde Zhang, Lianping Yang, Shuzhen Wang, Kaihao Zhang, Xiaochun Cao, Haifeng Shen.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/2008.08767)]

**FourFeat: Fourier Features Let Networks Learn High Frequency Functions in Low Dimensional Domains.**<br>
*Matthew Tancik, Pratul P. Srinivasan, Ben Mildenhall, Sara Fridovich-Keil, Nithin Raghavan, Utkarsh Singhal, Ravi Ramamoorthi, Jonathan T. Barron, Ren Ng.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.10739)] [[Project](https://people.eecs.berkeley.edu/~bmild/fourfeat/)]

**Can You Read Me Now? Content Aware Rectification using Angle Supervision.**<br>
*Amir Markovitz, Inbal Lavi, Or Perel, Shai Mazor, Roee Litman.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.02231)]

**DeepGIN: Deep Generative Inpainting Network for Extreme Image Inpainting.**<br>
*Chu-Tak Li, Wan-Chi Siu, Zhi-Song Liu, Li-Wen Wang, Daniel Pak-Kong Lun.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.07173)]

**SRFlow: Learning the Super-Resolution Space with Normalizing Flow.**<br>
*Andreas Lugmayr, Martin Danelljan, Luc Van Gool, Radu Timofte.*<br>
ECCV 2020. [[PDF](http://de.arxiv.org/abs/2006.14200)] [[Github](https://github.com/andreas128/SRFlow)]

**F2GAN: Fusing-and-Filling GAN for Few-shot Image Generation.**<br>
*Yan Hong, Li Niu, Jianfu Zhang, Weijie Zhao, Chen Fu, Liqing Zhang.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2008.01999)]

**Recurrent Feature Reasoning for Image Inpainting.**<br>
*Jingyuan Li, Ning Wang, Lefei Zhang, Bo Du, Dacheng Tao.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2008.03737)] [[GitHub](https://github.com/jingyuanli001/RFR-Inpainting)]

**ESRGAN+: Further Improving Enhanced Super-Resolution Generative Adversarial Network.**<br>
*Nathanaël Carraz Rakotonirina, Andry Rasoanaivo.*<br>
ICASSP 2020. [[PDF](https://arxiv.org/abs/2001.08073)] [[GitHub](https://github.com/ncarraz/ESRGANplus)]

**Rethinking Image Deraining via Rain Streaks and Vapors.**<br>
*Yinglong Wang, Yibing Song, Chao Ma, Bing Zeng.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.00823)]

**Transmission Map and Atmospheric Light Guided Iterative Updater Network for Single Image Dehazing.**<br>
*Aupendu Kar, Sobhan Kanti Dhara, Debashis Sen, Prabir Kumar Biswas.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.01701)] [[Project](https://aupendu.github.io/iterative-dehaze)]

**Implicit Euler ODE Networks for Single-Image Dehazing.**<br>
*Jiawei Shen, Zhuoyan Li, Lei Yu, Gui-Song Xia, Wen Yang.*<br>
CVPRW 2020. [[PDF](https://arxiv.org/abs/2007.06443)] [[Project](https://github.com/Jiawei-Shen)]

**Wavelet-Based Dual-Branch Network for Image Demoireing.**<br>
*Lin Liu, Jianzhuang Liu, Shanxin Yuan, Gregory Slabaugh, Ales Leonardis, Wengang Zhou, Qi Tian.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.07173)]

**Exploring Multi-Scale Feature Propagation and Communication for Image Super Resolution.**<br>
*Ruicheng Feng, Weipeng Guan, Yu qiao, Chao Dong.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.00239)]

**Deep Photo Cropper and Enhancer.**<br>
*Aaron Ott, Amir Mazaheri, Niels D. Lobo, Mubarak Shah.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.00634)]

**DCSFN: Deep Cross-scale Fusion Network for Single Image Rain Removal.**<br>
*Cong Wang, Xiaoying Xing, Zhixun Su, Junyang Chen.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2008.00767)] [[Github](https://supercong94.wixsite.com/supercong94)]

**Exploring Image Enhancement for Salient Object Detection in Low Light Images.**<br>
*Xin Xu, Shiqin Wang, Zheng Wang, Xiaolong Zhang, Ruimin Hu.*<br>
ACM Transactions on Multimedia Computing, Communications, and Applications 2020. [[PDF](https://arxiv.org/abs/2007.16124)]

**Cross-Scale Internal Graph Neural Network for Image Super-Resolution.**<br>
*Shangchen Zhou, Jiawei Zhang, Wangmeng Zuo, Chen Change Loy.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.16673)]

**Polarized Reflection Removal with Perfect Alignment in the Wild.**<br>
*Chenyang Lei, Xuhua Huang, Mengdi Zhang, Qiong Yan, [Wenxiu Sun](http://wenxiusun.com/), and [Qifeng Chen](https://cqf.io/publication).*</br>
CVPR 2020. [[PDF](http://openaccess.thecvf.com/content_CVPR_2020/papers/Lei_Polarized_Reflection_Removal_With_Perfect_Alignment_in_the_Wild_CVPR_2020_paper.pdf)] [[Project](https://leichenyang.weebly.com/project-polarized.html)] [[Github](https://github.com/ChenyangLEI/CVPR2020-Polarized-Reflection-Removal-with-Perfect-Alignment)]

**MuCAN: Multi-Correspondence Aggregation Network for Video Super-Resolution.**<br>
*Wenbo Li, Xin Tao, Taian Guo, Lu Qi, Jiangbo Lu, Jiaya Jia.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.11803)]

**PIPAL: a Large-Scale Image Quality Assessment Dataset for Perceptual Image Restoration.**<br>
*Jinjin Gu, Haoming Cai, Haoyu Chen, Xiaoxing Ye, Jimmy Ren, Chao Dong.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.12142)]

**Guided Deep Decoder: Unsupervised Image Pair Fusion.**<br>
*Tatsumi Uezato, Danfeng Hong, Naoto Yokoya, Wei He.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.11766)]

**Learning Disentangled Feature Representation for Hybrid-distorted Image Restoration.**<br>
*Xin Li, Xin Jin, Jianxin Lin, Tao Yu, Sen Liu, Yaojun Wu, Wei Zhou, Zhibo Chen.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.11430)]

**Texture Hallucination for Large-Factor Painting Super-Resolution.**<br>
*Yulun Zhang, Zhifei Zhang, Stephen DiVerdi, Zhaowen Wang, Jose Echevarria, Yun Fu.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/1912.00515)] [[Github](http://yulunzhang.com/papers/PaintingSR_supp_arXiv.pdf)]

**Microscopy Image Restoration with Deep Wiener-Kolmogorov filters.**<br>
*Valeriya Pronina, Filippos Kokkinos, Dmitry V. Dylov, Stamatios Lefkimmiatis.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/1911.10989)]

**Fully Trainable and Interpretable Non-Local Sparse Models for Image Restoration.**<br>
*Bruno Lecouat, Jean Ponce, Julien Mairal.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/1912.02456)]

**Learning Enriched Features for Real Image Restoration and Enhancement.**<br>
*Syed Waqas Zamir, Aditya Arora, Salman Khan, Munawar Hayat, Fahad Shahbaz Khan, Ming-Hsuan Yang, Ling Shao.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2003.06792)] [[Github](https://github.com/swz30/MIRNet)]

**Learning Disentangled Feature Representation for Hybrid-distorted Image Restoration.**<br>
*Xin Li, Xin Jin, Jianxin Lin, Sen Liu, Yaojun Wu, Tao Yu, Wei Zhou, [Zhibo Chen](http://staff.ustc.edu.cn/~chenzhibo/publi.html).*<br>
ECCV 2020.

**LIRA: Lifelong Image Restoration from Unknown Blended Distortions.**<br>
*Jianzhao Liu, Jianxin Lin, Xin Li, Wei Zhou, Sen Liu, Zhibo Chen.*<br>
ECCV 2020.

**Journey Towards Tiny Perceptual Super-Resolution.**<br>
*Royson Lee, Łukasz Dudziak, Mohamed Abdelfattah, Stylianos I. Venieris, Hyeji Kim, Hongkai Wen, Nicholas D. Lane.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.04356)]

**Lightweight Image Super-Resolution with Enhanced CNN.**<br>
*Chunwei Tian, Ruibin Zhuge, Zhihao Wu, Yong Xu, Wangmeng Zuo, Chen Chen, Chia-Wen Li.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.04344)]

**HDR-GAN: HDR Image Reconstruction from Multi-Exposed LDR Images with Large Motions.**<br>
*Yuzhen Niu, Jianbin Wu, Wenxi Liu, Wenzhong Guo, Rynson W.H. Lau.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.01628)]

**End-to-end Interpretable Learning of Non-blind Image Deblurring.**<br>
*Thomas Eboli, Jian Sun, Jean Ponce.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.01769)]

**LF-InterNet: Spatial-Angular Interaction for Light Field Image Super-Resolution.**<br>
*Yingqian Wang, Longguang Wang, Jungang Yang, Wei An, Jingyi Yu, Yulan Guo.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.07849)] [[Github](https://github.com/YingqianWang/LF-InterNet)]

**Invertible Image Rescaling.**<br>
*Mingqing Xiao, Shuxin Zheng, Chang Liu, Yaolong Wang, Di He, Guolin Ke, Jiang Bian, Zhouchen Lin, Tie-Yan Liu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2005.05650)] [[Github](https://github.com/pkuxmq/Invertible-Image-Rescaling)]

**You Only Look Yourself: Unsupervised and Untrained Single Image Dehazing Neural Network.**<br>
*Boyun Li, Yuanbiao Gou, Shuhang Gu, Jerry Zitao Liu, Joey Tianyi Zhou, Xi Peng.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.16829)]

**Cross-Scale Internal Graph Neural Network for Image Super-Resolution.**<br>
*Shangchen Zhou, Jiawei Zhang, Wangmeng Zuo, Chen Change Loy.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.16673)]

**End-to-End Differentiable Learning to HDR Image Synthesis for Multi-exposure Images.**<br>
*Jung Hee Kim, Siyeong Lee, Soyeon Jo, Suk-Ju Kang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.15833)]

**Hierarchical Patch VAE-GAN (HP-VAE-GAN): Generating Diverse Videos from a Single Sample.**<br>
*[Shir Gur](http://www.gurshir.com/), [Sagie Benaim](https://sagiebenaim.github.io/), [Lior Wolf](http://www.cs.tau.ac.il/~wolf/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.12226)] [[Project](https://shirgur.github.io/hp-vae-gan/)] [[Github](https://github.com/shirgur/hp-vae-gan)]

**Sigma-VAE: Simple and Effective VAE Training with Calibrated Decoders.**<br>
*[Oleh Rybkin](https://www.seas.upenn.edu/~oleh/), [Kostas Daniilidis](https://www.cis.upenn.edu/~kostas/), [Sergey Levine](https://people.eecs.berkeley.edu/~svlevine/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.13202)] [[Project](https://orybkin.github.io/sigma-vae/)] [[Github](https://github.com/orybkin/sigma-vae)]

**SRFlow: Learning the Super-Resolution Space with Normalizing Flow.**<br>
*Andreas Lugmayr, Martin Danelljan, Luc Van Gool, Radu Timofte.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.14200)]

**Burst Photography for Learning to Enhance Extremely Dark Images.**<br>
*Ahmet Serdar Karadeniz, Erkut Erdem, Aykut Erdem.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.09845)]

**Structured and Localized Image Restoration.**<br>
*Thomas Eboli, Alex Nowak-Vila, Jian Sun, Francis Bach, Jean Ponce, Alessandro Rudi.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.09261)]

**USRNet: Deep Unfolding Network for Image Super-Resolution.**<br>
*[Kai Zhang](https://cszn.github.io/), Luc Van Gool, Radu Timofte.*<br>
CVPR 2020. [[PDF](https://arxiv.org/pdf/2003.10428.pdf)] [[Github](https://github.com/cszn/USRNet)]

**Learning to Incorporate Structure Knowledge for Image Inpainting.**<br>
*Jie Yang, Zhiquan Qi, Yong Shi.*<br>
AAAI 2020. [[PDF](https://www.researchgate.net/publication/338984531_Learning_to_Incorporate_Structure_Knowledge_for_Image_Inpainting)] [[Github](https://github.com/YoungGod/sturcture-inpainting)]

**Single Image Reflection Removal through Cascaded Refinement.**<br>
*Chao Li, Yixiao Yang, Kun He, Stephen Lin, John E. Hopcroft.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/1911.06634)]

**Single Image Deraining Using Time-lapse Data.**<br>
*Jaehoon Cho, [Seungryong Kim](https://seungryong.github.io/), Dongbo Min, and Kwanghoon Sohn.*<br>
IEEE Trans. on Image Processing (TIP) 2020. [[PDF](https://seungryong.github.io/publication/derain_TIP2020.pdf)]

**GAN-Based Facial Attractiveness Enhancement.**<br>
*Yuhongze Zhou, Qinjie Xiao.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.02766)]

**PULSE: Self-Supervised Photo Upsampling via Latent Space Exploration of Generative Models.**<br>
*Sachit Menon, Alexandru Damian, Shijia Hu, Nikhil Ravi, Cynthia Rudin.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.03808)] [[Github](https://github.com/adamian98/pulse)]

**DeepUPE: Underexposed Photo Enhancement Using Deep Illumination Estimation.**<br>
*Ruixing Wang, Qing Zhang, Chi-Wing Fu, Xiaoyong Shen, Wei-Shi Zheng, Jiaya Jia.*<br>
CVPR 2019. [[PDF](http://jiaya.me/papers/photoenhance_cvpr19.pdf)] [[Github](https://github.com/luppx/DeepUPE)]

**Image Super-Resolution with Cross-Scale Non-Local Attention and Exhaustive Self-Exemplars Mining.**<br>
*Yiqun Mei, Yuchen Fan, Yuqian Zhou, Lichao Huang, Thomas S. Huang, and Humphrey Shi.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2006.01424)] [[Github](https://github.com/SHI-Labs/Cross-Scale-Non-Local-Attention)]

**Single Image HDR Reconstruction Using a CNN with Masked Features and Perceptual Loss.**<br>
*Marcel Santana Santos, Tsang Ing Ren, Nima Khademi Kalantari.*<br>
SIGGRAPH 2020. [[PDF](http://faculty.cs.tamu.edu/nimak/Papers/SIGGRAPH2020_HDR/files/SIGGRAPH2020Final.pdf)] [[Project](http://faculty.cs.tamu.edu/nimak/Papers/SIGGRAPH2020_HDR/)]

**Pyramid Attention Networks for Image Restoration.**<br>
*[Yiqun Mei](http://yiqunm2.web.illinois.edu/), [Yuchen Fan](https://scholar.google.com/citations?user=BlfdYL0AAAAJ&hl=en), [Yulun Zhang](http://yulunzhang.com/), [Jiahui Yu](https://jiahuiyu.com/), [Yuqian Zhou](https://yzhouas.github.io/), [Ding Liu](https://scholar.google.com/citations?user=PGtHUI0AAAAJ&hl=en), [Yun Fu](http://www1.ece.neu.edu/~yunfu/), [Thomas S. Huang](http://ifp-uiuc.github.io/), [Honghui Shi](https://www.humphreyshi.com/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/pdf/2004.13824.pdf)] [[Github](https://github.com/SHI-Labs/Pyramid-Attention-Networks)]

**Multi-Scale Boosted Dehazing Network with Dense Feature Fusion.**<br>
*Hang Dong, Jinshan Pan, Lei Xiang, Zhe Hu, Xinyi Zhang, Fei Wang, Ming-Hsuan Yang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.13388)] [[Github](https://github.com/BookerDeWitt/MSBDN-DFF)]

**Real Image Denoising with Feature Attention.**<br>
*Saeed Anwar, Nick Barnes.*<br>
ICCV 2019, [[PDF](https://arxiv.org/abs/1904.07396)]

**Deploying Image Deblurring across Mobile Devices: A Perspective of Quality and Latency.**<br>
*Cheng-Ming Chiang, Yu Tseng, Yu-Syuan Xu, Hsien-Kai Kuo, Yi-Min Tsai, Guan-Yu Chen, Koan-Sin Tan, Wei-Ting Wang, Yu-Chieh Lin, Shou-Yao Roy Tseng, Wei-Shiang Lin, Chia-Lin Yu, BY Shen, Kloze Kao, Chia-Ming Cheng, Hung-Jen Chen.*<br>
CVPR 2020 Workshop NTIRE. [[PDF](https://arxiv.org/abs/2004.12599)]

**Learning to Autofocus.**<br>
*Charles Herrmann, Richard Strong Bowen, Neal Wadwha, Rahul Garg, Qirui He, Jonathan T. Barron, Ramin Zabih.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.12260)]

**Conditional Variational Image Deraining.**<br>
*Ying-Jun Du, Jun Xu, Xian-Tong Zhen, Ming-Ming Cheng, Ling Shao.*<br>
TIP 2020. [[PDF](https://arxiv.org/abs/2004.11373)]

**A Review of an Old Dilemma: Demosaicking First, or Denoising First?**<br>
*Qiyu Jin, Gabriele Facciolo, Jean-Michel Morel.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.11577)]

**Quantization Guided JPEG Artifact Correction.**<br>
*Max Ehrlich, Ser-Nam Lim, Larry Davis, Abhinav Shrivastava.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.09320)]

**Unified Dynamic Convolutional Network for Super-Resolution with Variational Degradations.**<br>
*Yu-Syuan Xu, Shou-Yao Roy Tseng, Yu Tseng, Hsien-Kai Kuo, Yi-Min Tsai.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.06965)]

**Path-Restore: Learning Network Path Selection for Image Restoration.**<br>
*Ke Yu, Xintao Wang, Chao Dong, Xiaoou Tang, Chen Change Loy.*<br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1904.10343)] [[Project](https://yuke93.github.io/Path-Restore/)]

**ADEFAN: Divergence-Based Adaptive Extreme Video Completion.**<br>
*[Majed El Helou](http://majedelhelou.github.io/), Ruofan Zhou, Frank Schmutz, Fabrice Guibert, Sabine Süsstrunk.*<br>
ICASSP 2020. [[PDF](https://arxiv.org/abs/2004.06409)] [[Github](https://github.com/majedelhelou/ADEFAN)] [[Data](https://ieee-dataport.org/documents/extreme-video-completion-dataset)]

**Bringing Old Photos Back to Life.**<br>
*[Ziyu Wan](http://raywzy.com), Bo Zhang, [Dongdong Chen](http://www.dongdongchen.bid/), Pan Zhang, Dong Chen, Jing Liao, Fan Wen.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.09484)] [[Project](http://raywzy.com/Old_Photo/)]

**A General Decoupled Learning Framework for Parameterized Image Operators.**<br>
*Qingnan Fan, Dongdong Chen, Lu Yuan, Gang Hua, Nenghai Yu, Baoquan Chen.*<br>
TPAMI 2019. [[PDF](https://arxiv.org/abs/1907.05852.pdf)] 

**Decouple Learning for Parameterized Image Operators.**<br>
*Qingnan Fan, Dongdong Chen, Lu Yuan, Gang Hua, Nenghai Yu, Baoquan Chen.*<br>
ECCV 2018. [[PDF](http://www.dongdongchen.bid/pubs/colorization_sig18.pdf)] [[Github](https://github.com/msracver/Deep-Exemplar-based-Colorization)]

**Gated Context Aggregation Network for Image Dehazing and Deraining.**<br>
*Dongdong Chen, Mingming He, Qingnan Fan, Jing Liao, Liheng Zhang, Dongdong Hou, Lu Yuan, Gang Hua.*<br>
WACV 2019. [[PDF](https://arxiv.org/pdf/1811.08747.pdf)] [[Github](https://github.com/cddlyf/GCANet)]

**Spatially-Attentive Patch-Hierarchical Network for Adaptive Motion Deblurring.**<br>
*Maitreya Suin, Kuldeep Purohit, A. N. Rajagopalan.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.05343)]

**Learning Event-Based Motion Deblurring.**<br>
*Zhe Jiang, Yu Zhang, Dongqing Zou, Jimmy Ren, Jiancheng Lv, Yebin Liu.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.05794)]

**Structure-Preserving Super Resolution with Gradient Guidance.**<br>
*Cheng Ma, Yongming Rao, Yean Cheng, Ce Chen, Jiwen Lu, Jie Zhou.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.13081)] [[Github](https://github.com/Maclory/SPSR)]

**DeepSEE: Deep Disentangled Semantic Explorative Extreme Super-Resolution.**<br>
*Marcel Christoph Bühler, Andrés Romero, Radu Timofte.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.04433)] [[Project](https://mcbuehler.github.io/DeepSEE/)] [[Github](github.com/mcbuehler/DeepSEE)]

**Deblurring using Analysis-Synthesis Networks Pair.**<br>
*Adam Kaufman, Raanan Fattal.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.02956)]

**Self-Supervised Scene De-occlusion.**<br>
*[Xiaohang Zhan](https://xiaohangzhan.github.io/), [Xingang Pan](https://xingangpan.github.io/), Bo Dai, Ziwei Liu, Dahua Lin, Chen Change Loy.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.02788)] [[Project](https://xiaohangzhan.github.io/projects/deocclusion/)] [[Github](https://github.com/XiaohangZhan/deocclusion/)]

**Deep White-Balance Editing.**<br>
*[Mahmoud Afifi](https://sites.google.com/view/mafifi), [Michael S. Brown](http://www.cse.yorku.ca/~mbrown/).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.01354)]

**What Else Can Fool Deep Learning? Addressing Color Constancy Errors on Deep Neural Network Performance.**<br>
*[Mahmoud Afifi](http://www.cse.yorku.ca/~mafifi/), Michael S. Brown.*<br>
ICCV 2019. [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Afifi_What_Else_Can_Fool_Deep_Learning_Addressing_Color_Constancy_Errors_ICCV_2019_paper.pdf)] [[Project](http://cvil.eecs.yorku.ca/projects/public_html/wb_emulation/index.html)] [[Github](https://github.com/mahmoudnafifi/WB_color_augmenter)]

**When Color Constancy Goes Wrong: Correcting Improperly White-Balanced Images.**<br>
*Mahmoud Afifi, Brian Price, Scott Cohen, and Michael S. Brown.*<br>
CVPR 2019. [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/papers/Afifi_When_Color_Constancy_Goes_Wrong_Correcting_Improperly_White-Balanced_Images_CVPR_2019_paper.pdf)] [[Github](https://github.com/mahmoudnafifi/WB_sRGB)] 

**Rethinking Data Augmentation for Image Super-resolution: A Comprehensive Analysis and a New Strategy.**<br>
*Jaejun Yoo, Namhyuk Ahn, Kyung-Ah Sohn.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.00448)] [[Github](https://github.com/clovaai/cutblur)]

**Learning to See Through Obstructions.**<br>
*Yu-Lun Liu, Wei-Sheng Lai, Ming-Hsuan Yang, Yung-Yu Chuang.*<br>
CVPR 2020. [[PDF](https://www.cmlab.csie.ntu.edu.tw/~yulunliu/ObstructionRemoval_/02197.pdf)] [[Github](https://github.com/alex04072000/ObstructionRemoval)] [[Project](https://www.cmlab.csie.ntu.edu.tw/~yulunliu/ObstructionRemoval)]

**Learning to See Through Obstructions with Layered Decomposition.**<br>
*Yu-Lun Liu, Wei-Sheng Lai, Ming-Hsuan Yang, Yung-Yu Chuang, Jia-Bin Huang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.04902)]

**DeepLPF: Deep Local Parametric Filters for Image Enhancement.**<br>
*Sean Moran, Pierre Marza, Steven McDonagh, Sarah Parisot, Gregory Slabaugh.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.13985)]

**Replacing Mobile Camera ISP with a Single Deep Learning Model.**<br>
*Andrey Ignatov, Luc Van Gool, Radu Timofte.* <br>
arxiv, 13 Feb 2020. [[PDF](https://arxiv.org/abs/2002.05509)] [[Github](https://github.com/aiff22/PyNET)] [[Project](http://people.ee.ethz.ch/~ihnatova/pynet.html)]

**EEMEFN: Low-Light Image Enhancement via Edge-Enhanced Multi-Exposure Fusion Network.**<br>
*Minfeng Zhu, Pingbo Pan, Wei Chen, Yi Yang.*<br>
AAAI 2020. [[PDF](http://www.cad.zju.edu.cn/home/vagblog/VAG_Work/EEMEFN-Low%20Light%20Image%20Enhancement%20via%20Edge%20Enhanced%20MultiExposure%20Fusion%20Network.pdf)] [[Project](https://zjuvag.org/publications/eemefn/)]

### Challenge and Survey

**NTIRE 2020 Challenge on Perceptual Extreme Super-Resolution: Methods and Results.**<br>
*Kai Zhang, Shuhang Gu, Radu Timofte, et al..*<br>
NTIRE 2020 [Challenge](https://data.vision.ee.ethz.ch/cvl/ntire20/). [[PDF](https://arxiv.org/abs/2005.01056)]

**NTIRE 2020 Challenge on Image and Video Deblurring.**<br>
*[Seungjun Nah](https://seungjunnah.github.io/), [Sanghyun Son](https://cv.snu.ac.kr/sanghyun_son/sanghyun_son_cv.pdf), [Radu Timofte](https://vision.ee.ethz.ch/~timofter/), Kyoung Mu Lee.*<br>
CVPR 2020 Workshop: New Trends in Image Restoration and Enhancement. [[PDF](https://arxiv.org/abs/2005.01244)]

**NTIRE 2020 Challenge on Image Demoireing: Methods and Results.**<br>
*Shanxin Yuan, Radu Timofte et al..*<br>
NTIRE 2020. [[PDF](https://arxiv.org/abs/2005.03155)]

**AIM 2019 Challenge on Video Temporal Super-Resolution: Methods and Results.**<br>
*Seungjun Nah, Sanghyun Son, Radu Timofte, Kyoung Mu Lee.*<br>
ICCV 2019 Workshop: Advances in Image Manipulation. [[](https://arxiv.org/abs/2005.01233)]

## Diving Deep into Image Synthesis


### Invertible Neural Network (Flow-based Generative Model)

[[Normalizing Flows](https://paperswithcode.com/method/normalizing-flows)]

**SRFlow: Learning the Super-Resolution Space with Normalizing Flow.**<br>
*Andreas Lugmayr, Martin Danelljan, Luc Van Gool, Radu Timofte.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2006.14200)] [[Github](http://git.io/SRFlow)]

**Learning Likelihoods with Conditional Normalizing Flows.**<br>
*Christina Winkler, Daniel Worrall, Emiel Hoogeboom, Max Welling.*<br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1912.00042)]

**RealNVP: Density Estimation Using Real NVP.**<br>
*Laurent Dinh, Jascha Sohl-Dickstein, Samy Bengio.*<br>
ICLR 2017. [[PDF](https://arxiv.org/abs/1605.08803)]

**Training Normalizing Flows with the Information Bottleneck for Competitive Generative Classification.**<br>
*Lynton Ardizzone, Radek Mackowiak, Carsten Rother, Ullrich Köthe.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2001.06448)] [[Github](https://github.com/VLL-HD/exact_information_bottleneck)]

**Guided Image Generation with Conditional Invertible Neural Networks.**<br>
*Lynton Ardizzone, Carsten Lüth, Jakob Kruse, Carsten Rother, Ullrich Köthe.*<br>
arxiv 2019. [[https://arxiv.org/abs/1907.02392]()] [[Github](https://github.com/VLL-HD/conditional_invertible_neural_networks)] [[Supplement](https://drive.google.com/file/d/1_OoiIGhLeVJGaZFeBt0OWOq8ZCtiI7li)]

**Invertible Residual Networks.**<br>
*Jens Behrmann, Will Grathwohl, Ricky T. Q. Chen, David Duvenaud, Jörn-Henrik Jacobsen.*<br>
arxiv 2018. [[PDF](https://arxiv.org/abs/1811.00995)]

**Excessive Invariance Causes Adversarial Vulnerability.**<br>
*Jörn-Henrik Jacobsen, Jens Behrmann, Richard Zemel, Matthias Bethge.*<br>
arxiv 2018. [[PDF](https://arxiv.org/abs/1811.00401)]

**Analyzing inverse problems with invertible neural networks.**<br>
*Lynton Ardizzone, Jakob Kruse, Sebastian Wirkert, Daniel Rahner, Eric W. Pellegrini, Ralf S. Klessen, Lena Maier-Hein, Carsten Rother, Ullrich Köthe.*<br>
arxiv 2018. [[PDF](https://arxiv.org/abs/1808.04730)] [[Github](https://github.com/VLL-HD/analyzing_inverse_problems)]

**Flow-GAN: Combining Maximum Likelihood and Adversarial Learning in Generative Models.**<br>
*Aditya Grover, Manik Dhar, Stefano Ermon.*<br>
AAAI 2018. [[PDF](https://arxiv.org/abs/1705.08868)]

**NICE: Non-linear Independent Components Estimation.**<br>
*Laurent Dinh, David Krueger, Yoshua Bengio.*<br>
arxiv 2014. [[PDF](https://arxiv.org/abs/1410.8516)] [[Github](https://github.com/paultsw/nice_pytorch)]

### StyleGAN-Based Method

[[awesome-pretrained-stylegan2](https://github.com/justinpinkney/awesome-pretrained-stylegan2)]

**StyleGAN2: Analyzing and Improving the Image Quality of StyleGAN.**<br>
*[Tero Karras](https://research.nvidia.com/person/tero-karras), [Samuli Laine](https://research.nvidia.com/person/samuli-laine), [Miika Aittala](https://research.nvidia.com/person/miika-aittala), Janne Hellsten, Jaakko Lehtinen, [Timo Aila](https://research.nvidia.com/person/timo-aila).*<br>
arxiv, 3 Dec 2019.
[[PDF](https://arxiv.org/abs/1912.04958)] 
[[Offical TF](https://github.com/NVlabs/stylegan2)]
[[PyTorch](https://github.com/rosinality/stylegan2-pytorch)]
[[Unoffical Tensorflow 2.0](https://github.com/manicman1999/StyleGAN2-Tensorflow-2.0)]

**A Style-Based Generator Architecture for Generative Adversarial Networks.**<br>
*Tero Karras, Samuli Laine, Timo Aila.*<br>
CVPR 2019. 
[[Paper](https://arxiv.org/abs/1812.04948)]
[[Video](https://youtu.be/kSLJriaOumA)]
[[Code](https://github.com/NVlabs/stylegan)]
[[FFHQ](https://github.com/NVlabs/ffhq-dataset)]

**Style Generator Inversion for Image Enhancement and Animation.**<br>
*[Aviv Gabbay](https://www.cse.huji.ac.il/~avivga/), [Yedid Hoshen](https://www.cse.huji.ac.il/~ydidh/).*<br>
arxiv, 5 Jun 2019. [[PDF](https://arxiv.org/abs/1906.11880)] [[Project](http://www.vision.huji.ac.il/style-image-prior)] [[Github](https://github.com/avivga/style-image-prior)]

**SEAN: Image Synthesis with Semantic Region-Adaptive Normalization.**<br>
*eihao Zhu, Rameen Abdal, Yipeng Qin, Peter Wonka.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1911.12861)]

**SMIS: Semantically Multi-modal Image Synthesis.**<br> 
*[Zhen Zhu](https://zzhu.vision/), Zhiliang Xu, Ansheng You, [Xiang Bai](http://cloud.eic.hust.edu.cn:8071/~xbai/).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.12697)] [[Project](http://seanseattle.github.io/SMIS)] [[Github](https://github.com/Seanseattle/SMIS)]

**Hierarchical Style-based Networks for Motion Synthesis.**<br>
*Jingwei Xu, Huazhe Xu, Bingbing Ni, Xiaokang Yang, Xiaolong Wang, Trevor Darrell.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.10162)] [[Github](https://sites.google.com/view/hsnms)]

### Single-Image Training 

**ConSinGAN: Improved Techniques for Training Single-Image GANs.**<br>
*Tobias Hinz, Matthew Fisher, Oliver Wang, Stefan Wermter.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2003.11512)]  [[Github](https://github.com/tohinz/ConSinGAN)]

**MSG-GAN: Multi-Scale Gradient GAN for Stable Image Synthesis.**<br>
*Animesh Karnewar, Oliver Wang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1903.06048)] [[Github](https://github.com/akanimax/msg-stylegan-tf)]

**InGAN: Capturing and Retargeting the DNA of a Natural Image.**<br>
ICCV 2019. [[PDF](http://www.wisdom.weizmann.ac.il/~vision/ingan/resources/ingan.pdf)] [[Project](http://www.wisdom.weizmann.ac.il/~vision/ingan/)] [[Github](https://github.com/assafshocher/InGAN)] 

**SinGAN: Learning a Generative Model from a Single Natural Image.**<br>
*Tamar Rott Shaham, Tali Dekel, Tomer Michaeli.*<br>
ICCV 2019 (Best Paper). 
[[PDF](https://arxiv.org/abs/1905.01164)] [[UnOfficial](github.com/FriedRonaldo/SinGAN)] [[Official](github.com/tamarott/SinGAN)]

**TuiGAN: Learning Versatile Image-to-Image Translation with Two Unpaired Images.**<br>
*Jianxin Lin, Yingxue Pang, Yingce Xia, Zhibo Chen, Jiebo Luo.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.04634)]

### Misc

**Distribution Augmentation for Generative Modeling.**<br>
*Heewoo Jun, Rewon Child, Mark Chen, John Schulman, Aditya Ramesh, Alec Radford, Ilya Sutskever.*<br>
ICML 2020. [[PDF](https://proceedings.icml.cc/static/paper_files/icml/2020/6095-Paper.pdf)] [[Github](https://github.com/openai/distribution_augmentation)]

**Generative Pretraining from Pixels.**<br>
*Mark Chen, Alec Radford, Rewon Child, Jeff Wu, Heewoo Jun, Prafulla Dhariwal, David Luan, Ilya Sutskever.*<br>
ICML 2020. [[PDF](https://cdn.openai.com/papers/Generative_Pretraining_from_Pixels_V2.pdf)] [[Github](https://github.com/openai/image-gpt)]

**NVAE: A Deep Hierarchical Variational Autoencoder.**<br>
*[Arash Vahdat](http://latentspace.cc/arash_vahdat/), [Jan Kautz](http://jankautz.com/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.03898)] [[Github](https://github.com/NVlabs/NVAE)]

**A Lip Sync Expert Is All You Need for Speech to Lip Generation In The Wild.**<br>
*K R Prajwal, Rudrabha Mukhopadhyay, Vinay Namboodiri, C V Jawahar.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2008.10010)] [[Github](http://github.com/Rudrabha/Wav2Lip)] [[Project](https://bhaasha.iiit.ac.in/lipsync/)] [[Demo](http://bhaasha.iiit.ac.in/lipsync)]

**Real-Time Selfie Video Stabilization.**<br>
*Jiyang Yu, Ravi Ramamoorthi, Keli Cheng, Michel Sarkis, Ning Bi.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.02007)]

**SketchPatch: Sketch Stylization via Seamless Patch-level Synthesis.**<br>
*Noa Fish, Lilach Perry, Amit Bermano, Daniel Cohen-Or.*<br>
SIGGRAPH Asia 2020. [[PDF](https://arxiv.org/abs/2009.02216)]

**Towards Unsupervised Learning of Generative Models for 3D Controllable Image Synthesis.**<br>
*Yiyi Liao, Katja Schwarz, Lars Mescheder, Andreas Geiger.*<br>
CVPR 2020. [[PDF](https://avg.is.tuebingen.mpg.de/publications/liao2020cvpr)] [[Github](https://github.com/autonomousvision/controllable_image_synthesis)]

**Neural Crossbreed: Neural Based Image Metamorphosis.**<br>
*Sanghun Park, Kwanggyoon Seo, Junyong Noh.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.00905)]

**Generating Handwriting via Decouple Style Descriptors.**<br>
*Atsunobu Kotani, Stefanie Tellex, James Tompkin.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.11354)]

**Person-in-Context Synthesis with Compositional Structural Space.**<br>
*Weidong Yin, Ziwei Liu, Leonid Sigal.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.12679)]

**GIF: Generative Interpretable Faces.**<br>
*Partha Ghosh, Pravir Singh Gupta, Roy Uziel, Anurag Ranjan, Michael Black, Timo Bolkart.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.00149)] [[Github](https://github.com/ParthaEth/GIF)]

**SPAN: Spatial Pyramid Attention Network forImage Manipulation Localization.**<br>
*Xuefeng Hu, Zhihan Zhang, Zhenye Jiang, Syomantak Chaudhuri, Zhenheng Yang, Ram Nevatia.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2009.00726)]

**OKGAN: Online Kernel based Generative Adversarial Networks.**<br>
*Yeojoon Youn, Neil Thistlethwaite, Sang Keun Choe, Jacob Abernethy.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.11432v1)]

**Anime-to-Real Clothing: Cosplay Costume Generation via Image-to-Image Translation.**<br>
*Koya Tango, [Marie Katsurai](http://book.mkats.net/), Hayato Maki, Ryosuke Goto.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.11479)]

**AgingMapGAN (AMGAN): High-Resolution Controllable Face Aging with Spatially-Aware Conditional GANs.**<br>
*Julien Despois, Frederic Flament, Matthieu Perrot.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.10960)] [[Project](https://despoisj.github.io/AgingMapGAN/)]

**DAGAN: Dual Attention GANs for Semantic Image Synthesis.**<br>
*Hao Tang, Song Bai, Nicu Sebe.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2008.13024)] [[Github](https://github.com/Ha0Tang/DAGAN)]

**DeepFacePencil: Creating Face Images from Freehand Sketches.**<br>
*Yuhang Li, Xuejin Chen, Binxin Yang, Zihan Chen, Zhihua Cheng, Zheng-Jun Zha.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2008.13343)]

**Generative Hierarchical Features from Synthesizing Images.**<br>
*Yinghao Xu, Yujun Shen, Jiapeng Zhu, Ceyuan Yang, Bolei Zhou.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.10379)]

**A Lip Sync Expert Is All You Need for Speech to Lip Generation In The Wild.**<br>
*K R Prajwal, Rudrabha Mukhopadhyay, Vinay Namboodiri, C V Jawahar.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2008.10010)] [[Github](http://github.com/Rudrabha/Wav2Lip)] [[Project](http://cvit.iiit.ac.in/research/projects/cvit-projects/a-lip-sync-expert-is-all-you-need-for-speech-to-lip-generation-in-the-wild)]

**One-Shot Domain Adaptation For Face Generation.**<br>
*Chao Yang, Ser-Nam Lim.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.12869)]

**Disentangled Image Generation Through Structured Noise Injection.**<br>
*Yazeed Alharbi, Peter Wonka.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.12411)]

**FFWM: Learning Flow-based Feature Warping for Face Frontalization with Illumination Inconsistent Supervision.**<br>
*Yuxiang Wei, Ming Liu, Haolin Wang, Ruifeng Zhu, Guosheng Hu, Wangmeng Zuo.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.06843)] [[Github](https://github.com/csyxwei/FFWM)]

**Semantic Hierarchy Emerges in Deep Generative Representations for Scene Synthesis.**<br>
*Ceyuan Yang, Yujun Shen, Bolei Zhou.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/1911.09267)]

**F2GAN: Fusing-and-Filling GAN for Few-shot Image Generation.**<br>
*Yan Hong, Li Niu, Jianfu Zhang, Weijie Zhao, Chen Fu, Liqing Zhang.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2008.01999)]

**Generative Adversarial Networks for Image and Video Synthesis: Algorithms and Applications.**<br>
*Ming-Yu Liu, Xun Huang, Jiahui Yu, Ting-Chun Wang, Arun Mallya.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.02793)]

**Image Generation for Efficient Neural Network Training in Autonomous Drone Racing.**<br>
*Theo Morales, Andriy Sarabakha, Erdal Kayacan.*<br>
IJCNN 2020. [[PDF](https://arxiv.org/abs/2008.02596)]

**Graph Structure of Neural Networks.**<br>
*Jiaxuan You, Jure Leskovec, Kaiming He, Saining Xie.*<br>
ICML 2020. [[PDF](https://arxiv.org/abs/2007.06559)]

**Blending Generative Adversarial Image Synthesis with Rendering for Computer Graphics.**<br>
*Ekim Yurtsever, Dongfang Yang, Ibrahim Mert Koc, Keith A. Redmill.*<br>
arixv 2020. [[PDF](https://arxiv.org/abs/2007.15820)]

**A Unified Framework of Surrogate Loss by Refactoring and Interpolation.**<br>
*Lanlan Liu, Mingzhe Wang, Jia Deng.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.13870)] [[Github](https://github.com/princeton-vl/uniloss)]

**Style is a Distribution of Features.**<br>
*Eddie Huang, Sahil Gupta.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.13010)]

**MSG-GAN: Multi-Scale Gradients for Generative Adversarial Networks.**<br>
*Animesh Karnewar, Oliver Wang.*<br>
CVPR 2020.[[PDF](https://arxiv.org/abs/1903.06048)] [[Github](https://github.com/akanimax/msg-stylegan-tf)]

**NestedVAE: Isolating Common Factors via Weak Supervision.**<br>
*Matthew J. Vowels, Necati Cihan Camgoz, Richard Bowden.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2002.11576)]

**Sound2Sight: Generating Visual Dynamics from Sound and Context.**<br>
*Anoop Cherian, Moitreya Chatterjee, Narendra Ahuja.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.12130)]

**AE-OT-GAN: Training GANs from Data Specific Latent Distribution.**<br>
*Dongsheng An, Yang Guo, Min Zhang, Xin Qi, Na Lei, Shing-Tung Yau, Xianfeng Gu.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2001.03698)]

**Deep Preset: Blending and Retouching Photos with Color Style Transfer.**<br>
*Man M. Ho, Jinjia Zhou.*<br>
arxiv 2020. [[]PDF(https://arxiv.org/abs/2007.10701)] [[Project](https://github.com/minhmanho/deep_preset)]

**Visual Commonsense Graphs: Reasoning about the Dynamic Context of a Still Image.**<br>
*Jae Sung Park, Chandra Bhagavatula, Roozbeh Mottaghi, Ali Farhadi, Yejin Choi.*<br>
arxiv 2020. [[](https://arxiv.org/abs/2004.10796)] [[Project](http://visualcomet.xyz/)]

**Generative Hierarchical Features from Synthesizing Images.**<br>
*Yinghao Xu, Yujun Shen, Jiapeng Zhu, Ceyuan Yang, Bolei Zhou.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.10379)]

**Foley Music: Learning to Generate Music from Videos.**<br>
*Chuang Gan, Deng Huang, Peihao Chen, Joshua B. Tenenbaum, Antonio Torralba.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.10984)] [[Project](http://foley-music.csail.mit.edu/)]

**Example-Guided Image Synthesis across Arbitrary Scenes using Masked Spatial-Channel Attention and Self-Supervision.**<br>
*Haitian Zheng, Haofu Liao, Lele Chen, Wei Xiong, Tianlang Chen, Jiebo Luo.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2004.10024)]

**High-Fidelity Synthesis with Disentangled Representation.**<br>
*Wonkwang Lee, Donggyun Kim, Seunghoon Hong, Honglak Lee.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2001.04296)]

**House-GAN: Relational Generative Adversarial Networks for Graph-constrained House Layout Generation.**<br>
*Nelson Nauata, Kai-Hung Chang, Chin-Yi Cheng, Greg Mori, Yasutaka Furukawa.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2003.06988)]

**OneGAN: Simultaneous Unsupervised Learning of Conditional Image Generation, Foreground Segmentation, and Fine-Grained Clustering.**<br>
*Yaniv Benny, Lior Wolf.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/1912.13471)]

**Learning Visual Commonsense for Robust Scene Graph Generation.**<br>
*Alireza Zareian, Haoxuan You, Zhecan Wang, Shih-Fu Chang.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2006.09623)]

**Learning Canonical Representations for Scene Graph to Image Generation.**<br>
*Roei Herzig, Amir Bar, Huijuan Xu, Gal Chechik, Trevor Darrell, Amir Globerson.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/1912.07414)]

**GANwriting: Content-Conditioned Generation of Styled Handwritten Word Images.**<br>
*Lei Kang, Pau Riba, Yaxing Wang, Marçal Rusiñol, Alicia Fornés, Mauricio Villegas.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2003.02567)]

**Few-shot Compositional Font Generation with Dual Memory.**<br>
*Junbum Cha, Sanghyuk Chun, Gayoung Lee, Bado Lee, Seonghyeon Kim, Hwalsuk Lee.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2005.10510)] [[Github](https://github.com/clovaai/dmfont)]

**Piggyback GAN: Efficient Lifelong Learning for Image Conditioned Generation.**<br>
*[Mengyao Zhai](http://www.sfu.ca/~mnawhal), Lei Chen, Jiawei He, Megha Nawhal, Frederick Tung, and Greg Mori.*<br>
ECCV 2020. [[PDF](http://www.sfu.ca/~mnawhal/projects/zhai_eccv20.pdf)]

**Sketching Image Gist: Human-Mimetic Hierarchical Scene Graph Generation.**<br>
*[Wenbin Wang](http://www.kennethwong.tech/), Ruiping Wang, Shiguang Shan, Xilin Chen.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.08760)]

**Generating Person Images with Appearance-aware Pose Stylizer.**<br>
*Siyu Huang, Haoyi Xiong, Zhi-Qi Cheng, Qingzhong Wang, Xingran Zhou, Bihan Wen, Jun Huan, Dejing Dou.*<br>
IJCAI 2020. [[PDF](https://arxiv.org/abs/2007.09077)] [[Github](https://github.com/siyuhuang/PoseStylizer)]

**Neural Design Network: Graphic Layout Generation with Constraints.**<br>
*Hsin-Ying Lee, Weilong Yang, Lu Jiang, Madison Le, Irfan Essa, Haifeng Gong, Ming-Hsuan Yang.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/1912.09421)]

**D2D: Learning to Find Good Correspondences for Image Matching and Manipulation.**<br>
*Olivia Wiles, Sebastien Ehrhardt, Andrew Zisserman.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.08480)]

**RetrieveGAN: Image Synthesis via Differentiable Patch Retrieval.**<br>
*Hung-Yu Tseng, Hsin-Ying Lee, Lu Jiang, Ming-Hsuan Yang, Weilong Yang.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.08513)]

**World-Consistent Video-to-Video Synthesis.**<br>
*Arun Mallya, Ting-Chun Wang, Karan Sapra, Ming-Yu Liu.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.08509)]

**DeepSinger: Singing Voice Synthesis with Data Mined From the Web.**<br>
*Yi Ren, Xu Tan, Tao Qin, Jian Luan, Zhou Zhao, Tie-Yan Liu.*<br>
KDD 2020. [[PDF](https://arxiv.org/abs/2007.04590)] [[Project](https://speechresearch.github.io/deepsinger/)]

**Words as Art Materials: Generating Paintings with Sequential GANs.**<br>
*Azmi Can Özgen, Hazım Kemal Ekenel.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.04383)]

**DANet: Dual Adversarial Network: Toward Real-world Noise Removal and Noise Generation.**<br>
*Zongsheng Yue, Qian Zhao, Lei Zhang, Deyu Meng.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.05946)] [[Github](https://github.com/zsyOAOA/DANet)]

**Rethinking Image Inpainting via a Mutual Encoder-Decoder with Feature Equalizations.**<br>
*Hongyu Liu, Bin Jiang, Yibing Song, Wei Huang, Chao Yang.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.06929)]

**NVAE: A Deep Hierarchical Variational Autoencoder.**<br>
*[Arash Vahdat](https://arash-vahdat.github.io), Jan Kautz.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.03898)] [[Github](https://arash-vahdat.github.io/NVAE_arxiv.pdf)]

**Unsupervised Landmark Learning from Unpaired Data.**<br>
*Yinghao Xu, Ceyuan Yang, Ziwei Liu, Bo Dai, Bolei Zhou.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.01053)]

**RELATE: Physically Plausible Multi-Object Scene Synthesis Using Structured Latent Spaces.**<br>
*Sebastien Ehrhardt, Oliver Groth, Aron Monszpart, Martin Engelcke, Ingmar Posner, Niloy Mitra, Andrea Vedaldi.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.01272)]

**High-Resolution Neural Face Swapping for Visual Effects.**<br>
*Jacek Naruniec, Leonhard Helminger, Christopher Schroers, Romann M. Weber.*<br>
Eurographics Symposium on Rendering 2020. [[PDF](https://s3.amazonaws.com/disney-research-data/wp-content/uploads/2020/06/18013325/High-Resolution-Neural-Face-Swapping-for-Visual-Effects.pdf)] [[Project](http://studios.disneyresearch.com/2020/06/29/high-resolution-neural-face-swapping-for-visual-effects/)]

**On Leveraging Pretrained GANs for Limited-Data Generation.**<br>
*Miaoyun Zhao, Yulai Cong and Lawrence Carin.*<br>
ICML 2020. [[PDF](https://arxiv.org/asb/2002.11810)] [[Github](https://github.com/MiaoyunZhao/GANTransferLimitedData)]

**Learning Physical Graph Representations from Visual Scenes.**<br>
*Daniel M. Bear, Chaofei Fan, Damian Mrowca, Yunzhu Li, Seth Alter, Aran Nayebi, Jeremy Schwartz, Li Fei-Fei, Jiajun Wu, Joshua B. Tenenbaum, Daniel L.K. Yamins.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.12373)]

**Learning Canonical Representations for Scene Graph to Image Generation.**<br>
*[Roei Herzig](https://roeiherz.github.io/), [Amir Bar](http://www.amirbar.net/), [Huijuan Xu](https://cs-people.bu.edu/hxu/), [Gal Chechik](https://research.nvidia.com/person/gal-chechik), [Trevor Darrell](https://people.eecs.berkeley.edu/~trevor/), [Amir Globerson](http://www.cs.tau.ac.il/~gamir/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/1912.07414)]

**Training Generative Adversarial Networks with Limited Data.**<br>
*[Tero Karras](https://research.nvidia.com/person/tero-karras), [Miika Aittala](https://research.nvidia.com/person/miika-aittala), Janne Hellsten, Samuli Laine, Jaakko Lehtinen, [Timo Aila](https://research.nvidia.com/person/timo-aila).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.06676v1)] [[Project](https://research.nvidia.com/publication/2020-06_Training-Generative-Adversarial)]

**AlphaGAN: Fully Differentiable Architecture Search for Generative Adversarial Networks.**<br>
*Yuesong Tian, Li Shen, Li Shen, Guinan Su, Zhifeng Li, Wei Liu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.09134)] [[Github](https://github.com/yuesongtian/AlphaGAN)]

**Self-Supervised MultiModal Versatile Networks.**<br>
*Jean-Baptiste Alayrac, Adrià Recasens, Rosalia Schneider, Relja Arandjelović, Jason Ramapuram, Jeffrey De Fauw, Lucas Smaira, Sander Dieleman, Andrew Zisserman.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.16228)]

**Empirical Analysis of Overfitting and Mode Drop in GAN Training.**<br>
*Yasin Yazici, Chuan-Sheng Foo, Stefan Winkler, Kim-Hui Yap, Vijay Chandrasekhar.*<br>
ICIP 2020. [[PDF](https://arxiv.org/abs/2006.14265)]

**Implicit Neural Representations with Periodic Activation Functions.**<br>
*[Vincent Sitzmann](https://vsitzmann.github.io), Julien N. P. Martel, Alexander W. Bergman, David B. Lindell, Gordon Wetzstein.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.09661)] [[Project](https://vsitzmann.github.io/siren/)] [[Github](https://github.com/vsitzmann/siren)]

**Rethinking Semi-Supervised Learning in VAEs.**<br>
*Tom Joy, Sebastian M. Schmon, Philip H. S. Torr, N. Siddharth, Tom Rainforth.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.10102)] [[Github](https://github.com/thwjoy/revae-demo)]

**Fourier Features Let Networks Learn High Frequency Functions in Low Dimensional Domains.**<br>
*[Matthew Tancik](http://matthewtancik.com/), [Pratul P. Srinivasan](https://people.eecs.berkeley.edu/~pratul/), Ben Mildenhall, Sara Fridovich-Keil, Nithin Raghavan, Utkarsh Singhal, [Ravi Ramamoorthi](http://cseweb.ucsd.edu/~ravir/), [Jonathan T. Barron](https://jonbarron.info/), [Ren Ng](https://www2.eecs.berkeley.edu/Faculty/Homepages/yirenng.html).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.10739)] [[Project](https://people.eecs.berkeley.edu/~bmild/fourfeat/)] [[Github](https://github.com/tancik/fourier-feature-networks)]

**Sky Optimization: Semantically Aware Image Processing of Skies in Low-Light Photography.**<br>
*Orly Liba, Longqi Cai, Yun-Ta Tsai, Elad Eban, Yair Movshovitz-Attias, Yael Pritch, Huizhong Chen, [Jonathan T. Barron](https://jonbarron.info/).*<br>
CVPR Workshop 2020. [[PDF](https://arxiv.org/abs/2006.10172)]

**Pitfalls of the Gram Loss for Neural Texture Synthesis in Light of Deep Feature Histograms.**<br>
*Eric Heitz, Kenneth Vanhoey, Thomas Chambon, Laurent Belcour.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.07229)]

**Co-occurrence Based Texture Synthesis.**<br>
*Anna Darzi, Itai Lang, Ashutosh Taklikar, Hadar Averbuch-Elor, Shai Avidan.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2005.08186)] [[Github](https://github.com/Ashu7397/coco_texture)]

**CIAGAN: Conditional Identity Anonymization Generative Adversarial Networks.**<br>
*Maxim Maximov, Ismail Elezi, Laura Leal-Taixé.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2005.09544)] [[Github](https://github.com/dvl-tum/ciagan)]

**CONFIG: Controllable Neural Face Image Generation.**<br>
*Marek Kowalski, Stephan J. Garbin, Virginia Estellers, Tadas Baltrušaitis, Matthew Johnson, Jamie Shotton.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2005.02671)] [[Github](https://github.com/microsoft/ConfigNet)]

**Panoptic-based Image Synthesis.**<br>
*Aysegul Dundar, Karan Sapra, Guilin Liu, Andrew Tao, Bryan Catanzaro.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.10289)]

**ALAE: Adversarial Latent Autoencoders.**<br>
*[Stanislav Pidhorskyi](https://podgorskiy.com/), Donald A. Adjeroh, Gianfranco Doretto.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.04467)] [[Github](https://github.com/podgorskiy/ALAE)]

**LAG: Creating High Resolution Images with a Latent Adversarial Generator.**<br>
*David Berthelot, Peyman Milanfar, Ian Goodfellow.*<br>
arxiv, 4 Mar 2020. [[PDF](https://arxiv.org/abs/2003.02365)] [[Github](https://github.com/google-research/lag)]

**Bayesian Reasoning with Deep-Learned Knowledge.**<br>
*Jakob Knollmüller, Torsten Enßlin.*<br>
arxiv, 29 Jan 2020. [[PDF](https://arxiv.org/abs/2001.11031v1)]

**Overcoming the Disentanglement vs Reconstruction Trade-off via Jacobian Supervision.**<br>
*[José Lezama](https://iie.fing.edu.uy/~jlezama/).*<br>
ICLR 2019. [[PDF](https://openreview.net/pdf?id=Hkg4W2AcFm)] [[Github](https://github.com/jlezama/disentangling-jacobian)]

**Training End-to-end Single Image Generators without GANs.**<br>
*Yael Vinker, Nir Zabari, Yedid Hoshen.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.06014)] [[Project](http://www.vision.huji.ac.il/augurone)]

**Improving Sample Diversity of a Pre-trained, Class-Conditional GAN by Changing its Class Embeddings.**<br>
*Qi Li, Long Mai, Anh Nguyen.*<br>
arxiv, 10 Oct 2019. [[PDF](https://arxiv.org/abs/1910.04760)]

**Unsupervised K-modal Styled Content Generation.**<br>
*Omry Sendik, Dani Lischinski, Daniel Cohen-Or.*<br>
arxiv, 10 Jan 2020. [[PDF](https://arxiv.org/pdf/2001.03640.pdf)]

**Deep Video-Based Performance Cloning.**<br>
*Kfir Aberman, Mingyi Shi, Jing Liao, Dani Lischinski, Daniel Cohen-Or, Chen Baoquan.*<br>
Eurographics 2019. [[PDF](https://arxiv.org/pdf/1808.06847.pdf)]

## DeepFake and Forensic

[[FaceForensics Benchmark](http://kaldir.vc.in.tum.de/faceforensics_benchmark/)]
[[awesome-deepfakes-materials](https://github.com/datamllab/awesome-deepfakes-materials)]

**DeeperForensics-1.0: A Large-Scale Dataset for Real-World Face Forgery Detection.**<br>
*[Liming Jiang](https://liming-jiang.com/), [Wayne Wu](https://wywu.github.io/), [Ren Li](https://liren2515.github.io/page/), [Chen Qian](https://scholar.google.com/citations?user=AerkT0YAAAAJ&hl=en), [Chen Change Loy](http://personal.ie.cuhk.edu.hk/~ccloy/).*<br>
arxiv, 9 Jan 2020.
[[PDF](https://arxiv.org/abs/2001.03024)] 
[[Project](https://liming-jiang.com/projects/DrF1/DrF1.html)]
[[DeeperForensics-1.0 Dataset](https://github.com/EndlessSora/DeeperForensics-1.0)]
[[PDF](https://github.com/EndlessSora/DeeperForensics-1.0)]

**FaceForensics++: Learning to Detect Manipulated Facial Images.**<br>
*[Andreas Rössler](http://www.niessnerlab.org/members/andreas_roessler/profile.html), Davide Cozzolino, Luisa Verdoliva, Christian Riess, Justus Thies, [Matthias Nießner](http://www.niessnerlab.org/members/matthias_niessner/profile.html).*<br>
[[PDF](https://arxiv.org/abs/1901.08971)] [[Github](https://github.com/ondyari/FaceForensics)] [[Homepage & Dataset](http://www.niessnerlab.org/projects/roessler2018faceforensics.html)] [[Face Forensics  Image Recognition Suite](http://faceforensics.com/)]

**DeepFakes and Beyond: A Survey of Face Manipulation and Fake Detection.**<br>
*Ruben Tolosana, Ruben Vera-Rodriguez, Julian Fierrez, Aythami Morales, Javier Ortega-Garcia.*<br>
arxiv, 2020. [[PDF](https://arxiv.org/abs/2001.00179)]

**Cross-ethnicity Face Anti-spoofing Recognition Challenge: A Review.**<br>
*Ajian Liu, Xuan Li, Jun Wan, Sergio Escalera, Hugo Jair Escalante, Meysam Madadi, Yi Jin, Zhuoyuan Wu, Xiaogang Yu, Zichang Tan, Qi Yuan, Ruikun Yang, Benjia Zhou, Guodong Guo, Stan Z. Li.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.10998)]


**What Makes Fake Images Detectable? Understanding Properties That Generalize.**<br>
*Lucy Chai, David Bau, Ser-Nam Lim, Phillip Isola.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.10588)]  [[Github](https://chail.github.io/patch-forensics/)]

**Two-branch Recurrent Network for Isolating Deepfakes in Videos.**<br>
*Iacopo Masi, Aditya Killekar, Royston Marian Mascarenhas, Shenoy Pratik Gurudatt, Wael AbdAlmageed.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.03412)]

**The DeepFake Detection Challenge Dataset.**<br>
*Brian Dolhansky, Joanna Bitton, Ben Pflaum, Jikuo Lu, Russ Howes, Menglin Wang, Cristian Canton Ferrer.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.07397)] [[Dataset](http://ai.facebook.com/)]

**DeepFaceLab: A simple, flexible and extensible face swapping framework.**<br>
*Ivan Petrov, Daiheng Gao, Nikolay Chervoniy, Kunlin Liu, Sugasa Marangonda, Chris Umé, Mr. Dpfks, Carl Shift Facenheim, Luis RP, Jian Jiang, Sheng Zhang, Pingyu Wu, Bo Zhou, Weiming Zhang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2005.05535)] [[Github](https://github.com/iperov/DeepFaceLab/)]

**Not My Deepfake: Towards Plausible Deniability for Machine-Generated Media.**<br>
*Baiwu Zhang, Jin Peng Zhou, Ilia Shumailov, Nicolas Papernot.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.09194)]

**Face Anti-Spoofing Via Disentangled Representation Learning.**<br>
*Ke-Yue Zhang, Taiping Yao, Jian Zhang, Ying Tai, Shouhong Ding, Jilin Li, Feiyue Huang, Haichuan Song, Lizhuang Ma.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.08250)]

**Face Anti-Spoofing with Human Material Perception.**<br>
*Zitong Yu, Xiaobai Li, Xuesong Niu, Jingang Shi, Guoying Zhao.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.02157)]

**Look Locally Infer Globally: A Generalizable Face Anti-Spoofing Approach.**<br>
*Debayan Deb, Anil K. Jain.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.02834)]

**Learning Meta Model for Zero- and Few-shot Face Anti-Spoofing.**<br>
*Yunxiao Qin, Chenxu Zhao, Xiangyu Zhu, Zezheng Wang, Zitong Yu, Tianyu Fu, Feng Zhou, Jingping Shi, Zhen Lei.*<br>
AAAI 2020. [[PDF](https://arxiv.org/abs/1904.12490)] [[Gtihub](https://github.com/qyxqyx/AIM_FAS)]

**Detecting CNN-Generated Facial Images in Real-World Scenarios.**<br>
*Nils Hulzebosch, Sarah Ibrahimi, Marcel Worring.*<br>
Media Forensics at CVPR 2020. [[PDF](https://arxiv.org/abs/2005.05632)]

**Deepfake Video Forensics based on Transfer Learning.**<br>
*Rahul U, Ragul M, Raja Vignesh K, Tejeswinee K.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.14178)]

**Single-Side Domain Generalization for Face Anti-Spoofing.**<br>
*Yunpei Jia, Jie Zhang, Shiguang Shan, Xilin Chen.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.14043)]

**Preliminary Forensics Analysis of DeepFake Images.**<br>
*Luca Guarnera, Oliver Giudice, Cristina Nastasi, Sebastiano Battiato.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.12626)]

**Deep Face Forgery Detection.**<br>
*Nika Dogonadze, Jana Obernosterer, Ji Hou.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.11804)]

**PipeNet: Selective Modal Pipeline of Fusion Network for Multi-Modal Face Anti-Spoofing.**<br>
*Qing Yang, Xia Zhu, Jong-Kae Fwu, Yun Ye, Ganmei You, Yuan Zhu.*<br>
CVPR 2020 WMF. [[PDF](https://arxiv.org/abs/2004.11744)]

**Warwick Image Forensics Dataset for Device Fingerprinting In Multimedia Forensics.**<br>
*Yijun Quan, Chang-Tsun Li, Yujue Zhou, Li Li.*<br>
ICME 2020. [[PDF](https://arxiv.org/abs/2004.10469)]

**DeepFake Detection by Analyzing Convolutional Traces.**<br>
*Luca Guarnera, Oliver Giudice, Sebastiano Battiato.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.10448)]

**DeepFakes Evolution: Analysis of Facial Regions and Fake Detection Performance.**<br>
*Ruben Tolosana, Sergio Romero-Tapiador, Julian Fierrez, Ruben Vera-Rodriguez.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.07532)]

**CurricularFace: Adaptive Curriculum Learning Loss for Deep Face Recognition.**<br>
*Yuge Huang, Yuhan Wang, Ying Tai, Xiaoming Liu, Pengcheng Shen, Shaoxin Li, Jilin Li, Feiyue Huang.*<br>
CVPR 2020. [[PDF](https://github.com/HuangYG123/CurricularFace/blob/master)] [[Github](https://github.com/HuangYG123/CurricularFace)]

**Deep Spatial Gradient and Temporal Depth Learning for Face Anti-spoofing.**<br>
*Zezheng Wang, Zitong Yu, Chenxu Zhao, Xiangyu Zhu, Yunxiao Qin, Qiusheng Zhou, Feng Zhou, Zhen Lei.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.08061)]

**Evading Deepfake-Image Detectors with White- and Black-Box Attacks.**<br>
*Nicholas Carlini, Hany Farid.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.00622)]

**One-Shot GAN Generated Fake Face Detection.**<br>
*Hadi Mansourifar, Weidong Shi.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2003.12244)]

**Global Texture Enhancement for Fake Face Detection in the Wild.**<br>
*Zhengzhe Liu, Xiaojuan Qi, Philip H.S. Torr.*<br>
CVPR 2020. [[PDF](https://xjqi.github.io/real_fake.pdf)]

**Leveraging Frequency Analysis for Deep Fake Image Recognition.**<br>
*Joel Frank, Thorsten Eisenhofer, Lea Schönherr, Asja Fischer, Dorothea Kolossa, Thorsten Holz.*<br>
arxiv, 19 Mar 2020. [[PDF](https://arxiv.org/abs/2003.08685)] [[Github](https://github.com/RUB-SysSec/GANDCTAnalysis)]

**Disrupting DeepFakes: Adversarial Attacks Against Conditional Image Translation Networks and Facial Manipulation Systems.**<br>
*[Nataniel Ruiz](https://natanielruiz.github.io/), [Sarah Adel Bargal](https://cs-people.bu.edu/sbargal/), [Stan Sclaroff](http://www.cs.bu.edu/~sclaroff/).*<br>
arxiv, 3 Mar 2020. [[PDF](https://arxiv.org/abs/2003.01279)] [[Github](https://github.com/natanielruiz/disrupting-deepfakes)]

**Adversarial Deepfakes: Evaluating Vulnerability of Deepfake Detectors to Adversarial Examples.**<br>
*Paarth Neekhara, Shehzeen Hussain, Malhar Jere, Farinaz Koushanfar, Julian McAuley.*<br>
arxiv,  9 Feb 2020. [[PDF](https://arxiv.org/abs/2002.12749)]

**Real or Not Real, that is the Question.**<br>
*Yuanbo Xiangli, Yubin Deng, Bo Dai, Chen Change Loy, Dahua Lin.*<br>
ICLR 2020. [[PDF](https://openreview.net/forum?id=B1lPaCNtPB)] [[Github](https://github.com/kam1107/RealnessGAN)] 

**Fawkes: Protecting Personal Privacy against Unauthorized Deep Learning Models.**<br>
*Shawn Shan, Emily Wenger, Jiayun Zhang, Huiying Li, Haitao Zheng, Ben Y. Zhao.*<br>
arxiv, 19 Feb 2020. [[PDF](https://arxiv.org/abs/2002.08327)]

**FakeLocator: Robust Localization of GAN-Based Face Manipulations via Semantic Segmentation Networks with Bells and Whistles.**<br>
*Yihao Huang, Felix Juefei-Xu, Run Wang, Xiaofei Xie, Lei Ma, Jianwen Li, Weikai Miao, Yang Liu, Geguang Pu.*<br>
arxiv, 27 Jan 2020. [[PDF](https://arxiv.org/abs/2001.09598)]

**Face X-ray for More General Face Forgery Detection.**<br>
*Lingzhi Li, Jianmin Bao, Ting Zhang, Hao Yang, Dong Chen, Fang Wen, Baining Guo.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.13458)]

**FaceShifter: Towards High Fidelity And Occlusion Aware Face Swapping.**<br>
*Lingzhi Li, Jianmin Bao, Hao Yang, Dong Chen, Fang Wen.*<br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1912.13457)]

**Scalable Fine-grained Generated Image Classification Based on Deep Metric Learning.**<br>
*Xinsheng Xuan, Bo Peng, Wei Wang, Jing Dong.*<br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1912.11082)]

**Attributing Fake Images to GANs: Learning and Analyzing GAN Fingerprints.**<br>
*Ning Yu, Larry Davis, [Mario Fritz](https://cispa.saarland/people/mario.fritz/).*<br>
ICCV 2019.
[[PDF](https://arxiv.org/abs/1811.08180)] [[Github](https://github.com/ningyu1991/GANFingerprints)] [[Group of Mario Fritz at CISPA](https://cispa.saarland/group/fritz/)] [[Media Coverage](https://mp.weixin.qq.com/s/se1ZyR_gfzliWB5X72OZ1Q)]

**CNNDetection: CNN-Generated Images Are Surprisingly Easy to Spot...For Now.**<br>
*[Sheng-Yu Wang](https://peterwang512.github.io), [Oliver Wang](http://www.oliverwang.info/), [Richard Zhang](http://richzhang.github.io/), [Andrew Owens](http://andrewowens.com/), [Alexei A. Efros](http://www.eecs.berkeley.edu/~efros/).*<br>
CVPR 2020.
[[PDF](https://arxiv.org/abs/1906.05856)]  [[Code](https://github.com/peterwang512/FALdetector)]  [[Project](https://peterwang512.github.io/FALdetector)] 

**Detecting Photoshopped Faces by Scripting Photoshop.**<br>
*Sheng-Yu Wang, Oliver Wang, Andrew Owens, Richard Zhang, Alexei A. Efros.*<br>
ICCV, 2019.
[[PDF](https://arxiv.org/abs/1912.11035)]  [[Code](https://github.com/peterwang512/CNNDetection)]  [[Project](https://peterwang512.github.io/CNNDetection/)] [[Adobe Max](https://youtu.be/21lj8tCSMkg)]

**Fighting Fake News: Image Splice Detection via Learned Self-Consistency.**<br>
*Minyoung Huh, Andrew Liu, Andrew Owens, Alexei A. Efros.*<br>
ECCV 2018. [[Github](https://github.com/minyoungg/selfconsistency)] [[Project](https://minyoungg.github.io/selfconsistency/)]

## Video Prediction and Future Prediction

**DTVNet: Dynamic Time-lapse Video Generation via Single Still Image.**<br>
*Jiangning Zhang, Chao Xu, Liang Liu, Mengmeng Wang, Xia Wu, Yong Liu, Yunliang Jiang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.04776)]

**Transformation-based Adversarial Video Prediction on Large-Scale Data.**<br>
*Pauline Luc, Aidan Clark, Sander Dieleman, Diego de Las Casas, Yotam Doron, Albin Cassirer, Karen Simonyan.*<br>
arxiv, 9 Mar 2020. [[PDF](https://arxiv.org/abs/2003.04035)]

**The Garden of Forking Paths: Towards Multi-Future Trajectory Prediction.**<br>
*Junwei Liang, Lu Jiang, Kevin Murphy, Ting Yu, Alexander Hauptmann.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.06445)] [[Project](https://next.cs.cmu.edu/multiverse/index.html)] [[The Forking Paths Dataset](https://next.cs.cmu.edu/multiverse/index.html)]

**Learning to Generate Time-Lapse Videos Using Multi-Stage Dynamic Generative Adversarial Networks.**<br>
*[Wei Xiong](https://wxiong.me/), Wenhan Luo, Lin Ma, Wei Liu, Jiebo Luo.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1709.07592)] [[Github](https://github.com/weixiong-ur/mdgan)] [[Dataset](https://drive.google.com/open?id=1xWLiU-MBGN7MrsFHQm4_yXmfHBsMbJQo)] [[Project](https://sites.google.com/site/whluoimperial/mdgan)]

**Conditional Sig-Wasserstein GANs for Time Series Generation.**<br>
*Hao Ni, Lukasz Szpruch, Magnus Wiese, Shujian Liao, Baoren Xiao.*<br>
arxiv 2020. [[Github](https://github.com/SigCGANs/Conditional-Sig-Wasserstein-GANs)]

**Visual Dynamics: Stochastic Future Generation via Layered Cross Convolutional Networks.**<br>
*[Tianfan Xue](http://people.csail.mit.edu/tfxue/research_statement_tianfan.pdf), Jiajun Wu, Katherine L. Bouman, William T. Freeman.*<br>
TPAMI 2019 / NeurIPS 2016. [[PDF](https://arxiv.org/abs/1807.09245)] [[Project](visualdynamics.csail.mit.edu)] [[Github](https://github.com/tfxue/visual-dynamics)]

**Eidetic 3D LSTM: A Model for Video Prediction and Beyond.**<br>
*Yunbo Wang, Lu Jiang, Ming-Hsuan Yang, Li-Jia Li, Mingsheng Long, Li Fei-Fei.*<br>
ICLR 2019. [[PDF](https://openreview.net/forum?id=B1lKS2AqtX)] [[GitHub](https://github.com/google/e3d_lstm)]

**STGAT: Modeling Spatial-Temporal Interactions for Human Trajectory Prediction.**<br>
*Yingfan Huang, HuiKun Bi, Zhaoxin Li, Tianlu Mao, Zhaoqi Wang.*<br> 
ICCV 2019. [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Huang_STGAT_Modeling_Spatial-Temporal_Interactions_for_Human_Trajectory_Prediction_ICCV_2019_paper.pdf)]
[[GitHub](https://github.com/huang-xx/STGAT)] [[Social GAN](https://github.com/agrimgupta92/sgan)]

## Frame Interpolation, Extrapolation and Videos Generation

**SiENet: Siamese Expansion Network for Image Extrapolation.**<br>
*Xiaofeng Zhang, Feng Chen, Cailing Wang, Songsong Wu, Ming Tao, Guoping Jiang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.03851)]

**Extrapolative-Interpolative Cycle-Consistency Learning for Video Frame Extrapolation.**<br>
*Sangjin Lee, Hyeongmin Lee, Taeoh Kim, Sangyoun Lee.*<br>
ICIP 2020. [[PDF](https://arxiv.org/abs/2005.13194)]

**AdaCoF: Adaptive Collaboration of Flows for Video Frame Interpolation.**<br>
*[Hyeongmin Lee](https://hyeongminlee.github.io/), [Taeoh Kim](https://taeoh-kim.github.io/), Tae-young Chung, Daehyun Pak, Yuseok Ban, and Sangyoun Lee.*<br>
CVPR 2020.
[[PDF](https://arxiv.org/abs/1907.10244)] [[Video](https://www.youtube.com/watch?v=Z3q0YrBsNJc)] [[Github](https://github.com/HyeongminLEE/AdaCoF-pytorch)]

**Blurry Video Frame Interpolation.**<br>
*Wang Shen, Wenbo Bao, Guangtao Zhai, Li Chen, Xiongkuo Min, Zhiyong Gao.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2002.12259)]

**Novel-View Human Action Synthesis.**<br>
*Mohamed Ilyes Lakhal, Davide Boscaini, Fabio Poiesi, Oswald Lanz, Andrea Cavallaro.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.02808)]

**Structure-Aware Human-Action Generation.**<br>
*Ping Yu, Yang Zhao, Chunyuan Li, Changyou Chen.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.01971)]

**Video Prediction via Example Guidance.**<br>
*Jingwei Xu, Huazhe Xu, Bingbing Ni, Xiaokang Yang, Trevor Darrell.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.01738)] [[Project](https://sites.google.com/view/vpeg-supp/home)]

**Hierarchical Patch VAE-GAN: Generating Diverse Videos from a Single Sample.**<br>
*Shir Gur, Sagie Benaim, Lior Wolf.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.12226)]

**Zooming Slow-Mo: Fast and Accurate One-Stage Space-Time Video Super-Resolution.**<br>
*Xiaoyu Xiang, Yapeng Tian, Yulun Zhang, Yun Fu, Jan P. Allebach, Chenliang Xu.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2002.11616)]

**DAIN: Depth-Aware Video Frame Interpolation.**<br>
*Wenbo Bao, Wei-Sheng Lai, Chao Ma, Xiaoyun Zhang, Zhiyong Gao, Ming-Hsuan Yang.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1904.00830)]
[[Github](https://github.com/baowenbo/DAIN)]
[[Software](https://drive.google.com/file/d/1uuDkF4j4H1AI1ot88XdqzwMdvAPhxKN8/view)]

**Super SloMo: High Quality Estimation of Multiple Intermediate Frames for Video Interpolation.**<br>
*[Huaizu Jiang](http://jianghz.me/), [Deqing Sun](http://research.nvidia.com/person/deqing-sun), Varun Jampani, Ming-Hsuan Yang, Erik Learned-Miller, Jan Kautz.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1712.00080)] [[Project](https://people.cs.umass.edu/~hzjiang/projects/superslomo/)] [[Github](https://github.com/avinashpaliwal/Super-SloMo)]

## Free-Hand Sketch

[Awesome-Sketch-Based-Applications](https://github.com/MarkMoHR/Awesome-Sketch-Based-Applications)

[[TorchSketch](https://github.com/PengBoXiangShang/torchsketch)] is an open source software library for free-hand sketch oriented deep learning research, which is built on the top of PyTorch.


**DeepFacePencil: Creating Face Images from Freehand Sketches.**<br>
*Yuhang Li, Xuejin Chen, Binxin Yang, Zihan Chen, Zhihua Cheng, Zheng-Jun Zha.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2008.13343)]

**Unsupervised Sketch-to-Photo Synthesis.**<br> 
*Runtao Liu, Qian Yu, Stella Yu.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/1909.08313)] [[Github](https://github.com/rt219/Unpaired-Sketch-to-Photo-Translation)]

**On Learning Semantic Representations for Million-Scale Free-Hand Sketches.**<br> 
*Peng Xu, Yongye Huang, Tongtong Yuan, Tao Xiang, Timothy M. Hospedales, Yi-Zhe Song, Liang Wang.*<br> 
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.04101)]

**BézierSketch: A Generative Model For Scalable Vector Sketches.**<br> 
*Ayan Das, Yongxin Yang, Timothy Hospedales, Tao Xiang, Yi-Zhe Song.*<br> 
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.02190)]

**DeepFaceDrawing: Deep Generation of Face Images from Sketches.**<br> 
*[Shu-Yu Chen](http://people.geometrylearning.com/csy/), [Wanchao Su](https://www.scm.cityu.edu.hk/doctoral-researcher/wanchaosu2-c), Lin Gao, Shihong Xia, Hongbo Fu.*<br> 
SIGGRAPH 2020. [[PDF](https://arxiv.org/abs/2006.01047)] [[Project](http://www.geometrylearning.com/DeepFaceDrawing/)]

**LinesToFacePhoto: Face Photo Generation from Lines with Conditional Self-Attention Generative Adversarial Network.**<br> 
*Yuhang Li, [Xuejin Chen](http://staff.ustc.edu.cn/~xjchen99/), Feng Wu, Zheng-Jun Zha.*<br> 
ACM MM 2019. [[PDF](https://arxiv.org/abs/1910.08914)] [[Github]()]

**Interactive Sketch & Fill: Multiclass Sketch-to-Image Translation.**<br>
*[Arnab Ghosh](https://arnabgho.github.io/), [Richard Zhang](https://richzhang.github.io/), [Puneet K. Dokania](https://puneetkdokania.github.io/), [Oliver Wang](http://www.oliverwang.info/), [Alexei A. Efros](https://people.eecs.berkeley.edu/~efros/), [Philip H.S. Torr](http://www.robots.ox.ac.uk/~tvg/index.php), [Eli Shechtman](https://research.adobe.com/person/eli-shechtman/).*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1909.11081v2)] [[Project](https://arnabgho.github.io/iSketchNFill/)] [[Github](https://github.com/arnabgho/iSketchNFill)]

**Multi-Density Sketch-to-Image Translation Network.**<br> 
*Jialu Huang, Jing Liao, Zhifeng Tan, Sam Kwong.*<br> 
2020. [[PDF](https://arxiv.org/pdf/2006.10649)]

**Sketch-Guided Scenery Image Outpainting.**<br> 
*Yaxiong Wang, Yunchao Wei, Xueming Qian, Li Zhu, Yi Yang.*<br> 
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.09788)]

**3D Shape Reconstruction from Free-Hand Sketches.**<br> 
*Jiayun Wang, Jierui Lin, Qian Yu, Runtao Liu, Yubei Chen, Stella X. Yu.*<br> 
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.09694)]

**Synthesizing Human-Like Sketches From Natural Images Using A Conditional Convolutional Decoder.**<br> 
*Moritz Kampelmühler, Axel Pinz.*<br> 
WACV 2020. [[PDF](https://kampelmuehler.github.io/files/synthesizing_human_like_sketches.pdf)] [[Github](https://github.com/kampelmuehler/synthesizing_human_like_sketches)] [[Project](https://kampelmuehler.github.io/publications/synthesizing_human_like_sketches)]

**Unsupervised Sketch-to-Photo Synthesis.**<br>
*Runtao Liu, Qian Yu, Stella Yu.*<br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1909.08313)] [[Github](https://github.com/rt219/Unpaired-Sketch-to-Photo-Translation)]

**APDrawingGAN: Generating Artistic Portrait Drawings From Face Photos With Hierarchical GANs.**<br> 
*Ran Yi, Yong-Jin Liu, Yu-Kun Lai, Paul L. Rosin.*<br> 
CVPR 2019. [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/papers/Yi_APDrawingGAN_Generating_Artistic_Portrait_Drawings_From_Face_Photos_With_Hierarchical_CVPR_2019_paper)] [[Github](https://github.com/yiranran/APDrawingGAN)] [[Demo](https://face.lol/)]

**Synthesizing Human-Like Sketches From Natural Images Using A Conditional Convolutional Decoder.**<br> 
*Moritz Kampelmühler, Axel Pinz.*<br> 
WACV 2020. [[PDF](https://arxiv.org/abs/2003.07101)] [[Github](https://github.com/kampelmuehler/synthesizing_human_like_sketches)]

**Image Generation from Freehand Scene Sketches.**<br> 
*Chengying Gao, Qi Liu, Qi Xu, Jianzhuang Liu, Limin Wang, Changqing Zou.*<br> 
arxiv，5 Mar 2020. [[PDF](https://arxiv.org/abs/2003.02683)]

**Sketch-to-Art: Synthesizing Stylized Art Images From Sketches.**<br> 
*Bingchen Liu, Kunpeng Song, Ahmed Elgammal.*<br> 
arxiv, 26 Feb 2020. [[PDF](https://arxiv.org/abs/2002.12888)]

**Deep Plastic Surgery: Robust and Controllable Image Editing with Human-Drawn Sketches.**<br>
*Shuai Yang, Zhangyang Wang, Jiaying Liu, Zongming Guo.*<br>
arxiv, 9 Jan 2020. [[PDF](https://arxiv.org/abs/2001.02890)]

**Deep Learning for Free-Hand Sketch: A Survey.**<br>
*Peng Xu.*<br>
arxiv, 8 Jan 2020. [[PDF](https://arxiv.org/abs/2001.02600)]

**Examining Performance of Sketch-to-Image Translation Models with Multiclass Automatically Generated Paired Training Data.**<br>
*Dichao Hu.*<br>
arxiv, 2018. [[PDF](https://arxiv.org/abs/1811.00249)]

**Multi-Graph Transformer for Free-Hand Sketch Recognition.**<br>
*[Peng Xu](http://www.pengxu.net/), [Chaitanya K. Joshi](https://chaitjo.github.io/), [Xavier Bresson](https://www.ntu.edu.sg/home/xbresson/).*<br>
arxiv, 2019. [[PDF](https://arxiv.org/abs/1912.11258)] [[Github](https://github.com/PengBoXiangShang/multigraph_transformer)]

## Occlusion Reasoning

**Peek-a-Boo: Occlusion Reasoning in Indoor Scenes with Plane Representations.**<br>
*Ziyu Jiang, Buyu Liu, Samuel Schulter, Zhangyang Wang, [Manmohan Chandraker](http://cseweb.ucsd.edu/~mkchandraker/).*<br>
CVPR 2020. [[PDF](http://cseweb.ucsd.edu/~mkchandraker/pdf/cvpr20_peekaboo.pdf)]

**Self-Supervised Scene De-occlusion.**<br>
*[Xiaohang Zhan](https://xiaohangzhan.github.io/), [Xingang Pan](https://xingangpan.github.io/), Bo Dai, Ziwei Liu, Dahua Lin, Chen Change Loy.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.02788)] [[Project](https://xiaohangzhan.github.io/projects/deocclusion/)] [[Github](https://github.com/XiaohangZhan/deocclusion/)]

**Efficient Non-Line-of-Sight Imaging from Transient Sinograms.**<br>
*Mariko Isogawa, Dorian Chan, Ye Yuan, Kris Kitani, Matthew O'Toole.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.02787)]

## Motion Synthesis

**Style-Controllable Speech-Driven Gesture Synthesis Using Normalising Flows.**<br>
*Alexanderson, Simon and Henter, Gustav Eje and Kucherenko, Taras and Beskow, Jonas.*<br>
Computer Graphics Forum 2020. [[PDF](https://diglib.eg.org/handle/10.1111/cgf13946)] [[Github](https://github.com/simonalexanderson/StyleGestures)]

**MoGlow: Probabilistic and Controllable Motion Synthesis Using Normalising Flows.**<br>
*Gustav Eje Henter, Simon Alexanderson, Jonas Beskow.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/1905.06598)] [[Github](https://github.com/simonalexanderson/StyleGestures)]

## Image Harmonization

**Foreground-aware Semantic Representations for Image Harmonization.**<br> 
*Konstantin Sofiiuk, Polina Popenova, Anton Konushin.*<br> 
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.00809)] [[Github](https://github.com/saic-vul/image_harmonization)]

## Photorealistic Style Transfer

**Domain-Specific Mappings for Generative Adversarial Style Transfers.**<br>
*Hsin-Yu Chang, Zhixiang Wang, Yung-Yu Chuangs.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.02198)] [[Project](https://acht7111020.github.io/DSMAP-demo/)] [[Github](https://acht7111020.github.io/DSMAP-demo/)]

**Filter Style Transfer between Photos.**<br>
*Jonghwa Yim, Jisung Yoo, Won-joon Do, Beomsu Kim, Jihwan Choe.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.07925)]

**Geometric Style Transfer.**<br>
*Xiao-Chang Liu, Xuan-Yi Li, Ming-Ming Cheng, Peter Hall.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.05471)]

**Joint Bilateral Learning for Real-time Universal Photorealistic Style Transfer.**<br>
*Xide Xia, Meng Zhang, Tianfan Xue, Zheng Sun, Hui Fang, Brian Kulis, Jiawen Chen.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.10955)]

## Soft Segmentation and Background Matting

**Fast Soft Color Segmentation.**<br>
*Naofumi Akimoto, Huachun Zhu, Yanghua Jin, Yoshimitsu Aoki.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.08096)]

**Background Matting: The World is Your Green Screen.**<br>
*[Soumyadip Sengupta](https://homes.cs.washington.edu/~soumya91/), [Vivek Jayaram](http://www.vivekjayaram.com/research), Brian Curless, Steve Seitz, Ira Kemelmacher-Shlizerman.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.00626)] [[Github](https://github.com/senguptaumd/Background-Matting)] [[Project](https://grail.cs.washington.edu/projects/background-matting/)]

**Semantic Soft Segmentation.**<br>
*[Yagiz Aksoy](http://yaksoy.github.io/), Tae-Hyun Oh, Sylvain Paris, Marc Pollefeys and Wojciech Matusik.*<br>
ACM Transactions on Graphics (Proc. SIGGRAPH), 2018. [[PDF](http://cfg.mit.edu/sites/cfg.mit.edu/files/sss_3.pdf)] [[Project](http://yaksoy.github.io/sss/)] [[Github-Matlab](https://github.com/yaksoy/SemanticSoftSegmentation)] [[Github-Python](https://github.com/iyah4888/SIGGRAPH18SSS)]

## Reciprocal Computer Vision Tasks

**DSNet: Joint Learning for Scene Segmentation and Disparity Estimation.**<br>
*Wujing Zhan, Xinqi Ou, Yunyi Yang and Long Chen.*<br>
ICRA 2019. [[PDF](https://ieeexplore.ieee.org/document/8793573)] 

**Real-Time Joint Semantic Segmentation and Depth Estimation Using Asymmetric Annotations.** <br> 
*Vladimir Nekrasov, Thanuja Dharmasiri, Andrew Spek, Tom Drummond, Chunhua Shen, Ian Reid.*<br> 
ICRA 2019. [[PDF](https://ieeexplore.ieee.org/document/8794220)]

**RDSNet: A New Deep Architecture for Reciprocal Object Detection and Instance Segmentation.** <br>
*Shaoru Wang, Yongchao Gong, Junliang Xing, Lichao Huang, Chang Huang, Weiming Hu.* <br>
AAAI 2020. [[PDF](https://arxiv.org/abs/1912.05070)] [[Github](https://github.com/wangsr126/RDSNet)]

**MOTSFusion: Track to Reconstruct and Reconstruct to Track.**<br>
*Jonathon Luiten, Tobias Fischer, Bastian Leibe.*<br>
[[PDF](https://arxiv.org/abs/1910.00130v1)] [[Github](https://github.com/tobiasfshr/MOTSFusion)]

**Cooperative Image Segmentation and Restoration in Adverse Environmental Conditions.** <br>
*Weihao Xia, Zhanglin Cheng, Yujiu Yang, Jing-Hao Xue.*<br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1911.00679)]

