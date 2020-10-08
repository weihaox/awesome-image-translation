# Controllable Image Generation

This repository is about *Controllable and Interpretable Image Generation* or *intelligent image manipulation*, which is a collection of papers on image generation and manipulation with the guidance by text, audio, camera pose or other information.  The Controlable Parameters can be Camera, Pose, Lighting, Color, Texture, Semantics, Expression, Speech.

## Table of Contents

- [Interactive and Controllable Image Manipulation](#interactive-and-controllable-image-manipulation)
  * [Highlight Component](#highlight-component)
  * [Change Where You Want](#change-where-you-want)
  * [Guided Translation](#guided-translation)
  * [Individual Object Manipulation](#individual-object-manipulation)
  * [Generating Accurate Descriptions](#generating-accurate-descriptions)
  * [Guided Image-to-image translation](#guided-image-to-image-translation)
  * [Image-Based Virtual Try-On](#image-based-virtual-try-on)
  * [Attribute Editing and Makeup Transfer](#attribute-editing-and-makeup-transfer)
  * [Texture and Surface Mapping](#texture-and-surface-mapping)
  * [Novel-View Synthesis](#novel-view-synthesis)
  * [Motion Transfer, Retargeting, Reenactment, Dubbing and Animation](#motion-transfer--retargeting--reenactment--dubbing-and-animation)
  * [3D Pose Transfer](#3d-pose-transfer)
- [Prediction and Reasoning](#prediction-and-reasoning)
  * [Occlusion Reasoning](#occlusion-reasoning)
  * [Video Prediction and Future Prediction](#video-prediction-and-future-prediction)
  * [Frame Interpolation, Extrapolation and Videos Generation](#frame-interpolation--extrapolation-and-videos-generation)
- [Multi-Modality Translation](#multi-modality-translation)
  * [Image-to-Text](#image-to-text)
  * [Text-to-Image](#text-to-image)
  * [Speech and Text](#speech-and-text)
  * [Image-and-Voice](#image-and-voice)
  * [Voice-to-Voice](#voice-to-voice)
- [Diving Deep into Image Synthesis](#diving-deep-into-image-synthesis)
  * [Invertible Neural Network (Flow-based Generative Model)](#invertible-neural-network--flow-based-generative-model-)
  * [StyleGAN-Based Method](#stylegan-based-method)
  * [Single-Image Training](#single-image-training)
  * [Scene Graph Generation](#scene-graph-generation)
  * [Misc](#misc)
- [DeepFake and Forensic](#deepfake-and-forensic)
- [Free-Hand Sketch](#free-hand-sketch)

## Interactive and Controllable Image Manipulation

### Highlight Component 

**Zoom-in to the details of human-centric videos.**<br>
*Guanghan Li, Yaping Zhao, Mengqi Ji, Xiaoyun Yuan, Lu Fang.*<br>
ICIP 2020. [[PDF](https://arxiv.org/abs/2005.13222)]

**Layered Neural Rendering for Retiming People in Video.**<br>
*Erika Lu, Forrester Cole, Tali Dekel, Weidi Xie, Andrew Zisserman, David Salesin, William T. Freeman, Michael Rubinstein.*<br>
SIGGRAPH Asia 2020. [[PDF](https://arxiv.org/abs/2009.07833)] [[Project](https://retiming.github.io/)]

**Real-Time Selfie Video Stabilization.**<br>
*Jiyang Yu, Ravi Ramamoorthi, Keli Cheng, Michel Sarkis, Ning Bi.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.02007)]

### Change Where You Want

**Lightweight Generative Adversarial Networks for Text-Guided Image Manipulation.**<br>
*Bowen Li, Xiaojuan Qi, Philip Torr, Thomas Lukasiewicz.*<br>
NeurIPS 2020. [[PDF]()]

**A Benchmark and Baseline for Language-Driven Image Editing.**<br>
*Jing Shi, Ning Xu, Trung Bui, Franck Dernoncourt, Zheng Wen, Chenliang Xu.*<br>
ACCV 2020. [[PDF](https://arxiv.org/abs/2010.02330)]

**SSCR: Iterative Language-Based Image Editing via Self-Supervised Counterfactual Reasoning.**<br>
*[Tsu-Jui Fu](https://tsujuifu.github.io/), [Xin Eric Wang](https://eric-xw.github.io/), Scott Grafton, Miguel Eckstein, William Yang Wang.*<br>
EMNLP 2020. [[PDF](https://tsujuifu.github.io/pubs/emnlp20_sscr.pdf)] [[Github](https://github.com/tsujuifu/pytorch_sscr)]

**Describe What to Change: A Text-guided Unsupervised Image-to-Image Translation Approach.**<br>
*Yahui Liu, Marco De Nadai, Deng Cai, Huayang Li, Xavier Alameda-Pineda, Nicu Sebe, Bruno Lepri.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2008.04200)]

**Unselfie: Translating Selfies to Neutral-pose Portraits in the Wild.**<br>
*[Liqian Ma](https://homes.esat.kuleuven.be/~liqianma), Zhe Lin, Connelly Barnes, Alexei A. Efros, Jingwan Lu.*<br>
ECCV 2020. [[PDF](https://homes.esat.kuleuven.be/~liqianma/pdf/ECCV20_Unselfie.pdf)]

**CooGAN: A Memory-Efficient Framework for High-Resolution Facial Attribute Editing.**<br>
*Xuanhong Chen, Bingbing Ni, Naiyuan Liu, Ziang Liu, Yiliu Jiang, Loc Truong, Qi Tian.*<br> 
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123560647.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123560647-supp.pdf)]

**Deep Relighting Networks for Image Light Source Manipulation.**<br>
*Li-Wen Wang, Wan-Chi Siu, Zhi-Song Liu, Chu-Tak Li, Daniel P.K. Lun.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.08298)]

**Dual In-painting Model for Unsupervised Gaze Correction and Animation in the Wild.**<br>
*Jichao Zhang, Jingjing Chen, Hao Tang, Wei Wang, Yan Yan, Enver Sangineto, Nicu Sebe.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2008.03834)]

**Open-Edit: Open-Domain Image Manipulation with Open-Vocabulary Instructions.**<br>
*[Xihui Liu](https://xh-liu.github.io/), Zhe Lin, Jianming Zhang, Handong Zhao, Quan Tran, Xiaogang Wang, and Hongsheng Li.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.01576v1)] [[Github](https://github.com/xh-liu/Open-Edit)]

**Translate the Facial Regions You Like Using Region-Wise Normalization.**<br>
*Wenshuang Liu, Wenting Chen, Linlin Shen.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.14615)]

### Guided Translation

**Style-Controllable Speech-Driven Gesture Synthesis Using Normalising Flows.**<br>
*Alexanderson, Simon and Henter, Gustav Eje and Kucherenko, Taras and Beskow, Jonas.*<br>
Computer Graphics Forum 2020. [[PDF](https://diglib.eg.org/handle/10.1111/cgf13946)] [[Github](https://github.com/simonalexanderson/StyleGestures)]

**MoGlow: Probabilistic and Controllable Motion Synthesis Using Normalising Flows.**<br>
*Gustav Eje Henter, Simon Alexanderson, Jonas Beskow.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/1905.06598)] [[Github](https://github.com/simonalexanderson/StyleGestures)]

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

**Image Sentiment Transfer.**<br>
*Tianlang Chen, Wei Xiong, Haitian Zheng, [Jiebo Luo](https://www.cs.rochester.edu/u/jluo/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.11337)]

**Global Image Sentiment Transfer.**<br>
*Jie An, Tianlang Chen, Songyang Zhang, [Jiebo Luo](https://www.cs.rochester.edu/u/jluo/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.11989)]

**MichiGAN: Multi-Input-Conditioned Hair Image Generation for Portrait Editing.**<br>
*Zhentao Tan, [Menglei Chai](https://mlchai.com/), Dongdong Chen, Jing Liao, Qi Chu, Lu Yuan, Sergey Tulyakov, Nenghai Yu.*
SIGGRAPH 2020. [[PDF](https://mlchai.com/files/tan2020michigan.pdf)]

**Interactive Sketch & Fill: Multiclass Sketch-to-Image Translation.**<br>
*[Arnab Ghosh](https://arnabgho.github.io/), [Richard Zhang](https://richzhang.github.io/), [Puneet K. Dokania](https://puneetkdokania.github.io/), [Oliver Wang](http://www.oliverwang.info/), [Alexei A. Efros](https://people.eecs.berkeley.edu/~efros/), [Philip H.S. Torr](http://www.robots.ox.ac.uk/~tvg/index.php), [Eli Shechtman](https://research.adobe.com/person/eli-shechtman/).*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1909.11081v2)] [[Github](https://arnabgho.github.io/iSketchNFill/)]

**SMIS: Semantically Multi-modal Image Synthesis.**<br> 
*[Zhen Zhu](https://zzhu.vision/), Zhiliang Xu, Ansheng You, [Xiang Bai](http://cloud.eic.hust.edu.cn:8071/~xbai/).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.12697)] [[Project](http://seanseattle.github.io/SMIS)] [[Github](https://github.com/Seanseattle/SMIS)]

**SEAN: Image Synthesis with Semantic Region-Adaptive Normalization.**</br>
*Peihao Zhu, Rameen Abdal, Yipeng Qin, Peter Wonka.*<br> 
CVPR 2020. [[PDF](https://arxiv.org/abs/1911.12861)] [[Video](https://youtu.be/0Vbj9xFgoUw)] [[Github](https://github.com/ZPdesu/SEAN)]

**MichiGAN: Multi-Input-Conditioned Hair Image Generation for Portrait Editing.**<br>
*Zhentao Tan, Menglei Chai, Dongdong Chen, Jing Liao, Qi Chu, Lu Yuan, Sergey Tulyakov, Nenghai Yu.*<br>
SIGGRAPH 2020. [[PDF](https://mlchai.com/files/tan2020michigan.pdf)]

**Describing Textures using Natural Language.**<br>
*Chenyun Wu, Mikayla Timm, Subhransu Maji.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.01180)] [[Project](https://people.cs.umass.edu/~chenyun/texture)]

**Controllable Image Synthesis via SegVAE.**<br>
*Yen-Chi Cheng, Hsin-Ying Lee, Min Sun, Ming-Hsuan Yang.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.08397)] [[Project](https://yccyenchicheng.github.io/SegVAE/)] [[Github](https://github.com/yccyenchicheng/SegVAE)]

**Few-shot Knowledge Transfer for Fine-grained Cartoon Face Generation.**<br>
*Nan Zhuang, Cheng Yang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.13332)] [[Github](https://github.com/minivision-ai/photo2cartoon)]

**CONFIG: Controllable Neural Face Image Generation.**<br>
*Marek Kowalski, Stephan J. Garbin, Virginia Estellers, Tadas Baltrušaitis, Matthew Johnson, Jamie Shotton.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2005.02671)] [[Github](https://github.com/microsoft/ConfigNet)]

**Controlling Style and Semantics in Weakly-Supervised Image Generation.**<br>
*Dario Pavllo, Aurelien Lucchi, and Thomas Hofmann.*<br>
ECCV 2020. [[PDF](https://dariopavllo.github.io/papers/style-semantics.pdf)] [[Github](https://github.com/dariopavllo/style-semantics)]

**ArtEditing: Modeling Artistic Workflows for Image Generation and Editing.**<br>
*[Hung-Yu Tseng](https://sites.google.com/site/hytseng0509/), [Matt Fisher](https://techmatt.github.io/), [Jingwan (Cynthia) Lu](https://research.adobe.com/person/jingwan-lu/), [Yijun Li](https://yijunmaverick.github.io/), [Vladimir (Vova) Kim](http://www.vovakim.com/), [Ming-Hsuan Yang](http://faculty.ucmerced.edu/mhyang/).*<br>
ECCV 2020. [[Github](https://github.com/hytseng0509/ArtEditing)]

**Task-agnostic Temporally Consistent Facial Video Editing.**<br>
*Meng Cao, Haozhi Huang, Hao Wang, Xuan Wang, Li Shen, Sheng Wang, Linchao Bao, Zhifeng Li, Jiebo Luo.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.01466)]

**XingGAN for Person Image Generation.**<br>
*[Hao Tang](http://disi.unitn.it/~hao.tang/), Song Bai, Li Zhang, Philip H. S. Torr, Nicu Sebe.*<br>
ECCV 2020.  [[Github](https://github.com/Ha0Tang/XingGAN)]

**DEEPSim: Deep Single Image Manipulation.**<br>
*[Yael Vinker](https://www.linkedin.com/in/yael-vinker-a91a00157/), [Eliahu Horwitz](https://www.linkedin.com/in/eliahu-horwitz), [Nir Zabari](), [Yedid Hoshen](http://www.cs.huji.ac.il/~ydidh).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.01289)] [[Project](http://www.vision.huji.ac.il/deepsim/)] [[Github](https://github.com/eliahuhorwitz/DeepSIM)]

**High-Resolution Neural Face Swapping for Visual Effects.**<br>
*Jacek Naruniec, Leonhard Helminger, Christopher Schroers, Romann M. Weber.*<br>
Eurographics Symposium on Rendering 2020. [[PDF](https://s3.amazonaws.com/disney-research-data/wp-content/uploads/2020/06/18013325/High-Resolution-Neural-Face-Swapping-for-Visual-Effects.pdf)] [[Project](http://studios.disneyresearch.com/2020/06/29/high-resolution-neural-face-swapping-for-visual-effects/)]

**Attentive Normalization for Conditional Image Generation.**<br>
*Yi Wang, Ying-Cong Chen, Xiangyu Zhang, Jian Sun, Jiaya Jia.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.03828)]

**Diverse Image Generation via Self-Conditioned GANs.**<br>
*Steven Liu, Tongzhou Wang, David Bau, Jun-Yan Zhu, Antonio Torralba.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2006.10728)] [[Project](http://selfcondgan.csail.mit.edu/)] [[Github](https://github.com/stevliu/self-conditioned-gan)] 

**Facial Expression Editing with Continuous Emotion Labels.**<br>
*Alexandra Lindt, Pablo Barros, Henrique Siqueira, Stefan Wermter.*<br>
FG 2019. [[PDF](https://arxiv.org/abs/2006.12210)]

**Neural Graphics Pipeline for Controllable Image Generation.**<br>
*Xuelin Chen, Daniel Cohen-Or, Baoquan Chen, Niloy J. Mitra.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.10569)]

**CONFIG: Controllable Neural Face Image Generation.**<br>
*Marek Kowalski, Stephan J. Garbin, Virginia Estellers, Tadas Baltrušaitis, Matthew Johnson, Jamie Shotton.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2005.02671)]

**Interactive Video Stylization Using Few-Shot Patch-Based Training.**<br>
*[Ondřej Texler](https://ondrejtexler.github.io/), David Futschik, Michal Kučera, Ondřej Jamriška, Šárka Sochorová, Menglei Chai, Sergey Tulyakov, Daniel Sýkora.*<br>
TOG 2020 (SIGGRAPH 2020) [[PDF](https://ondrejtexler.github.io/res/Texler20-SIG_patch-based_training_main.pdf)] [[Project](https://ondrejtexler.github.io/patch-based_training/)]

**Disentangled and Controllable Face Image Generation via 3D Imitative-Contrastive Learning.**<br>
*Yu Deng, Jiaolong Yang, Dong Chen, Fang Wen, Xin Tong.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.11660)]

### Individual Object Manipulation

**Learning to Manipulate Individual Objects in an Image.**<br>
*Yanchao Yang, Yutong Chen, Stefano Soatto.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.05495)]

**AssembleNet++: Assembling Modality Representations via Attention Connections.**<br>
*Michael S. Ryoo, AJ Piergiovanni, Juhana Kangaspunta, Anelia Angelova.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.08072)] [[Project](https://sites.google.com/corp/view/assemblenet/)]

**Object Properties Inferring from and Transfer for Human Interaction Motions.**<br>
*Qian Zheng, Weikai Wu, Hanting Pan, Niloy Mitra, Daniel Cohen-Or, Hui Huang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.08999)] [[Project](http://vcc.szu.edu.cn/research/2020/IT)]

**SESAME: Semantic Editing of Scenes by Adding, Manipulating or Erasing Objects.**<br>
*Evangelos Ntavelis, Andrés Romero, Iason Kastanis, Luc Van Gool, Radu Timofte.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.04977)]

**Self-Supervised Scene De-occlusion.**<br>
*[Xiaohang Zhan](https://xiaohangzhan.github.io/), Xingang Pan, Bo Dai, Ziwei Liu, Dahua Lin, and Chen Change Loy.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.02788)] [[Github](https://github.com/XiaohangZhan/deocclusion)] [[Project](https://xiaohangzhan.github.io/projects/deocclusion/)] [[Demo](https://www.youtube.com/watch?v=xIHCyyaB5gU)]

**3DLSN: End-to-End Optimization of Scene Layout.**<br>
*Andrew Luo, Zhoutong Zhang, Jiajun Wu, Joshua B. Tenenbaum.*<br>
CVPR 2020. [[PDF](https://jiajunwu.com/papers/3dsln_cvpr.pdf)] [[Project](http://3dsln.csail.mit.edu/)]

**DJRN: Detailed 2D-3D Joint Representation for Human-Object Interaction.**<br>
*Yong-Lu Li, Xinpeng Liu, Han Lu, Shiyi Wang, Junqi Liu, Jiefeng Li, Cewu Lu.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.08154)] [[Github](https://github.com/DirtyHarryLYL/DJ-RN)]

**AutoSweep: Recovering 3D Editable Objects from a Single Photograph.**<br>
*Xin Chen, Yuwei Li, Xi Luo, Tianjia Shao, Jingyi Yu, Kun Zhou, Youyi Zheng.*<br>
IVCJ 2018. [[PDF](https://arxiv.org/abs/2005.13312)] [[Project](https://chenxin.tech/files/Paper/TVCG2018_AutoSweep/AutoSweep.html)]

**Intrinsic Autoencoders for Joint Neural Rendering and Intrinsic Image Decomposition.**<br>
*Hassan Abu Alhaija, Siva Karthik Mustikovela, Justus Thies, Matthias Nießner, Andreas Geiger, Carsten Rother.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.16011)]

**Conditional Image Generation and Manipulation for User-Specified Content.**<br>
*David Stap, Maurits Bleeker, Sarah Ibrahimi, Maartje ter Hoeve.*<br>
AI for content creation workshop at CVPR 2020. [[PDF](https://arxiv.org/abs/2005.04909)]

**Context-Aware Synthesis and Placement of Object Instances.**<br>
*Donghoon Lee, Sifei Liu, Jinwei Gu, Ming-Yu Liu, Ming-Hsuan Yang, Jan Kautz.*<br>
NeurIPS 2018. [[PDF](https://arxiv.org/abs/1812.02350v1)] [[Project](https://research.nvidia.com/publication/2018-10_Context-aware-Synthesis-and)]

### Generating Accurate Descriptions

**Fashion Captioning: Towards Generating Accurate Descriptions with Semantic Rewards.**<br>
*Xuewen Yang, Heming Zhang, Di Jin, Yingru Liu, Chi-Hao Wu, Jianchao Tan, Dongliang Xie, Jue Wang, Xin Wang.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.02693)]

**POS-SCAN: More Grounded Image Captioning by Distilling Image-Text Matching Model.**<br>
*Yuanen Zhou, Meng Wang, Daqing Liu, Zhenzhen Hu, Hanwang Zhang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.00390v1)] [[Github](https://github.com/YuanEZhou/Grounded-Image-Captioning)]

**Spatio-Temporal Graph for Video Captioning with Knowledge Distillation.**<br>
*Boxiao Pan, Haoye Cai, De-An Huang, Kuan-Hui Lee, Adrien Gaidon, Ehsan Adeli, Juan Carlos Niebles.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.13942)]

### Guided Image-to-image translation

Part of this repository is about *Guided Image-to-image translation* which can be found [here](https://github.com/xiaweihao/awesome-image-translation/blob/master/README_.md#guided-image-to-image-translation).

**Graph2Plan: Learning Floorplan Generation from Layout Graphs.**<br>
*Ruizhen Hu, Zeyu Huang, Yuhan Tang, Oliver van Kaick, Hao Zhang, Hui Huang.*<br>
ACM Transactions on Graphics 2020. [[PDF](https://arxiv.org/abs/2004.13204)]

### Image-Based Virtual Try-On
*Image-Based Virtual Try-On* can be found [here](https://github.com/xiaweihao/awesome-image-translation/blob/master/clothed-human.md#image-based-virtual-try-on).

### Attribute Editing and Makeup Transfer
*Attribute Editing and Makeup Transfer* can be found [here](https://github.com/xiaweihao/awesome-image-translation/blob/master/README_.md#attribute-editing).

### Texture and Surface Mapping
*Texture and Surface Mapping* can be found [here](https://github.com/xiaweihao/awesome-neural-rendering/blob/master/README.md#texture-and-surface-mapping).

### Novel-View Synthesis
*Novel-View Synthesis* can be found [here](https://github.com/xiaweihao/awesome-neural-rendering/blob/master/README.md#novel-view-synthesis).

### Motion Transfer, Retargeting, Reenactment, Dubbing and Animation
*Motion Transfer, Retargeting, Reenactment, Dubbing and Animation* can be found [here](https://github.com/xiaweihao/awesome-neural-rendering/blob/master/README.md#motion-transfer--retargeting--reenactment--dubbing-and-animation).

### 3D Pose Transfer
*3D Pose Transfer* can be found [here](https://github.com/xiaweihao/awesome-neural-rendering/blob/master/README.md#attribute-editing).


## Prediction and Reasoning 

### Occlusion Reasoning

**Peek-a-Boo: Occlusion Reasoning in Indoor Scenes with Plane Representations.**<br>
*Ziyu Jiang, Buyu Liu, Samuel Schulter, Zhangyang Wang, [Manmohan Chandraker](http://cseweb.ucsd.edu/~mkchandraker/).*<br>
CVPR 2020. [[PDF](http://cseweb.ucsd.edu/~mkchandraker/pdf/cvpr20_peekaboo.pdf)]

**Self-Supervised Scene De-occlusion.**<br>
*[Xiaohang Zhan](https://xiaohangzhan.github.io/), [Xingang Pan](https://xingangpan.github.io/), Bo Dai, Ziwei Liu, Dahua Lin, Chen Change Loy.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.02788)] [[Project](https://xiaohangzhan.github.io/projects/deocclusion/)] [[Github](https://github.com/XiaohangZhan/deocclusion/)]

**Efficient Non-Line-of-Sight Imaging from Transient Sinograms.**<br>
*Mariko Isogawa, Dorian Chan, Ye Yuan, Kris Kitani, Matthew O'Toole.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.02787)]

### Video Prediction and Future Prediction

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

### Frame Interpolation, Extrapolation and Videos Generation

**Enhanced Quadratic Video Interpolation.**<br>
*Yihao Liu, Liangbin Xie, Li Siyao, Wenxiu Sun, Yu Qiao, Chao Dong.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2009.04642)]

**Boundary Content Graph Neural Network for Temporal Action Proposal Generation.**<br>
*Yueran Bai, Yingying Wang, Yunhai Tong, Yang Yang, Qiyue Liu, Junhui Liu.*<br>
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730120.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730120-supp.pdf)]

**DTVNet: Dynamic Time-lapse Video Generation via Single Still Image.**<br>
*Jiangning Zhang, Chao Xu, Liang Liu, Mengmeng Wang, Xia Wu, Yong Liu, Yunliang Jiang.*<br>
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500290.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500290-supp.zip)]

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


## Multi-Modality Translation

[[Eurus-Holmes/Awesome-Multimodal-Research](https://github.com/Eurus-Holmes/Awesome-Multimodal-Research)]</br>
[[pliang279/awesome-multimodal-ml](https://github.com/pliang279/awesome-multimodal-ml)]</br>

### Image-to-Text

**Structure-Aware Generation Network for Recipe Generation from Images.**<br>
*Hao Wang, Guosheng Lin, Steven C. H. Hoi, Chunyan Miao.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2009.00944)]

**Identity-Aware Multi-Sentence Video Description.**<br>
*Jae Sung Park, Trevor Darrell, Anna Rohrbach.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.09791)] [[Project](https://sites.google.com/site/describingmovies/lsmdc-2019/)]

**Decomposed Generation Networks with Structure Prediction for Recipe Generation from Food Images.**<br>
*Hao Wang, Guosheng Lin, Steven C. H. Hoi, Chunyan Miao.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.13374)]

**Inverse Cooking: Recipe Generation from Food Images.**<br>
*Amaia Salvador, Michal Drozdzal, Xavier Giro-i-Nieto, Adriana Romero.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1812.06164)]

### Text-to-Image

**DF-GAN: Deep Fusion Generative Adversarial Networks for Text-to-Image Synthesis.**<br>
*Ming Tao, Hao Tang, Songsong Wu, Nicu Sebe, Fei Wu, Xiao-Yuan Jing.*<br>
[[PDF](https://arxiv.org/abs/2008.05865)] [[Github](https://github.com/tobran/DF-GAN)]

**CVSE: Consensus-Aware Visual-Semantic Embedding for Image-Text Matching.**<br>
*Haoran Wang, Ying Zhang, Zhong Ji, Yanwei Pang, Lin Ma.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.08883)] [[Gtihub](https://github.com/BruceW91/CVSE)]

**CPGAN: Content-Parsing Generative Adversarial Networks for Text-to-Image Synthesis.**<br>
*Jiadong Liang, Wenjie Pei, Feng Lu.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/1912.08562)]

**TIME: Text and Image Mutual-Translation Adversarial Networks.**<br>
*Bingchen Liu, Kunpeng Song, Yizhe Zhu, Gerard de Melo, Ahmed Elgammal.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2005.13192)]

**S2IGAN: Speech-to-Image Generation via Adversarial Learning.**<br>
*Xinsheng Wang, Tingting Qiao, Jihua Zhu, Alan Hanjalic, Odette Scharenborg.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2005.06968)]

**3DLSN: End-to-End Optimization of Scene Layout.**<br>
*Andrew Luo, Zhoutong Zhang, Jiajun Wu, Joshua B. Tenenbaum.*<br>
CVPR 2020. [[PDF](https://jiajunwu.com/papers/3dsln_cvpr.pdf)] [[Project](http://3dsln.csail.mit.edu/)]

**CookGAN: Meal Image Synthesis from Ingredients.**<br>
*Fangda Han, Ricardo Guerrero, Vladimir Pavlovic.*<br>
WACV 2020. [[PDF](https://arxiv.org/abs/2002.11493)]

**ControlGAN: Controllable Text-to-Image Generation.**<br>
*Bowen Li, Xiaojuan Qi, Thomas Lukasiewicz, Philip H. S. Torr.*<br>
NeurIPS 2019. [[PDF](https://papers.nips.cc/paper/8480-controllable-text-to-image-generation.pdf)] [[Github](https://github.com/mrlibw/ControlGAN)]

**Object-driven Text-to-Image Synthesis via Adversarial Training.**<br>
*Wenbo Li, Pengchuan Zhang, Lei Zhang, Qiuyuan Huang, Xiaodong He, Siwei Lyu, Jianfeng Gao.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1902.10740)]

**SwapText: Image Based Texts Transfer in Scenes.**<br>
*Qiangpeng Yang, Hongsheng Jin, Jun Huang, Wei Lin.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.08152)]

**Local-Global Video-Text Interactions for Temporal Grounding.**<br>
*[Jonghwan Mun](http://cvlab.postech.ac.kr/~jonghwan/), [Minsu Cho](http://cvlab.postech.ac.kr/~mcho/), [Bohyung Han](https://cv.snu.ac.kr/index.php/bhhan/).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.07514)] [[Github](https://github.com/JonghwanMun/LGI4temporalgrounding)]

**Image-to-Image Translation with Text Guidance.**<br>
*Bowen Li, Xiaojuan Qi, Philip H. S. Torr, Thomas Lukasiewicz.*<br>
arxiv, 12 Feb 2020. [[PDF](https://arxiv.org/abs/2002.05235)]

**Neural Image Inpainting Guided with Descriptive Text.**<br>
*Lisai Zhang, Qingcai Chen, Baotian Hu, Shuoran Jiang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.03212)]

**Cycle Text-To-Image GAN with BERT.**<br>
*Trevor Tsue, Samir Sen, Jason Li.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2003.12137)] [Github](https://github.com/suetAndTie/cycle-image-gan)]

**ManiGAN: Text-Guided Image Manipulation.**<br>
*[Bowen Li](https://mrlibw.github.io/), [Xiaojuan Qi](https://xjqi.github.io/), Thomas Lukasiewicz, Philip H. S. Torr.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.06203)] [[Github](https://github.com/mrlibw/ManiGAN)]

**Controllable Text-to-Image Generation.**<br>
*Bowen Li, [Xiaojuan Qi](https://xjqi.github.io/), Thomas Lukasiewicz, Philip H. S. Torr.*<br>
NeurIPS 2019. [[PDF](https://arxiv.org/abs/1909.07083)]

**MirrorGAN: Learning Text-to-image Generation by Redescription.**<br>
*Tingting Qiao, Jing Zhang, Duanqing Xu, Dacheng Tao.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1903.05854)] [[Unofficial TensorFlow](https://github.com/taki0112/MirrorGAN-Tensorflow)]

**AttnGAN: Fine-Grained Text to Image Generation with Attentional Generative Adversarial Networks.**<br>
*Tao Xu, Pengchuan Zhang, Qiuyuan Huang, Han Zhang, Zhe Gan, Xiaolei Huang, Xiaodong He.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1711.10485)] [[Github](https://github.com/taoxugit/AttnGAN)]

**StackGAN++: Realistic Image Synthesis with Stacked Generative Adversarial Networks.**<br>
*Han Zhang, Tao Xu, Hongsheng Li, Shaoting Zhang, Xiaogang Wang, Xiaolei Huang, Dimitris Metaxas.*<br>
TPAMI 2018. [[PDF](https://arxiv.org/abs/1710.10916)] [[Github](https://github.com/hanzhanggit/StackGAN-v2)]

**StackGAN: Text to Photo-realistic Image Synthesis with Stacked Generative Adversarial Networks.**<br>
*Han Zhang, Tao Xu, Hongsheng Li, Shaoting Zhang, Xiaogang Wang, Xiaolei Huang, Dimitris Metaxas.*<br>
ICCV 2017. [[PDF](https://arxiv.org/abs/1612.03242v2)] [[Github](https://github.com/hanzhanggit/StackGAN-Pytorch)]

**Generative Adversarial Text to Image Synthesis.**<br>
*Scott Reed, Zeynep Akata, Xinchen Yan, Lajanugen Logeswaran, Bernt Schiele, Honglak Lee.*<br>
ICML 2016. [[PDF](https://arxiv.org/abs/1605.05396)] [[Github](https://github.com/reedscot/icml2016)]

**Learning Deep Representations of Fine-grained Visual Descriptions.**<br>
*Scott Reed, Zeynep Akata, Bernt Schiele, Honglak Lee.*<br>
CVPR 2016. [[PDF](https://arxiv.org/abs/1605.05395)] [[Github](https://github.com/reedscot/cvpr2016)]

### Speech and Text

**Synchronous Speech Recognition and Speech-to-Text Translation with Interactive Decoding.**<br>
*Yuchen Liu, Jiajun Zhang, Hao Xiong, Long Zhou, Zhongjun He, Hua Wu, Haifeng Wang, Chengqing Zong.*<br>
AAAI 2020. [[PDF](https://arxiv.org/abs/1912.07240)]

**Transfer Learning from Speaker Verification to Multispeaker Text-To-Speech Synthesis.**<br>
*Ye Jia, Yu Zhang, Ron J. Weiss, Quan Wang, Jonathan Shen, Fei Ren, Zhifeng Chen, Patrick Nguyen, Ruoming Pang, Ignacio Lopez Moreno, Yonghui Wu.*<br>
eurIPS 2018. [[PDF](https://arxiv.org/abs/1806.04558v4)] [[Github](https://github.com/CorentinJ/Real-Time-Voice-Cloning)] [[Github](https://github.com/Suhee05/Text-Independent-Speaker-Verification)]

**In Other News: a Bi-style Text-to-speech Model for Synthesizing Newscaster Voice with Limited Data.**<br>
*Nishant Prateek, Mateusz Łajszczak, Roberto Barra-Chicote, Thomas Drugman, Jaime Lorenzo-Trueba, Thomas Merritt, Srikanth Ronanki, Trevor Wood.*<br>
NAACL. [[PDF](https://www.aclweb.org/anthology/N19-2026/)]

**The Theory behind Controllable Expressive Speech Synthesis: a Cross-disciplinary Approach.**<br>
*Noé Tits, Kevin El Haddad, Thierry Dutoit.*<br>
arxiv, 14 Oct 2019. IntechOpen. [[PDF](https://arxiv.org/abs/1910.06234v1)]

**Token-Level Ensemble Distillation for Grapheme-to-Phoneme Conversion.**<br>
*Hao Sun, Xu Tan, Jun-Wei Gan, Hongzhi Liu, Sheng Zhao, Tao Qin, Tie-Yan Liu.*<br>
interspeech 2019. [[PDF](https://arxiv.org/abs/1911.06573v1)] 

**Independent and Automatic Evaluation of Acoustic-to-Articulatory Inversion Models.**<br>
*Maud Parrot, Juliette Millet, Ewan Dunbar.*<br>
arxiv, 15 Nov 2019. [[PDF](https://arxiv.org/pdf/1911.06573v1.pdf)]

**Using VAEs and Normalizing Flows for One-shot Text-To-Speech Synthesis of Expressive Speech.**<br>
*Vatsal Aggarwal, Marius Cotescu, Nishant Prateek, Jaime Lorenzo-Trueba, Roberto Barra-Chicote.*<br>
arxiv, 20 Nov 2019. [[PDF](https://arxiv.org/abs/1911.12760v1)] 

### Image-and-Voice

**Music Gesture for Visual Sound Separation.**<br>
*Chuang Gan, Deng Huang, Hang Zhao, Joshua B. Tenenbaum, Antonio Torralba.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.09476)] [[Project](http://music-gesture.csail.mit.edu/)]

**Vector Quantized Contrastive Predictive Coding for Template-based Music Generation.**<br>
*Gaëtan Hadjeres, Léopold Crestel.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.10120)] [[Github](https://github.com/SonyCSLParis/vqcpc-bach)]

**Foley Music: Learning to Generate Music from Videos.**<br>
*Chuang Gan, Deng Huang, Peihao Chen, Joshua B. Tenenbaum, Antonio Torralba.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.10984)] [[Project](http://foley-music.csail.mit.edu/)]

**Crossing You in Style: Cross-modal Style Transfer from Music to Visual Arts.**<br>
*Cheng-Che Lee, Wan-Yi Lin, Yen-Ting Shih, Pei-Yi Patricia Kuo, Li Su.*<br>
[[PDF](https://arxiv.org/abs/2009.08083)]

**DanceIt: Music-inspired Dancing Video Synthesis.**<br>
*Xin Guo, Jia Li, Yifan Zhao.*<br>

**Learning Individual Speaking Styles for Accurate Lip to Speech Synthesis.**<br>
*K R Prajwal, Rudrabha Mukhopadhyay, Vinay Namboodiri, C V Jawahar.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2005.08209)] [[Github](https://github.com/Rudrabha/Lip2Wav)]

**Attention-based Residual Speech Portrait Model for Speech to Face Generation.**<br>
*Jianrong Wang, Xiaosheng Hu, Li Liu, Wei Liu, Mei Yu, Tianyi Xu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.04536)]

**Speech2Face: Learning the Face Behind a Voice.**<br>
*Tae-Hyun Oh, Tali Dekel, Changil Kim, Inbar Mosseri, William T. Freeman, Michael Rubinstein, Wojciech Matusik.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1905.09773)] [[project](https://speech2face.github.io/)] [[Related Work](https://speech2face.github.io/)]

### Voice-to-Voice

**Generative Modelling for Controllable Audio Synthesis of Expressive Piano Performance.**<br>
*Hao Hao Tan, Yin-Jyun Luo, Dorien Herremans.*<br>
ICML Workshop 2020. [[PDF](https://arxiv.org/abs/2006.09833)] [[Github](https://github.com/gudgud96/piano-synthesis)] [[MAESTRO v2.0.0](https://magenta.tensorflow.org/datasets/maestro)] [[WaveGlow](https://github.com/yjlolo/constant-memory-waveglow)]

**REMI: Pop Music Transformer: Generating Music with Rhythm and Harmony.**<br>
*Yu-Siang Huang, Yi-Hsuan Yang.*<br>
arxiv, 1 Feb 2020. [[PDF](https://arxiv.org/abs/2002.00212)] [[Github](https://github.com/YatingMusic/remi)] [[Demo](http://vibertthio.com/transformer/)]

**Speech-to-Singing Conversion in an Encoder-Decoder Framework.**<br>
*Jayneel Parekh, Preeti Rao, Yi-Hsuan Yang.*<br>
ICASSP 2020. 
[[PDF](https://arxiv.org/abs/2002.06595)] [[Github](https://github.com/jayneelparekh/sp2si-code)] 
[[Project](https://jayneelparekh.github.io/icassp20/)]
[[NUS-48E dataset](https://smcnus.comp.nus.edu.sg/nus-48e-sung-and-spoken-lyrics-corpus/)]

**GAN-TTS: High Fidelity Speech Synthesis with Adversarial Networks.**<br>
*Mikołaj Bińkowski, Jeff Donahue, Sander Dieleman, Aidan Clark, Erich Elsen, Norman Casagrande, Luis C. Cobo, Karen Simonyan.*<br>
ICASSP 2020. [[PDF](https://arxiv.org/abs/1909.11646)]

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

**Hierarchical Style-based Networks for Motion Synthesis.**<br> 
*Jingwei Xu, Huazhe Xu, Bingbing Ni, Xiaokang Yang, Xiaolong Wang, Trevor Darrell.*<br>
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123560171.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123560171-supp.pdf)]

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


### Scene Graph Generation

**Scene Graph to Image Generation with Contextualized Object Layout Refinement.**<br>
*Maor Ivgi, Yaniv Benny, Avichai Ben-David, Jonathan Berant, Lior Wolf.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2009.10939)]

**Visual Commonsense Graphs: Reasoning about the Dynamic Context of a Still Image.**<br>
*Jae Sung Park, Chandra Bhagavatula, Roozbeh Mottaghi, Ali Farhadi, Yejin Choi.*<br>
arxiv 2020. [[](https://arxiv.org/abs/2004.10796)] [[Project](http://visualcomet.xyz/)]

**High-Fidelity Synthesis with Disentangled Representation.**<br>
*Wonkwang Lee, Donggyun Kim, Seunghoon Hong, Honglak Lee.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2001.04296)]

**House-GAN: Relational Generative Adversarial Networks for Graph-constrained House Layout Generation.**<br>
*Nelson Nauata, Kai-Hung Chang, Chin-Yi Cheng, Greg Mori, Yasutaka Furukawa.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2003.06988)]

**Learning Visual Commonsense for Robust Scene Graph Generation.**<br>
*Alireza Zareian, Haoxuan You, Zhecan Wang, Shih-Fu Chang.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2006.09623)]

**Learning Canonical Representations for Scene Graph to Image Generation.**<br>
*Roei Herzig, Amir Bar, Huijuan Xu, Gal Chechik, Trevor Darrell, Amir Globerson.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/1912.07414)]

**Sketching Image Gist: Human-Mimetic Hierarchical Scene Graph Generation.**<br>
*[Wenbin Wang](http://www.kennethwong.tech/), Ruiping Wang, Shiguang Shan, Xilin Chen.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.08760)]

**Neural Design Network: Graphic Layout Generation with Constraints.**<br>
*Hsin-Ying Lee, Weilong Yang, Lu Jiang, Madison Le, Irfan Essa, Haifeng Gong, Ming-Hsuan Yang.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/1912.09421)]

**Learning Physical Graph Representations from Visual Scenes.**<br>
*Daniel M. Bear, Chaofei Fan, Damian Mrowca, Yunzhu Li, Seth Alter, Aran Nayebi, Jeremy Schwartz, Li Fei-Fei, Jiajun Wu, Joshua B. Tenenbaum, Daniel L.K. Yamins.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.12373)]

**Learning Canonical Representations for Scene Graph to Image Generation.**<br>
*[Roei Herzig](https://roeiherz.github.io/), [Amir Bar](http://www.amirbar.net/), [Huijuan Xu](https://cs-people.bu.edu/hxu/), [Gal Chechik](https://research.nvidia.com/person/gal-chechik), [Trevor Darrell](https://people.eecs.berkeley.edu/~trevor/), [Amir Globerson](http://www.cs.tau.ac.il/~gamir/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/1912.07414)]

### Misc


**Swapping Autoencoder for Deep Image Manipulation.**<br>
*Taesung Park, Jun-Yan Zhu, Oliver Wang, Jingwan Lu, Eli Shechtman, Alexei Efros, Richard Zhang.*<br>
NeurIPS 2020. [[PDF]()]

**Differentiable Augmentation for Data-Efficient GAN Training.**<br>
*Shengyu Zhao, Zhijian Liu, Ji Lin (MIT) · Jun-Yan Zhu, Song Han.*<br>
NeurIPS 2020. [[PDF]()]

**GRAF: Generative Radiance Fields for 3D-Aware Image Synthesis.**<br>
*Katja Schwarz, Yiyi Liao, Michael Niemeyer, Andreas Geiger.*<br>
NeurIPS 2020. [[PDF]()]

**SMILE: Semantically-guided Multi-attribute Image and Layout Editing.**<br>
*Andrés Romero, Luc Van Gool, Radu Timofte.*<br>
arxiv 2020.[[PDF](https://arxiv.org/abs/2010.02315)]

**Stuttering Speech Disfluency Prediction using Explainable Attribution Vectors of Facial Muscle Movements.**<br>
*Arun Das, Jeffrey Mock, Henry Chacon, Farzan Irani, Edward Golob, Peyman Najafirad.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.01231)]

**MaterialGAN: Reflectance Capture using a Generative SVBRDF Model.**<br>
*Yu Guo, Cameron Smith, Miloš Hašan, Kalyan Sunkavalli, Shuang Zhao.*<br>
Siggraph Asia 2020. [[PDF](https://arxiv.org/abs/2010.00114)]

**CariMe: Unpaired Caricature Generation with Multiple Exaggerations.**<br>
*Zheng Gu, Chuanqi Dong, Jing Huo, Wenbin Li, Yang Gao.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.00246)]

**Structure-Aware Human-Action Generation.**<br>
*Ping Yu, Yang Zhao, Chunyuan Li, Junsong Yuan, Changyou Chen.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.01971)] [[Github](https://github.com/PingYu-iris/SA-GCN)]

**Exposing GAN-generated Faces Using Inconsistent Corneal Specular Highlights.**<br>
*Shu Hu, Yuezun Li, Siwei Lyu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.11924)]

**X-LXMERT: Paint, Caption and Answer Questions with Multi-Modal Transformers.**<br>
*Jaemin Cho, Jiasen Lu, Dustin Schwenk, Hannaneh Hajishirzi, Aniruddha Kembhavi.*<br>
EMNLP 2020. [[PDF](https://arxiv.org/abs/2009.11278)]

**VAL: Image Search with Text Feedback by Visiolinguistic Attention Learning.**<br>
*Yanbei Chen, Shaogang Gong, Loris Bazzani.*<br>
CVPR 2020. [[PDF](http://openaccess.thecvf.com/content_CVPR_2020/papers/Chen_Image_Search_With_Text_Feedback_by_Visiolinguistic_Attention_Learning_CVPR_2020_paper.pdf)] [[Gtihub](https://github.com/yanbeic/VAL)]

**ShapeAssembly: Learning to Generate Programs for 3D Shape Structure Synthesis.**<br>
*R. Kenny Jones, Theresa Barton, Xianghao Xu, Kai Wang, Ellen Jiang, Paul Guerrero, Niloy J. Mitra, Daniel Ritchie.*<br>
SIGGRAPH Asia 2020. [[PDF](https://arxiv.org/abs/2009.08026)] [[Project](https://rkjones4.github.io/shapeAssembly.html)]

**Semantic Pyramid for Image Generation.**<br>
*Assaf Shocher, Yossi Gandelsman, Inbar Mosseri, Michal Yarom, Michal Irani, William T. Freeman, Tali Dekel.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.06221)] [[Github](https://github.com/rosinality/semantic-pyramid-pytorch)]

**Dynamic Future Net: Diversified Human Motion Generation.**<br>
*Wenheng Chen, He Wang, Yi Yuan, Tianjia Shao, Kun Zhou.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2009.05109)]

**High Frequency Component Helps Explain the Generalization of Convolutional Neural Networks.**<br> 
*Haohan Wang, Xindi Wu, Zeyi Huang, Eric P. Xing.*<br> 
CVPR 2020. [[PDF](https://arxiv.org/abs/1905.13545)]

**Learning Latent Representations Across Multiple Data Domains Using Lifelong VAEGAN.**<br> 
*Fei Ye, Adrian G. Bors.*<br> 
[[PDF](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650766.pdf)]

**TopoGAN: A Topology-Aware Generative Adversarial Network.**<br> 
*Fan Wang, Huidong Liu, Dimitris Samaras, Chao Chen.*<br> 
ECCV 2020. [[PDF](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123480120.pdf)]

**Piggyback GAN: Efficient Lifelong Learning for Image Conditioned Generation.**<br> 
*Mengyao Zhai, Lei Chen, Jiawei He, Megha Nawhal, Frederick Tung, Greg Mori.*<br> 
ECCV 2020. [[PDF](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660392.pdf)]

**not-so-BigGAN: Generating High-Fidelity Images on a Small Compute Budget.**<br> 
*Seungwook Han, Akash Srivastava, Cole Hurwitz, Prasanna Sattigeri, David D. Cox.*<br> 
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.04433)]

**Stability and Expressiveness of Deep Generative Models.**<br> 
*Mescheder, Lars Morten.*<br> 
PhD Dissertation 2020. [[PDF](https://publikationen.uni-tuebingen.de/xmlui/handle/10900/106074)]

**World-Consistent Video-to-Video Synthesis.**<br> 
*Arun Mallya, Ting-Chun Wang, Karan Sapra, Ming-Yu Liu.*<br> 
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.08509)] [[Github](https://nvlabs.github.io/wc-vid2vid/)]

**Fast Bi-layer Neural Synthesis of One-Shot Realistic Head Avatars.**<br> 
*Egor Zakharov, Aleksei Ivakhnenko, Aliaksandra Shysheya, Victor Lempitsky.*<br>
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123570511.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123570511-supp.pdf)]

**AutoSimulate: (Quickly) Learning Synthetic Data Generation.**<br>
*Harkirat Singh Behl, Atilim Güneş Baydin, Ran Gal, Philip H.S. Torr, Vibhav Vineet.*<br>
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670256.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670256-supp.pdf)]

**Structure-Aware Human-Action Generation.**<br>
*Ping Yu, Yang Zhao, Chunyuan Li, Junsong Yuan, Changyou Chen.*<br>
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123750018.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123750018-supp.pdf)]

**Synthesis and Completion of Facades from Satellite Imagery.**<br> 
*Xiaowei Zhang, Christopher May, Daniel Aliaga.*<br>
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470562.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470562-supp.zip)]

**Incorporating Reinforced Adversarial Learning in Autoregressive Image Generation.**<br>
*Kenan E. Ak, Ning Xu, Zhe Lin, Yilin Wang.*<br>
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660018.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660018-supp.pdf)]

**Visual-Relation Conscious Image Generation from Structured-Text.**<br>
*Duc Minh Vo, Akihiro Sugimoto.*<br>
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730290.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730290-supp.pdf)]

**Controlling Style and Semantics in Weakly-Supervised Image Generation.**<br> 
*Dario Pavllo, Aurelien Lucchi, Thomas Hofmann.*<br>
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123510477.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123510477-supp.zip)]

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

**Generative Hierarchical Features from Synthesizing Images.**<br>
*Yinghao Xu, Yujun Shen, Jiapeng Zhu, Ceyuan Yang, Bolei Zhou.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.10379)]

**Example-Guided Image Synthesis across Arbitrary Scenes using Masked Spatial-Channel Attention and Self-Supervision.**<br>
*Haitian Zheng, Haofu Liao, Lele Chen, Wei Xiong, Tianlang Chen, Jiebo Luo.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2004.10024)]

**OneGAN: Simultaneous Unsupervised Learning of Conditional Image Generation, Foreground Segmentation, and Fine-Grained Clustering.**<br>
*Yaniv Benny, Lior Wolf.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/1912.13471)]

**GANwriting: Content-Conditioned Generation of Styled Handwritten Word Images.**<br>
*Lei Kang, Pau Riba, Yaxing Wang, Marçal Rusiñol, Alicia Fornés, Mauricio Villegas.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2003.02567)]

**Few-shot Compositional Font Generation with Dual Memory.**<br>
*Junbum Cha, Sanghyuk Chun, Gayoung Lee, Bado Lee, Seonghyeon Kim, Hwalsuk Lee.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2005.10510)] [[Github](https://github.com/clovaai/dmfont)]

**Piggyback GAN: Efficient Lifelong Learning for Image Conditioned Generation.**<br>
*[Mengyao Zhai](http://www.sfu.ca/~mnawhal), Lei Chen, Jiawei He, Megha Nawhal, Frederick Tung, and Greg Mori.*<br>
ECCV 2020. [[PDF](http://www.sfu.ca/~mnawhal/projects/zhai_eccv20.pdf)]

**Generating Person Images with Appearance-aware Pose Stylizer.**<br>
*Siyu Huang, Haoyi Xiong, Zhi-Qi Cheng, Qingzhong Wang, Xingran Zhou, Bihan Wen, Jun Huan, Dejing Dou.*<br>
IJCAI 2020. [[PDF](https://arxiv.org/abs/2007.09077)] [[Github](https://github.com/siyuhuang/PoseStylizer)]

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

## Free-Hand Sketch

[Awesome-Sketch-Based-Applications](https://github.com/MarkMoHR/Awesome-Sketch-Based-Applications)

[[TorchSketch](https://github.com/PengBoXiangShang/torchsketch)] is an open source software library for free-hand sketch oriented deep learning research, which is built on the top of PyTorch.

**SketchEmbedNet: Learning Novel Concepts by Imitating Drawings.**<br>
*Alexander Wang, Mengye Ren, Richard Zemel.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.04806)]

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