# Visual Contents Generation and Manipulation

This repository is about *controllable, interpretable, and generalizable visual contents creation*, which is primaly a collection of papers on image, video, 3D shape generation and manipulation with the guidance by text, audio, camera pose, or other information.  The Controlable Parameters can be Camera, Pose, Lighting, Color, Texture, Semantics, Expression, Speech.

## Table of Contents
- [Industry Demo or Product](#industry-demo-or-product)
- [PhD Thesis and Dissertation](#phd-thesis-and-dissertation)
- [Classical Method Revisiting](#classical-method-revisiting)
- [Lottery Tickets Hypothesis](#lottery-tickets-hypothesis)
- [Interactive and Controllable Image Manipulation](#interactive-and-controllable-image-manipulation)
  * [Highlight Component](#highlight-component)
  * [Rearrange and Retiming](#rearrange-and-retiming)
  * [Human-Object Interaction](#human-object-interaction)
  * [Continuous Image Representation](#continuous-image-representation)
  * [Change Where You Want](#change-where-you-want)
  * [Disentanglement](#disentanglement)
  * [Guided Translation](#guided-translation)
  * [Individual Object Manipulation](#individual-object-manipulation)
  * [Generating Accurate Descriptions](#generating-accurate-descriptions)
- [High-Resolution](#high-resolution)
- [Prediction and Reasoning](#prediction-and-reasoning)
  * [Occlusion Reasoning](#occlusion-reasoning)
  * [Video Generation and Future Prediction](#video-generation-and-future-prediction)
  * [Frame Interpolation and Extrapolation](#frame-interpolation-and-extrapolation)
  * [Video Spatio-Temporal Consistency](#video-spatio-temporal-consistency)
- [3D-Aware Image Synthesis](#3d-aware-image-synthesis)
- [3D Shape Generation and Manipulation](#3d-shape-generation-and-manipulation)
- [Diving Deep into Image Synthesis](#diving-deep-into-image-synthesis)
  * [Generative Models](#generative-models)
  * [StyleGAN-Based Method](#stylegan-based-method)
  * [misc](#misc)
- [2D to 3D Convertion](#2d-to-3d-convertion)
- [Free-Hand Sketch](#free-hand-sketch)
  * [2D Sketch to 3D Model](#2d-sketch-to-3d-model)
  * [2D Sketch to 2D Image](#2d-sketch-to-2d-image)

## Industry Demo or Product

**[MyHeritage](https://www.myheritage.com/deep-nostalgia)**: Animate the faces in your family photos.

**[Google Chimera Painter](https://storage.googleapis.com/chimera-painter/index.html)**: Using GANs to Create Fantastical Creatures.

**Adobe Sensei**: Material World, Scantastic, Sharp Shot, Super Dancing Queen/King, 2D Plus, Comic Blast, AR Together.

**Nvidia Maxine**: Nvidia’s AI-powered video-conferencing technology.

**Nvidia Imaginaire**: [Imaginaire](https://github.com/NVlabs/imaginaire) is a pytorch library that contains optimized implementation of several image and video synthesis methods developed at NVIDIA.

## PhD Thesis and Dissertation

**Learning to See the Physical World.**<br>
*Jiajun Wu.*<br>
ACM Doctoral Dissertation Award Honorable Mention.<br>
Joint AAAI/ACM SIGAI Doctoral Dissertation Award.<br>
MIT George M. Sprowls PhD Thesis Award in Artificial Intelligence and Decision-Making.<br>
2019. [[Dissertation](https://jiajunwu.com/papers/dissertation.pdf)]

**Learning to Synthesize and Manipulate Natural Images.**<br>
*[Jun-Yan Zhu](https://www.cs.cmu.edu/~junyanz/).*<br>
ACM SIGGRAPH Outstanding Doctoral Dissertation Award.<br>
David J. Sakrison Memorial Prize for outstanding doctoral research, by the UC Berkeley EECS Dept.<br>
December, 2017. [Thesis](https://www.cs.cmu.edu/~junyanz/pdf/thesis_highres.pdf) | [Talk](https://youtu.be/MkluiD2lYCc?t=1h16m58s) | [News](https://www.siggraph.org/outstanding-doctoral-dissertation-award-jun-yan-zhu) | [Cover](https://www.cs.cmu.edu/~junyanz/pdf/thesis_cover.pdf)

## Classical Method Revisiting

**X-volution: On the Unification of Convolution and Self-attention.**<br>
*Xuanhong Chen, Hang Wang, Bingbing Ni.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2106.02253)]

**Rethinking "Batch" in BatchNorm.**<br>
*Yuxin Wu, Justin Johnson.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2105.07576)]

**Pay Attention to MLPs.**<br>
*Hanxiao Liu, Zihang Dai, David R. So, Quoc V. Le.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2105.08050)]

**MLP-Mixer: An all-MLP Architecture for Vision.**<br>
*Ilya Tolstikhin, Neil Houlsby, Alexander Kolesnikov, Lucas Beyer, Xiaohua Zhai, Thomas Unterthiner, Jessica Yung, Daniel Keysers, Jakob Uszkoreit, Mario Lucic, Alexey Dosovitskiy.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2105.01601)]

**Do You Even Need Attention? A Stack of Feed-Forward Layers Does Surprisingly Well on ImageNet.**<br>
*Luke Melas-Kyriazi.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2105.02723)] [[Github](https://github.com/lukemelas/do-you-even-need-attention)]

**Beyond Self-attention: External Attention using Two Linear Layers for Visual Tasks.**<br>
*Meng-Hao Guo, Zheng-Ning Liu, Tai-Jiang Mu, Shi-Min Hu.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2105.02358)]

**Involution: Inverting the Inherence of Convolution for Visual Recognition.**<br>
*Duo Li, Jie Hu, Changhu Wang, Xiangtai Li, Qi She, Lei Zhu, Tong Zhang, Qifeng Chen.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.06255)] [[Github](https://github.com/d-li14/involution)]

**Characterizing Signal Propagation to Close the Performance Gap in Unnormalized ResNets.**<br>
*Andrew Brock, Soham De, and Samuel L. Smith.*<br>
ICLR 2021. [[PDF](https://arxiv.org/abs/2102.06171)] [[Github](https://github.com/deepmind/deepmind-research/tree/master/nfnets)]

**Revisiting ResNets: Improved Training and Scaling Strategies.**<br>
*Irwan Bello, William Fedus, Xianzhi Du, Ekin D. Cubuk, Aravind Srinivas, Tsung-Yi Lin, Jonathon Shlens, Barret Zoph.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.07579)] [[Github](https://github.com/tensorflow/models/tree/master/official/vision/beta)] [[ResNet_RS](https://github.com/tensorflow/tpu/tree/master/models/official/resnet/resnet_rs)]

**RepVGG: Making VGG-style ConvNets Great Again.**<br>
*Xiaohan Ding, Xiangyu Zhang, Ningning Ma, Jungong Han, Guiguang Ding, Jian Sun.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.03697)] [[Github](https://github.com/megvii-model/RepVGG)]

## Network Subspace

**Learning Neural Network Subspaces.**<br> 
*Mitchell Wortsman, Maxwell Horton, Carlos Guestrin, Ali Farhadi, Mohammad Rastegari.*<br>
ICML 2021. [[PDF]()]

**Low-Rank Subspaces in GANs.**<br> 
*Jiapeng Zhu, Ruili Feng, Yujun Shen, Deli Zhao, Zhengjun Zha, Jingren Zhou, Qifeng Chen.*<br> 
arxiv 2021. [[PDF](https://arxiv.org/abs/2106.04488)] [[Github](https://github.com/zhujiapeng/LowRankGAN)]

## Deep Learning Explaination

See [Neural Network Interpretability](https://github.com/weihaox/awesome-image-translation/blob/master/awesome-robustness-efficiency-privacy.md#neural-network-interpretability)

## Lottery Tickets Hypothesis

**A Unified Lottery Ticket Hypothesis for Graph Neural Networks.**<br> 
*Tianlong Chen, Yongduo Sui, Xuxi Chen, Aston Zhang, Zhangyang Wang.*<br>
ICML 2021. [[PDF](https://arxiv.org/abs/2102.06790)]

**Efficient Lottery Ticket Finding: Less Data is More.**<br> 
*Zhenyu Zhang, Xuxi Chen, Tianlong Chen, Zhangyang Wang.*<br>
ICML 2021. [[PDF](https://arxiv.org/abs/2106.03225)]

**Playing Lottery Tickets with Vision and Language.**<br>
*Zhe Gan, Yen-Chun Chen, Linjie Li, Tianlong Chen, Yu Cheng, Shuohang Wang, Jingjing Liu.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2104.11832)]

**A Unified Lottery Ticket Hypothesis for Graph Neural Networks.**<br>
*Tianlong Chen, Yongduo Sui, Xuxi Chen, Aston Zhang, Zhangyang Wang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.06790)] [[Github](https://github.com/VITA-Group/Unified-LTH-GNN)]

**The Lottery Tickets Hypothesis for Supervised and Self-supervised Pre-training in Computer Vision Models.**<br>
*Tianlong Chen, Jonathan Frankle, Shiyu Chang, Sijia Liu, Yang Zhang, Michael Carbin, [Zhangyang Wang](https://vita-group.github.io/).*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2012.06908)] [[Github](https://github.com/VITA-Group/CV_LTH_Pre-training)]

**Long Live the Lottery: The Existence of Winning Tickets in Lifelong Learning.**<br>
*Tianlong Chen, Zhenyu Zhang, Sijia Liu, Shiyu Chang, Zhangyang Wang.*<br>
ICLR 2021. [[PDF](https://openreview.net/forum?id=LXMSvPmsm0g)] [[Github](https://github.com/VITA-Group/Lifelong-Learning-LTH)]

**GAN-LTH: GANs Can Play Lottery Tickets Too.**<br> 
*Xuxi Chen, Zhenyu Zhang, Yongduo Sui, Tianlong Chen.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=1AoMhc_9jER)] [[Github](https://github.com/VITA-Group/GAN-LTH)]

**Multi-Prize Lottery Ticket Hypothesis: Finding Accurate Binary Neural Networks by Pruning A Randomly Weighted Network.**<br>
*James Diffenderfer, Bhavya Kailkhura.*<br> 
ICLR 2021. [[PDF](https://openreview.net/forum?id=U_mat0b9iv)] [[Github](https://github.com/chrundle/biprop)]

**The Lottery Ticket Hypothesis for Pre-trained BERT Networks.**<br> 
*Tianlong Chen, Jonathan Frankle, Shiyu Chang, Sijia Liu, Yang Zhang, Zhangyang Wang, Michael Carbin.*<br> 
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2007.12223)] [[Github](https://github.com/VITA-Group/BERT-Tickets)]

**The Early Phase of Neural Network Training.**<br> 
*Jonathan Frankle, David J. Schwab, Ari S. Morcos.*<br> 
ICLR 2020. [[PDF](https://openreview.net/forum?id=Hkl1iRNFwS)] [[Github](https://github.com/VITA-Group/Early-Bird-Tickets)]

**Comparing Rewinding and Fine-tuning in Neural Network Pruning.**<br> 
*Alex Renda, Jonathan Frankle, Michael Carbin.*<br> 
ICLR 2020. [[PDF](https://arxiv.org/abs/2003.02389)] [[Github](https://github.com/lottery-ticket/rewinding-iclr20-public)]

**Drawing Early-bird Tickets: Towards more Efficient Training of Deep Networks.**<br> 
*Haoran You, Chaojian Li, Pengfei Xu, Yonggan Fu, Yue Wang, Xiaohan Chen, Richard G. Baraniuk, Zhangyang Wang, Yingyan Lin.*<br> 
ICLR 2020. [[PDF](https://arxiv.org/abs/1909.11957)] [[Github](https://github.com/RICE-EIC/Early-Bird-Tickets)]

**Playing the Lottery with Rewards and Multiple Languages: Lottery Tickets in RL and NLP.**<br> 
*Haonan Yu, Sergey Edunov, Yuandong Tian, Ari S. Morcos.*<br> 
ICLR 2020. [[PDF](https://openreview.net/forum?id=S1xnXRVFwH)]

**Linear Mode Connectivity and the Lottery Ticket Hypothesis.**<br> 
*Jonathan Frankle, Gintare Karolina Dziugaite, Daniel M. Roy, Michael Carbin.*<br> 
ICML 2020. [[PDF](https://arxiv.org/abs/1912.05671)]

**Pruning neural networks without any data by iteratively conserving synaptic flow.**<br> 
*Hidenori Tanaka, Daniel Kunin, Daniel L. K. Yamins, Surya Ganguli.*<br> 
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.05467)] [[Github](https://github.com/ganguli-lab/Synaptic-Flow)]

**One Ticket to Win Them All: Generalizing Lottery Ticket Initializations across Datasets and Optimizers.**<br> 
*Ari S. Morcos, Haonan Yu, Michela Paganini, Yuandong Tian.*<br> 
NeurIPS 2019. [[PDF](https://arxiv.org/abs/1906.02773)] [[Github](https://github.com/varungohil/Generalizing-Lottery-Tickets)]

**Deconstructing Lottery Tickets: Zeros, Signs, and the Supermask.**<br> 
*Hattie Zhou, Janice Lan, Rosanne Liu, Jason Yosinski.*<br> 
NeurIPS 2019. [[PDF](https://arxiv.org/abs/1905.01067)] [[Github]()]

**The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks.**<br> 
*[Jonathan Frankle](http://www.jfrankle.com/), Michael Carbin.*<br> 
ICLR 2019 (Best paper award). [[PDF](https://arxiv.org/abs/1803.03635)] [[Github](https://github.com/facebookresearch/open_lth)]

## Interactive and Controllable Image Manipulation

### Heterogeneous Face Translation

**FaceInpainter: High Fidelity Face Adaptation to Heterogeneous Domains.**<br>
*Jia Li, Zhaoyang Li, Jie Cao, Xingguan Song, Ran He.*<br>
CVPR 2021.

**Few-shot Image Generation via Cross-domain Correspondence.**<br>
*[Utkarsh Ojha](https://utkarshojha.github.io/), [Yijun Li](https://yijunmaverick.github.io/), [Jingwan Lu](https://research.adobe.com/person/jingwan-lu/), [Alexei A. Efros](https://people.eecs.berkeley.edu/~efros/), [Yong Jae Lee](https://web.cs.ucdavis.edu/~yjlee/), [Eli Shechtman](https://research.adobe.com/person/eli-shechtman/), [Richard Zhang](https://richzhang.github.io/).*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.06820)] [[Project](https://utkarshojha.github.io/few-shot-gan-adaptation/)] [[Github](https://github.com/utkarshojha/few-shot-gan-adaptation)]

**Cross-Spectral Face Hallucination via Disentangling Independent Factors.**<br>
*Boyan Duan, Chaoyou Fu, Yi Li, Xingguang Song, Ran He.*<br>
CVPR 2020. [[PDF](https://openaccess.thecvf.com/content_CVPR_2020/papers/Duan_Cross-Spectral_Face_Hallucination_via_Disentangling_Independent_Factors_CVPR_2020_paper.pdf)]

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

**NeRViS: Neural Re-rendering for Full-frame Video Stabilization.**<br>
*[Yu-Lun Liu](https://www.cmlab.csie.ntu.edu.tw/~nothinglo/), [Wei-Sheng Lai](https://www.wslai.net/), [Ming-Hsuan Yang](https://faculty.ucmerced.edu/mhyang/), [Yung-Yu Chuang](https://www.csie.ntu.edu.tw/~cyy/), [Jia-Bin Huang](https://filebox.ece.vt.edu/~jbhuang/).*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.06205)] [[Github](https://alex04072000.github.io/NeRViS/)]

### Rearrange and Retiming

**Learning by Aligning Videos in Time.**<br>
*Sanjay Haresh, Sateesh Kumar, Huseyin Coskun, Shahram Najam Syed, Andrey Konin, Muhammad Zeeshan Zia, Quoc-Huy Tran.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.17260)]

**Repopulating Street Scenes.**<br>
*Yifan Wang, Andrew Liu, Richard Tucker, Jiajun Wu, Brian L. Curless, Steven M. Seitz, Noah Snavely.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.16183)]

**Visual Room Rearrangement.**<br>
*Luca Weihs, Matt Deitke, Aniruddha Kembhavi, Roozbeh Mottaghi.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.16544)]

**Human De-occlusion: Invisible Perception and Recovery for Humans.**<br>
*[Qiang Zhou](https://scholar.google.com/citations?user=8NIZGJcAAAAJ&hl=en), Shiyin Wang, [Yitong Wang](https://scholar.google.com/citations?user=NfFTKfYAAAAJ&hl=en), [Zilong Huang](https://speedinghzl.github.io/), [Xinggang Wang](http://xinggangw.info/).*<br>
CVPR 2021. [[PDF](https://sydney0zq.github.io/ahp/files/human_deocclusion-cvpr2021.pdf)] [[Github](https://sydney0zq.github.io/ahp/)]

**Layered Neural Rendering for Retiming People in Video.**<br>
*Erika Lu, Forrester Cole, Tali Dekel, Weidi Xie, Andrew Zisserman, David Salesin, William T. Freeman, Michael Rubinstein.*<br>
SIGGRAPH Asia 2020. [[PDF](https://arxiv.org/abs/2009.07833)] [[Project](https://retiming.github.io/)]

**Neural Scene Graphs for Dynamic Scenes.**<br>
*Julian Ost, Fahim Mannan, Nils Thuerey, Julian Knodt, Felix Heide.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.10379)]

**Self-Supervised Scene De-occlusion.**<br>
*[Xiaohang Zhan](https://xiaohangzhan.github.io/), Xingang Pan, Bo Dai, Ziwei Liu, Dahua Lin, and Chen Change Loy.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.02788)] [[Github](https://github.com/XiaohangZhan/deocclusion)] [[Project](https://xiaohangzhan.github.io/projects/deocclusion/)] [[Demo](https://www.youtube.com/watch?v=xIHCyyaB5gU)]

### Neural Simulation

**DriveGAN: Towards a Controllable High-Quality Neural Simulation.**<br>
*[Seung Wook Kim](http://www.cs.toronto.edu/~seung/), [Jonah Philion](http://www.cs.toronto.edu/), [Antonio Torralba](http://web.mit.edu/torralba/www/), [Sanja Fidler](https://www.cs.utoronto.ca/~fidler/).*<br>
CVPR 2021 (oral). [[PDF](https://arxiv.org/abs/2104.15060)] [[Project](https://nv-tlabs.github.io/DriveGAN/)]

**Learning to Simulate Dynamic Environments with GameGAN.**<br>
*[Seung Wook Kim](http://www.cs.toronto.edu/~seung/), [Yuhao Zhou](https://henryzhou7.github.io/), [Jonah Philion](http://www.cs.toronto.edu/), [Antonio Torralba](http://web.mit.edu/torralba/www/), [Sanja Fidler](https://www.cs.utoronto.ca/~fidler/).*<br>
CVPR 2020. [[PDF]()] [[Github](https://github.com/nv-tlabs/GameGAN_code)] [[Project](https://nv-tlabs.github.io/gameGAN/)]

### Human-Object Interaction

**Detecting Human-Object Interaction via Fabricated Compositional Learning.**<br>
*Zhi Hou, Baosheng Yu, Yu Qiao, Xiaojiang Peng, Dacheng Tao.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.08214)]

**QPIC: Query-Based Pairwise Human-Object Interaction Detection with Image-Wide Contextual Information.**<br>
*Masato Tamura, Hiroki Ohashi, Tomoaki Yoshinaga.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.05399)]

**DJRN: Detailed 2D-3D Joint Representation for Human-Object Interaction.**<br>
*Yong-Lu Li, Xinpeng Liu, Han Lu, Shiyi Wang, Junqi Liu, Jiefeng Li, Cewu Lu.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.08154)] [[Github](https://github.com/DirtyHarryLYL/DJ-RN)]

**Learning Asynchronous and Sparse Human-Object Interaction in Videos.**<br>
*Romero Morais, Vuong Le, Svetha Venkatesh, Truyen Tran.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.02758)]

**HOI Analysis: Integrating and Decomposing Human-Object Interaction.**<br>
*[Yong-Lu Li](https://dirtyharrylyl.github.io/), Xinpeng Liu, Xiaoqian Wu, Yizhuo Li, [Cewu Lu](http://mvig.sjtu.edu.cn/).*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2010.16219)] [[Project](https://github.com/DirtyHarryLYL/HAKE-Action-Torch)] [[Github](http://github.com/DirtyHarryLYL/HAKE-Action-Torch/tree/IDN-(Integrating-Decomposing-Network))]

### Continuous Image Representation

**LIIF: Learning Continuous Image Representation with Local Implicit Image Function.**<br>
*Yinbo Chen, Sifei Liu, Xiaolong Wang.*<br>
CVPR 2021 (oral). [[PDF](https://arxiv.org/abs/2012.09161)] [[Github](https://github.com/yinboc/liif)] [[Project](https://yinboc.github.io/liif/)]

**INR: Adversarial Generation of Continuous Images.**<br>
*Ivan Skorokhodov, Savva Ignatyev, Mohamed Elhoseiny.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2011.12026)] [[Github](https://github.com/universome/inr-gan)]

**CoMoGAN: Continuous Model-guided Image-to-image Translation.**<br>
*[Fabio Pizzati](https://fabvio.github.io/), [Pietro Cerri](https://scholar.google.fr/citations?user=MEidJHwAAAAJ), [Raoul de Charette](https://team.inria.fr/rits/membres/raoul-de-charette/).*<br>
CVPR 2021 (oral). [[PDF](https://arxiv.org/abs/2103.06879)] [[GitHub](https://github.com/cv-rits/CoMoGAN)]

### Change Where You Want

**High-Fidelity and Arbitrary Face Editing.**<br>
*Yue Gao, Fangyun Wei, Jianmin Bao, Shuyang Gu, Dong Chen, Fang Wen, Zhouhui Lian.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.15814)]

**Paint by Word.**<br>
*David Bau, Alex Andonian, Audrey Cui, YeonHwan Park, Ali Jahanian, Aude Oliva, Antonio Torralba.*<br>
arxiv 2021. [[PDF](https://arxiv.org/pdf/2103.10951)]

**Using Latent Space Regression to Analyze and Leverage Compositionality in GANs.**<br> 
*Lucy Chai, Jonas Wulff, Phillip Isola.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=sjuuTm4vj0)]

**DeFLOCNet: Deep Image Editing via Flexible Low-level Controls.**<br>
*Hongyu Liu, Ziyu Wan, Wei Huang, Yibing Song, Xintong Han, Jing Liao, Bin Jiang, and Wei Liu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.12723)] [[Github](https://github.com/KumapowerLIU/DeFLOCNet)]

**Enjoy Your Editing: Controllable GANs for Image Editing via Latent Space Navigation.**<br>
*Peiye Zhuang, Oluwasanmi Koyejo, Alexander G. Schwing.*<br>
ICLR 2021. [[PDF](https://arxiv.org/abs/2102.01187)]

**GAN-Control: Explicitly Controllable GANs.**<br>
*Alon Shoshan, Nadav Bhonker, Igor Kviatkovsky, Gerard Medioni.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2101.02477)]

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
ACM MM 2020. [[PDF](https://arxiv.org/abs/2008.04200)] [[Github](https://github.com/yhlleo/DWC-GAN)]

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

**FaceController: Controllable Attribute Editing for Face in the Wild.**<br>
*Zhiliang Xu, Xiyu Yu, Zhibin Hong, Zhen Zhu, Junyu Han, Jingtuo Liu, Errui Ding, Xiang Bai.*<br>
AAAI 2021. [[PDF](https://arxiv.org/abs/2102.11464)]

**MorphNet: One-Shot Face Synthesis GAN for Detecting Recognition Bias.**<br>
*Nataniel Ruiz, Barry-John Theobald, Anurag Ranjan, Ahmed Hussein Abdelaziz, Nicholas Apostoloff.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.05225)]

**Lifting 2D StyleGAN for 3D-Aware Face Generation.**<br>
*Yichun Shi, Divyansh Aggarwal, Anil K. Jain.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.13126)]

**Legacy Photo Editing with Learned Noise Prior.**<br>
*Yuzhi Zhao, Lai-Man Po, Xuehui Wang, Kangcheng Liu, Yujia Zhang, Wing-Yin Yu, Pengfei Xian, Jingjing Xiong.*<br>
WACV 2021. [[PDF](https://arxiv.org/abs/2011.11309)] [[Github](https://github.com/zhaoyuzhi/Legacy-Photo-Editing-with-Learned-Noise-Prior)]

**Disentangling Latent Space for Unsupervised Semantic Face Editing.**<br>
*Kanglin Liu, Gaofeng Cao, Fei Zhou, Bozhi Liu, Jiang Duan, Guoping Qiu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.02638)] [[Github](https://github.com/max-liu-112/STGAN-WO)]

**Learning a Deep Reinforcement Learning Policy Over the Latent Space of a Pre-trained GAN for Semantic Age Manipulation.**<br>
*Kumar Shubham, Gopalakrishnan Venkatesh, Reijul Sachdev, Akshi, Dinesh Babu Jayagopi, G. Srinivasaraghavan.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.00954)]

### Disentanglement

**Omnimatte: Associating Objects and Their Effects in Video.**<br>
*Erika Lu, Forrester Cole, Tali Dekel, Andrew Zisserman, William T. Freeman, Michael Rubinstein.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2105.06993)] [[Github](https://omnimatte.github.io/)]

**CS-DisMo: Rethinking Content and Style - Exploring Bias for Unsupervised Disentanglement.**<br>
*Xuanchi Ren, Tao Yang, Yuwang Wang, Wenjun Zeng.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.10544)] [[Github](https://github.com/xrenaa/CS-DisMo)]

**DisCo: Do Generative Models Know Disentanglement? Contrastive Learning is All You Need.**<br>
*Xuanchi Ren, Tao Yang, Yuwang Wang, Wenjun Zeng.*<br>
arxiv 2021. [[PDF](https://arxiv.org/pdf/2102.10543.pdf)] [[Github](https://github.com/xrenaa/DisCo)]<br>

### Image Style Transfer

**Style-Aware Normalized Loss for Improving Arbitrary Style Transfer.**<br>
*Jiaxin Cheng, Ayush Jaiswal, Yue Wu, Pradeep Natarajan, Prem Natarajan.*<br>
CVPR 2021 (oral). [[PDF](https://arxiv.org/abs/2104.10064)]

**Rethinking and Improving the Robustness of Image Style Transfer.**<br>
*Pei Wang, Yijun Li, Nuno Vasconcelos.*<br>
CVPR 2021 (oral). [[PDF](https://arxiv.org/abs/2104.05623)]

**Drafting and Revision: Laplacian Pyramid Network for Fast High-Quality Artistic Style Transfer.**<br>
*Tianwei Lin, Zhuoqi Ma, Fu Li, Dongliang He, Xin Li, Errui Ding, Nannan Wang, Jie Li, Xinbo Gao.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.05376)] [[Github](https://github.com/PaddlePaddle/PaddleGAN/)]

**ArtFlow: Unbiased Image Style Transfer via Reversible Neural Flows.**<br>
*Jie An, [Siyu Huang](https://siyuhuang.github.io/), Yibing Song, Dejing Dou, Wei Liu, and Jiebo Luo.*<br>
CVPR 2021. [[PDF](https://arxiv.org/pdf/2103.16877.pdf)] [[Github](https://github.com/pkuanjie/ArtFlow)]

**Towards Ultra-Resolution Neural Style Transfer via Thumbnail Instance Normalization.**<br>
*Zhe Chen, Wenhai Wang, Enze Xie, Tong Lu, Ping Luo.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.11784)]

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

**Avatar-Net: Multi-scale Zero-shot Style Transfer by Feature Decoration.**<br>
*Lu Sheng, Ziyi Lin, Jing Shao, Xiaogang Wang.*<br>
CVPR 2018. [[PDF](https://arxiv.org/abs/1805.03857)] [[Project](https://lucassheng.github.io/avatar-net/)] [[Github](https://github.com/LucasSheng/avatar-net)]

**AdaIN: Arbitrary Style Transfer in Real-time with Adaptive Instance Normalization.**<br>
*Xun Huang, Serge Belongie.*<br>
ICCV 2017 (Oral). [[PDF](https://arxiv.org/abs/1703.06868)] [[Github](https://github.com/xunhuang1995/AdaIN-style)]

**WCT: Universal Style Transfer via Feature Transforms.**<br>
*Yijun Li, Chen Fang, Jimei Yang, Zhaowen Wang, Xin Lu, Ming-Hsuan Yang.*<br>
NIPS 2017. [[PDF](https://arxiv.org/abs/1705.08086)] [[Github](https://github.com/Yijunmaverick/UniversalStyleTransfer)]

### Guided Translation

Part of this repository is about *Guided Image-to-image translation* which can be found [here](https://github.com/xiaweihao/awesome-image-translation/blob/master/README_.md#guided-image-to-image-translation).

**AgileGAN: Stylizing Portraits by Inversion-Consistent Transfer Learning.**<br>
*[Guoxian Song](https://guoxiansong.github.io/homepage/index.html), [Linjie Luo](http://linjieluo.com/), Jing Liu, Wan-Chun Ma, Chunpong Lai, Chuanxia Zheng, Tat-Jen Cham.*<br>
ACM Transactions on Graphics (Siggraph 2021). [[PDF](https://guoxiansong.github.io/homepage/paper/AgileGAN.pdf)] [[Project](https://guoxiansong.github.io/homepage/agilegan)] [[Demo](http://www.agilegan.com/)]

**Enhancing Photorealism Enhancement.**<br>
*Stephan R. Richter, Hassan Abu AlHaija, Vladlen Koltun.*<br>
arxiv 2021. [[PDF](https://arxiv.org/pdf/2105.04619.pdf)] [[Github](https://github.com/intel-isl/PhotorealismEnhancement)]  [[Video](https://youtu.be/P1IcaBn3ej0)]

**iLAT: The Image Local Autoregressive Transformer.**<br>
*Chenjie Cao, Yuxin Hong, Xiang Li, Chengrong Wang, Chengming Xu, XiangYang Xue, Yanwei Fu.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2106.02514)]

**UFC-BERT: Unifying Multi-Modal Controls for Conditional Image Synthesis.**<br>
*Zhu Zhang, Jianxin Ma, Chang Zhou, Rui Men, Zhikang Li, Ming Ding, Jie Tang, Jingren Zhou, Hongxia Yang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2105.14211)]

**Controllable Person Image Synthesis with Spatially-Adaptive Warped Normalization.**<br> 
*Jichao Zhang, Aliaksandr Siarohin, Hao Tang, Jingjing Chen, Enver Sangineto, Wei Wang, Nicu Sebe.*<br> 
arxiv 2021. [[PDF](https://arxiv.org/abs/2105.14739)]

**HistoGAN: Controlling Colors of GAN-Generated and Real Images via Color Histograms.**<br> 
*[Mahmoud Afifi](https://sites.google.com/view/mafifi), [Marcus A. Brubaker](https://mbrubake.github.io/), [Michael S. Brown](http://www.cse.yorku.ca/~mbrown/).*<br> 
CVPR 2021. [[PDF](https://arxiv.org/abs/2011.11731)] [[Github](https://github.com/mahmoudnafifi/HistoGAN)]

**Progressive and Aligned Pose Attention Transfer for Person Image Generation.**<br> 
*Zhen Zhu, Tengteng Huang, Mengde Xu, Baoguang Shi, Wenqing Cheng, Xiang Bai.*<br> 
TPAMI 2021. [[PDF](https://arxiv.org/abs/2103.11622)]

**PhotoApp: Photorealistic Appearance Editing of Head Portraits.**<br>
*Mallikarjun B R, Ayush Tewari, Abdallah Dib, Tim Weyrich, Bernd Bickel, Hans-Peter Seidel, Hanspeter Pfister, Wojciech Matusik, Louis Chevallier, Mohamed Elgharib, Christian Theobalt.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.07658)] [[Project](http://gvv.mpi-inf.mpg.de/projects/PhotoApp/)]

**PISE: Person Image Synthesis and Editing with Decoupled GAN.**<br>
*[Jinsong Zhang](https://zhangjinso.github.io/), [Kun Li](http://cic.tju.edu.cn/faculty/likun/), [Yu-Kun Lai](http://users.cs.cf.ac.uk/Yukun.Lai/), [Jingyu Yang](http://tju.iirlab.org/).*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.04023)] [[Project](http://cic.tju.edu.cn/faculty/likun/projects/PISE/)] [[Github](https://github.com/Zhangjinso/PISE)]

**MeInGame: Create a Game Character Face from a Single Portrait.**<br>
*Jiangke Lin, Yi Yuan, Zhengxia Zou.*<br>
AAAI 2021. [[PDF](https://arxiv.org/abs/2102.02371)]

**Style-Controllable Speech-Driven Gesture Synthesis Using Normalising Flows.**<br>
*Alexanderson, Simon and Henter, Gustav Eje and Kucherenko, Taras and Beskow, Jonas.*<br>
Computer Graphics Forum 2020. [[PDF](https://diglib.eg.org/handle/10.1111/cgf13946)] [[Github](https://github.com/simonalexanderson/StyleGestures)]

**MoGlow: Probabilistic and Controllable Motion Synthesis Using Normalising Flows.**<br>
*Gustav Eje Henter, Simon Alexanderson, Jonas Beskow.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/1905.06598)] [[Github](https://github.com/simonalexanderson/StyleGestures)]

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
*[Yael Vinker](https://www.linkedin.com/in/yael-vinker-a91a00157/), [Eliahu Horwitz](https://www.linkedin.com/in/eliahu-horwitz), Nir Zabari, [Yedid Hoshen](http://www.cs.huji.ac.il/~ydidh).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.01289)] [[Project](http://www.vision.huji.ac.il/deepsim/)] [[Github](https://github.com/eliahuhorwitz/DeepSIM)]

**HifiFace: 3D Shape and Semantic Prior Guided High Fidelity Face Swapping.**<br>
*Yuhan Wang, Xu Chen, Junwei Zhu, Wenqing Chu, Ying Tai, Chengjie Wang, Jilin Li, Yongjian Wu, Feiyue Huang, Rongrong Ji.*<br>
IJCAI 2021. [[PDF](https://arxiv.org/abs/2106.09965)] [[Project](https://johann.wang/HifiFace)]

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


**Progressive Pose Attention Transfer for Person Image Generation.**<br> 
*Zhen Zhu, Tengteng Huang, Baoguang Shi, Miao Yu, Bofei Wang, Xiang Bai.*<br> 
CVPR 2019 (oral). [[PDF](https://arxiv.org/abs/1904.03349)] [[Github](https://github.com/tengteng95/Pose-Transfer.git)]

**Diverse Semantic Image Synthesis via Probability Distribution Modeling.**<br> 
*Zhentao Tan, Menglei Chai, Dongdong Chen, Jing Liao, Qi Chu, Bin Liu, Gang Hua, Nenghai Yu.*<br> 
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.06878)]

**Graph2Plan: Learning Floorplan Generation from Layout Graphs.**<br>
*Ruizhen Hu, Zeyu Huang, Yuhan Tang, Oliver van Kaick, Hao Zhang, Hui Huang.*<br>
ACM Transactions on Graphics 2020. [[PDF](https://arxiv.org/abs/2004.13204)]

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

**e-ViL: A Dataset and Benchmark for Natural Language Explanations in Vision-Language Tasks.**<br>
*Maxime Kayser, Oana-Maria Camburu, Leonard Salewski, Cornelius Emde, Virginie Do, Zeynep Akata, Thomas Lukasiewicz.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2105.03761)]

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

## High-Resolution Image Synthesis

### Toward 1024-Resolution

**In&Out : Diverse Image Outpainting via GAN Inversion.**<br>
*Yen-Chi Cheng, Chieh Hubert Lin, Hsin-Ying Lee, Jian Ren, Sergey Tulyakov, Ming-Hsuan Yang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2104.00675)] [[Github](https://yccyenchicheng.github.io/InOut/)]

**A Good Image Generator Is What You Need for High-Resolution Video Synthesis.**<br>
*Yu Tian, Jian Ren, Menglei Chai, Kyle Olszewski, Xi Peng, Dimitris N. Metaxas, Sergey Tulyakov.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=6puCSjH3hwA)]

### Toward Infinite-Resolution

**Aligning Latent and Image Spaces to Connect the Unconnectable.**<br>
*Ivan Skorokhodov, Grigorii Sotnikov, Mohamed Elhoseiny.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2104.06954)] [[Project](https://universome.github.io/alis)] [[Github](https://github.com/universome/alis)]

**In&Out : Diverse Image Outpainting via GAN Inversion.**<br>
*Yen-Chi Cheng, Chieh Hubert Lin, Hsin-Ying Lee, Jian Ren, Sergey Tulyakov, Ming-Hsuan Yang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2104.00675)] [[Github](https://yccyenchicheng.github.io/InOut/)]

**InfinityGAN: Towards Infinite-Resolution Image Synthesis.**<br>
*Chieh Hubert Lin, Hsin-Ying Lee, Yen-Chi Cheng, Sergey Tulyakov, Ming-Hsuan Yang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2104.03963)] [[Project](https://hubert0527.github.io/infinityGAN/)]

**Taming Transformers for High-Resolution Image Synthesis.**<br>
*[Patrick Esser](https://github.com/pesser), [Robin Rombach](https://github.com/rromb), [Björn Ommer](https://hci.iwr.uni-heidelberg.de/Staff/bommer).*<br>
CVPR 2021 (Oral). [[PDF](https://arxiv.org/abs/2012.09841)] [[Project](https://compvis.github.io/taming-transformers/)] [[Github](https://github.com/CompVis/taming-transformers)]

**Boundless: Generative Adversarial Networks for Image Extension.**<br>
*Piotr Teterwak, Aaron Sarna, Dilip Krishnan, Aaron Maschinot, David Belanger, Ce Liu, William T. Freeman.*<br>
ICCV 2019. [[PDF](https://arxiv.org/pdf/1908.07007.pdf)] [[Project](https://sites.google.com/view/boundless-iccv/home)] [[Github](https://github.com/recong/Boundless-in-Pytorch)]

**NS-Outpainting: Very Long Natural Scenery Image Prediction by Outpainting.**<br>
*Zongxin Yang, Jian Dong, Ping Liu, Yi Yang, Shuicheng Yan.*<br>
ICCV 2019. [[PDF](https://arxiv.org/pdf/1912.12688.pdf)] [[Github](https://github.com/z-x-yang/NS-Outpainting)]

## Lightweight High-Resolution Image Synthesis

**Lite-HRNet: A Lightweight High-Resolution Network.**<br>
*Changqian Yu, Bin Xiao, Changxin Gao, Lu Yuan, Lei Zhang, Nong Sang, Jingdong Wang.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.06403)] [[Github](https://github.com/HRNet/Lite-HRNet)]

**Anycost GANs for Interactive Image Synthesis and Editing.**<br>
*Ji Lin, Richard Zhang, Frieder Ganz, Song Han, Jun-Yan Zhu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.03243)] [[Github](https://github.com/mit-han-lab/anycost-gan)] [[Project](https://hanlab.mit.edu/projects/anycost-gan/)]

**Content-Aware GAN Compression.**<br>
*Yuchen Liu, Zhixin Shu, Yijun Li, Zhe Lin, Federico Perazzi, S.Y. Kung.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.02244)]

**MobileStyleGAN: A Lightweight Convolutional Neural Network for High-Fidelity Image Synthesis.**<br>
*Sergei Belousov.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2104.04767)] [[Github](https://github.com/bes-dev/MobileStyleGAN.pytorch)]

## Prediction and Reasoning 

### Occlusion Reasoning

**Peek-a-Boo: Occlusion Reasoning in Indoor Scenes with Plane Representations.**<br>
*Ziyu Jiang, Buyu Liu, Samuel Schulter, Zhangyang Wang, [Manmohan Chandraker](http://cseweb.ucsd.edu/~mkchandraker/).*<br>
CVPR 2020. [[PDF](http://cseweb.ucsd.edu/~mkchandraker/pdf/cvpr20_peekaboo.pdf)]

**Self-Supervised Scene De-occlusion.**<br>
*[Xiaohang Zhan](https://xiaohangzhan.github.io/), [Xingang Pan](https://xingangpan.github.io/), Bo Dai, Ziwei Liu, Dahua Lin, Chen Change Loy.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.02788)] [[Project](https://xiaohangzhan.github.io/projects/deocclusion/)] [[Github](https://github.com/XiaohangZhan/deocclusion/)]

**Human De-occlusion: Invisible Perception and Recovery for Humans.**<br>
*[Qiang Zhou](https://scholar.google.com/citations?user=8NIZGJcAAAAJ&hl=en), Shiyin Wang, [Yitong Wang](https://scholar.google.com/citations?user=NfFTKfYAAAAJ&hl=en), [Zilong Huang](https://speedinghzl.github.io/), [Xinggang Wang](http://xinggangw.info/).*<br>
CVPR 2021. [[PDF](https://sydney0zq.github.io/ahp/files/human_deocclusion-cvpr2021.pdf)] [[Github](https://sydney0zq.github.io/ahp/)]

**Efficient Non-Line-of-Sight Imaging from Transient Sinograms.**<br>
*Mariko Isogawa, Dorian Chan, Ye Yuan, Kris Kitani, Matthew O'Toole.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.02787)]

### Video Generation and Future Prediction

[[Image Generation SOTA](https://paperswithcode.com/task/image-generation)] 

[[Video Generation SOTA](https://paperswithcode.com/task/video-generation)]

Video from a single image or text can be found at [here](https://github.com/weihaox/awesome-image-translation/blob/master/content/multi-modal-representation.md#image-to-video).

**VideoGPT: Video Generation using VQ-VAE and Transformers.**<br>
*Wilson Yan, Yunzhi Zhang, Pieter Abbeel, Aravind Srinivas.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2104.10157)] [[Project](https://wilson1yan.github.io/videogpt/index.html)]

**Deep Animation Video Interpolation in the Wild.**<br>
*Li Siyao, Shiyu Zhao, Weijiang Yu, Wenxiu Sun, Dimitris N. Metaxas, Chen Change Loy, Ziwei Liu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.02495)] [[Github](https://github.com/lisiyao21/AnimeInterp/)]

**Playable Video Generation.**<br>
*Willi Menapace, Stéphane Lathuilière, Sergey Tulyakov, Aliaksandr Siarohin, Elisa Ricci.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2101.12195)] [[Github](https://github.com/willi-menapace/PlayableVideoGeneration)]

**The Invertible U-Net for Optical-Flow-free Video Interframe Generation.**<br>
*Saem Park, Donghun Han, Nojun Kwak.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.09576)]

**FloMo: Tractable Motion Prediction with Normalizing Flows.**<br>
*Christoph Schöller, Alois Knoll.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.03614)]

**Predicting Video with VQVAE.**<br>
*Jacob Walker, Ali Razavi, Aäron van den Oord.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.01950)]

**One Shot Audio to Animated Video Generation.**<br>
*Neeraj Kumar, Srishti Goel, Ankur Narang, Brejesh Lall, Mujtaba Hasan, Pranshu Agarwal, Dipankar Sarkar.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.09737)]

**Clockwork Variational Autoencoders for Video Prediction.**<br>
*Vaibhav Saxena, Jimmy Ba, Danijar Hafner.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.09532)]

**Robust Motion In-betweening.**<br>
*Félix G. Harvey, Mike Yurick, Derek Nowrouzezahrai, Christopher Pal.*<br>
SIGGRAPH 2020. [[PDF](https://arxiv.org/abs/2102.04942)]

**Controllable and Progressive Image Extrapolation.**<br>
*Yijun Li, Lu Jiang, Ming-Hsuan Yang.*<br>
WACV 2021. [[PDF](https://openaccess.thecvf.com/content/WACV2021/html/Li_Controllable_and_Progressive_Image_Extrapolation_WACV_2021_paper.html)]

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
arxiv 2020. [[PDF](https://arxiv.org/abs/2003.04035)]

**The Garden of Forking Paths: Towards Multi-Future Trajectory Prediction.**<br>
*Junwei Liang, Lu Jiang, Kevin Murphy, Ting Yu, Alexander Hauptmann.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.06445)] [[Project](https://next.cs.cmu.edu/multiverse/index.html)] [[The Forking Paths Dataset](https://next.cs.cmu.edu/multiverse/index.html)]

**Future Video Synthesis with Object Motion Prediction.**<br>
*Yue Wu, Rongrong Gao, Jaesik Park, Qifeng Chen.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.00542)] [[Github](https://github.com/YueWuHKUST/FutureVideoSynthesis)]

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

**World-Consistent Video-to-Video Synthesis.**<br>
*Arun Mallya, Ting-Chun Wang, Karan Sapra, Ming-Yu Liu.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.08509)]

**Generative Adversarial Networks for Image and Video Synthesis: Algorithms and Applications.**<br>
*Ming-Yu Liu, Xun Huang, Jiahui Yu, Ting-Chun Wang, Arun Mallya.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.02793)]

**World-Consistent Video-to-Video Synthesis.**<br> 
*Arun Mallya, Ting-Chun Wang, Karan Sapra, Ming-Yu Liu.*<br> 
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.08509)] [[Github](https://nvlabs.github.io/wc-vid2vid/)]

**Intrinsic Temporal Regularization for High-resolution Human Video Synthesis.**<br>
*Lingbo Yang, Zhanning Gao, Peiran Ren, Siwei Ma, Wen Gao.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.06134)]

**Latent Neural Differential Equations for Video Generation.**<br>
*Cade Gordon, Natalie Parde.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.03864)]

### Frame Interpolation and Extrapolation

**Motion-blurred Video Interpolation and Extrapolation.**<br>
*Dawit Mureja Argaw, Junsik Kim, Francois Rameau, In So Kweon.*<br>
AAAI 2021. [[PDF](https://arxiv.org/abs/2103.02984)]

**Texture-aware Video Frame Interpolation.**<br>
*Duolikun Danier, David Bull.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.13520)]

**Softmax Splatting for Video Frame Interpolation.**<br>
*Simon Niklaus, Feng Liu.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.05534)] [[Github](http://sniklaus.com/softsplat)]

**FLAVR: Flow-Agnostic Video Representations for Fast Frame Interpolation.**<br>
*Tarun Kalluri, Deepak Pathak, Manmohan Chandraker, Du Tran.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2012.08512)] [[Project](https://tarun005.github.io/FLAVR/)] [[Github](https://tarun005.github.io/FLAVR/Code)]

**NSFF: Neural Scene Flow Fields for Space-Time View Synthesis of Dynamic Scenes.**<br>
*Zhengqi Li, Simon Niklaus, Noah Snavely, Oliver Wang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.13084)] [[Github](http://www.cs.cornell.edu/~zl548/NSFF/)]

**ConvTransformer: A Convolutional Transformer Network for Video Frame Synthesis.**<br>
*Zhouyong Liu, Shun Luo, Wubin Li, Jingben Lu, Yufan Wu, Chunguo Li, Luxi Yang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.10185)]

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

### Video Spatio-Temporal Consistency

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

## 3D-Aware Image Synthesis

**Exemplar-Based 3D Portrait Stylization.**<br>
*Fangzhou Han, Shuquan Ye, Mingming He, Menglei Chai, Jing Liao.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2104.14559)] [[Project](https://halfjoe.github.io/projs/3DPS/index.html)]

**Cross-Domain and Disentangled Face Manipulation with 3D Guidance.**<br>
*Can Wang, Menglei Chai, Mingming He, Dongdong Chen, Jing Liao.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2104.11228)]

**VariTex: Variational Neural Face Textures.**<br>
*Marcel C. Bühler, Abhimitra Meka, Gengyan Li, Thabo Beeler, Otmar Hilliges.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2104.05988)]

**CAMPARI: Camera-Aware Decomposed Generative Neural Radiance Fields.**<br>
*Michael Niemeyer, Andreas Geiger.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.17269)]

**DiscoFaceGAN: Disentangled and Controllable Face Image Generation via 3D Imitative-Contrastive Learning.**<br>
*Yu Deng, Jiaolong Yang, Dong Chen, Fang Wen, Xin Tong.*<br>
CVPR 2020. [[PDF](https://arxiv.org/pdf/2004.11660.pdf)] [[Github](https://github.com/microsoft/DiscoFaceGAN)] 

**Lifting 2D StyleGAN for 3D-Aware Face Generation.**<br>
*[Yichun Shi(https://seasonsh.github.io/), Divyansh Aggarwal, [Anil K. Jain](http://www.cse.msu.edu/~jain/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.13126)]

**Inverse Graphics GAN: Learning to Generate 3D Shapes from Unstructured 2D Data.**<br>
*Sebastian Lunz, Yingzhen Li, Andrew Fitzgibbon, Nate Kushman.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2002.12674)]

**Image GANs meet Differentiable Rendering for Inverse Graphics and Interpretable 3D Neural Rendering.**<br>
*Yuxuan Zhang, Wenzheng Chen, Huan Ling, Jun Gao, Yinan Zhang, Antonio Torralba, Sanja Fidler.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.09125)]

**pi-GAN: Periodic Implicit Generative Adversarial Networks for 3D-Aware Image Synthesis.**<br>
*[Eric R. Chan](https://ericryanchan.github.io/), [Marco Monteiro](https://marcoamonteiro.github.io/pi-GAN-website/), [Petr Kellnhofer](https://kellnhofer.xyz/), [Jiajun Wu](https://jiajunwu.com/), [Gordon Wetzstein](https://stanford.edu/~gordonwz/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.00926)] [[Project](https://marcoamonteiro.github.io/pi-GAN-website/)]

**RGBD-GAN: Unsupervised 3D Representation Learning From Natural Image Datasets via RGBD Image Synthesis.**<br>
*Atsuhiro Noguchi, Tatsuya Harada.*<br>
ICLR 2020. [[PDF](https://arxiv.org/abs/1909.12573)] [[Github](https://github.com/nogu-atsu/RGBD-GAN)]

**SIREN: Implicit Neural Representations with Periodic Activation Functions.**<br>
*[Vincent Sitzmann](https://vsitzmann.github.io/), [Julien N. P. Martel](http://www.jmartel.net/), [Alexander W. Bergman](http://alexanderbergman7.github.io/), [David B. Lindell](http://www.davidlindell.com/), [Gordon Wetzstein](https://stanford.edu/~gordonwz/).*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.09661)] [[Project](https://vsitzmann.github.io/siren/)] [[Github](https://github.com/vsitzmann/siren)]

**Towards Unsupervised Learning of Generative Models for 3D Controllable Image Synthesis.**<br>
*Yiyi Liao, Katja Schwarz, Lars Mescheder, Andreas Geiger.*<br>
CVPR 2020. [[PDF](https://avg.is.tuebingen.mpg.de/publications/liao2020cvpr)] [[Github](https://github.com/autonomousvision/controllable_image_synthesis)]

**GRAF: Generative Radiance Fields for 3D-Aware Image Synthesis.**<br>
*Katja Schwarz, Yiyi Liao, Michael Niemeyer, Andreas Geiger.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2007.02442)] [[Github](https://github.com/autonomousvision/graf)]

## 3D Shape Generation and Manipulation

**Scene-aware Generative Network for Human Motion Synthesis.**<br>
*Jingbo Wang, Sijie Yan, Bo Dai, Dahua Lin.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2105.14804)]

**KeypointDeformer: Unsupervised 3D Keypoint Discovery for Shape Control.**<br>
*Tomas Jakab, Richard Tucker, Ameesh Makadia, Jiajun Wu, Noah Snavely, Angjoo Kanazawa.*<br>
CVPR 2021 (oral). [[PDF](https://arxiv.org/abs/2104.11224)] [[Project](http://tomasjakab.github.io/KeypointDeformer)]

**Diffusion Probabilistic Models for 3D Point Cloud Generation.**<br>
*Shitong Luo, Wei Hu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/pdf/2103.01458.pdf)] [[Github](https://github.com/luost26/diffusion-point-cloud)]

**Deformed Implicit Field: Modeling 3D Shapes with Learned Dense Correspondence.**<br>
*Yu Deng, [Jiaolong Yang](https://jlyang.org/), [Xin Tong](https://www.microsoft.com/en-us/research/people/xtong/).*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2011.13650)] [[Github](https://github.com/microsoft/DIF-Net)]

**Learning to Infer Semantic Parameters for 3D Shape Editing.**<br>
*Fangyin Wei, Elena Sizikova, Avneesh Sud, Szymon Rusinkiewicz, Thomas Funkhouser.*<br>
3DV 2020. [[PDF](https://arxiv.org/abs/2011.04755)]

**3DSNet: Unsupervised Shape-to-Shape 3D Style Transfer.**<br>
*Mattia Segu, Margarita Grinvald, Roland Siegwart, Federico Tombari.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.13388)]

**ShapeFlow: Learnable Deformations Among 3D Shapes.**<br>
*[Chiyu "Max" Jiang](http://maxjiang.ml/), [Jingwei Huang](http://stanford.edu/~jingweih/), [Andrea Tagliasacchi](http://gfx.uvic.ca/people/ataiya/), [Leonidas Guibas](https://geometry.stanford.edu/member/guibas/).*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.07982)] [[Github](https://github.com/maxjiang93/ShapeFlow)]

## Diving Deep into Image Synthesis

### Generative Models

There are basicly two main types of generative models: likelihood based models, which include VAEs, flow based and autoregressive models; and implicit generative models such as Generative Adversarial Networks (GANs).

**Deep Generative Modelling: A Comparative Review of VAEs, GANs, Normalizing Flows, Energy-Based and Autoregressive Models.**<br> 
*Sam Bond-Taylor, Adam Leach, Yang Long, Chris G. Willcocks.*<br> 
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.04922)]

#### VAE

**Hierarchical VAEs Know What They Don’t Know.**<br> 
*Jakob Havtorn (Technical University of Denmark) · Jes Frellsen (Technical University of Denmark) · Søren Hauberg (Technical University of Denmark) · Lars Maaløe.*<br>
ICML 2021. [[PDF]()]

**Monte Carlo Variational Auto-Encoders.**<br> 
*Achille Thin, Nikita Kotelevskii, Arnaud Doucet, Alain Durmus, Eric Moulines, Maxim Panov.*<br>
ICML 2021. [[PDF]()]

**BasisDeVAE: Interpretable Simultaneous Dimensionality Reduction and Feature-Level Clustering with Derivative-Based Variational Autoencoders.**<br>
*Dominic Danks (Alan Turing Institute) · Christopher Yau.*<br>
ICML 2021. [[PDF]()]

**Autoencoding Under Normalization Constraints.**<br> 
*Sangwoong Yoon, Yung-Kyun Noh, Frank Chongwoo Park.*<br>
ICML 2021. [[PDF]()]

**Unified Robust Semi-Supervised Variational Autoencoder.**<br> 
*Xu Chen.*<br> 
ICML 2021. [[PDF]()]

**Ornstein-Uhlenbeck Smoothing for Hierarchical Variational Autoencoders.**<br> 
*Adeel Pervez, Efstratios Gavves.*<br>
ICML 2021. [[PDF]()]

**Lie Group VAE for Disentanglement Learning.**<br> 
*Xinqi Zhu, Chang Xu, Dacheng Tao.*<br>
ICML 2021. [[PDF]()]

**Autoencoder Image Interpolation by Shaping the Latent Space.**<br> 
*Alon Oring, Zohar Yakhini (Herzliya Interdisciplinary Center) · Yacov Hel-Or.*<br>
ICML 2021. [[PDF]()]

**Spatial Dependency Networks: Neural Layers for Improved Generative Image Modeling.**<br> 
*[Đorđe Miladinović](https://djordjemila.github.io/), [Aleksandar Stanić](https://astanic.github.io/), [Stefan Bauer](https://www.is.mpg.de/~sbauer), [Jürgen Schmidhuber](https://people.idsia.ch/~juergen/), [Joachim M. Buhmann](https://inf.ethz.ch/people/person-detail.buhmann.html).*<br> 
ICLR 2021. [[PDF](https://openreview.net/forum?id=I4c4K9vBNny)] [[Github](https://github.com/djordjemila/sdn)]

**Capturing Label Characteristics in VAEs.**<br>  
*Tom Joy, Sebastian Schmon, Philip Torr, Siddharth N, Tom Rainforth.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=wQRlSUZ5V7B)]

**Generalized Multimodal ELBO.**<br> 
*Thomas Marco Sutter, Imant Daunhawer, Julia E Vogt.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=5Y21V0RDBV)]

**Disentangled Recurrent Wasserstein Autoencoder.**<br>
*Jun Han, Martin Renqiang Min, Ligong Han, Xuan Zhang, Li Erran Li.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=O7ms4LFdsX)]

**Very Deep VAEs Generalize Autoregressive Models and Can Outperform Them on Images.**<br>
*Rewon Child.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=RLRXCV6DbEJ)]

**Taming Transformers for High-Resolution Image Synthesis.**<br>
*[Patrick Esser](https://github.com/pesser), [Robin Rombach](https://github.com/rromb), [Björn Ommer](https://hci.iwr.uni-heidelberg.de/Staff/bommer).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.09841)] [[Project](https://compvis.github.io/taming-transformers/)] [[Github](https://github.com/CompVis/taming-transformers)]

**Generating Diverse High-Fidelity Images with VQ-VAE-2.**<br>
*Ali Razavi, Aaron van den Oord, Oriol Vinyals.*<br>
NeurIPS 2019. [[PDF](https://arxiv.org/pdf/1906.00446v1.pdf)] [[Github](https://github.com/deepmind/sonnet)]

**VQ-VAE: Neural Discrete Representation Learning.**<br>
*[Aaron van den Oord](https://avdnoord.github.io/), Oriol Vinyals, Koray Kavukcuoglu.*<br>
NeurIPS 2017. [[PDF](https://avdnoord.github.io/homepage/slides/SANE2017.pdf)] [[Github](https://github.com/1Konny/VQ-VAE)]

**Exemplar VAE: Linking Generative Models, Nearest Neighbor Retrieval, and Data Augmentation.**<br>
*Sajad Norouzi, David J. Fleet, Mohammad Norouzi.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2004.04795)] [[Github](https://github.com/sajadn/Exemplar-VAE)]

**Soft-IntroVAE: Analyzing and Improving the Introspective Variational Autoencoder.**<br>
*Tal Daniel, Aviv Tamar.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.13253)] [[Project](https://taldatech.github.io/soft-intro-vae-web)]

**Private-Shared Disentangled Multimodal VAE for Learning of Hybrid Latent Representations.**<br>
*Mihee Lee, Vladimir Pavlovic.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.13024)]

**VDVAE: Very Deep VAEs Generalize Autoregressive Models and Can Outperform Them on Images.**<br>
*Anonymous authors.*<br>
ICLR 2021. [[PDF](https://openreview.net/forum?id=RLRXCV6DbEJ)] [[Github](https://github.com/openai/vdvae)]

**NCP-VAE: Variational Autoencoders with Noise Contrastive Priors.**<br>
*Jyoti Aneja, Alexander Schwing, Jan Kautz, Arash Vahdat.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.02917)]

**Swapping Autoencoder for Deep Image Manipulation.**<br>
*Taesung Park, Jun-Yan Zhu, Oliver Wang, Jingwan Lu, Eli Shechtman, Alexei Efros, Richard Zhang.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2007.00653)] [[PyTorch](https://github.com/taesungp/swapping-autoencoder-pytorch)] [[TensorFlow](https://github.com/zhangqianhui/Swapping-Autoencoder-tf)] 

**Learning Latent Representations Across Multiple Data Domains Using Lifelong VAEGAN.**<br> 
*Fei Ye, Adrian G. Bors.*<br> 
ECCV 2020. [[PDF](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650766.pdf)]

**NVAE: A Deep Hierarchical Variational Autoencoder.**<br>
*[Arash Vahdat](http://latentspace.cc/arash_vahdat/), [Jan Kautz](http://jankautz.com/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.03898)] [[Github](https://github.com/NVlabs/NVAE)]

**NestedVAE: Isolating Common Factors via Weak Supervision.**<br>
*Matthew J. Vowels, Necati Cihan Camgoz, Richard Bowden.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2002.11576)]

**ALAE: Adversarial Latent Autoencoders.**<br>
*[Stanislav Pidhorskyi](https://podgorskiy.com/), Donald A. Adjeroh, Gianfranco Doretto.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.04467)] [[Github](https://github.com/podgorskiy/ALAE)]

**Controllable Image Synthesis via SegVAE.**<br>
*Yen-Chi Cheng, Hsin-Ying Lee, Min Sun, Ming-Hsuan Yang.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.08397)] [[Project](https://yccyenchicheng.github.io/SegVAE/)] [[Github](https://github.com/yccyenchicheng/SegVAE)]

#### Frequency

**Fourier Features Let Networks Learn High Frequency Functions in Low Dimensional Domains.**<br>
*[Matthew Tancik](http://matthewtancik.com/), [Pratul P. Srinivasan](https://people.eecs.berkeley.edu/~pratul/), Ben Mildenhall, Sara Fridovich-Keil, Nithin Raghavan, Utkarsh Singhal, [Ravi Ramamoorthi](http://cseweb.ucsd.edu/~ravir/), [Jonathan T. Barron](https://jonbarron.info/), [Ren Ng](https://www2.eecs.berkeley.edu/Faculty/Homepages/yirenng.html).*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.10739)] [[Project](https://people.eecs.berkeley.edu/~bmild/fourfeat/)] [[Github](https://github.com/tancik/fourier-feature-networks)]

**Implicit Neural Representations with Periodic Activation Functions.**<br>
*[Vincent Sitzmann](https://vsitzmann.github.io), Julien N. P. Martel, Alexander W. Bergman, David B. Lindell, Gordon Wetzstein.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.09661)] [[Project](https://vsitzmann.github.io/siren/)] [[Github](https://github.com/vsitzmann/siren)]

**Learnable Fourier Features for Multi-DimensionalSpatial Positional Encoding.**<br>
*Yang Li, Si Si, Gang Li, Cho-Jui Hsieh, Samy Bengio.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2106.02795)]

**LPTN: High-Resolution Photorealistic Image Translation in Real-Time: A Laplacian Pyramid Translation Network.**<br>
*Jie Liang, Hui Zeng, Lei Zhang.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2105.09188)] [[Github](https://arxiv.org/pdf/2105.09188.pdf)]

**High-Fidelity and Arbitrary Face Editing.**<br>
*Yue Gao, Fangyun Wei, Jianmin Bao, Shuyang Gu, Dong Chen, Fang Wen, Zhouhui Lian.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.15814)]

**Frequency-aware Discriminative Feature Learning Supervised by Single-Center Loss for Face Forgery Detection.**<br>
*Jiaming Li, Hongtao Xie, Jiahong Li, Zhongyuan Wang, Yongdong Zhang.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.09096)]

**Fourier Space Losses for Efficient Perceptual Image Super-Resolution.**<br>
*Dario Fuoli, Luc Van Gool, Radu Timofte.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2106.00783)]

**Learning Frequency-aware Dynamic Network for Efficient Super-Resolution.**<br>
*Wenbin Xie, Dehua Song, Chang Xu, Chunjing Xu, Hui Zhang, Yunhe Wang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.08357)]

**Generating Images with Sparse Representations.**<br>
*Charlie Nash, Jacob Menick, Sander Dieleman, Peter W. Battaglia.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.03841)]

**Universal Adversarial Perturbations Through the Lens of Deep Steganography: Towards A Fourier Perspective.**<br>
*Chaoning Zhang, Philipp Benz, Adil Karjauv, In So Kweon.*<br>
AAAI 2021. [[PDF](https://arxiv.org/abs/2102.06479)]

**FcaNet: Frequency Channel Attention Networks.**<br>
*Zequn Qin, Pengyi Zhang, Fei Wu, Xi Li.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.11879)] [[Github](https://github.com/cfzd/FcaNet)]

**Fourier Features Let Networks Learn High Frequency Functions in Low Dimensional Domains.**<br>
*Matthew Tancik, Pratul P. Srinivasan, Ben Mildenhall, Sara Fridovich-Keil, Nithin Raghavan, Utkarsh Singhal, Ravi Ramamoorthi, Jonathan T. Barron, Ren Ng.*<br>
arxiv 2020. [[PDF]](https://arxiv.org/abs/2006.10739)] [[Project](https://people.eecs.berkeley.edu/~bmild/fourfeat/)] [[Github](https://github.com/tancik/fourier-feature-networks)]

**Focal Frequency Loss for Generative Models.**<br>
*Liming Jiang, Bo Dai, Wayne Wu, Chen Change Loy.*<br>
arxiv 2020. [[PDF]](https://arxiv.org/abs/2012.12821)] [[Github](https://github.com/EndlessSora/focal-frequency-loss)]

#### GAN Improvement

**Pareto GAN: Extending the Representational Power of GANs to Heavy-Tailed Distributions.**<br> 
*Todd Huster, Jeremy Cohen, Zinan Lin, Kevin Chan, Charles Kamhoua, Nandi O. Leslie, Cho-Yu Chiang, Vyas Sekar.*<br>
ICML 2021. [[PDF]()]

**WGAN with an Infinitely Wide Generator Has No Spurious Stationary Points.**<br> 
*Albert No (Hongik University) · TaeHo Yoon, Kwon Sehyun, Ernest Ryu.*<br>
ICML 2021. [[PDF]()]

**Functional Space Analysis of Local GAN Convergence.**<br> 
*Valentin Khrulkov (Skolkovo Institute Of Science And Technology) · Artem Babenko, Ivan Oseledets.*<br>
ICML 2021. [[PDF]()]

**Understanding Noise Injection in GANs.**<br> 
*Ruili Feng, Deli Zhao, Zheng-Jun Zha.*<br>
ICML 2021. [[PDF]()]

**Uncertainty Principles of Encoding GANs.**<br> 
*Ruili Feng, Zhouchen Lin, Jiapeng Zhu, Deli Zhao, Jingren Zhou, Zheng-Jun Zha.*<br> 
ICML 2021. [[PDF]()]

**Positional Encoding as Spatial Inductive Bias in GANs.**<br>
*Rui Xu, Xintao Wang, Kai Chen, Bolei Zhou, Chen Change Loy.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2012.05217)] [[Project](https://nbei.github.io/gan-pos-encoding.html)]

**Partition-Guided GANs.**<br> 
*Mohammadreza Armandpour, Ali Sadeghian, Chunyuan Li, Mingyuan Zhou.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2104.00816)]

**ContraD: Training GANs with Stronger Augmentations via Contrastive Discriminator.**<br> 
*[Jongheon Jeong](https://sites.google.com/view/jongheonj) and [Jinwoo Shin](http://alinlab.kaist.ac.kr/shin.html).*<br>
ICLR 2021. [[PDF](https://openreview.net/forum?id=eo6U4CAwVmg)] [[Github](https://github.com/jh-jeong/ContraD)]

**GAN-LTH: GANs Can Play Lottery Tickets Too.**<br> 
*Xuxi Chen, Zhenyu Zhang, Yongduo Sui, Tianlong Chen.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=1AoMhc_9jER)] [[Github](https://github.com/VITA-Group/GAN-LTH)]

**Distributional Sliced-Wasserstein and Applications to Generative Modeling.**<br>
*Khai Nguyen, Nhat Ho, Tung Pham, Hung Bui.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=QYjO70ACDK)]

**Ultra-Data-Efficient GAN Training: Drawing A Lottery Ticket First, Then Training It Toughly.**<br>
*Tianlong Chen, Yu Cheng, Zhe Gan, Jingjing Liu, Zhangyang Wang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.00397)] [[Github](https://github.com/VITA-Group/Ultra-Data-Efficient-GAN-Training)]

**Generating Images with Sparse Representations.**<br>
*Charlie Nash, Jacob Menick, Sander Dieleman, Peter W. Battaglia.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.03841)]

**Training Generative Adversarial Networks in One Stage.**<br>
*Chengchao Shen, Youtan Yin, Xinchao Wang, Xubin LI, Jie Song, Mingli Song.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.00430)]

**Dual Contradistinctive Generative Autoencoder.**<br>
*[Gaurav Parmar](https://gauravparmar.com/), Dacheng Li, Kwonjoon Lee, [Zhuowen Tu](https://pages.ucsd.edu/~ztu/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/pdf/2011.10063.pdf)]

**FastGAN: Towards Faster and Stabilized GAN Training for High-fidelity Few-shot Image Synthesis.**<br>
*Bingchen Liu, Yizhe Zhu, Kunpeng Song, Ahmed Elgammal.*<br>
ICLR 2021. [[PDF](https://arxiv.org/abs/2101.04775)] [[Github](https://github.com/lucidrains/lightweight-gan)] [[Data](https://github.com/odegeasslbc/FastGAN-pytorch)]

**Focal Frequency Loss for Generative Models.**<br>
*[Liming Jiang](https://liming-jiang.com/), [Bo Dai](http://daibo.info/), [Wayne Wu](https://wywu.github.io/), [Chen Change Loy](http://personal.ie.cuhk.edu.hk/~ccloy/).*<br>
arXiv 2020. [[PDF](https://arxiv.org/abs/2012.12821)] [[Github](https://github.com/EndlessSora/focal-frequency-loss)]

**SariGAN: Learning Semantic-aware Normalization for Generative Adversarial Networks.**<br>
*Heliang Zheng1, Jianlong Fu, Yanhong Zeng, Jiebo Luo, Zheng-Jun Zha.*<br>
NeurIPS 2020. [[PDF](https://proceedings.neurips.cc/paper/2020/file/f885a14eaf260d7d9f93c750e1174228-Paper.pdf)] [[Github](https://github.com/researchmm/SariGAN)]

**MODNet: Is a Green Screen Really Necessary for Real-Time Portrait Matting?**<br>
*Zhanghan Ke, Kaican Li, Yurou Zhou, Qiuhua Wu, Xiangyu Mao, Qiong Yan, Rynson W.H. Lau.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.11961)] [[Github](https://github.com/ZHKKKe/MODNet)]

**Score-Based Generative Modeling through Stochastic Differential Equations.**<br>
*Yang Song, Jascha Sohl-Dickstein, Diederik P. Kingma, Abhishek Kumar, Stefano Ermon, Ben Poole.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.13456)]

**CIPS: Image Generators with Conditionally-Independent Pixel Synthesis.**<br>
*Ivan Anokhin, Kirill Demochkin, Taras Khakhulin, Gleb Sterkin, Victor Lempitsky, Denis Korzhenkov.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.13775)] [[Github](https://github.com/saic-mdal/CIPS)]

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

**Self Normalizing Flows.**<br>
*T. Anderson Keller, [Jorn W.T. Peters](http://jornpeters.nl/), [Priyank Jaini](https://cs.uwaterloo.ca/~pjaini/home/), Emiel Hoogeboom, Patrick Forré, [Max Welling](https://staff.fnwi.uva.nl/m.welling/).*<br>
Beyond Backpropagation workshop at NeurIPS 2020. [[PDF](https://arxiv.org/abs/2011.07248)] [[Github](https://github.com/akandykeller/SelfNormalizingFlows)]

**Self-Gradient Networks.**<br>
*Hossein Aboutalebi, Mohammad Javad Shafiee Alexander Wong.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.09364)]

**COCO-GAN: Generation by Parts via Conditional Coordinating.**<br>
*[Chieh Hubert Lin](https://hubert0527.github.io/), [Chia-Che Chang](https://chang810249.github.io/), [Yu-Sheng Chen](https://www.cmlab.csie.ntu.edu.tw/~nothinglo/), [Da-Cheng Juan](https://ai.google/research/people/DaChengJuan), [Wei Wei](https://ai.google/research/people/105672), [Hwann-Tzong Chen](https://htchen.github.io/).*<br> 
ICCV 2019. [[PDF](https://arxiv.org/abs/1904.00284)] [[Project](https://hubert0527.github.io/COCO-GAN/)] [[Code (TensorFlow)](https://github.com/hubert0527/COCO-GAN)] [[Code (PyTorch)](https://github.com/NeverGiveU/CoCoGAN_pytorch_master)]

#### Invertible Neural Network (Flow-based Generative Model)

[[Normalizing Flows](https://paperswithcode.com/method/normalizing-flows)]

**Generative Flows with Invertible Attentions.**<br> 
*Rhea Sanjay Sukthanker, Zhiwu Huang, Suryansh Kumar, Radu Timofte, Luc Van Gool.*<br> 
arxiv 2021. [[PDF](https://arxiv.org/abs/2106.03959)]

**Self Normalizing Flows.**<br> 
*Thomas Keller, Jorn Peters, Priyank Jaini, Emiel Hoogeboom, Patrick Forré, Max Welling.*<br>
ICML 2021. [[PDF]()]

**Neural Parts: Learning Expressive 3D Shape Abstractions with Invertible Neural Networks.**<br>
*[Despoina Paschalidou](https://paschalidoud.github.io/), [Angelos Katharopoulos](https://angeloskath.github.io/), [Andreas Geiger](http://cvlibs.net/), [Sanja Fidler](https://www.cs.utoronto.ca/~fidler/).*<br>
CVPR 2021. [[PDF](https://arxiv.org/pdf/2103.10429.pdf)] [[Github](https://github.com/paschalidoud/neural_parts)] [[Project](https://paschalidoud.github.io/neural_parts)]

**iFlowGAN: An Invertible Flow-based Generative Adversarial Network For Unsupervised Image-to-Image Translation.**<br>
*Longquan Dai, Jinhui Tang.*<br>
TPAMI 2021. [[PDF](https://www.computer.org/csdl/journal/tp/5555/01/09367012/1rDQXw8mKnC)]

**Implicit Normalizing Flows.**<br>
*Cheng Lu, Jianfei Chen, Chongxuan Li, Qiuhao Wang, Jun Zhu.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=8PS8m9oYtNy)]

**Network-to-Network Translation with Conditional Invertible Neural Networks.**<br>
*[Robin Rombach](https://github.com/rromb), [Patrick Esser](https://github.com/pesser), [Björn Ommer](https://hci.iwr.uni-heidelberg.de/Staff/bommer).*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2005.13580)] [[Github](https://github.com/CompVis/net2net)] [[Project](https://compvis.github.io/net2net/)]

**Making Sense of CNNs: Interpreting Deep Representations & Their Invariances with Invertible Neural Networks.**<br>
*[Robin Rombach](https://github.com/rromb), [Patrick Esser](https://github.com/pesser), [Björn Ommer](https://hci.iwr.uni-heidelberg.de/Staff/bommer).*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.01777)] [[Project](https://compvis.github.io/invariances/)] [[Github](https://compvis.github.io/invariances/)]

**Flow-based Generative Models for Learning Manifold to Manifold Mappings.**<br>
*Xingjian Zhen, Rudrasis Chakraborty, Liu Yang, Vikas Singh.*<br>
AAAI 2021. [[PDF](https://arxiv.org/abs/2012.10013)]

**Full-Glow: Fully conditional Glow for more realistic image generation.**<br>
*Moein Sorkhei, Gustav Eje Henter, Hedvig Kjellström.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.05846)]

**Decoupling Global and Local Representations via Invertible Generative Flows.**<br>
*Anonymous.*<br>
ICLR 2021 Submission. [[PDF](https://openreview.net/forum?id=iWLByfvUhN)]

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
arxiv 2019. [[PDF](https://arxiv.org/abs/1907.02392)] [[Github](https://github.com/VLL-HD/conditional_invertible_neural_networks)] [[Supplement](https://drive.google.com/file/d/1_OoiIGhLeVJGaZFeBt0OWOq8ZCtiI7li)]

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

**Few-shot Image Generation via Cross-domain Correspondence.**<br>
*[Utkarsh Ojha](https://utkarshojha.github.io/), [Yijun Li](https://yijunmaverick.github.io/), [Jingwan Lu](https://research.adobe.com/person/jingwan-lu/), [Alexei A. Efros](https://people.eecs.berkeley.edu/~efros/), [Yong Jae Lee](https://web.cs.ucdavis.edu/~yjlee/), [Eli Shechtman](https://research.adobe.com/person/eli-shechtman/), [Richard Zhang](https://richzhang.github.io/).*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.06820)] [[Project](https://utkarshojha.github.io/few-shot-gan-adaptation/)] [[Github](https://github.com/utkarshojha/few-shot-gan-adaptation)]

**StyleMapGAN: Exploiting Spatial Dimensions of Latent in GAN for Real-time Image Editing.**<br>
*Hyunsu Kim, Yunjey Choi, Junho Kim, Sungjoo Yoo, Youngjung Uh.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.14754)] [[Github](https://github.com/naver-ai/StyleMapGAN)]

**Style-based Point Generator with Adversarial Rendering for Point Cloud Completion.**<br>
*Chulin Xie, Chuxin Wang, Bo Zhang, Hao Yang, Dong Chen, Fang Wen.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.02535)]

**AniGAN: Style-Guided Generative Adversarial Networks for Unsupervised Anime Face Generation.**<br>
*Bing Li, Yuanlue Zhu, Yitong Wang, Chia-Wen Lin, Bernard Ghanem, Linlin Shen.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.12593)]

**SWAGAN: A Style-based Wavelet-driven Generative Model.**<br>
*Rinon Gal, Dana Cohen, Amit Bermano, Daniel Cohen-Or.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2102.06108)]

**INR: Adversarial Generation of Continuous Images.**<br>
*Ivan Skorokhodov, Savva Ignatyev, Mohamed Elhoseiny.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2011.12026)] [[Github](https://github.com/universome/inr-gan)]

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

**Systematic Analysis and Removal of Circular Artifacts for StyleGAN.**<br>
*Way Tan, Bihan Wen, Xulei Yang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.01090)]

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

### Diffusion Probabilistic Models

**Cascaded Diffusion Models for High Fidelity Image Generation.**<br>
*Jonathan Ho, Chitwan Saharia, William Chan, David J. Fleet, Mohammad Norouzi, Tim Salimans.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2106.15282)]

**Diffusion Models Beat GANs on Image Synthesis.**<br>
*[Prafulla Dhariwal](https://prafulladhariwal.com/), Alex Nichol.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2105.05233)] [[Github](https://github.com/openai/guided-diffusion)]

**Improved Denoising Diffusion Probabilistic Models.**<br>
*Alex Nichol, Prafulla Dhariwal.*<br>
ICLM 2021. [[PDF](https://arxiv.org/abs/2102.09672)] [[Github](https://github.com/openai/improved-diffusion)]

**DDPM: Denoising Diffusion Probabilistic Models.**<br>
*[Jonathan Ho](http://www.jonathanho.me/), [Ajay Jain](https://www.ajayjain.net/), [Pieter Abbeel](https://people.eecs.berkeley.edu/~pabbeel/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.11239)] [[Project](https://hojonathanho.github.io/diffusion)] [[Github](https://github.com/hojonathanho/diffusion)]

**DDIM: Denoising Diffusion Implicit Models.**<br>
*Jiaming Song, Chenlin Meng, Stefano Ermon.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.02502)] [[Github](https://github.com/ermongroup/ddim)]

### misc

**DatasetGAN: Efficient Labeled Data Factory with Minimal Human Effort.**<br>
*[Yuxuan Zhang](https://www.alexyuxuanzhang.com/), [Huan Ling](http://www.cs.toronto.edu/~linghuan/), [Jun Gao](http://www.cs.toronto.edu/~jungao/), [Kangxue Yin](https://kangxue.org/), [Jean-Francois Lafleche](), [Adela Barriuso](), [Antonio Torralba](https://groups.csail.mit.edu/vision/torralbalab/), [Sanja Fidler](http://www.cs.utoronto.ca/~fidler/).*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.06490)] [[Github](https://github.com/nv-tlabs/datasetGAN_release)] [[Project](https://nv-tlabs.github.io/datasetGAN/)]

**Exploiting Relationship for Complex-scene Image Generation.**<br>
*Tianyu Hua, Hongdong Zheng, Yalong Bai, Wei Zhang, Xiao-Ping Zhang, Tao Mei.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2104.00356)]

**TrajeVAE: Controllable Human Motion Generation from Trajectories.**<br>
*Kacper Kania, Marek Kowalski, Tomasz Trzciński.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2104.00351)]

**Generative Max-Mahalanobis Classifiers for Image Classification, Generation and More.**<br>
*Xiulong Yang, Hui Ye, Yang Ye, Xiang Li, Shihao Ji.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.00122)]

**End-to-End Chinese Landscape Painting Creation Using Generative Adversarial Networks.**<br>
*Alice Xue.*<br>
WACV 2021. [[PDF](https://arxiv.org/abs/2011.05552)] [[Chinese-Landscape-Painting-Dataset](https://github.com/alicex2020/Chinese-Landscape-Painting-Dataset)]

**OASIS: You Only Need Adversarial Supervision for Semantic Image Synthesis.**<br>
*Vadim Sushko, Edgar Schönfeld, Dan Zhang, Juergen Gall, Bernt Schiele, Anna Khoreva.*<br>
ICLR 2021. [[PDF](https://arxiv.org/abs/2012.04781)] [[Github](https://github.com/boschresearch/OASIS)]

**Semantic Image Synthesis via Efficient Class-Adaptive Normalization.**<br>
*Zhentao Tan, Dongdong Chen, Qi Chu, Menglei Chai, Jing Liao, Mingming He, Lu Yuan, Gang Hua, Nenghai Yu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.04644)] [[Github](https://github.com/tzt101/CLADE.git)]

**Spectral Distribution aware Image Generation.**<br>
*Steffen Jung, Margret Keuper.*<br>
AAAI 2021. [[PDF](https://arxiv.org/abs/2012.03110)]

**Creative Sketch Generation.**<br>
*Songwei Ge, Vedanuj Goswami, C. Lawrence Zitnick, Devi Parikh.*<br>
ICLR 2021. [[PDF](https://arxiv.org/abs/2011.10039)] [[Github](https://github.com/facebookresearch/DoodlerGAN)] [[Project](http://doodlergan.cloudcv.org/)]

**CircleGAN: Generative Adversarial Learning across Spherical Circles.**<br>
*Woohyeon Shim, Minsu Cho.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.12486)]

**HistoGAN: Controlling Colors of GAN-Generated and Real Images via Color Histograms.**<br>
*[Mahmoud Afifi](https://sites.google.com/view/mafifi), Marcus A. Brubaker, Michael S. Brown.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.11731)] [[Github](https://github.com/mahmoudnafifi/HistoGAN)] [[4K Landscape](https://ln2.sync.com/dl/1891becc0/uhsxtprq-33wfwmyq-dhhqeb3s-mtstuqw7/view/default/11118541390008)]

**Generative Adversarial Stacked Autoencoders.**<br>
*Ariel Ruiz-Garcia, Ibrahim Almakky, Vasile Palade, Luke Hicks.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.12236)]

**CEN: Deep Multimodal Fusion by Channel Exchanging.**<br>
*Yikai Wang, Wenbing Huang, Fuchun Sun, Tingyang Xu, Yu Rong, Junzhou Huang.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2011.05005)] [[Github](https://github.com/yikaiw/CEN)]

**Few-shot Image Generation with Elastic Weight Consolidation.**<br>
*Yijun Li, Richard Zhang, Jingwan (Cynthia) Lu, Eli Shechtman.*<br>
NeurIPS 2020. [[PDF](https://papers.nips.cc/paper/2020/hash/b6d767d2f8ed5d21a44b0e5886680cb9-Abstract.html)] [[Project](https://yijunmaverick.github.io/publications/ewc/)]

**Neural FFTs for Universal Texture Image Synthesis.**<br>
*Morteza Mardani, Guilin Liu, Aysegul Dundar, Shiqiu Liu, Andrew Tao, Bryan Catanzaro.*<br>
NeurIPS 2020. [[PDF](https://papers.nips.cc/paper/2020/hash/a23156abfd4a114c35b930b836064e8b-Abstract.html)]

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

**A Lip Sync Expert Is All You Need for Speech to Lip Generation In The Wild.**<br>
*K R Prajwal, Rudrabha Mukhopadhyay, Vinay Namboodiri, C V Jawahar.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2008.10010)] [[Github](http://github.com/Rudrabha/Wav2Lip)] [[Project](https://bhaasha.iiit.ac.in/lipsync/)] [[Demo](http://bhaasha.iiit.ac.in/lipsync)]

**SketchPatch: Sketch Stylization via Seamless Patch-level Synthesis.**<br>
*Noa Fish, Lilach Perry, Amit Bermano, Daniel Cohen-Or.*<br>
SIGGRAPH Asia 2020. [[PDF](https://arxiv.org/abs/2009.02216)]

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
IJCV 2020. [[PDF](https://arxiv.org/abs/1911.09267)] [[Project](https://genforce.github.io/higan)] [[Github](https://github.com/genforce/higan)]

**F2GAN: Fusing-and-Filling GAN for Few-shot Image Generation.**<br>
*Yan Hong, Li Niu, Jianfu Zhang, Weijie Zhao, Chen Fu, Liqing Zhang.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2008.01999)]

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
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.09661)] [[Project](https://vsitzmann.github.io/siren/)] [[Github](https://github.com/vsitzmann/siren)]

**Rethinking Semi-Supervised Learning in VAEs.**<br>
*Tom Joy, Sebastian M. Schmon, Philip H. S. Torr, N. Siddharth, Tom Rainforth.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.10102)] [[Github](https://github.com/thwjoy/revae-demo)]

**Fourier Features Let Networks Learn High Frequency Functions in Low Dimensional Domains.**<br>
*[Matthew Tancik](http://matthewtancik.com/), [Pratul P. Srinivasan](https://people.eecs.berkeley.edu/~pratul/), Ben Mildenhall, Sara Fridovich-Keil, Nithin Raghavan, Utkarsh Singhal, [Ravi Ramamoorthi](http://cseweb.ucsd.edu/~ravir/), [Jonathan T. Barron](https://jonbarron.info/), [Ren Ng](https://www2.eecs.berkeley.edu/Faculty/Homepages/yirenng.html).*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.10739)] [[Project](https://people.eecs.berkeley.edu/~bmild/fourfeat/)] [[Github](https://github.com/tancik/fourier-feature-networks)]

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

## 2D to 3D Convertion

**Solid Texture Synthesis using Generative Adversarial Networks.**<br>
*Xin Zhao, Lin Wang, Jifeng Guo, Bo Yang, Junteng Zheng, Fanqi Li.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.03973)]

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

**Sketch2Model: View-Aware 3D Modeling from Single Free-Hand Sketches.**<br>
*Song-Hai Zhang, Yuan-Chen Guo, Qing-Wen Gu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2105.06663)]

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

**Adversarial Open Domain Adaption for Sketch-to-Photo Synthesis.**<br>
*Xiaoyu Xiang, Ding Liu, Xiao Yang, Yiheng Zhu, Xiaohui Shen, Jan P. Allebach.*<br>
arxiv 2021. [[PDF](https://arxiv.org/pdf/2104.05703v1.pdf)] [[AODA](https://github.com/Mukosame/AODA)] [[Anime2Sketch](https://github.com/Mukosame/Anime2Sketch)]

**Sketch2Mesh: Reconstructing and Editing 3D Shapes from Sketches.**<br>
*Benoit Guillard, Edoardo Remelli, Pierre Yvernay, Pascal Fua.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2104.00482)]

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
ACM MM 2019. [[PDF](https://arxiv.org/abs/1910.08914)]

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