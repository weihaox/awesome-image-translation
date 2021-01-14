# Controllable Image Generation

This repository is about *Controllable and Interpretable Image Generation* or *intelligent image manipulation*, which is a collection of papers on image generation and manipulation with the guidance by text, audio, camera pose or other information.  The Controlable Parameters can be Camera, Pose, Lighting, Color, Texture, Semantics, Expression, Speech.

## Table of Contents
- [Industry Demo or Product](#industry-demo-or-product)
- [Interactive and Controllable Image Manipulation](#interactive-and-controllable-image-manipulation)
  * [Highlight Component](#highlight-component)
  * [Rearrange and Retiming](#rearrange-and-retiming)
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
  * [Video Generation and Future Prediction](#video-generation-and-future-prediction)
  * [Videos Generation, Frame Interpolation and Extrapolation](#videos-generation--frame-interpolation-and-extrapolation)
- [Multi-modal Representation Learning and Application](#multi-modal-representation-learning-and-application)
  * [Visual Representation Learning (with Transformers)](#visual-representation-learning--with-transformers-)
  * [Image-Text Matching (Visual-Semantic/Lingustic Embedding)](#image-text-matching--visual-semantic-lingustic-embedding-)
  * [Unsupervised Visual Representation Learning](#unsupervised-visual-representation-learning)
- [Multi-Modality Translation](#multi-modality-translation)
  * [Image-to-Video](#image-to-video)
  * [Text-to-Video](#text-to-video)
  * [Image-to-Text](#image-to-text)
  * [Text-to-Image](#text-to-image)
  * [Speech-and-Text](#speech-and-text)
  * [Image-and-Voice](#image-and-voice)
  * [Voice-to-Voice](#voice-to-voice)
- [3D Shape Generation and Manipulation](#3d-shape-generation-and-manipulation)
- [GAN Improvement](#gan-improvement)
- [Image Quality Assessment](#image-quality-assessment)
- [Diving Deep into Image Synthesis](#diving-deep-into-image-synthesis)
  * [Invertible Neural Network (Flow-based Generative Model)](#invertible-neural-network--flow-based-generative-model-)
  * [StyleGAN-Based Method](#stylegan-based-method)
  * [Transformer-Based](#transformer-based)
  * [Single-Image Training](#single-image-training)
  * [Fairness, Accountability, Privacy, Transparency and Ethics](#fairness--accountability--privacy--transparency-and-ethics)
  * [Data Efficiency](#data-efficiency)
  * [Dataset Biases](#dataset-biases)
  * [Hard or Unfamiliar Example](#hard-or-unfamiliar-example)
  * [Data or Distribution Augmentation](#data-or-distribution-augmentation)
  * [Long-Tailed, Open Set, and Class-Imbalanced Dataset](#long-tailed--open-set--and-class-imbalanced-dataset)
  * [Spatio-Temporal](#spatio-temporal)
  * [Neural Network Interpretability](#neural-network-interpretability)
  * [Others](#others)
- [DeepFake and Forensic](#deepfake-and-forensic)
- [2D to 3D Convertion](#2d-to-3d-convertion)
- [Free-Hand Sketch](#free-hand-sketch)
  * [2D Sketch to 3D Model](#2d-sketch-to-3d-model)
  * [2D Sketch to 2D Image](#2d-sketch-to-2d-image)

## Industry Demo or Product

**Google**: [Chimera Painter](https://storage.googleapis.com/chimera-painter/index.html).

**Adobe Sensei**: Material World, Scantastic, Sharp Shot, Super Dancing Queen/King, 2D Plus, Comic Blast, AR Together.

**Nvidia Maxine**: Nvidia’s AI-powered video-conferencing technology.

**Nvidia Imaginaire**: [Imaginaire](https://github.com/NVlabs/imaginaire) is a pytorch library that contains optimized implementation of several image and video synthesis methods developed at NVIDIA.

## Interactive and Controllable Image Manipulation

### Highlight Component 

**Zoom-in to the Details of Human-Centric Videos.**<br>
*Guanghan Li, Yaping Zhao, Mengqi Ji, Xiaoyun Yuan, Lu Fang.*<br>
ICIP 2020. [[PDF](https://arxiv.org/abs/2005.13222)]

**Layered Neural Rendering for Retiming People in Video.**<br>
*Erika Lu, Forrester Cole, Tali Dekel, Weidi Xie, Andrew Zisserman, David Salesin, William T. Freeman, Michael Rubinstein.*<br>
SIGGRAPH Asia 2020. [[PDF](https://arxiv.org/abs/2009.07833)] [[Project](https://retiming.github.io/)]

**Real-Time Selfie Video Stabilization.**<br>
*Jiyang Yu, Ravi Ramamoorthi, Keli Cheng, Michel Sarkis, Ning Bi.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.02007)]

### Rearrange and Retiming

**Layered Neural Rendering for Retiming People in Video.**<br>
*Erika Lu, Forrester Cole, Tali Dekel, Weidi Xie, Andrew Zisserman, David Salesin, William T. Freeman, Michael Rubinstein.*<br>
SIGGRAPH Asia 2020. [[PDF](https://arxiv.org/abs/2009.07833)] [[Project](https://retiming.github.io/)]

**Neural Scene Graphs for Dynamic Scenes.**<br>
*Julian Ost, Fahim Mannan, Nils Thuerey, Julian Knodt, Felix Heide.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.10379)]

**Self-Supervised Scene De-occlusion.**<br>
*[Xiaohang Zhan](https://xiaohangzhan.github.io/), Xingang Pan, Bo Dai, Ziwei Liu, Dahua Lin, and Chen Change Loy.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.02788)] [[Github](https://github.com/XiaohangZhan/deocclusion)] [[Project](https://xiaohangzhan.github.io/projects/deocclusion/)] [[Demo](https://www.youtube.com/watch?v=xIHCyyaB5gU)]

### Change Where You Want

**GAN-Control: Explicitly Controllable GANs.**<br>
*Alon Shoshan, Nadav Bhonker, Igor Kviatkovsky, Gerard Medioni.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2101.02477)]

**HOI Analysis: Integrating and Decomposing Human-Object Interaction.**<br>
*[Yong-Lu Li](https://dirtyharrylyl.github.io/), Xinpeng Liu, Xiaoqian Wu, Yizhuo Li, [Cewu Lu](http://mvig.sjtu.edu.cn/).*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2010.16219)] [[Project](https://github.com/DirtyHarryLYL/HAKE-Action-Torch)] [[Github](http://github.com/DirtyHarryLYL/HAKE-Action-Torch/tree/IDN-(Integrating-Decomposing-Network))]

**SymNet: Symmetry and Group in Attribute-Object Compositions.**<br>
*Yong-Lu Li, [Yue Xu](https://silicx.github.io/), Xiaohan Mao, Cewu Lu.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.00587)] [[Github](https://github.com/DirtyHarryLYL/SymNet)]

**Shapes and Context: In-the-Wild Image Synthesis & Manipulation.**<br>
*[Aayush Bansal](http://www.cs.cmu.edu/~aayushb/), [Yaser Sheikh](http://www.cs.cmu.edu/~yaser/), [Deva Ramanan](http://www.cs.cmu.edu/~deva/).*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1906.04728)] [[Project](http://www.cs.cmu.edu/~aayushb/OpenShapes/)] [[Github](https://github.com/aayushbansal/OpenShapes)]

**SkyAR: Castle in the Sky: Dynamic Sky Replacement and Harmonization in Videos.**<br>
*Zhengxia Zou.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.11800)] [[Project](https://jiupinjia.github.io/skyar/)] [[Github](https://github.com/jiupinjia/SkyAR)]

**Lightweight Generative Adversarial Networks for Text-Guided Image Manipulation.**<br>
*Bowen Li, Xiaojuan Qi, Philip Torr, Thomas Lukasiewicz.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2010.12136)] [[Github](https://github.com/mrlibw/Lightweight-Manipulation)]

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

**Cue Me In: Content-Inducing Approaches to Interactive Story Generation.**<br>
*Faeze Brahman, Alexandru Petrusca, Snigdha Chaturvedi.*<br>
AACL 2020. [[PDF](https://arxiv.org/abs/2010.09935)]

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
SIGGRAPH 2020. [[PDF](https://mlchai.com/files/tan2020michigan.pdf)] [[Github](https://github.com/tzt101/MichiGAN)]

**Interactive Sketch & Fill: Multiclass Sketch-to-Image Translation.**<br>
*[Arnab Ghosh](https://arnabgho.github.io/), [Richard Zhang](https://richzhang.github.io/), [Puneet K. Dokania](https://puneetkdokania.github.io/), [Oliver Wang](http://www.oliverwang.info/), [Alexei A. Efros](https://people.eecs.berkeley.edu/~efros/), [Philip H.S. Torr](http://www.robots.ox.ac.uk/~tvg/index.php), [Eli Shechtman](https://research.adobe.com/person/eli-shechtman/).*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1909.11081v2)] [[Github](https://arnabgho.github.io/iSketchNFill/)]

**SMIS: Semantically Multi-modal Image Synthesis.**<br> 
*[Zhen Zhu](https://zzhu.vision/), Zhiliang Xu, Ansheng You, [Xiang Bai](http://cloud.eic.hust.edu.cn:8071/~xbai/).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.12697)] [[Project](http://seanseattle.github.io/SMIS)] [[Github](https://github.com/Seanseattle/SMIS)]

**SEAN: Image Synthesis with Semantic Region-Adaptive Normalization.**</br>
*Peihao Zhu, Rameen Abdal, Yipeng Qin, Peter Wonka.*<br> 
CVPR 2020. [[PDF](https://arxiv.org/abs/1911.12861)] [[Video](https://youtu.be/0Vbj9xFgoUw)] [[Github](https://github.com/ZPdesu/SEAN)]

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

**Neural Scene Graphs for Dynamic Scenes.**<br>
*Julian Ost, Fahim Mannan, Nils Thuerey, Julian Knodt, Felix Heide.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.10379)]

**Self-Supervised Scene De-occlusion.**<br>
*[Xiaohang Zhan](https://xiaohangzhan.github.io/), Xingang Pan, Bo Dai, Ziwei Liu, Dahua Lin, and Chen Change Loy.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.02788)] [[Github](https://github.com/XiaohangZhan/deocclusion)] [[Project](https://xiaohangzhan.github.io/projects/deocclusion/)] [[Demo](https://www.youtube.com/watch?v=xIHCyyaB5gU)]

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

**Describing Textures using Natural Language.**<br>
*Chenyun Wu, Mikayla Timm, Subhransu Maji.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.01180)] [[Project](https://people.cs.umass.edu/~chenyun/texture)]

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

### Video Generation and Future Prediction

**Learning to Anticipate Egocentric Actions by Imagination.**<br>
*Yu Wu, Linchao Zhu, Xiaohan Wang, Yi Yang, Fei Wu.*<br>
TIP 2021. [[PDF](https://arxiv.org/abs/2101.04924)]

**ArrowGAN: Learning to Generate Videos by Learning Arrow of Time.**<br>
*Kibeom Hong, Youngjung Uh, Hyeran Byun.*<br>
Neurocomputing 2021. [[PDF](https://arxiv.org/abs/2101.03710)]

**InMoDeGAN: Interpretable Motion Decomposition Generative Adversarial Network for Video Generation.**<br>
*Yaohui Wang, Francois Bremond, Antitza Dantcheva.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.03049)] [[Project](https://wyhsirius.github.io/InMoDeGAN/)]

**Animating Pictures with Eulerian Motion Fields.**<br>
*Aleksander Holynski, Brian Curless, Steven M. Seitz, Richard Szeliski.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.15128)]

**Vid-ODE: Continuous-Time Video Generation with Neural Ordinary Differential Equation.**<br>
*Sunghyun Park, Kangyeol Kim, Junsoo Lee, Jaegul Choo, Joonseok Lee, Sookyung Kim, Edward Choi.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.08188)]

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
 

### Videos Generation, Frame Interpolation and Extrapolation

Video from a single image or text can be found at [here](https://github.com/weihaox/awesome-image-translation/blob/master/content/image-generation.md#image-to-video).

**Softmax Splatting for Video Frame Interpolation.**<br>
*Simon Niklaus, Feng Liu.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.05534)] [[Github](http://sniklaus.com/softsplat)]

**FLAVR: Flow-Agnostic Video Representations for Fast Frame Interpolation.**<br>
*Tarun Kalluri, Deepak Pathak, Manmohan Chandraker, Du Tran.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.08512)] [[Project](https://tarun005.github.io/FLAVR/)]

**NSFF: Neural Scene Flow Fields for Space-Time View Synthesis of Dynamic Scenes.**<br>
*Zhengqi Li, Simon Niklaus, Noah Snavely, Oliver Wang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.13084)] [[Github](http://www.cs.cornell.edu/~zl548/NSFF/)]

ConvTransformer: A Convolutional Transformer Network for Video Frame Synthesis
Zhouyong Liu, Shun Luo, Wubin Li, Jingben Lu, Yufan Wu, Chunguo Li, Luxi Yang

**RIFE: Real-Time Intermediate Flow Estimation for Video Frame Interpolation.**<br>
*Zhewei Huang, Tianyuan Zhang, Wen Heng, Boxin Shi, Shuchang Zhou.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.06294)] [[Github](https://github.com/hzwer/arXiv2020-RIFE)]

**Enhanced Quadratic Video Interpolation.**<br>
*Yihao Liu, Liangbin Xie, Li Siyao, Wenxiu Sun, Yu Qiao, Chao Dong.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2009.04642)]

**Boundary Content Graph Neural Network for Temporal Action Proposal Generation.**<br>
*Yueran Bai, Yingying Wang, Yunhai Tong, Yang Yang, Qiyue Liu, Junhui Liu.*<br>
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730120.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730120-supp.pdf)]

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

## Multi-modal Representation Learning and Application

### Visual Representation Learning (with Transformers)

**CLIP: Learning Transferable Visual Models From Natural Language Supervision.**<br>
*Alec Radford, Jong Wook Kim, Chris Hallacy, Aditya Ramesh, Gabriel Goh, Sandhini Agarwal, Girish Sastry, Amanda Askell, Pamela Mishkin, Jack Clark, Gretchen Krueger, Ilya Sutskever.*<br>
2021. [[PDF](https://cdn.openai.com/papers/Learning_Transferable_Visual_Models_From_Natural_Language.pdf)] [[Github](https://github.com/openai/CLIP)] [[Blog](https://openai.com/blog/clip/)]

**VirTex: Learning Visual Representations from Textual Annotations.**<br>
*Karan Desai, Justin Johnson.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.06666)] [[Github](https://github.com/kdexd/virtex)]

**HERO: Hierarchical Encoder for Video+Language Omni-representation Pre-training.**<br>
*Linjie Li, Yen-Chun Chen, Yu Cheng, Zhe Gan, Licheng Yu, Jingjing Liu.*<br>
EMNLP 2020. [[PDF](https://arxiv.org/abs/2005.00200)] [[Github](https://github.com/linjieli222/HERO_Video_Feature_Extractor)]

**Multimodal Pretraining Unmasked: Unifying the Vision and Language BERTs.**<br>
*Emanuele Bugliarello, Ryan Cotterell, Naoaki Okazaki, Desmond Elliott.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.15124)]

**MAG: Integrating Multimodal Information in Large Pretrained Transformers.**<br>
*Wasifur Rahman, Md. Kamrul Hasan, Sangwu Lee, Amir Zadeh, Chengfeng Mao, Louis-Philippe Morency, Ehsan Hoque.*<br>
ACL 2020. [[PDF](https://arxiv.org/abs/1908.05787)] [[Github](https://github.com/WasifurRahman/BERT_multimodal_transformer)]

**UNITER: UNiversal Image-TExt Representation Learning.**<br> 
*Yen-Chun Chen, Linjie Li, Licheng Yu, Ahmed El Kholy, Faisal Ahmed, Zhe Gan, Yu Cheng, Jingjing Liu.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/1909.11740)] [[Github](https://github.com/ChenRocks/UNITER)]

**VL-BERT: Pre-training of Generic Visual-Linguistic Representations.**<br>
*Weijie Su, Xizhou Zhu, Yue Cao, Bin Li, Lewei Lu, Furu Wei, Jifeng Dai.*<br>
ICLR 2020. [[PDF] (https://arxiv.org/abs/190 8.08530)] [[Github](https://github.com/jackroos/VL-BERT)]

**VILLA: Large-Scale Adversarial Training for Vision-and-Language Representation Learning.**<br>
*Zhe Gan, Yen-Chun Chen, Linjie Li, Chen Zhu, Yu Cheng, Jingjing Liu.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.06195)] [[Github](https://github.com/zhegan27/LXMERT-AdvTrain)]

**LXMERT: Learning Cross-Modality Encoder Representations from Transformers.**<br>
*Hao Tan, Mohit Bansal.*<br>
EMNLP 2019. [[PDF](https://arxiv.org/abs/1908.07490)] [[Github](https://github.com/airsplay/lxmert)]

**ViLBERT: Pretraining Task-Agnostic Visiolinguistic Representations for Vision-and-Language Tasks.**<br>
*Jiasen Lu, Dhruv Batra, Devi Parikh, Stefan Lee.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/1908.02265)] [[Github](https://github.com/jiasenlu/vilbert_beta)]

**12-in-1: Multi-Task Vision and Language Representation Learning.**<br>
*Jiasen Lu, Vedanuj Goswami, Marcus Rohrbach, Devi Parikh, Stefan Lee.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.02315)] [[Github](https://github.com/facebookresearch/vilbert-multi-task)]

**VisualBERT: A Simple and Performant Baseline for Vision and Language.**<br>
*Liunian Harold Li, Mark Yatskar, Da Yin, Cho-Jui Hsieh, Kai-Wei Chang.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/1908.03557)] [[Github](https://github.com/uclanlp/visualbert)]

### Image-Text Matching (Visual-Semantic/Lingustic Embedding)

[a collection of Image-Text Matching (Visual-Semantic/Lingustic Embedding)](https://blog.csdn.net/weixin_42/article/details/104275300)

**Similarity Reasoning and Filtration for Image-Text Matching.**<br>
*Haiwen Diao, Ying Zhang, Lin Ma, Huchuan Lu.*<br>
AAAI 2021. [[PDF](https://arxiv.org/abs/2101.01368)]

**Natural Language Rationales with Full-Stack Visual Reasoning: From Pixels to Semantic Frames to Commonsense Graphs.**<br>
*Ana Marasović, Chandra Bhagavatula, Jae Sung Park, Ronan Le Bras, Noah A. Smith, Yejin Choi.*<br>
EMNLP 2020. [[PDF](https://arxiv.org/abs/2010.07526)]

**Vokenization: Improving Language Understanding with Contextualized, Visual-Grounded Supervision.**<br>
*Hao Tan, Mohit Bansal.*<br>
EMNLP 2020. [[PDF](https://arxiv.org/abs/2010.06775)] [[Github](https://github.com/airsplay/vokenization)]

**VIVO: Surpassing Human Performance in Novel Object Captioning with Visual Vocabulary Pre-Training.**<br>
*Xiaowei Hu Xi Yin Kevin Lin Lijuan Wang Lei Zhang Jianfeng Gao Zicheng Liu.*<br>
arxiv 2020. [[PDF](https://www.microsoft.com/en-us/research/publication/vivo-surpassing-human-performance-in-novel-object-captioning-with-visual-vocabulary-pre-training/)] [[Project](https://www.microsoft.com/en-us/research/project/azure-florence-vision-and-language/)]

**CVSE: Consensus-Aware Visual-Semantic Embedding for Image-Text Matching.**<br>
*Haoran Wang, Ying Zhang, Zhong Ji, Yanwei Pang, Lin Ma.*<br>
ECCV 2020. [[PDF] (https://arxiv.org/abs/2007.08883)] [[Github](https://github.com/BruceW91/CVSE)]

**Visual Semantic Reasoning for Image-Text Matching.**<br>
*Kunpeng Li, Yulun Zhang, Kai Li, Yuanyuan Li, Yun Fu.*<br>
ICCV 2019. [[PDF] (arxiv.org/abs/1909.02701)] [[Github](https://github.com/KunpengLi1994/VSRN)]

**Cross-modal Scene Graph Matching for Relationship-aware Image-Text Retrieval.**<br>
*Sijin Wang, Ruiping Wang, Ziwei Yao, Shiguang Shan, xilin Chen.*<br>
WACV 2020. [[PDF](https://arxiv.org/abs/1910.0513)]

**SAN: Saliency-Guided- Attention Network for Image-Sentence Matching.**<br>
*Zhong Ji, Haoran Wang, Jungong Han, Yanwei Pang.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1904.09471v1)]

**VSE++: Improving Visual-Semantic- Embeddings with Hard Negatives.**<br>
*Fartash Faghri, David. Fleet, Jamie Ryan Kiros, Sanja Fidler.*<br>
BMVC 2018. [[PDF](https://arxiv.org/abs/1707.05612)] [[Github](https://github.com/fartashf/vsepp)]

**Deep Fragment Embeddings for Bidirectional Image Sentence Mapping.**<br>
*Andrej Karpathy, Armand Joulin, Li Fei-Fei.*<br>
NeurIPS 2014. [[PDF](https://arxiv.org/abs/1406.5679)]

**DeViSE: Deep Visual/Semantic Embedding Model.**<br>
*Andrea Frome, Greg Corrado, Jonathon ShLens, Samy Bengio, Jeffrey Dean, Marc'Aurelio Ranzato Tomas Mikolov.*<br> 
NeurIPS 2013. [[PDF](https://static.googleusercontent.com/media/researchgoogle.com/zh-CN/pubs/archive/41473.pdf)]

**Learning Representations from Audio-Visual Spatial Alignment.**<br>
*Pedro Morgado, Yi Li, Nuno Vasconcelos.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2011.01819)]

**Representation Learning via Invariant Causal Mechanisms.**<br>
*Jovana Mitrovic, Brian McWilliams, Jacob Walker, Lars Buesing, Charles Blundell.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.07922)] 

**Contrastive Learning of General-Purpose Audio Representations.**<br>
*Aaqib Saeed, David Grangier, Neil Zeghidour.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.10915)]

**Learning Visual Representations for Transfer Learning by Suppressing Texture.**<br>
*Shlok Mishra, Anshul Shah, Ankan Bansal, Jonghyun Choi, Abhinav Shrivastava, Abhishek Sharma, David Jacobs.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.01901)]

### Unsupervised Visual Representation Learning

**Propagate Yourself: Exploring Pixel-Level Consistency for Unsupervised Visual Representation Learning.**<br>
*Zhenda Xie, Yutong Lin, Zheng Zhang, Yue Cao, Stephen Lin, Han Hu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.10043)] [[Github](https://github.com/lucidrains/pixel-level-contrastive-learning)]

**VinVL: Making Visual Representations Matter in Vision-Language Models.**<br>
*Pengchuan Zhang, Xiujun Li, Xiaowei Hu, Jianwei Yang, Lei Zhang, Lijuan Wang, Yejin Choi, Jianfeng Gao.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.00529)]


## Multi-Modality Translation

[[Eurus-Holmes/Awesome-Multimodal-Research](https://github.com/Eurus-Holmes/Awesome-Multimodal-Research)]</br>
[[pliang279/awesome-multimodal-ml](https://github.com/pliang279/awesome-multimodal-ml)]</br>

### Image-to-Video

**Animating Pictures with Eulerian Motion Fields.**<br>
*[Aleksander Holynski](http://www.holynski.org/), [Brian Curless](https://homes.cs.washington.edu/~curless/), [Steven M. Seitz](https://homes.cs.washington.edu/~seitz/), [Richard Szeliski](http://szeliski.org/RichardSzeliski.htm).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.15128)] [[Project](https://eulerian.cs.washington.edu/)] [[Video](https://www.youtube.com/watch?v=4zKliOMilGY)]

**Pose-Guided Human Animation from a Single Image in the Wild.**<br>
*Jae Shin Yoon, Lingjie Liu, Vladislav Golyanik, Kripasindhu Sarkar, Hyun Soo Park, Christian Theobalt.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.03796)]

**Lifespan Age Transformation Synthesis.**<br>
*Roy Or-El, Soumyadip Sengupta, Ohad Fried, Eli Shechtman, Ira Kemelmacher-Shlizerman.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2003.09764)] [[Project](https://grail.cs.washington.edu/projects/lifespan_age_transformation_synthesis/)] [[Github](https://github.com/royorel/Lifespan_Age_Transformation_Synthesis)] [[FFHQ-Aging Dataset](https://github.com/royorel/FFHQ-Aging-Dataset)]

**DeepLandscape: Adversarial Modeling of Landscape Videos.**<br>
*E. Logacheva, R. Suvorov, O. Khomenko, A. Mashikhin, and V. Lempitsky.*<br>
ECCV 2020. [[PDF](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123680256.pdf)] [[Github](https://github.com/saic-mdal/deep-landscape)] [[Project](https://saic-mdal.github.io/deep-landscape/)]

**DTVNet: Dynamic Time-lapse Video Generation via Single Still Image.**<br>
*Jiangning Zhang, Chao Xu, Liang Liu, Mengmeng Wang, Xia Wu, Yong Liu, Yunliang Jiang.*<br>
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500290.pdf)] [[Supplement](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500290-supp.zip)]

**SiENet: Siamese Expansion Network for Image Extrapolation.**<br>
*Xiaofeng Zhang, Feng Chen, Cailing Wang, Songsong Wu, Ming Tao, Guoping Jiang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.03851)]

**Hierarchical Patch VAE-GAN: Generating Diverse Videos from a Single Sample.**<br>
*Shir Gur, Sagie Benaim, Lior Wolf.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.12226)]

### Text-to-Video

**Video Generation From Text.**<br>
*Yitong Li, Martin Renqiang Min, Dinghan Shen, David Carlson, Lawrence Carin.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/1710.00421)]

**TiVGAN: Text to Image to Video Generation with Step-by-Step Evolutionary Generator.**<br>
*Doyeon Kim, Donggyu Joo, Junmo Kim.*<br>
IEEE Access 2020. [[PDF](https://arxiv.org/abs/2009.02018)]

### Image-to-Text

**End-to-End Video Question-Answer Generation with Generator-Pretester Network.**<br>
*Hung-Ting Su, Chen-Hsi Chang, Po-Wei Shen, Yu-Siang Wang, Ya-Liang Chang, Yu-Cheng Chang, Pu-Jen Cheng, Winston H. Hsu.*<br>
TCSVT 2020. [[PDF](https://arxiv.org/abs/2101.01447)]

**RecipeNLG: A Cooking Recipes Dataset for Semi-Structured Text Generation.**<br>
*Michał Bień, Michał Gilski, Martyna Maciejewska, Wojciech Taisner, Dawid Wiśniewski, Agnieszka Ławrynowicz.*<br>
arxiv 2020. [[PDF](https://www.aclweb.org/anthology/2020.inlg-1.4.pdf)] [[Github](https://github.com/Glorf/recipenlg)] [[Project](https://recipenlg.cs.put.poznan.pl/)] [[RecipeNLG dataset](https://recipenlg.cs.put.poznan.pl/dataset)] [[RecipeNLG's Recipe Generator](https://recipenlg.cs.put.poznan.pl/generator)]

**AutoCaption: Image Captioning with Neural Architecture Search.**<br>
*Xinxin Zhu, Weining Wang, Longteng Guo, Jing Liu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.09742)]

**Simple is not Easy: A Simple Strong Baseline for TextVQA and TextCaps.**<br>
*Qi Zhu, Chenyu Gao, Peng Wang, Qi Wu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.05153)] [[Github](https://github.com/ZephyrZhuQi/ssbaseline)]

**TAP: Text-Aware Pre-training for Text-VQA and Text-Caption.**<br>
*Zhengyuan Yang, Yijuan Lu, Jianfeng Wang, Xi Yin, Dinei Florencio, Lijuan Wang, Cha Zhang, Lei Zhang, Jiebo Luo.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.04638)]

**Image Captioning with Context-Aware Auxiliary Guidance.**<br>
*Zeliang Song, Xiaofei Zhou, Zhendong Mao, Jianlong Tan.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.05545)]

**LaBERT: Length-Controllable Image Captioning.**<br>
*Chaorui Deng, Ning Ding, Mingkui Tan, Qi Wu.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.09580)] [[Github](https://github.com/bearcatt/LaBERT)]

**Generating Image Descriptions via Sequential Cross-Modal Alignment Guided by Human Gaze.**<br>
*Ece Takmaz, Sandro Pezzelle, Lisa Beinborn, Raquel Fernández.*<br>
EMNLP 2020. [[PDF](https://arxiv.org/abs/2011.04592)]

**CapWAP: Captioning with a Purpose.**<br>
*Adam Fisch, Kenton Lee, Ming-Wei Chang, Jonathan H. Clark, Regina Barzilay.*<br>
EMNLP 2020. [[PDF](https://arxiv.org/abs/2011.04264)]

**Diverse Image Captioning with Context-Object Split Latent Spaces.**<br>
*Shweta Mahajan, Stefan Roth.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2011.00966)]

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

**Cross-Modal Contrastive Learning for Text-to-Image Generation.**<br>
*Han Zhang, Jing Yu Koh, Jason Baldridge, Honglak Lee, Yinfei Yang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.04702)]

**TediGAN: Text-Guided Diverse Image Generation and Manipulation.**<br>
*Weihao Xia, Yujiu Yang, Jing-Hao Xue, Baoyuan Wu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.03308)] [[Data](https://github.com/weihaox/Multi-Modal-CelebA-HQ)] [[Github](https://github.com/weihaox/TediGAN)]

**MPG: A Multi-ingredient Pizza Image Generator with Conditional StyleGANs.**<br>
*Fangda Han, Guoyao Hao, Ricardo Guerrero, Vladimir Pavlovic.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.02821)]

**Text-to-Image Generation Grounded by Fine-Grained User Attention.**<br>
*Jing Yu Koh, Jason Baldridge, Honglak Lee, Yinfei Yang.*<br>
WACV 2021. [[PDF](https://arxiv.org/abs/2011.03775)]

**SD-GAN: Semantics Disentangling for Text-to-Image Generation.**<br>
*Guojun Yin, Bin Liu, Lu Sheng, Nenghai Yu, Xiaogang Wang, Jing Shao.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1904.01480v1)]

**Leveraging Visual Question Answering to Improve Text-to-Image Synthesis.**<br>
*Stanislav Frolov, Shailza Jolly, Jörn Hees, Andreas Dengel.*<br>
LANTERN workshop at COLING 2020. [[PDF](https://arxiv.org/abs/2010.14953)]

**Lightweight Generative Adversarial Networks for Text-Guided Image Manipulation.**<br>
*Bowen Li, Xiaojuan Qi, Philip H. S. Torr, Thomas Lukasiewicz.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2010.12136)]

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

**Learning Deep Representations of Fine-grained Visual Descriptions.**<br>
*Scott Reed, Zeynep Akata, Bernt Schiele, Honglak Lee.*<br>
CVPR 2016. [[PDF](https://arxiv.org/abs/1605.05395)] [[Github](https://github.com/reedscot/cvpr2016)]

**Text-Adaptive Generative Adversarial Networks: Manipulating Images with Natural Language.**<br>
*Seonghyeon Nam, Yunji Kim, Seon Joo Kim.*<br>
NeurIPS 2018. [[PDF](https://arxiv.org/abs/1810.11919)] [[Github](https://github.com/xiaweihao/awesome-image-translation)]

**Semantic Image Synthesis via Adversarial Learning.**<br>
*Hao Dong, Simiao Yu, Chao Wu, Yike Guo.*<br>
ICCV 2017. [[PDF](https://arxiv.org/abs/1707.06873)] [[Github](https://github.com/woozzu/dong_iccv_2017)]

**Generative Adversarial Text to Image Synthesis.**<br>
*Scott Reed, Zeynep Akata, Xinchen Yan, Lajanugen Logeswaran, Bernt Schiele, Honglak Lee.*<br>
ICML 2016. [[PDF](https://arxiv.org/abs/1605.05396)] [[Github](https://github.com/reedscot/icml2016)]

### Speech-and-Text

**End-to-End Text-to-Speech using Latent Duration based on VQ-VAE.**<br>
*Yusuke Yasuda, Xin Wang, Junichi Yamagishi.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.09602)]

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

**VisualVoice: Audio-Visual Speech Separation with Cross-Modal Consistency.**<br>
*Ruohan Gao, Kristen Grauman.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2101.03149)] [[Project](http://vision.cs.utexas.edu/projects/VisualVoice/)]

**Visual Speech Enhancement Without A Real Visual Stream.**<br>
*Sindhu B Hegde, K R Prajwal, Rudrabha Mukhopadhyay, Vinay Namboodiri, C.V. Jawahar.*<br>
WACV 2021. [[PDF](https://arxiv.org/abs/2012.10852)] [[Project](http://cvit.iiit.ac.in/research/projects/cvit-projects/visual-speech-enhancement-without-a-real-visual-stream)] [[Github](https://github.com/Sindhu-Hegde/pseudo-visual-speech-denoising)]

**AudioViewer: Learning to Visualize Sound.**<br>
*Yuchi Zhang, Willis Peng, Bastian Wandt, Helge Rhodin.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.13341)]

**Multi-Instrumentalist Net: Unsupervised Generation of Music from Body Movements.**<br>
*Kun Su, Xiulong Liu, Eli Shlizerman.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.03478)] [[Video](https://www.youtube.com/watch?v=yo5OZKBbBh4)]

**Universal MelGAN: A Robust Neural Vocoder for High-Fidelity Waveform Generation in Multiple Domains.**<br>
*Won Jang, Dan Lim, Jaesam Yoon.*<br>
ICASSP 2021. [[PDF](https://arxiv.org/abs/2011.09631)]

**Everybody Sign Now: Translating Spoken Language to Photo Realistic Sign Language Video.**<br>
*Ben Saunders, Necati Cihan Camgoz, Richard Bowden.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.09846)]

**S2IGAN: Speech-to-Image Generation via Adversarial Learning.**<br>
*Xinsheng Wang, Tingting Qiao, Jihua Zhu, Alan Hanjalic, Odette Scharenborg.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2005.06968)]

**Lets Play Music: Audio-driven Performance Video Generation.**<br>
*Hao Zhu, Yi Li, Feixia Zhu, Aihua Zheng, Ran He.*<br>
ICPR 2020. [[PDF](https://arxiv.org/abs/2011.02631)]

**Show and Speak: Directly Synthesize Spoken Description of Images.**<br>
*Xinsheng Wang, Siyuan Feng, Jihua Zhu, Mark Hasegawa-Johnson, Odette Scharenborg.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.12267)]

**Latent Vector Recovery of Audio GANs.**<br>
*Andrew Keyes, Nicky Bayat, Vahid Reza Khazaie, Yalda Mohsenzadeh.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.08534)]

**MakeItTalk: Speaker-Aware Talking-Head Animation.**<br>
*Yang Zhou, Xintong Han, Eli Shechtman, Jose Echevarria, Evangelos Kalogerakis, Dingzeyu Li.*<br>
SIGGRAPH Asia 2020. [[PDF](https://arxiv.org/abs/2004.12992)] [[Github](https://github.com/adobe-research/MakeItTalk)]

**Objects that Sound.**<br>
*Relja Arandjelovi´c, Andrew Zisserman.*<br>
ECCV 2018. [[PDF](https://arxiv.org/pdf/1712.06651.pdf)]

**The Sound of Motions.**<br>
*Hang Zhao, Chuang Gan, Wei-Chiu Ma, Antonio Torralba.*<br>
ICCV 2019. [[PDF](https://arxiv.org/pdf/1904.05979.pdf)]  [[Project]()]

**The Sound of Pixels.**<br>
*Hang Zhao, Chuang Gan, Andrew Rouditchenko, Carl Vondrick, Josh McDermott, Antonio Torralba.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1804.03160)] [[Project](http://sound-of-pixels.csail.mit.edu/)] [[Github](https://github.com/hangzhaomit/Sound-of-Pixels)] [[MUSIC_dataset](https://github.com/roudimit/MUSIC_dataset)]

**DanceIt: Music-inspired Dancing Video Synthesis.**<br>
*Xin Guo, Jia Li, Yifan Zhao.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.08027)]

**Music Gesture for Visual Sound Separation.**<br>
*Chuang Gan, Deng Huang, Hang Zhao, Joshua B. Tenenbaum, Antonio Torralba.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.09476)] [[Project](http://music-gesture.csail.mit.edu/)]

**Foley Music: Learning to Generate Music from Videos.**<br>
*Chuang Gan, Deng Huang, Peihao Chen, Joshua B. Tenenbaum, Antonio Torralba.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.10984)] [[Project](http://foley-music.csail.mit.edu/)]

**Learning Individual Speaking Styles for Accurate Lip to Speech Synthesis.**<br>
*K R Prajwal, Rudrabha Mukhopadhyay, Vinay Namboodiri, C V Jawahar.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2005.08209)] [[Github](https://github.com/Rudrabha/Lip2Wav)]

**Crossing You in Style: Cross-modal Style Transfer from Music to Visual Arts.**<br>
*Cheng-Che Lee, Wan-Yi Lin, Yen-Ting Shih, Pei-Yi Patricia Kuo, Li Su.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2009.08083)] [[Github](https://github.com/SunnerLi/Cross-you-in-style)][[project](https://sunnerli.github.io/Cross-you-in-style/)] [[Dataset](https://github.com/SunnerLi/Cross-you-in-style#)]

**Attention-based Residual Speech Portrait Model for Speech to Face Generation.**<br>
*Jianrong Wang, Xiaosheng Hu, Li Liu, Wei Liu, Mei Yu, Tianyi Xu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.04536)]

**Speech2Face: Learning the Face Behind a Voice.**<br>
*Tae-Hyun Oh, Tali Dekel, Changil Kim, Inbar Mosseri, William T. Freeman, Michael Rubinstein, Wojciech Matusik.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1905.09773)] [[project](https://speech2face.github.io/)] [[Related Work](https://speech2face.github.io/)]

**Vector Quantized Contrastive Predictive Coding for Template-based Music Generation.**<br>
*Gaëtan Hadjeres, Léopold Crestel.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.10120)] [[Github](https://github.com/SonyCSLParis/vqcpc-bach)]

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

## 3D Shape Generation and Manipulation

**Learning to Infer Semantic Parameters for 3D Shape Editing.**<br>
*Fangyin Wei, Elena Sizikova, Avneesh Sud, Szymon Rusinkiewicz, Thomas Funkhouser.*<br>
3DV 2020. [[PDF](https://arxiv.org/abs/2011.04755)]

**3DSNet: Unsupervised Shape-to-Shape 3D Style Transfer.**<br>
*Mattia Segu, Margarita Grinvald, Roland Siegwart, Federico Tombari.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.13388)]

**Deformed Implicit Field: Modeling 3D Shapes with Learned Dense Correspondence.**<br>
*Yu Deng, Jiaolong Yang, Xin Tong.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.13650)] [[Github](https://github.com/microsoft/DIF-Net)]

**3DSNet: Unsupervised Shape-to-Shape 3D Style Transfer.**<br>
*Mattia Segu, Margarita Grinvald, Roland Siegwart, Federico Tombari.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.13388)]

**ShapeFlow: Learnable Deformations Among 3D Shapes.**<br>
*Chiyu "Max" Jiang, Jingwei Huang, Andrea Tagliasacchi, Leonidas Guibas.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.07982)]

## GAN Improvement

**Focal Frequency Loss for Generative Models.**<br>
*[Liming Jiang](https://liming-jiang.com/), [Bo Dai](http://daibo.info/), [Wayne Wu](https://wywu.github.io/), [Chen Change Loy](http://personal.ie.cuhk.edu.hk/~ccloy/).*<br>
arXiv 2020. [[PDF](https://arxiv.org/abs/2012.12821)] [[Github](https://github.com/EndlessSora/focal-frequency-loss)]

**Exemplar VAE: Linking Generative Models, Nearest Neighbor Retrieval, and Data Augmentation.**<br>
*Sajad Norouzi, David J. Fleet, Mohammad Norouzi.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2004.04795)] [[Github](https://github.com/sajadn/Exemplar-VAE)]

**Soft-IntroVAE: Analyzing and Improving the Introspective Variational Autoencoder.**<br>
*Tal Daniel, Aviv Tamar.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.13253)] [[Project](https://taldatech.github.io/soft-intro-vae-web)]

**Private-Shared Disentangled Multimodal VAE for Learning of Hybrid Latent Representations.**<br>
*Mihee Lee, Vladimir Pavlovic.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.13024)]

**SariGAN: Learning Semantic-aware Normalization for Generative Adversarial Networks.**<br>
*Heliang Zheng1, Jianlong Fu, Yanhong Zeng, Jiebo Luo, Zheng-Jun Zha.*<br>
NeurIPS 2020. [[PDF](https://proceedings.neurips.cc/paper/2020/file/f885a14eaf260d7d9f93c750e1174228-Paper.pdf)] [[Github](https://github.com/researchmm/SariGAN)]

**MODNet: Is a Green Screen Really Necessary for Real-Time Portrait Matting?**<br>
*Zhanghan Ke, Kaican Li, Yurou Zhou, Qiuhua Wu, Xiangyu Mao, Qiong Yan, Rynson W.H. Lau.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.11961)] [[Github](https://github.com/ZHKKKe/MODNet)]

**Score-Based Generative Modeling through Stochastic Differential Equations.**<br>
*Yang Song, Jascha Sohl-Dickstein, Diederik P. Kingma, Abhishek Kumar, Stefano Ermon, Ben Poole.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.13456)]

**Image Generators with Conditionally-Independent Pixel Synthesis.**<br>
*Ivan Anokhin, Kirill Demochkin, Taras Khakhulin, Gleb Sterkin, Victor Lempitsky, Denis Korzhenkov.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.13775)]

**PriorGAN: Real Data Prior for Generative Adversarial Nets.**<br>
*Shuyang Gu, Jianmin Bao, Dong Chen, Fang Wen.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.16990)]

**Omni-GAN: On the Secrets of cGANs and Beyond.**<br>
*Peng Zhou, Lingxi Xie, Bingbing Ni, Qi Tian.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.13074)] [[Github](https://github.com/PeterouZh/Omni-GAN-PyTorch)]

**Association: Remind Your GAN not to Forget.**<br>
*Yi Gu, Yuting Gao, Ruoxin Chen, Feiyang Cai, Jie Li, Chentao Wu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.13553)]

**Towards Faster and Stabilized GAN Training for High-fidelity Few-shot Image Synthesis.**<br>
*Anonymous authors.*<br>
ICLR 2021. [[PDF](https://openreview.net/forum?id=1Fqg133qRaI)]

**VDVAE: Very Deep VAEs Generalize Autoregressive Models and Can Outperform Them on Images.**<br>
*Anonymous authors.*<br>
ICLR 2021. [[PDF](https://openreview.net/forum?id=RLRXCV6DbEJ)] [[Github](https://github.com/openai/vdvae)]

**Self Normalizing Flows.**<br>
*T. Anderson Keller, [Jorn W.T. Peters](http://jornpeters.nl/), [Priyank Jaini](https://cs.uwaterloo.ca/~pjaini/home/), Emiel Hoogeboom, Patrick Forré, [Max Welling](https://staff.fnwi.uva.nl/m.welling/).*<br>
Beyond Backpropagation workshop at NeurIPS 2020. [[PDF](https://arxiv.org/abs/2011.07248)] [[Github](https://github.com/akandykeller/SelfNormalizingFlows)]

**Self-Gradient Networks.**<br>
*Hossein Aboutalebi, Mohammad Javad Shafiee Alexander Wong.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.09364)]

## Diving Deep into Image Synthesis

[[Image Generation SOTA](https://paperswithcode.com/task/image-generation)] 

[[Video Generation SOTA](https://paperswithcode.com/task/video-generation)]

### Invertible Neural Network (Flow-based Generative Model)

[[Normalizing Flows](https://paperswithcode.com/method/normalizing-flows)]

**Flow-based Generative Models for Learning Manifold to Manifold Mappings.**<br>
*Xingjian Zhen, Rudrasis Chakraborty, Liu Yang, Vikas Singh.*<br>
AAAI 2021. [[PDF](https://arxiv.org/abs/2012.10013)]

**Full-Glow: Fully conditional Glow for more realistic image generation.**<br>
*Moein Sorkhei, Gustav Eje Henter, Hedvig Kjellström.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.05846)]

**Decoupling Global and Local Representations via Invertible Generative Flows.**<br>
*Anonymous.*<br>
ICLR 2021 Submission. [[PDF](https://openreview.net/forum?id=iWLByfvUhN)]

**Network-to-Network Translation with Conditional Invertible Neural Networks.**<br>
*[Robin Rombach](https://github.com/rromb), [Patrick Esser](https://github.com/pesser), [Björn Ommer](https://hci.iwr.uni-heidelberg.de/Staff/bommer).*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2005.13580)] [[Github](https://github.com/CompVis/net2net)] [[Project](https://compvis.github.io/net2net/)]

**VideoFlow: A Conditional Flow-Based Model for Stochastic Video Generation.**<br>
*Manoj Kumar, Mohammad Babaeizadeh, Dumitru Erhan, Chelsea Finn, Sergey Levine, Laurent Dinh, Durk Kingma.*<br>
ICLR 2020. [[PDF](https://arxiv.org/abs/1903.01434v3)]

**Wavelet Flow: Fast Training of High Resolution Normalizing Flows.**<br>
*[Jason J. Yu](https://jasonjyu.com/), Konstantinos G. Derpanis](https://scs.ryerson.ca/~kosta/), [Marcus A. Brubaker](https://mbrubake.github.io/).*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2010.13821)] [[Github](https://github.com/YorkUCVIL/Wavelet-Flow/)] [[Project](https://yorkucvil.github.io/Wavelet-Flow/)]

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

**Adversarial Generation of Continuous Images.**<br>
*Ivan Skorokhodov, Savva Ignatyev, Mohamed Elhoseiny.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.12026)] [[Github](https://github.com/universome/inr-gan)]

**StyleGAN2vp: Learning Disentangled Representations with Latent Variation Predictability.**<br>
*Xinqi Zhu and Chang Xu and Dacheng Tao.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.12885)] [[Github](https://github.com/zhuxinqimac/)]

**StyleGAN2-Ada: Training Generative Adversarial Networks with Limited Data.**<br>
*Tero Karras, Miika Aittala, Janne Hellsten, Samuli Laine, Jaakko Lehtinen, Timo Aila.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.06676)] [[Github](https://github.com/NVlabs/stylegan2-ada)] [[Steam StyleGAN2-ADA
](https://github.com/woctezuma/steam-stylegan2-ada)]

**StyleGAN2: Analyzing and Improving the Image Quality of StyleGAN.**<br>
*[Tero Karras](https://research.nvidia.com/person/tero-karras), [Samuli Laine](https://research.nvidia.com/person/samuli-laine), [Miika Aittala](https://research.nvidia.com/person/miika-aittala), Janne Hellsten, Jaakko Lehtinen, [Timo Aila](https://research.nvidia.com/person/timo-aila).*<br>
CVPR 2020.
[[PDF](https://arxiv.org/abs/1912.04958)] 
[[Offical TF](https://github.com/NVlabs/stylegan2)]
[[PyTorch](https://github.com/rosinality/stylegan2-pytorch)]
[[Unoffical Tensorflow 2.0](https://github.com/manicman1999/StyleGAN2-Tensorflow-2.0)]

**Transforming Facial Weight of Real Images by Editing Latent Space of StyleGAN.**<br>
*V N S Rama Krishna Pinnimty, Matt Zhao, Palakorn Achananuparp, Ee-Peng Lim.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.02606)]

**A Style-Based Generator Architecture for Generative Adversarial Networks.**<br>
*Tero Karras, Samuli Laine, Timo Aila.*<br>
CVPR 2019. 
[[Paper](https://arxiv.org/abs/1812.04948)]
[[Video](https://youtu.be/kSLJriaOumA)]
[[Github](https://github.com/NVlabs/stylegan)]
[[FFHQ](https://github.com/NVlabs/ffhq-dataset)]

**DeepLandscape: Adversarial Modeling of Landscape Videos.**<br>
*E. Logacheva, R. Suvorov, O. Khomenko, A. Mashikhin, and V. Lempitsky.*<br>
ECCV 2020. [[PDF](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123680256.pdf)] [[Github](https://github.com/saic-mdal/deep-landscape)] [[Project](https://saic-mdal.github.io/deep-landscape/)]

**PIE: Portrait Image Embedding for Semantic Control.**<br> 
*[A. Tewari](http://people.mpi-inf.mpg.de/~atewari/), M. Elgharib, M. BR, F. Bernard, H-P. Seidel, P. P‌érez, M. Zollhöfer, C.Theobalt.*<br> 
SIGGRAPH Asia 2020. [[PDF](http://gvv.mpi-inf.mpg.de/projects/PIE/data/paper.pdf)] [[Project](http://gvv.mpi-inf.mpg.de/projects/PIE/)]

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

**Conditional Spoken Digit Generation with StyleGAN.**<br>
*Kasperi Palkama, Lauri Juvela, Alexander Ilin.*<br>
Interspeech 2020. [[PDF](https://arxiv.org/abs/2004.13764)]

### Transformer-Based

#### Survey

**A Survey on Visual Transformer.**<br>
*Kai Han, Yunhe Wang, Hanting Chen, Xinghao Chen, Jianyuan Guo, Zhenhua Liu, Yehui Tang, An Xiao, Chunjing Xu, Yixing Xu, Zhaohui Yang, Yiman Zhang, Dacheng Tao.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2012.12556)]

**Transformers in Vision: A Survey.**<br>
*Salman Khan, Muzammal Naseer, Munawar Hayat, Syed Waqas Zamir, Fahad Shahbaz Khan, Mubarak Shah.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.01169)]

#### 3D 

**Spherical Transformer: Adapting Spherical Signal to Convolutional Networks.**<br>
*Haikuan Du, Hui Cao, Shen Cai, Junchi Yan, Siyu Zhang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.03848)]

**Human Mesh Recovery from Multiple Shots.**<br>
*Georgios Pavlakos, Jitendra Malik, Angjoo Kanazawa.*<br>
arxiv 2021. [[PDF](https://arxiv.org/pdf/2012.09843.pdf)] [[Github](https://geopavlakos.github.io/multishot)]

**PCT: PCT: Point Cloud Transformer.**<br>
*Meng-Hao Guo, Jun-Xiong Cai, Zheng-Ning Liu, Tai-Jiang Mu, Ralph R. Martin, Shi-Min Hu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.09688)] [[Github](https://github.com/MenghaoGuo/PCT)]

**Point Transformer.**<br>
*Hengshuang Zhao, Li Jiang, Jiaya Jia, Philip Torr, Vladlen Koltun.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.09164)]

**Revisiting Stereo Depth Estimation From a Sequence-to-Sequence Perspective with Transformers.**<br>
*Zhaoshuo Li, Xingtong Liu, Francis X. Creighton, Russell H. Taylor, Mathias Unberath.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.02910)] [[Github](https://github.com/mli0603/stereo-transformer)]

**TransPose: Towards Explainable Human Pose Estimation by Transformer.**<br>
*Sen Yang, Zhibin Quan, Mu Nie, Wankou Yang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.14214)]

**End-to-End Human Pose and Mesh Reconstruction with Transformers.**<br>
*Kevin Lin, Lijuan Wang, Zicheng Liu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.09760)]

#### Multi-modality

**DALL·E: Creating Images from Text.**<br>
*OpenAI.*<br> [[Blog](https://openai.com/blog/dall-e/#fn1)] [[Github](https://github.com/lucidrains/DALLE-pytorch)]

**CLIP: Learning Transferable Visual Models From Natural Language Supervision.**<br>
*Alec Radford, Jong Wook Kim, Chris Hallacy, Aditya Ramesh, Gabriel Goh, Sandhini Agarwal, Girish Sastry, Amanda Askell, Pamela Mishkin, Jack Clark, Gretchen Krueger, Ilya Sutskever.*<br>
2021. [[PDF](https://cdn.openai.com/papers/Learning_Transferable_Visual_Models_From_Natural_Language.pdf)] [[Github](https://github.com/openai/CLIP)] [[Blog](https://openai.com/blog/clip/)]

**VisualSparta: Sparse Transformer Fragment-level Matching for Large-scale Text-to-Image Search.**<br>
*Xiaopeng Lu, Tiancheng Zhao, Kyusong Lee.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.00265)]

**COOT: Cooperative Hierarchical Transformer for Video-Text Representation Learning.**<br>
*Simon Ging, Mohammadreza Zolfaghari, Hamed Pirsiavash, Thomas Brox.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2011.00597)] [[Github](https://github.com/gingsi/coot-videotext)]

#### Tracking, Detection and Segmentation

**LSTR: End-to-end Lane Shape Prediction with Transformers.**<br>
*Ruijin Liu, Zejian Yuan, Tie Liu, Zhiliang Xiong.*<br>
WACV 2021. [[PDF](https://arxiv.org/abs/2011.04233)] [[Github](https://github.com/liuruijin17/LSTR)]

**Line Segment Detection Using Transformers without Edges.**<br>
*Yifan Xu, Weijian Xu, David Cheung, Zhuowen Tu.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.01909)]

**SETR: Rethinking Semantic Segmentation from a Sequence-to-Sequence Perspective with Transformers.**<br>
*Sixiao Zheng, Jiachen Lu, Hengshuang Zhao, Xiatian Zhu, Zekun Luo, Yabiao Wang, Yanwei Fu, Jianfeng Feng, Tao Xiang, Philip H.S. Torr, Li Zhang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2012.15840)] [[Project](https://fudan-zvg.github.io/SETR/)]

**TrackFormer: Multi-Object Tracking with Transformers.**<br>
*Tim Meinhardt, Alexander Kirillov, Laura Leal-Taixe, Christoph Feichtenhofer.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.02702)]

**TransTrack: Multiple-Object Tracking with Transformer.**<br>
*Peize Sun, Yi Jiang, Rufeng Zhang, Enze Xie, Jinkun Cao, Xinting Hu, Tao Kong, Zehuan Yuan, Changhu Wang, Ping Luo.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2012.15460)]

**MaX-DeepLab: End-to-End Panoptic Segmentation with Mask Transformers.**<br>
*Huiyu Wang, Yukun Zhu, Hartwig Adam, Alan Yuille, Liang-Chieh Chen.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.00759)]

**UP-DETR: Unsupervised Pre-training for Object Detection with Transformers.**<br>
*Zhigang Dai, Bolun Cai, Yugeng Lin, Junying Chen.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.09094)]

**End-to-End Video Instance Segmentation with Transformers.**<br>
*Yuqing Wang, Zhaoliang Xu, Xinlong Wang, Chunhua Shen, Baoshan Cheng, Hao Shen, Huaxia Xia.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.14503)]

**Visual Transformers: Token-based Image Representation and Processing for Computer Vision.**<br>
*Bichen Wu, Chenfeng Xu, Xiaoliang Dai, Alvin Wan, Peizhao Zhang, Zhicheng Yan, Masayoshi Tomizuka, Joseph Gonzalez, Kurt Keutzer, Peter Vajda.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.03677)] [[Github](https://github.com/tahmid0007/VisualTransformers)]

**Deformable DETR: Deformable Transformers for End-to-End Object Detection.**<br>
*Xizhou Zhu, Weijie Su, Lewei Lu, Bin Li, Xiaogang Wang, Jifeng Dai.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.04159)]

**Topological Planning with Transformers for Vision-and-Language Navigation.**<br>
*Kevin Chen, Junshen K. Chen, Jo Chuang, Marynel Vázquez, Silvio Savarese.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.05292)]

**RelationNet++: Bridging Visual Representations for Object Detection via Transformer Decoder.**<br>
*Cheng Chi, Fangyun Wei, Han Hu.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2010.15831)] [[Github](https://github.com/microsoft/RelationNet2)]

#### Generation

**Transformer for Image Quality Assessment.**<br>
*Junyong You, Jari Korhonen.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.01097)]

**ConvTransformer: A Convolutional Transformer Network for Video Frame Synthesis.**<br>
*Zhouyong Liu, Shun Luo, Wubin Li, Jingben Lu, Yufan Wu, Chunguo Li, Luxi Yang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.10185)]

**General Invertible Transformations for Flow-based Generative Modeling.**<br>
*Jakub M. Tomczak.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.15056v1)] [[Github](https://github.com/jmtomczak/git_flow)]

**Taming Transformers for High-Resolution Image Synthesis.**<br>
*[Patrick Esser](https://github.com/pesser), [Robin Rombach](https://github.com/rromb), [Björn Ommer](https://hci.iwr.uni-heidelberg.de/Staff/bommer).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.09841)] [[Project](https://compvis.github.io/taming-transformers/)] [[Github](https://github.com/CompVis/taming-transformers)]

**DeiT: Training data-efficient image transformers & distillation through attention.**<br>
*Hugo Touvron, Matthieu Cord, Matthijs Douze, Francisco Massa, Alexandre Sablayrolles, Hervé Jégou.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.12877)] [[Github](https://github.com/facebookresearch/deit)]

**Transformer Interpretability Beyond Attention Visualization.**<br>
*Hila Chefer, Shir Gur, Lior Wolf.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.09838)]

**TSceneFormer: Indoor Scene Generation with Transformers.**<br>
*Xinpeng Wang, Chandan Yeshwanth, Matthias Nießner.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.09793)]

**Synthesizer: Rethinking Self-Attention in Transformer Models.**<br>
*Yi Tay, Dara Bahri, Donald Metzler, Da-Cheng Juan, Zhe Zhao, Che Zheng.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2005.00743)] [[Github](https://github.com/10-zin/Synthesizer)]

**Improving Image Captioning by Leveraging Intra- and Inter-layer Global Representation in Transformer Network.**<br>
*Jiayi Ji, Yunpeng Luo, Xiaoshuai Sun, Fuhai Chen, Gen Luo, Yongjian Wu, Yue Gao, Rongrong Ji.*<br>
AAAI 2021. [[PDF](https://arxiv.org/abs/2012.07061)]

**Vision Transformer-An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale.**<br>
*Alexey Dosovitskiy, Lucas Beyer, Alexander Kolesnikov, Dirk Weissenborn, Xiaohua Zhai, Thomas Unterthiner, Mostafa Dehghani, Matthias Minderer, Georg Heigold, Sylvain Gelly, Jakob Uszkoreit, Neil Houlsby.*<br>
ICLR 2021. [[PDF](https://arxiv.org/abs/2010.11929)] [[Official](https://github.com/google-research/vision_transformer)] [[Github](https://github.com/lukemelas/PyTorch-Pretrained-ViT)] [[Github](https://github.com/lucidrains/vit-pytorch)] [[Github](https://github.com/gupta-abhay/ViT)] [[Code Collection](https://paperswithcode.com/paper/an-image-is-worth-16x16-words-transformers)]

**Image-GPT: Generative Pretraining from Pixels.**<br>
*Mark Chen, Alec Radford, Rewon Child, Jeff Wu, Heewoo Jun, Prafulla Dhariwal, David Luan, Ilya Sutskever.*<br>
Tech Report 2020. [[PDF](https://cdn.openai.com/papers/Generative_Pretraining_from_Pixels_V2.pdf)] [[Github](https://github.com/openai/image-gpt)]

**Generative Pretraining from Pixels.**<br>
*Mark Chen, Alec Radford, Rewon Child, Jeff Wu, Heewoo Jun, Prafulla Dhariwal, David Luan, Ilya Sutskever.*<br>
ICML 2020. [[PDF](https://cdn.openai.com/papers/Generative_Pretraining_from_Pixels_V2.pdf)] [[Github](https://github.com/openai/image-gpt)]

#### Restoration

**TTSR: Learning Texture Transformer Network for Image Super-Resolution.**<br>
*Fuzhi Yang, Huan Yang, Jianlong Fu, Hongtao Lu, Baining Guo.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2006.04139)] [[Github](https://github.com/researchmm/TTSR)]

**Pre-Trained Image Processing Transformer.**<br>
*Hanting Chen, Yunhe Wang, Tianyu Guo, Chang Xu, Yiping Deng, Zhenhua Liu, Siwei Ma, Chunjing Xu, Chao Xu, Wen Gao.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.00364)]

#### Misc

**AttentionLite: Towards Efficient Self-Attention Models for Vision.**<br>
*Souvik Kundu, Sairam Sundaresan.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2101.05216)]

**Transformer Interpretability Beyond Attention Visualization.**<br>
*Hila Chefer, Shir Gur, Lior Wolf.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.09838)] [[Github](https://github.com/hila-chefer/Transformer-Explainability)]

**FPT: Feature Pyramid Transformer.**<br>
*Dong Zhang, Hanwang Zhang, Jinhui Tang, Meng Wang, Xiansheng Hua, Qianru Sun.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.09451)] [[Github](https://github.com/ZHANGDONG-NJUST/FPT)]

**R-Transformer: Recurrent Neural Network Enhanced Transformer.**<br>
*Zhiwei Wang, Yao Ma, Zitao Liu, Jiliang Tang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/1907.05572)] [[Github](https://github.com/DSE-MSU/R-transformer)]

**Rethinking Attention with Performers.**<br>
*Krzysztof Choromanski, Valerii Likhosherstov, David Dohan, Xingyou Song, Andreea Gane, Tamas Sarlos, Peter Hawkins, Jared Davis, Afroz Mohiuddin, Lukasz Kaiser, David Belanger, Lucy Colwell, Adrian Weller.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.14794)] [[Github](https://github.com/google-research/google-research/tree/master/performer)]

### Single-Image Training 

**Blind Motion Deblurring through SinGAN Architecture.**<br>
*Harshil Jain, Rohit Patil, Indra Deep Mastan, Shanmuganathan Raman.*<br>
ECCV 2020 Workshop. [[PDF](https://arxiv.org/abs/2011.03705)]

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

### Fairness, Accountability, Privacy, Transparency and Ethics

**Unlearnable Examples: Making Personal Data Unexploitable.**<br>
*Hanxun Huang, Xingjun Ma, Sarah Monazam Erfani, James Bailey, Yisen Wang.*<br>
ICLR 2021. [[PDF](https://arxiv.org/abs/2101.04898)]

**This Face Does Not Exist ... But It Might Be Yours! Identity Leakage in Generative Models.**<br>
*Patrick Tinsley, Adam Czajka, Patrick Flynn.*<br>
WACV 2021. [[PDF](https://arxiv.org/abs/2101.05084)]

### Data Efficiency

**StyleGAN2-Ada: Training Generative Adversarial Networks with Limited Data.**<br>
*Tero Karras, Miika Aittala, Janne Hellsten, Samuli Laine, Jaakko Lehtinen, Timo Aila.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.06676)] [[Github](https://github.com/NVlabs/stylegan2-ada)] [[Steam StyleGAN2-ADA
](https://github.com/woctezuma/steam-stylegan2-ada)]

**VirTex: Learning Visual Representations from Textual Annotations.**<br>
*Karan Desai, Justin Johnson.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.06666)] [[Github](https://github.com/kdexd/virtex)]

**DeiT: Training Data-Efficient Image Transformers & Distillation Through Attention.**<br>
*Hugo Touvron, Matthieu Cord, Matthijs Douze, Francisco Massa, Alexandre Sablayrolles, Hervé Jégou.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.12877)] [[Github](https://github.com/facebookresearch/deit)]

**YuruGAN: Yuru-Chara Mascot Generator Using Generative Adversarial Networks With Clustering Small Dataset.**<br>
*Yuki Hagiwara, Toshihisa Tanaka.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.08066)]

### Dataset Biases

**EEC: Learning to Encode and Regenerate Images for Continual Learning.**<br>
*Ali Ayub, Alan R. Wagner.*<br>
ICLR 2021. [[PDF](https://arxiv.org/abs/2101.04904)]

**FairGen: Improving the Fairness of Deep Generative Models without Retraining.**<br>
*[Shuhan Tan](https://ariostgx.github.io/), Yujun Shen, Bolei Zhou.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.04842)] [[Project](https://genforce.github.io/fairgen/)] [[Github](https://github.com/genforce/fairgen)]

**Positional Encoding as Spatial Inductive Bias in GANs.**<br>
*Rui Xu, Xintao Wang, Kai Chen, Bolei Zhou, Chen Change Loy.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.05217)] [[Project](https://nbei.github.io/gan-pos-encoding.html)]

**Permuted AdaIN: Reducing the Bias Towards Global Statistics in Image Classification.**<br>
*Oren Nuriel, Sagie Benaim, Lior Wolf.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.05785)] [[Github](https://github.com/onuriel/PermutedAdaIN)]

**A Note on Data Biases in Generative Models.**<br>
*Patrick Esser, Robin Rombach, Björn Ommer.*<br>
NeurIPS 2020 Workshop on Machine Learning for Creativity and Design. [[PDF](https://arxiv.org/abs/2012.02516)] [[Github](https://github.com/CompVis/net2net)]

**Fair Generative Modeling via Weak Supervision.**<br>
*Kristy Choi, Aditya Grover, Trisha Singh, Rui Shu, Stefano Ermon.*<br>
ICML 2020. [[PDF](http://proceedings.mlr.press/v119/choi20a.html)] [[Github](https://github.com/ermongroup/fairgen)]

**Inclusive GAN: Improving Data and Minority Coverage in Generative Models.**<br>
*Ning Yu, Ke Li, Peng Zhou, Jitendra Malik, Larry Davis, Mario Fritz.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2004.03355)]

**Bias and Generalization in Deep Generative Models: An Empirical Study.**<br>
*Shengjia Zhao, Hongyu Ren, Arianna Yuan, Jiaming Song, Noah Goodman, Stefano Ermon.*<br>
NeurIPS 2018. [[PDF](https://arxiv.org/abs/1811.03259)]

### Hard or Unfamiliar Example

**Flexible Few-Shot Learning with Contextual Similarity.**<br>
*Mengye Ren, Eleni Triantafillou, Kuan-Chieh Wang, James Lucas, Jake Snell, Xaq Pitkow, Andreas S. Tolias, Richard Zemel.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.05895)]

**Improving Confidence Estimates for Unfamiliar Examples.**<br>
*[Zhizhong Li](https://zhizhongli.vision/), [Derek Hoiem](https://dhoiem.cs.illinois.edu/).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1804.03166)] [[Github](https://github.com/lizhitwo/ConfidenceEstimates)] [[Project](https://zhizhongli.vision/projects/improving-confidence-estimates/)]

**MetaInfoNet: Learning Task-Guided Information for Sample Reweighting.**<br>
*Hongxin Wei, Lei Feng, Rundong Wang, Bo An.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.05273)]

**Learning to Sample the Most Useful Training Patches from Images.**<br>
*Shuyang Sun, Liang Chen, Gregory Slabaugh, Philip Torr.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.12097)]

**Enhanced Balancing GAN: Minority-class Image Generation.**<br>
*Gaofeng Huang, Amir H. Jafari.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.00189)]

**Fewer is More: A Deep Graph Metric Learning Perspective Using Fewer Proxies.**<br>
*Yuehua Zhu, Muli Yang, Cheng Deng, Wei Liu.*<br>
NeurlPS 2020. [[PDF](https://arxiv.org/abs/2010.13636)] [[Github](https://github.com/YuehuaZhu/ProxyGML)]

**Hard Example Generation by Texture Synthesis for Cross-domain Shape Similarity Learning.**<br>
*Huan Fu, Shunming Li, Rongfei Jia, Mingming Gong, Binqiang Zhao, Dacheng Tao.*<br>
NeurlPS 2020. [[PDF](https://arxiv.org/abs/2010.12238)] [[Github](https://github.com/3D-FRONT-FUTURE/IBSR-texture)]

**Rethinking the Value of Labels for Improving Class-Imbalanced Learning.**<br>
*Yuzhe Yang, Zhi Xu.*<br>
NeurlPS 2020. [[PDF](https://arxiv.org/abs/2006.07529)] [[Github](https://github.com/YyzHarry/imbalanced-semi-self)]

### Data or Distribution Augmentation

**StyleGAN2-Ada: Training Generative Adversarial Networks with Limited Data.**<br>
*Tero Karras, Miika Aittala, Janne Hellsten, Samuli Laine, Jaakko Lehtinen, Timo Aila.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.06676)] [[Github](https://github.com/NVlabs/stylegan2-ada)] [[Steam StyleGAN2-ADA
](https://github.com/woctezuma/steam-stylegan2-ada)]

**SnapMix: Semantically Proportional Mixing for Augmenting Fine-grained Data.**<br>
*Shaoli Huang, Xinchao Wang, Dacheng Tao.*<br>
AAAI 2021. [[PDF](https://arxiv.org/abs/2012.04846)] [[Github](https://github.com/Shaoli-Huang/SnapMix.git)]

**Augmentation Inside the Network.**<br>
*Maciej Sypetkowski, Jakub Jasiulewicz, Zbigniew Wojna.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.10769)]

**Joint Search of Data Augmentation Policies and Network Architectures.**<br>
*Taiga Kashima, Yoshihiro Yamada, Shunta Saito.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.09407)]

**Augmentation Inside the Network.**<br>
*Maciej Sypetkowski, Jakub Jasiulewicz, Zbigniew Wojna.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.10769)]

**Distribution Augmentation for Generative Modeling.**<br>
*Heewoo Jun, Rewon Child, Mark Chen, John Schulman, Aditya Ramesh, Alec Radford, Ilya Sutskever.*<br>
ICML 2020. [[PDF](https://proceedings.icml.cc/static/paper_files/icml/2020/6095-Paper.pdf)] [[Github](https://github.com/openai/distribution_augmentation)]

**Differentiable Augmentation for Data-Efficient GAN Training.**<br>
*Shengyu Zhao, Zhijian Liu, Ji Lin, Jun-Yan Zhu, Song Han.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.10738)] [[Project](https://hanlab.mit.edu/projects/data-efficient-gans/)] [[Github](https://github.com/mit-han-lab/data-efficient-gans)]

### Long-Tailed, Open Set, and Class-Imbalanced Dataset

**Few-Shot Learning with Class Imbalance.**<br>
*Mateusz Ochal, Massimiliano Patacchiola, Amos Storkey, Jose Vazquez, Sen Wang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.02523)]

**Feature Space Augmentation for Long-Tailed Data.**<br>
*Peng Chu, Xiao Bian, Shaopeng Liu, Haibin Ling.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.03673)]

**Overcoming Classifier Imbalance for Long-tail Object Detection with Balanced Group Softmax.**<br>
*Yu Li, Tao Wang, Bingyi Kang, Sheng Tang, Chunfeng Wang, Jintao Li, Jiashi Feng.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2006.10408)] [[Github](https://github.com/FishYuLi/BalancedGroupSoftmax)]

**Decoupling Representation and Classifier for Long-Tailed Recognition.**<br>
*Bingyi Kang, Saining Xie,Marcus Rohrbach, Zhicheng Yan, Albert Gordo, Jiashi Feng, Yannis Kalantidis.*<br>
ICLR 2020. [[PDF](https://arxiv.org/abs/1910.09217)] [[Github](https://github.com/facebookresearch/classifier-balancing)]

**Open-World Learning Without Labels.**<br>
*Mohsen Jafarzadeh, Akshay Raj Dhamija, Steve Cruz, Chunchun Li, Touqeer Ahmad, Terrance E. Boult.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.12906)]

**M2M: Imbalanced Classification via Major-to-Minor Translation.**<br>
*Jaehyung Kim, Jongheon Jeong, Jinwoo Shin.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.00431)]

**Rethinking the Value of Labels for Improving Class-Imbalanced Learning.**<br>
*Yuzhe Yang, Zhi Xu.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.07529)] [[Github](https://github.com/YyzHarry/imbalanced-semi-self)]

**OSLNet: Deep Small-Sample Classification with an Orthogonal Softmax Layer.**<br>
*Xiaoxu Li, Dongliang Chang, Zhanyu Ma, Zheng-Hua Tan, Jing-Hao Xue, Jie Cao, Jingyi Yu, Jun Guo.*<br>
TIP 2020. [[PDF](https://arxiv.org/abs/2004.09033)] [[Github](https://github.com/dongliangchang/OSLNet)] 

**Towards Inheritable Models for Open-Set Domain Adaptation.**<br>
*Jogendra Nath Kundu, Naveen Venkat, Ambareesh Revanur, Rahul M V, R. Venkatesh Babu.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.04388)] [[Github](https://github.com/val-iisc/inheritune)]

**BBN: Bilateral-Branch Network with Cumulative Learning for Long-Tailed Visual Recognition.**<br>
*Boyan Zhou, Quan Cui, Xiu-Shen Wei, Zhao-Min Chen.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.02413)] [[Github](https://github.com/Megvii-Nanjing/BBN)]

**Rethinking Class-Balanced Methods for Long-Tailed Visual Recognition from a Domain Adaptation Perspective.**<br>
*Muhammad Abdullah Jamal, Matthew Brown, Ming-Hsuan Yang, Liqiang Wang, Boqing Gong.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.10780)]

**Domain Balancing: Face Recognition on Long-Tailed Domains.**<br>
*Dong Cao, Xiangyu Zhu, Xingyu Huang, Jianzhu Guo, Zhen Lei.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.13791)]

<details>
  <summary> Datasets </summary> 
<li><a href="https://www.microsoft.com/en-us/research/project/ms-celeb-1m-challenge-recognizing-one-million-celebrities-real-world/">MS-Celeb-1M</a>. Challenge of Recognizing One Million Celebrities in the Real World.</li>
<li><a href="https://pgram.com/dataset/casia-webface/">CASIA-WebFace</a>. The CASIA WebFace Facial Dataset consists of 453,453 images over 10,575 identities after face detection. This dataset can be download from <a href="https://pan.baidu.com/s/1hQCOD4Kr66MOW0_PE8bL0w">Baidu Cloud</a> with password y3wj or <a href="https://drive.google.com/open?id=1Of_EVz-yHV7QVWQGihYfvtny9Ne8qXVz">Google Drive</a>. The original <a href="http://www.cbsr.ia.ac.cn/english/CASIA-WebFace-Database.html">CASIA-webface Dataset</a> is very dirty and requires some filtering for quality. <a href="https://github.com/happynear/FaceVerification">Some</a> have washed the CASIA-webface database manually. After washing, 27703 wrong images are deleted. The washed list can be downloaded from <a href="http://pan.baidu.com/s/1hrKpbm8">Baidu Cloud</a>. There is also a <a href="https://1drv.ms/u/s!AjMP8wpvXdkfhMhnmNDEdj5oor7M_A">CASIA-maxpy-clean.zip</a> that kindly shared by <a href="https://github.com/cmusatyalab/openface/issues/119">OpenFace</a> Community.</li>
</details>

**DRAGON: Long-tail learning with attributes.**<br>
*Dvir Samuel, Yuval Atzmon, Gal Chechik.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.02235)] [[Github](https://github.com/dvirsamuel/DRAGON)]

<details>
  <summary> Datasets </summary>
<li><a href="http://www.vision.caltech.edu/visipedia/CUB-200-2011.html">CUB-200-2011</a>. The Caltech-UCSD Birds-200-2011 contains 11,788 visual images of 200 bird species for fine-grained classification. Each species is described by 312 binary attributes (like tail-pattern:solid, wing-color:black).</li>
<li><a href="http://groups.csail.mit.edu/vision/SUN/">SUN</a>. The SUN Attribute Database contains 14,340 complex visual scenes, from 717 scene types and 102 attributes (like material:rock, function:eating, surface:glossy).</li>
<li><a href="http://attributes.kyb.tuebingen.mpg.de/">AWA</a>. The Animals with Attributes consists of 30,475 images of 50 animal classes and 85 attributes(like texture: furry, or color: black).</li>
</details>

**OLTR: Large-Scale Long-Tailed Recognition in an Open World.**<br>
*[Ziwei Liu](https://liuziwei7.github.io/), [Zhongqi Miao](https://github.com/zhmiao), [Xiaohang Zhan](https://xiaohangzhan.github.io/), [Jiayun Wang](http://pwang.pw/), [Boqing Gong](http://boqinggong.info/), [Stella X. Yu](https://www1.icsi.berkeley.edu/~stellayu/).*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1904.05160)] [[Github](https://github.com/zhmiao/OpenLongTailRecognition-OLTR)] [[Project](https://liuziwei7.github.io/projects/LongTail.html)]

**Long-Tailed Recognition Using Class-Balanced Experts.**<br>
*Saurabh Sharma, Ning Yu, Mario Fritz, Bernt Schiele.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.03706)]

**Learning to Segment the Tail.**<br>
*Xinting Hu, Yi Jiang, Kaihua Tang, Jingyuan Chen, Chunyan Miao, Hanwang Zhang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.00900)] [[Github](https://github.com/JoyHuYY1412/LST_LVIS)]

### Spatio-Temporal

**ESTRNN: Efficient Spatio-Temporal Recurrent Neural Network for Video Deblurring.**<br>
*Zhihang Zhong, Ye Gao, Yinqiang Zheng, Bo Zheng.*<br>
ECCV 2020. [[PDF](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123510188.pdf)] [[Github](https://github.com/zzh-tech/ESTRNN)]

**Blind Video Temporal Consistency via Deep Video Prior.**<br>
*[Chenyang Lei](https://chenyanglei.github.io/), Yazhou Xing, [Qifeng Chen](https://cqf.io/).*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2010.11838)] [[Poject](https://chenyanglei.github.io/DVP/index.html)] [[Github](https://github.com/ChenyangLEI/deep-video-prior)]

**CDVD-TSP: Cascaded Deep Video Deblurring Using Temporal Sharpness Prior.**<br>
*Jinshan Pan, Haoran Bai, Jinhui Tang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.02501)] [[Github](https://github.com/csbhr/CDVD-TSP)]

**STEm-Seg: Spatio-temporal Embeddings for Instance Segmentation in Videos.**<br>
*Ali Athar, Sabarinath Mahadevan, Aljoša Ošep, Laura Leal-Taixé, Bastian Leibe.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2003.08429)] [[Github](https://github.com/sabarim/STEm-Seg)] [[Project](https://www.vision.rwth-aachen.de/publication/00202/)]

**HRVGAN: High Resolution Video Generation using Spatio-Temporal GAN.**<br>
*Abhinav Sagar.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.09646)]

### Neural Network Interpretability

**A Survey on Neural Network Interpretability.**<br>
*Yu Zhang, Peter Tiňo, Aleš Leonardis, Ke Tang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2012.14261)]

### Others

#### Scene Graph Generation

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

#### Speech Synthesis

**HiFi-GAN: Generative Adversarial Networks for Efficient and High Fidelity Speech Synthesis.**<br>
*Jungil Kong, Jaehyeon Kim, Jaekyoung Bae.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.05646)] [[Github](https://github.com/jik876/hifi-gan)]

**Tacotron2: Natural TTS Synthesis by Conditioning WaveNet on Mel Spectrogram Predictions.**<br>
*Jonathan Shen, Ruoming Pang, Ron J. Weiss, Mike Schuster, Navdeep Jaitly, Zongheng Yang, Zhifeng Chen, Yu Zhang, Yuxuan Wang, RJ Skerry-Ryan, Rif A. Saurous, Yannis Agiomyrgiannakis, Yonghui Wu.*<br>
ICASSP 2018. [[PDF](https://arxiv.org/abs/1712.05884)] [[Github](https://github.com/NVIDIA/tacotron2)]

**WaveTransformer: A Novel Architecture for Audio Captioning Based on Learning Temporal and Time-Frequency Information.**<br>
*An Tran, Konstantinos Drossos, Tuomas Virtanen.*<br>
ICASSP 2021. [[PDF](https://arxiv.org/abs/2010.11098)] [[Github](https://github.com/haantran96/wavetransformer)] [[Demo](https://haantran96.github.io/wavetransformer-web-demo/)]

**MelGAN: Generative Adversarial Networks for Conditional Waveform Synthesis.**<br>
*Kundan Kumar, Rithesh Kumar, Thibault de Boissiere, Lucas Gestin, Wei Zhen Teoh, Jose Sotelo, Alexandre de Brebisson, Yoshua Bengio, Aaron Courville.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/1910.06711)] [[Github](https://github.com/descriptinc/melgan-neurips)] [[Project](https://melgan-neurips.github.io/)]

**WaveGlow: a Flow-based Generative Network for Speech Synthesis.**<br>
*Ryan Prenger, Rafael Valle, and Bryan Catanzaro.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/1811.00002)] [[Github](https://github.com/NVIDIA/waveglow)] [[Project](https://nv-adlr.github.io/WaveGlow)]

#### misc

**Generative Max-Mahalanobis Classifiers for Image Classification, Generation and More.**<br>
*Xiulong Yang, Hui Ye, Yang Ye, Xiang Li, Shihao Ji.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.00122)]

**Intrinsic Temporal Regularization for High-resolution Human Video Synthesis.**<br>
*Lingbo Yang, Zhanning Gao, Peiran Ren, Siwei Ma, Wen Gao.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.06134)]

**End-to-End Chinese Landscape Painting Creation Using Generative Adversarial Networks.**<br>
*Alice Xue.*<br>
WACV 2021. [[PDF](https://arxiv.org/abs/2011.05552)] [[Chinese-Landscape-Painting-Dataset](https://github.com/alicex2020/Chinese-Landscape-Painting-Dataset)]

**Lifting 2D StyleGAN for 3D-Aware Face Generation.**<br>
*Yichun Shi, Divyansh Aggarwal, Anil K. Jain.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.13126)]

**MorphNet: One-Shot Face Synthesis GAN for Detecting Recognition Bias.**<br>
*Nataniel Ruiz, Barry-John Theobald, Anurag Ranjan, Ahmed Hussein Abdelaziz, Nicholas Apostoloff.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.05225)]

**You Only Need Adversarial Supervision for Semantic Image Synthesis.**<br>
*Vadim Sushko, Edgar Schönfeld, Dan Zhang, Juergen Gall, Bernt Schiele, Anna Khoreva.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.04781)]

**Semantic Image Synthesis via Efficient Class-Adaptive Normalization.**<br>
*Zhentao Tan, Dongdong Chen, Qi Chu, Menglei Chai, Jing Liao, Mingming He, Lu Yuan, Gang Hua, Nenghai Yu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.04644)] [[Github](https://github.com/tzt101/CLADE.git)]

**Spectral Distribution aware Image Generation.**<br>
*Steffen Jung, Margret Keuper.*<br>
AAAI 2021. [[PDF](https://arxiv.org/abs/2012.03110)]

**Creative Sketch Generation.**<br>
*Songwei Ge, Vedanuj Goswami, C. Lawrence Zitnick, Devi Parikh.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.10039)] [[Github](https://github.com/facebookresearch/DoodlerGAN)] [[Project](http://doodlergan.cloudcv.org/)]

**CircleGAN: Generative Adversarial Learning across Spherical Circles.**<br>
*Woohyeon Shim, Minsu Cho.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.12486)]

**HistoGAN: Controlling Colors of GAN-Generated and Real Images via Color Histograms.**<br>
*[Mahmoud Afifi](https://sites.google.com/view/mafifi), Marcus A. Brubaker, Michael S. Brown.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.11731)] [[Github](https://github.com/mahmoudnafifi/HistoGAN)] [[4K Landscape](https://ln2.sync.com/dl/1891becc0/uhsxtprq-33wfwmyq-dhhqeb3s-mtstuqw7/view/default/11118541390008)]

**Generative Adversarial Stacked Autoencoders.**<br>
*Ariel Ruiz-Garcia, Ibrahim Almakky, Vasile Palade, Luke Hicks.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.12236)]

**Legacy Photo Editing with Learned Noise Prior.**<br>
*Yuzhi Zhao, Lai-Man Po, Xuehui Wang, Kangcheng Liu, Yujia Zhang, Wing-Yin Yu, Pengfei Xian, Jingjing Xiong.*<br>
WACV 2021. [[PDF](https://arxiv.org/abs/2011.11309)] [[Github](https://github.com/zhaoyuzhi/Legacy-Photo-Editing-with-Learned-Noise-Prior)]

**CEN: Deep Multimodal Fusion by Channel Exchanging.**<br>
*Yikai Wang, Wenbing Huang, Fuchun Sun, Tingyang Xu, Yu Rong, Junzhou Huang.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2011.05005)] [[Github](https://github.com/yikaiw/CEN)]

**Few-shot Image Generation with Elastic Weight Consolidation.**<br>
*Yijun Li, Richard Zhang, Jingwan (Cynthia) Lu, Eli Shechtman.*<br>
NeurIPS 2020. [[PDF](https://papers.nips.cc/paper/2020/hash/b6d767d2f8ed5d21a44b0e5886680cb9-Abstract.html)] [[Project](https://yijunmaverick.github.io/publications/ewc/)]

**Neural FFTs for Universal Texture Image Synthesis.**<br>
*Morteza Mardani, Guilin Liu, Aysegul Dundar, Shiqiu Liu, Andrew Tao, Bryan Catanzaro.*<br>
NeurIPS 2020. [[PDF](https://papers.nips.cc/paper/2020/hash/a23156abfd4a114c35b930b836064e8b-Abstract.html)]

**Latent Neural Differential Equations for Video Generation.**<br>
*Cade Gordon, Natalie Parde.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.03864)]

**Disentangling Latent Space for Unsupervised Semantic Face Editing.**<br>
*Kanglin Liu, Gaofeng Cao, Fei Zhou, Bozhi Liu, Jiang Duan, Guoping Qiu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.02638)] [[Github](https://github.com/max-liu-112/STGAN-WO)]

**Learning a Deep Reinforcement Learning Policy Over the Latent Space of a Pre-trained GAN for Semantic Age Manipulation.**<br>
*Kumar Shubham, Gopalakrishnan Venkatesh, Reijul Sachdev, Akshi, Dinesh Babu Jayagopi, G. Srinivasaraghavan.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.00954)]

**Contrastive Learning with Adversarial Examples.**<br>
*Chih-Hui Ho, Nuno Vasconcelos.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2010.12050)]

**Learning Invariances in Neural Networks.**<br>
*Gregory Benton, Marc Finzi, Pavel Izmailov, Andrew Gordon Wilson.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2010.11882)] [[Github](https://github.com/g-benton/learning-invariances)]

**One Model to Reconstruct Them All: A Novel Way to Use the Stochastic Noise in StyleGAN.**<br>
*Christian Bartz, Joseph Bethge, Haojin Yang, Christoph Meinel.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.11113)] [[Github](https://github.com/Bartzi/one-model-to-reconstruct-them-all)]

**LT-GAN: Self-Supervised GAN with Latent Transformation Detection.**<br>
*Parth Patel, Nupur Kumari, Mayank Singh, Balaji Krishnamurthy.*<br>
WACV2021. [[PDF](https://arxiv.org/abs/2010.09893)]

**SynthCP: Synthesize then Compare: Detecting Failures and Anomalies for Semantic Segmentation.**<br>
*[Yingda Xia](https://yingdaxia.xyz/), [Yi Zhang](https://edz-o.github.io/), [Fengze Liu](https://scholar.google.com/citations?user=T3EjsaAAAAAJ&hl=en), [Wei Shen](http://wei-shen.weebly.com/), [Alan Yuille](https://www.cs.jhu.edu/~ayuille/).*<br>
ECCV 2020. [[PDF](https://arxiv.org/pdf/2003.08440.pdf)] [[Github](https://github.com/YingdaXia/SynthCP)]

**Robust Optimal Transport with Applications in Generative Modeling and Domain Adaptation.**<br>
*Yogesh Balaji, Soheil Feizi.*<br>
NeurIPS 2020. [[PDF](arxiv.org/abs/2010.05862)] [[Github](https://github.com/yogeshbalaji/robustOT)]

**Learning from the Past: Meta-Continual Learning with Knowledge Embedding for Jointly Sketch, Cartoon, and Caricature Face Recognition.**<br>
*Wenbo  Zheng, Lan Yan, Feiyue Wang, Chao Gou.*<br>
ACM MM 2020. [[PDF](https://dl.acm.org/doi/abs/10.1145/3394171.3413892)]

**Random Network Distillation as a Diversity Metric for Both Image and Text Generation.**<br>
*Liam Fowl, Micah Goldblum, Arjun Gupta, Amr Sharaf, Tom Goldstein.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.06715)]

**Experimental Quantum Generative Adversarial Networks for Image Generation.**<br>
*He-Liang Huang, Yuxuan Du, Ming Gong, Youwei Zhao, Yulin Wu, Chaoyue Wang, Shaowei Li, Futian Liang, Jin Lin, Yu Xu, Rui Yang, Tongliang Liu, Min-Hsiu Hsieh, Hui Deng, Hao Rong, Cheng-Zhi Peng, Chao-Yang Lu, Yu-Ao Chen, Dacheng Tao, Xiaobo Zhu, Jian-Wei Pan.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.06201)]

**A Deep Learning Based Interactive Sketching System for Fashion Images Design.**<br>
*Yao Li, Xianggang Yu, Xiaoguang Han, Nianjuan Jiang, Kui Jia, Jiangbo Lu.*<br>
Pacific Graphics 2020. [[PDF](https://arxiv.org/abs/2010.04413)]

**Towards Diverse and Interactive Facial Image Manipulation.**<br>
*Cheng-Han Lee, Ziwei Liu, Lingyun Wu, Ping Luo.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1907.11922)] [[Github](https://github.com/switchablenorms/CelebAMask-HQ)]

**NCP-VAE: Variational Autoencoders with Noise Contrastive Priors.**<br>
*Jyoti Aneja, Alexander Schwing, Jan Kautz, Arash Vahdat.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.02917)]

**Swapping Autoencoder for Deep Image Manipulation.**<br>
*Taesung Park, Jun-Yan Zhu, Oliver Wang, Jingwan Lu, Eli Shechtman, Alexei Efros, Richard Zhang.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2007.00653)] [[Github](https://github.com/zhangqianhui/Swapping-Autoencoder-tf)]

**GRAF: Generative Radiance Fields for 3D-Aware Image Synthesis.**<br>
*Katja Schwarz, Yiyi Liao, Michael Niemeyer, Andreas Geiger.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2007.02442)] [[Github](https://github.com/autonomousvision/graf)]

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
[[Awesome-GANS-and-Deepfakes](https://github.com/enochkan/awesome-gans-and-deepfakes)]

**WildDeepfake: A Challenging Real-World Dataset for Deepfake Detection.**<br>
*Bojia Zi, Minghao Chang, Jingjing Chen, Xingjun Ma, Yu-Gang Jiang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.01456)]

**DeeperForensics-1.0: A Large-Scale Dataset for Real-World Face Forgery Detection.**<br>
*[Liming Jiang](https://liming-jiang.com/), [Wayne Wu](https://wywu.github.io/), [Ren Li](https://liren2515.github.io/page/), [Chen Qian](https://scholar.google.com/citations?user=AerkT0YAAAAJ&hl=en), [Chen Change Loy](http://personal.ie.cuhk.edu.hk/~ccloy/).*<br>
arxiv 2020.
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

**NAS-FAS: Static-Dynamic Central Difference Network Search for Face Anti-Spoofing.**<br>
*Zitong Yu, Jun Wan, Yunxiao Qin, Xiaobai Li, Stan Z. Li, Guoying Zhao.*<br>
TPAMI 2020. [[PDF](https://arxiv.org/abs/2011.02062)] [[CASIA-SURF 3DMask Dataset](http://www.cbsr.ia.ac.cn/users/jwan/database/3DMask.pdf)]

**Cross-ethnicity Face Anti-spoofing Recognition Challenge: A Review.**<br>
*Ajian Liu, Xuan Li, Jun Wan, Sergio Escalera, Hugo Jair Escalante, Meysam Madadi, Yi Jin, Zhuoyuan Wu, Xiaogang Yu, Zichang Tan, Qi Yuan, Ruikun Yang, Benjia Zhou, Guodong Guo, Stan Z. Li.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.10998)]

**Lips Don't Lie: A Generalisable and Robust Approach to Face Forgery Detection.**<br>
*Alexandros Haliassos, Konstantinos Vougioukas, Stavros Petridis, Maja Pantic.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.07657)]

**Face Forgery Detection by 3D Decomposition.**<br>
*Xiangyu Zhu, Hao Wang, Hongyan Fei, Zhen Lei, Stan Z. Li.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.09737)]

**A Survey On Anti-Spoofing Methods For Face Recognition with RGB Cameras of Generic Consumer Devices.**<br>
*Zuheng Ming, Muriel Visani, Muhammad Muzzamil Luqman, Jean-Christophe Burie.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.04145)]

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

## 2D to 3D Convertion

**Unveiling Real-Life Effects of Online Photo Sharing.**<br>
*Van-Khoa Nguyen, Adrian Popescu, Jerome Deshayes-Chossart.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.13180)]

**Cycle-Consistent Generative Rendering for 2D-3D Modality Translation.**<br>
*Tristan Aumentado-Armstrong, Alex Levinshtein, Stavros Tsogkas, Konstantinos G. Derpanis, Allan D. Jepson.*<br>
3DV 2020. [[PDF](https://arxiv.org/abs/2011.08026)] [[Project](https://ttaa9.github.io/genren/)]

**One Shot 3D Photography.**<br>
*Johannes Kopf, Kevin Matzen, Suhib Alsisan, Ocean Quigley, Francis Ge, Yangming Chong, Josh Patterson, Jan-Michael Frahm, Shu Wu, Matthew Yu, Peizhao Zhang, Zijian He, Peter Vajda, Ayush Saraf, Michael Cohen.*<br>
SIGGRAPH 2020. [[PDF](https://arxiv.org/abs/2008.12298)] [[Github](https://github.com/facebookresearch/one_shot_3d_photography)] [[Project](https://facebookresearch.github.io/one_shot_3d_photography/)]

**Deep 3D Portrait from a Single Image.**<br>
*Sicheng Xu, Jiaolong Yang, Dong Chen, Fang Wen, Yu Deng, Yunde Jia, Xin Tong.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.11598)] [[Github](https://github.com/sicxu/Deep3dPortrait)]

**3D-CariGAN: An End-to-End Solution to 3D Caricature Generation from Face Photos.**<br>
*Zipeng Ye, Ran Yi, Minjing Yu, Juyong Zhang, Yu-Kun Lai, Yong-jin Liu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2003.06841)]

**3D Photography using Context-aware Layered Depth Inpainting.**<br>
*[Meng-Li Shih](https://shihmengli.github.io/), [Shih-Yang Su](https://lemonatsu.github.io/), [Johannes Kopf](https://johanneskopf.de/), and [Jia-Bin Huang](https://filebox.ece.vt.edu/~jbhuang/).*<br>
CVPR 2020. [[PDF](https://drive.google.com/file/d/17ki_YAL1k5CaHHP3pIBFWvw-ztF4CCPP/view?usp=sharing)] [[Project](https://shihmengli.github.io/3D-Photo-Inpainting/)] [[Github](https://github.com/vt-vl-lab/3d-photo-inpainting)]

**Self-Supervised 2D Image to 3D Shape Translation with Disentangled Representations.**<br>
*Berk Kaya, Radu Timofte.*<br>
3DV 2020. [[PDF](https://arxiv.org/pdf/2003.10016)]

**Deep 3D-Zoom Net: Unsupervised Learning of Photo-Realistic 3D-Zoom.**<br>
*Juan Luis Gonzalez Bello, Munchurl Kim.*<br>
ICLR 2020. [[PDF](https://arxiv.org/abs/1909.09349)] [[Video](https://www.youtube.com/watch?v=Gz76VYwUzZ8)]

**SynSin: End-to-end View Synthesis from a Single Image.**<br>
*Olivia Wiles, Georgia Gkioxari, Richard Szeliski, Justin Johnson.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.08804)] [[Github](http://www.robots.ox.ac.uk/~ow/synsin.html)]

**NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis.**<br>
*Ben Mildenhall, Pratul P. Srinivasan, Matthew Tancik, Jonathan T. Barron, Ravi Ramamoorthi, Ren Ng.*<br>
arxiv, 19 Mar 2020. [[PDF](https://arxiv.org/abs/2003.08934)] [[Project](http://tancik.com/nerf)] [[Github](https://github.com/bmild/nerf)]

**Photo Wake-Up: 3D Character Animation from a Single Photo.**<br>
*Chung-Yi Weng, Brian Curless, Ira Kemelmacher-Shlizerman.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1812.02246)] [[Project](https://grail.cs.washington.edu/projects/wakeup/)]

**View Independent Generative Adversarial Network for Novel View Synthesis.**<br>
*Xiaogang Xu, Ying-Cong Chen, Jiaya Jia.*<br>
ICCV 2019. [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_View_Independent_Generative_Adversarial_Network_for_Novel_View_Synthesis_ICCV_2019_paper.pdf)]

**Robust Flow-Guided Neural Prediction for Sketch-Based Freeform Surface Modeling.**<br>
*Changjian Li, Hao Pan, Yang Liu, Xin Tong, Alla Sheffer, Wenping Wang.*<br>
SIGGRAPH Asia 2018. [[Project](http://haopan.github.io/sketchCNN.html)] [[PDF](https://enigma-li.github.io/projects/sketchcnn/SketchCNN_SIGA_2018.pdf)] [[Code,Data - GitHub](https://github.com/Enigma-li/SketchCNN/)]

**BendSketch: Modeling Freeform Surfaces Through 2D Sketching.**<br>
*[Changjian Li](https://enigma-li.github.io/), Hao Pan, Yang Liu, Xin Tong, Alla Sheffer, Wenping Wang.*<br>
SIGGRAPH 2017. [[Project](http://haopan.github.io/bendsketch.html)] [[PDF](https://enigma-li.github.io/projects/bendsketching/bendsketch.pdf)]


## Free-Hand Sketch

[Awesome-Sketch-Based-Applications](https://github.com/MarkMoHR/Awesome-Sketch-Based-Applications)

[[TorchSketch](https://github.com/PengBoXiangShang/torchsketch)] is an open source software library for free-hand sketch oriented deep learning research, which is built on the top of PyTorch.

### 2D Sketch to 3D Model

**Sketch2CAD: Sequential CAD Modeling by Sketching in Context.**<br>
*[Changjian Li](https://enigma-li.github.io/), [Hao Pan](http://haopan.github.io/), [Adrien Bousseau](http://www-sop.inria.fr/members/Adrien.Bousseau/), [Niloy J. Mitra](http://www0.cs.ucl.ac.uk/staff/n.mitra/).*<br>
SIGGRAPH Asia 2020. [[PDF](https://arxiv.org/abs/2009.04927)] [[Github](https://github.com/Enigma-li/Sketch2CAD)] [[Project](http://geometry.cs.ucl.ac.uk/projects/2020/sketch2cad/)]

**Vid2CAD: CAD Model Alignment using Multi-View Constraints from Videos.**<br>
*Kevis-Kokitsi Maninis, Stefan Popov, Matthias Nießner, Vittorio Ferrari.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.04641)] [[Project](https://www.kmaninis.com/vid2cad/)] [[Video](https://www.youtube.com/watch?v=R1cXg0vpwe4)]

**A Single-View Approach to Casual 3D Modeling and Animation.**<br>
*[Marek Dvorožňák](http://dcgi.fel.cvut.cz/people/dvoromar/), [Daniel Sýkora](https://dcgi.felk.cvut.cz/~sykorad/), [Cassidy Curtis](http://otherthings.com/), [Brian Curless](https://homes.cs.washington.edu/~curless/), [Olga Sorkine-Hornung](https://igl.ethz.ch/people/sorkine/), [David Salesin](http://salesin.cs.washington.edu/).*<br>
SIGGRAPH Asia 2020. [[PDF](https://dcgi.fel.cvut.cz/home/sykorad/Dvoroznak20-SA.pdf)] [[Project](https://dcgi.fel.cvut.cz/home/sykorad/monster_mash)] [[Demo](http://monstermash.zone/)]

**Towards 3D VR-Sketch to 3D Shape Retrieval.**<br>
*Ling Luo, Yulia Gryaditskaya, Yongxin Yang, Tao Xiang, Yi-Zhe Song.*<br> 
3DV 2020. [[PDF](https://rowl1ng.com/projects/3DSketch3DV/)]

**Deep Sketch-Based Modelling: Tips and Tricks.**<br> 
*Yue Zhong, Yulia Gryaditskaya, Honggang Zhang, Yi-Zhe Song.*<br> 
3DV 2020. [[PDF](https://arxiv.org/pdf/2011.06133.pdf)]

**3D Shape Reconstruction from Sketches via Multi-view Convolutional Networks.**<br> 
*Zhaoliang Lun, Matheus Gadelha, Evangelos Kalogerakis, Subhransu Maji, Rui Wang.*<br> 
3DV 2017. [[PDF](https://arxiv.org/abs/1707.06375)] [[Github](https://github.com/happylun/SketchModeling)] [[Project](http://people.cs.umass.edu/~zlun/papers/SketchModeling/)]

**3D Shape Reconstruction from Free-Hand Sketches.**<br> 
*[Jiayun Wang](http://pwang.pw/), Jierui Lin, [Qian Yu](https://yuqian1023.github.io//), Runtao Liu, [Yubei Chen](https://redwood.berkeley.edu/people/yubei-chen/), [Stella X. Yu](https://www1.icsi.berkeley.edu/~stellayu/).*<br> 
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.09694)] [[Project](http://pwang.pw/3dsketch.html)] [[Github](https://github.com/samaonline/3D-Shape-Reconstruction-from-Free-Hand-Sketches)]

**SketchCNN: Robust Flow-Guided Neural Prediction for Sketch-Based Freeform Surface Modeling.**<br> 
*[Changjian Li](https://enigma-li.github.io/), Hao Pan, Yang Liu, Xin Tong, Alla Sheffer, Wenping Wang.*<br> 
SIGGRAPH Asia 2018. [[PDF](https://dl.acm.org/doi/10.1145/3272127.3275051)] [[Project](http://haopan.github.io/sketchCNN.html)] [[Github](https://github.com/Enigma-li/SketchCNN)]

### 2D Sketch to 2D Image

**Self-Supervised Sketch-to-Image Synthesis.**<br>
*Bingchen Liu, Yizhe Zhu, Kunpeng Song, Ahmed Elgammal.*<br>
AAAI 2020. [[PDF](https://arxiv.org/abs/2012.09290)]

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
ECCV 2020. [[PDF](https://arxiv.org/abs/2001.02890)] [[Github](https://github.com/VITA-Group/DeepPS)]

**Deep Learning for Free-Hand Sketch: A Survey.**<br>
*Peng Xu.*<br>
arxiv, 8 Jan 2020. [[PDF](https://arxiv.org/abs/2001.02600)]

**Examining Performance of Sketch-to-Image Translation Models with Multiclass Automatically Generated Paired Training Data.**<br>
*Dichao Hu.*<br>
arxiv, 2018. [[PDF](https://arxiv.org/abs/1811.00249)]

**Multi-Graph Transformer for Free-Hand Sketch Recognition.**<br>
*[Peng Xu](http://www.pengxu.net/), [Chaitanya K. Joshi](https://chaitjo.github.io/), [Xavier Bresson](https://www.ntu.edu.sg/home/xbresson/).*<br>
arxiv, 2019. [[PDF](https://arxiv.org/abs/1912.11258)] [[Github](https://github.com/PengBoXiangShang/multigraph_transformer)]