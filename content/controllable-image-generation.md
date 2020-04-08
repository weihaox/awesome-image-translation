# Controllable Image Generation

This repository is about *Controllable Image Generation* or *intelligent image manipulation*, which is a collection of papers on image generation and manipulation with the guidance by text, audio, camera pose or other information. 

## Table of Contents
- [Guided Image-to-image translation](#guided-image-to-image-translation)
- [Image-Based Virtual Try-On](#image-based-virtual-try-on)
- [Attribute Editing and Makeup Transfer](#attribute-editing)
- [Texture Mapping & Surface Mapping](#texture-mapping---surface-mapping)
- [2D to 3D](#2d-to-3d)
- [Novel-View Synthesis](#novel-view-synthesis)
- [Motion Transfer, Retargeting, Reenactment, Dubbing, nimation](#motion-transfer---retargeting---reenactment---dubbing---animation)
- [3D Pose Transfer](#3d-pose-transfer)
- [Multi-Modality Translation](#multi-modality-translation)
	* [Voice-to-Voice](#voice-to-voice)
	* [Text-to-Image](#text-to-image)
	* [Voice-to-Image](#voice-to-image)
	* [speech-to-Text](#speech-to-text)
	* [Text-to-speech](#text-to-speech)
- [Gaze Estimation, Tracking, Redirection, Correction and Blink Detection](#gaze-estimation--tracking--redirection--correction-and-blink-detection)
  * [Gaze Dataset](#gaze-dataset)
  * [Gaze Redirection and Correction](#gaze-redirection-and-correction)
  * [Gaze Estimation](#gaze-estimation)
  * [Eye Tracking](#eye-tracking)

## Guided Image-to-image translation

Part of this repository is about *Guided Image-to-image translation* which can be found [here](https://github.com/xiaweihao/awesome-image-translation/blob/master/README_.md#guided-image-to-image-translation).

## Image-Based Virtual Try-On
*Image-Based Virtual Try-On* can be found [here](https://github.com/xiaweihao/awesome-image-translation/blob/master/clothed-human.md##image-based-virtual-try-on).

## Attribute Editing and Makeup Transfer

*Attribute Editing and Makeup Transfer* can be found [here](https://github.com/xiaweihao/awesome-image-translation/blob/master/README_.md##attribute-editing).

## Texture Mapping & Surface Mapping

**Articulation-aware Canonical Surface Mapping.**<br>
*Nilesh Kulkarni, Abhinav Gupta, David F. Fouhey, Shubham Tulsiani.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.00614)] [[Github](https://github.com/nileshkulkarni/acsm/)] [[Project](https://nileshkulkarni.github.io/acsm/)]

**UnrealText: Synthesizing Realistic Scene Text Images from the Unreal World.**<br>
*Shangbang Long, Cong Yao.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.10608)] [[Github](https://github.com/Jyouhou/UnrealText)]

**Adversarial Texture Optimization from RGB-D Scans.**<br>
*[Jingwei Huang](http://stanford.edu/~jingweih/), [Justus Thies](http://abhijitkundu.info/), [Angela Dai](https://www.3dunderstanding.org/), [Abhijit Kundu](https://justusthies.github.io/), [Chiyu Jiang](https://www.maxjiang.ml/), [Leonidas Guibas](https://geometry.stanford.edu/member/guibas/), [Matthias Nießner](http://www.niessnerlab.org/), [Thomas Funkhouser](https://www.cs.princeton.edu/~funk/).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.08400)] [[Project](http://stanford.edu/~jingweih/papers/advtex/)] [[Github](https://github.com/hjwdzh/AdversarialTexture)] [[pyRender](https://github.com/hjwdzh/pyRender)]

**CSM: Canonical Surface Mapping via Geometric Cycle Consistency.**<br>
*Nilesh Kulkarni, Abhinav Gupta, Shubham Tulsiani.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1907.10043)] [[Github](https://nileshkulkarni.github.io/csm/)] [[Project](https://nileshkulkarni.github.io/csm/)]

**Texture Mapping for 3D Reconstruction with RGB-D Sensor.**<br>
*Yanping Fu, [Qingan Yan](https://yanqingan.github.io/), Long Yang, Jie Liao, [Chunxia Xiao](http://graphvision.whu.edu.cn/).*<br>
CVPR 2018. [[PDF](https://yanqingan.github.io/docs/cvpr18_texture.pdf)] [[thecvf](http://openaccess.thecvf.com/content_cvpr_2018/papers/Fu_Texture_Mapping_for_CVPR_2018_paper.pdf)] [[Code on Github](https://github.com/fdp0525/G2LTex)]

**Let There Be Color! - Large-Scale Texturing of 3D Reconstructions.**<br>
*Waechter, Michael and Moehrle, Nils and Goesele, Michael.*<br>
ECCV 2018. [[PDF](https://www.gcc.tu-darmstadt.de/media/gcc/papers/Waechter-2014-LTB.pdf)] [[Project](http://www.gcc.tu-darmstadt.de/home/proj/texrecon/)] [[Github](https://github.com/nmoehrle/mvs-texturing)] [[rayint](https://github.com/nmoehrle/rayint)] [[Eigen](http://eigen.tuxfamily.org)] [[Multi-View Environment](http://www.gcc.tu-darmstadt.de/home/proj/mve)] [[mapMAP](http://www.gcc.tu-darmstadt.de/home/proj/mapmap)]

**Learning Category-Specific Mesh Reconstruction from Image Collections.**<br>
*Angjoo Kanazawa, Shubham Tulsiani Alexei A. Efros, Jitendra Malik.*<br>
ECCV 2018. [[Github](akanazawa.github.io/cmr/)] [[Project](https://github.com/akanazawa/cmr)]
 
**Texture Fields: Learning Texture Representations in Function Space.**<br>
*Michael Oechsle, Lars Mescheder, Michael Niemeyer, Thilo Strauss, Andreas Geiger.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1905.07259)]

**AtlasNet: A Papier-Mache Approach to Learning 3D Surface Generation.**<br>
*Thibault Groueix, Matthew Fisher, Vladimir Kim, Bryan Russell, Mathieu Aubry.*<br>
CVPR 2018. [[PDF](https://hal.inria.fr/hal-01718933/file/1802.05384.pdf)] [[Project](http://imagine.enpc.fr/~groueixt/atlasnet/)] [[Github](https://github.com/ThibaultGROUEIX/AtlasNet)]

**Learning Elementary Structures For 3D Shape Generation And Matching.**<br>
*Theo Deprelle, Thibault Groueix, Matthew Fisher, Vladimir G. Kim, Bryan C. Russell, Mathieu Aubry.*<br>
arxiv, 2019. [[PDF](https://arxiv.org/abs/1908.04725)]
[[Project](http://imagine.enpc.fr/~deprellt/atlasnet2/)]
[[Github](https://github.com/TheoDEPRELLE/AtlasNetV2)]

**Learning to Generate Textures on Meshes.**<br>
*Amit Raj, [Cusuh Ham](https://cusuh.github.io/), Connelly Barnes, Vladimir Kim, Jingwan Lu, James Hays.*<br>
CVPR [Deep Generative Models for 3D Understanding 2019](https://sites.google.com/view/3d-widget/) (Best Paper). [[PDF](http://openaccess.thecvf.com/content_cvprw_20/papers/3D-WidDGET/Amit_Raj_Learning_to_Generate_Textures_on_3D_Meshes_CVPRW_2019_paper.pdf)]

**Unsupervised Texture Transfer from Images to Model Collections.**<br>
*[Tuanfeng Yand Wang](http://geometry.cs.ucl.ac.uk/tuanfeng/), [Hao Su](http://ai.ucsd.edu/~haosu/), Qixing Huang, Jingwei Huang, Leonidas J. Guibas, [Niloy J. Mitra](http://www0.cs.ucl.ac.uk/staff/n.mitra/index.html).*<br>
SIGGRAPH Asia 2016. [[PDF](http://ai.ucsd.edu/~haosu/papers/siga16.texture_transfer_small.pdf)]
[[Project](http://geometry.cs.ucl.ac.uk/projects/2016/texture_transfer/)]
[[Data](http://geometry.cs.ucl.ac.uk/tuanfeng/texturetransfer/texture_transfer_code_and_data.zip)]

## 2D to 3D

**3D-CariGAN: An End-to-End Solution to 3D Caricature Generation from Face Photos.**<br>
*Zipeng Ye, Ran Yi, Minjing Yu, Juyong Zhang, Yu-Kun Lai, Yong-jin Liu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2003.06841)]

**Robust Flow-Guided Neural Prediction for Sketch-Based Freeform Surface Modeling.**<br>
*Changjian Li, Hao Pan, Yang Liu, Xin Tong, Alla Sheffer, Wenping Wang.*<br>
SIGGRAPH Asia 2018.
[[Project](http://haopan.github.io/sketchCNN.html)]  [[PDF](https://enigma-li.github.io/projects/sketchcnn/SketchCNN_SIGA_2018.pdf)]  [[Code,Data - GitHub](https://github.com/Enigma-li/SketchCNN/)]

**BendSketch: Modeling Freeform Surfaces Through 2D Sketching.**<br>
*[Changjian Li](https://enigma-li.github.io/), Hao Pan, Yang Liu, Xin Tong, Alla Sheffer, Wenping Wang.*<br>
SIGGRAPH 2017. [[Project](http://haopan.github.io/bendsketch.html)] [[PDF](https://enigma-li.github.io/projects/bendsketching/bendsketch.pdf)]

**Self-Supervised 2D Image to 3D Shape Translation with Disentangled Representations.**<br>
*Berk Kaya, Radu Timofte.*<br>
arxiv 2020. [[PDF](https://arxiv.org/pdf/2003.10016)]

**Deep 3D-Zoom Net: Unsupervised Learning of Photo-Realistic 3D-Zoom.**<br>
*Juan Luis Gonzalez Bello, Munchurl Kim.*<br>
ICLR 2020. [[PDF](https://arxiv.org/abs/1909.09349)] [[Video](https://www.youtube.com/watch?v=Gz76VYwUzZ8)]

**SynSin: End-to-end View Synthesis from a Single Image.**<br>
*Olivia Wiles, Georgia Gkioxari, Richard Szeliski, Justin Johnson.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.08804)] [[Github](http://www.robots.ox.ac.uk/~ow/synsin.html)]

**NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis.**<br>
*Ben Mildenhall, Pratul P. Srinivasan, Matthew Tancik, Jonathan T. Barron, Ravi Ramamoorthi, Ren Ng.*<br>
arxiv, 19 Mar 2020. [[PDF](https://arxiv.org/abs/2003.08934)] [[Project](http://tancik.com/nerf)] [[Gtihub](https://github.com/bmild/nerf)]

**View Independent Generative Adversarial Network for Novel View Synthesis.**<br>
*Xiaogang Xu, Ying-Cong Chen, Jiaya Jia.*<br>
ICCV 2019. [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_View_Independent_Generative_Adversarial_Network_for_Novel_View_Synthesis_ICCV_2019_paper.pdf)]

## Novel-View Synthesis
[Novel-View Synthesis](https://paperswithcode.com/task/novel-view-synthesis/codeless)

**GPU-Accelerated Mobile Multi-view Style Transfer.**<br>
*Puneet Kohli, Saravana Gunaseelan, Jason Orozco, Yiwen Hua, Edward Li, Nicolas Dahlquist.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2003.00706v1)]

**IGNOR: Image-guided Neural Object Rendering.**<br>
*Justus Thies, Michael Zollhöfer, Christian Theobalt, Marc Stamminger, [Matthias Nießner](http://niessnerlab.org/publications.html).*<br>
ICLR 2020. arxiv, 26 Nov 2018 (15 Jan 2020). [[PDF](https://arxiv.org/abs/1811.10720)] [[Project](http://niessnerlab.org/projects/thies2020ignor.html)]

**Monocular Neural Image Based Rendering with Continuous View Control.**<br>
*[Xu Chen](https://ait.ethz.ch/people/xu/), [Jie Song](https://ait.ethz.ch/people/song/), Otmar Hilliges.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1901.01880)]

**Extreme View Synthesis.**<br>
*Inchang Choi, Orazio Gallo, Alejandro Troccoli, Min H. Kim, Jan Kautz.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1812.04777)]

**Transformable Bottleneck Networks.**<br>
*Kyle Olszewski, Sergey Tulyakov, Oliver Woodford, Hao Li, Linjie Luo.*<br>
ICCV 2019. [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Olszewski_Transformable_Bottleneck_Networks_ICCV_2019_paper.pdf)]

**View Independent Generative Adversarial Network for Novel View Synthesis.**<br>
*Xiaogang Xu, Ying-Cong Chen, Jiaya Jia.*<br>
ICCV 2019. [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_View_Independent_Generative_Adversarial_Network_for_Novel_View_Synthesis_ICCV_2019_paper.pdf)]

**DNR: A Neural Rendering Framework for Free-Viewpoint Relighting.**<br>
*Zhang Chen, Anpei Chen, Guli Zhang, Chengyuan Wang, Yu Ji, Kiriakos N. Kutulakos, Jingyi Yu.*<br>
arxiv, 26 Nov 2019. [[PDF](https://arxiv.org/pdf/1911.11530v1.pdf)]

## Motion Transfer & Retargeting & Reenactment & Dubbing & Animation

[[awesome-human-motion](https://github.com/derikon/awesome-human-motion)]

**StyleRig: Rigging StyleGAN for 3D Control over Portrait Images.**<br>
*A. Tewari, M. Elgharib, G. Bharaj, F. Bernard, H-P. Seidel, P. Perez, M. Zollhöfer, C.Theobalt.*<br>
CVPR 2020. [[PDF](http://gvv.mpi-inf.mpg.de/projects/StyleRig/data/paper.pdf)] [[Project](http://gvv.mpi-inf.mpg.de/projects/StyleRig/)]

**TransMoMo: Invariance-Driven Unsupervised Video Motion Retargeting.**<br>
*Zhuoqian Yang, Wentao Zhu, Wayne Wu, Chen Qian, Qiang Zhou, Bolei Zhou, Chen Change Loy.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.14401)] [[Github](https://github.com/yzhq97/transmomo.pytorch)] [[Project](https://yzhq97.github.io/transmomo)]

**Human Motion Transfer from Poses in the Wild.**<br>
*Jian Ren, Menglei Chai, Sergey Tulyakov, Chen Fang, Xiaohui Shen, Jianchao Yang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.03142)]

**First Order Motion Model for Image Animation.**<br>
*[Aliaksandr Siarohin](https://aliaksandrsiarohin.github.io/), [Stéphane Lathuilière](http://stelat.eu/), [Sergey Tulyakov](http://stulyakov.com/), [Elisa Ricci](http://elisaricci.eu/), [Nicu Sebe](http://disi.unitn.it/~sebe/).*<br>
NeurIPS 2019. [[PDF](http://papers.nips.cc/paper/8935-first-order-motion-model-for-image-animation)] [[Project](https://aliaksandrsiarohin.github.io/first-order-model-website)] [[Github](https://github.com/AliaksandrSiarohin/first-order-model)]

**Neural Human Video Rendering: Joint Learning of Dynamic Textures and Rendering-to-Video Translation.**<br>
*Lingjie Liu, Weipeng Xu, Marc Habermann, Michael Zollhoefer, Florian Bernard, Hyeongwoo Kim, Wenping Wang, Christian Theobalt.*<br>
arxiv, 14 Jan 2020. [[PDF](https://arxiv.org/abs/2001.04947)]

**Deferred Neural Rendering: Image Synthesis using Neural.**<br>
*Justus Thies, Michael Zollhöfer, Matthias Nießner.*<br>
SIGGRAPH 2019. [[](https://arxiv.org/abs/1904.12356)]

**LOGAN: Unpaired Shape Transform in Latent Overcomplete Space.**<br>
*Kangxue Yin, Zhiqin Chen, Hui Huang, Daniel Cohen-Or, Hao Zhang.*<br>
SIGGRAPH Asia, 2019. [[PDF](https://arxiv.org/pdf/1903.10170.pdf)]

**EBT: Everybody's Talkin': Let Me Talk as You Want.**<br>
*Linsen Song, [Wayne Wu](http://wywu.github.io/), Chen Qian, [Ran He](https://scholar.google.com/citations?user=ayrg9AUAAAAJ&hl=en), Chen Change Loy.*<br>
arxiv, 15 Jan 2020. [[PDF](https://arxiv.org/abs/2001.05201)] [[Project](https://wywu.github.io/projects/EBT/EBT.html)]

**Neural Human Video Rendering: Joint Learning of Dynamic Textures and Rendering-to-Video Translation.**<br>
*Lingjie Liu, Weipeng Xu, Marc Habermann, Michael Zollhoefer, Florian Bernard, Hyeongwoo Kim, Wenping Wang, Christian Theobalt.*<br>
arxiv, 14 Jan 2020. [[PDF](https://arxiv.org/abs/2001.04947)]

**FLNet: Landmark Driven Fetching and Learning Network for Faithful Talking Facial Animation Synthesis.**<br>
*Kuangxiao Gu, Yuqian Zhou, Thomas Huang.*<br>
AAAI 2020. [[PDF](https://arxiv.org/abs/1911.09224)] [[GitHub](https://github.com/kgu3/FLNet_AAAI2020)]

**Liquid Warping GAN: A Unified Framework for Human Motion Imitation, Appearance Transfer and Novel View Synthesis.**<br>
*Wen Liu, Zhixin Piao, Jie Min, Wenhan Luo, Lin Ma, Shenghua Gao.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1909.12224)] [[HomePage]( https://motionretargeting2d.github.io)] 	[[Github](https://github.com/svip-lab/impersonator)]. 

**Learning Character-Agnostic Motion for Motion Retargeting in 2D.**<br>
*Kfir Aberman, Rundi Wu, Dani Lischinski, Baoquan Chen, Daniel Cohen-Or.*<br>
SIGGRAPH 2019. [[PDF](https://arxiv.org/abs/1905.01680)] [[Github](https://github.com/ChrisWu1997/2D-Motion-Retargeting)] [[Project](https://motionretargeting2d.github.io/)]

**Progressive Pose Attention Transfer for Person Image Generation.**<br>
*Zhen Zhu, Tengteng Huang, Baoguang Shi, Miao Yu, Bofei Wang, Xiang Bai.*<br>
CVPR 2019. [[Project](https://github.com/tengteng95/Pose-Transfer)] [[PDF](https://arxiv.org/abs/1904.03349)]

**Deep 3D-Zoom Net: Unsupervised Learning of Photo-Realistic 3D-Zoom.**<br>
*Juan Luis Gonzalez Bello, Munchurl Kim.*<br>
arxiv, 20 Sep 2019. [[PDF](https://arxiv.org/abs/1909.09349v1)]

**Photo Wake-Up: 3D Character Animation from a Single Photo.**<br>
*Chung-Yi Weng, Brian Curless, Ira Kemelmacher-Shlizerman.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1812.02246)] [[Project](https://grail.cs.washington.edu/projects/wakeup/)]

**Textured Neural Avatars.**<br>
*Aliaksandra Shysheya, Egor Zakharov, Kara-Ali Aliev, Renat Bashirov, Egor Burkov, Karim Iskakov, Aleksei Ivakhnenko, Yury Malkov, Igor Pasechnik, Dmitry Ulyanov, Alexander Vakhitov, Victor Lempitsky.*<br>
CVPR 2019 (oral). [[PDF](https://arxiv.org/abs/1905.08776)] [[Project](https://saic-violet.github.io/texturedavatar/)]

**Appearance Composing GAN: A General Method for Appearance-Controllable Human Video Motion Transfer.**<br>
*Dongxu Wei, Haibin Shen, Kejie Huang.*<br>
arxiv, 25 Nov 2019. [[PDF](https://arxiv.org/abs/1911.10672)]

## 3D Pose Transfer
**Neural Pose Transfer by Spatially Adaptive Instance Normalization.**<br>
*Jiashun Wang, Chao Wen, Yanwei Fu, Haitao Lin, Tianyun Zou, Xiangyang Xue, Yinda Zhang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.07254)] [[Github](https://github.com/jiashunwang/Neural-Pose-Transfer)]

## Multi-Modality Translation

[[Eurus-Holmes/Awesome-Multimodal-Research](https://github.com/Eurus-Holmes/Awesome-Multimodal-Research)]</br>
[[pliang279/awesome-multimodal-ml](https://github.com/pliang279/awesome-multimodal-ml)]</br>

### Voice-to-Voice

**REMI: Pop Music Transformer: Generating Music with Rhythm and Harmony.**<br>
*Yu-Siang Huang, Yi-Hsuan Yang.*<br>
arxiv, 1 Feb 2020. [[PDF](https://arxiv.org/abs/2002.00212)] [[Github](https://github.com/YatingMusic/remi)] [[Demo](http://vibertthio.com/transformer/)]

**Speech-to-Singing Conversion in an Encoder-Decoder Framework.**<br>
*Jayneel Parekh, Preeti Rao, Yi-Hsuan Yang.*<br>
ICASSP 2020. 
[[PDF](https://arxiv.org/abs/2002.06595)] [[Github](https://github.com/jayneelparekh/sp2si-code)] 
[[Project](https://jayneelparekh.github.io/icassp20/)]
[[NUS-48E dataset](https://smcnus.comp.nus.edu.sg/nus-48e-sung-and-spoken-lyrics-corpus/)]

### Text-to-Image

**ControlGAN: Controllable Text-to-Image Generation.**<br>
*Bowen Li, Xiaojuan Qi, Thomas Lukasiewicz, Philip H. S. Torr.*<br>
NeurIPS 2019. [[PDF](https://papers.nips.cc/paper/8480-controllable-text-to-image-generation.pdf)] [[Github](https://github.com/mrlibw/ControlGAN)]

**Object-driven Text-to-Image Synthesis via Adversarial Training.**<br>
*Wenbo Li, Pengchuan Zhang, Lei Zhang, Qiuyuan Huang, Xiaodong He, Siwei Lyu, Jianfeng Gao.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1902.10740)]

**SwapText: Image Based Texts Transfer in Scenes.**<br>
*Qiangpeng Yang, Hongsheng Jin, Jun Huang, Wei Lin.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.08152)]

### Voice-to-Image
**Speech2Face: Learning the Face Behind a Voice.**<br>
*Tae-Hyun Oh, Tali Dekel, Changil Kim, Inbar Mosseri, William T. Freeman, Michael Rubinstein, Wojciech Matusik.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1905.09773)] [[project](https://speech2face.github.io/)] [[Related Work](https://speech2face.github.io/)]

### speech-to-Text
**Synchronous Speech Recognition and Speech-to-Text Translation with Interactive Decoding.**<br>
*Yuchen Liu, Jiajun Zhang, Hao Xiong, Long Zhou, Zhongjun He, Hua Wu, Haifeng Wang, Chengqing Zong.*<br>
AAAI 2020. [[PDF](https://arxiv.org/abs/1912.07240)]

### Text-to-speech
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

## Gaze Estimation, Tracking, Redirection, Correction and Blink Detection

[[Awesome Work on Gaze Estimation.](https://github.com/cvlab-uob/Awesome-Gaze-Estimation)]

ICCV 2019 WorkShop: [Gaze Estimation and Prediction in the Wild](http://openaccess.thecvf.com/ICCV2019_workshops/ICCV2019_GAZE.py) [[Homepage](http://gazeworkshop.github.io/)]

* A Generalized and Robust Method Towards Practical Gaze Estimation on Smart Phone. [[PDF]](http://openaccess.thecvf.com/content_ICCVW_2019/papers/GAZE/Guo_A_Generalized_and_Robust_Method_Towards_Practical_Gaze_Estimation_on_ICCVW_2019_paper.pdf)
Tianchu Guo, Yongchao Liu, Hui Zhang, Xiabing Liu, Youngjun Kwak, Byung In Yoo, Jae-Joon Han, Changkyu Choi.

* Learning to Personalize in Appearance-Based Gaze Tracking. [[PDF]](http://openaccess.thecvf.com/content_ICCVW_2019/papers/GAZE/Linden_Learning_to_Personalize_in_Appearance-Based_Gaze_Tracking_ICCVW_2019_paper.pdf)
Erik Linden, Jonas Sjostrand, Alexandre Proutiere.

* On-Device Few-Shot Personalization for Real-Time Gaze Estimation. [[PDF]](http://openaccess.thecvf.com/content_ICCVW_2019/papers/GAZE/He_On-Device_Few-Shot_Personalization_for_Real-Time_Gaze_Estimation_ICCVW_2019_paper.pdf)
Junfeng He, Khoi Pham, Nachiappan Valliappan, Pingmei Xu, Chase Roberts, Dmitry Lagun, Vidhya Navalpakkam.

* RT-BENE: A Dataset and Baselines for Real-Time Blink Estimation in Natural Environments. [[PDF]](http://openaccess.thecvf.com/content_ICCVW_2019/papers/GAZE/Cortacero_RT-BENE_A_Dataset_and_Baselines_for_Real-Time_Blink_Estimation_in_ICCVW_2019_paper.pdf)
Kevin Cortacero, Tobias Fischer, Yiannis Demiris.

* SalGaze: Personalizing Gaze Estimation using Visual Saliency. [[PDF]](http://openaccess.thecvf.com/content_ICCVW_2019/papers/GAZE/Chang_SalGaze_Personalizing_Gaze_Estimation_using_Visual_Saliency_ICCVW_2019_paper.pdf)
Zhuoqing Chang, J. Matias Di Martino, Qiang Qiu, Steven Espinosa, Guillermo Sapiro.

### Gaze Dataset

**Columbia Gaze Data Set: Gaze Locking: Passive Eye Contact Detection for Human–Object Interaction.**<br>
*Brian A. Smith,  Qi Yin,  Steven K. Feiner,  Shree K. Nayar.*<br>
ACM Symposium on User Interface Software and Technology (UIST), 2013. [[PDF](http://www.cs.columbia.edu/~brian/publications/gaze_locking.html)] [[Columbia Gaze Data Set](http://www.cs.columbia.edu/CAVE/databases/columbia_gaze/)]

**GazeCapture: Eye Tracking for Everyone.**<br>
*Kyle Krafka*, Aditya Khosla*, Petr Kellnhofer, Harini Kannan, Suchendra Bhandarkar, Wojciech Matusik, Antonio Torralba.*<br>
CVPR 2016. [[PDF](https://gazecapture.csail.mit.edu/)] [[GazeCapture](https://gazecapture.csail.mit.edu/)] [[Github](https://github.com/CSAILVision/GazeCapture)]

**MPIIGaze: Appearance-based Gaze Estimation in the Wild.**<br>
*Xucong Zhang, Yusuke Sugano, Mario Fritz, Andreas Bulling.*<br>
CVPR 2015. [[PDF](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Zhang_Appearance-Based_Gaze_Estimation_2015_CVPR_paper.pdf)] [[MPIIGaze Dataset](https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/gaze-based-human-computer-interaction/appearance-based-gaze-estimation-in-the-wild/)] [[Max Planck Institute for Informatics](www.mpi-inf.mpg.de/)]

**MPIIFaceGaze: It’s Written All Over Your Face: Full-Face Appearance-Based Gaze Estimation.**<br>
*X. Zhang, Y. Sugano, M. Fritz and A. Bulling.*<br>
CVPR Workshop, 2017. [[PDF]](https://perceptual.mpi-inf.mpg.de/files/2017/05/zhang_cvprw2017.pdf) [[Homepage]](https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/gaze-based-human-computer-interaction/its-written-all-over-your-face-full-face-appearance-based-gaze-estimation/) [MPIIFaceGaze [Original](http://datasets.d2.mpi-inf.mpg.de/MPIIGaze/MPIIFaceGaze.zip) or [Normalized](http://datasets.d2.mpi-inf.mpg.de/MPIIGaze/MPIIFaceGaze_normalized.zip)]

**UT: Learning by Synthesis for Appearance-based 3D Gaze Estimation.**<br>
*Yusuke Sugano, Yasuyuki Matsushita, Yoichi Sato.*<br>
CVPR 2014. [[PDF](https://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Sugano_Learning-by-Synthesis_for_Appearance-based_2014_CVPR_paper.pdf)] [[UT Dataset](www.hci.iis.u-Tokyo.ac.jp/datasets)]

**Monocular Free-head 3D Gaze Tracking with Deep Learning and Geometry Constraints.**
*Haoping Deng, Wangjiang Zhu.*
ICCV 2017. [[PDF](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zhu_Monocular_Free-Head_3D_ICCV_2017_paper.pdf)]

### Gaze Redirection and Correction

**MGGR: MultiModal-Guided Gaze Redirection with Coarse-to-Fine Learning.**<br> 
*Jingjing Chen, Jichao Zhang, Jiayuan Fan, Tao Chen, Enver Sangineto, Nicu Sebe.*<br> 
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.03064)]

**GazeCorrection: Self-Guided Eye Manipulation in the wild using Self-Supervised Generative Adversarial Networks.**<br> 
*Jichao Zhang, Meng Sun, Jingjing Chen, Hao Tang, Yan Yan, Xueying Qin, Nicu Sebe.*<br> 
arxiv, 2019. [[PDF](https://arxiv.org/abs/1906.00805)] [[Github](https://github.com/zhangqianhui/GazeCorrection)]

**Look at Me! Correcting Eye Gaze in Live Video Communication.**<br> 
*Chih-Fan Hsu, Yushuen  Wang, C.-L Lei, Kuan-Ta Chen.*<br> 
TOMM (ACM Transactions on Multimedia Computing, Communications, and Applications). [[PDF](https://dl.acm.org/doi/10.1145/3311784)] [[Github](https://github.com/chihfanhsu/gaze_correction)]

**Photo-Realistic Monocular Gaze Redirection Using Generative Adversarial Networks.**<br>
*Zhe He, Adrian Spurr, Xucong Zhang, Otmar Hilliges ([AIT Lab, ETH Zurich](https://ait.ethz.ch/)).*<br> 
ICCV 2019. [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/He_Photo-Realistic_Monocular_Gaze_Redirection_Using_Generative_Adversarial_Networks_ICCV_2019_paper.pdf)] [[Github](https://github.com/HzDmS/gaze_redirection)] [[Columbia Gaze Dataset](http://www.cs.columbia.edu/~brian/projects/columbia_gaze.html)] [[Processed](https://drive.google.com/file/d/1tE3QfFjxtRco4ruLZwYyUhjyYSp2QIJL/view?usp=sharing)]

**Improving Few-Shot User-Specific Gaze Adaptation via Gaze Redirection Synthesis.**<br>
*Yu Yu, Gang Liu, Jean-Marc Odobez.*<br>
CVPR 2019. [[PDF](http://www.idiap.ch/~odobez/publications/YuLiuOdobez-CVPR2019.pdf)]

**GazeDirector: Fully Articulated Eye Gaze Redirection in Video.**<br>
*Erroll Wood, Tadas Baltrusaitis, Louis-Philippe Morency, Peter Robinson, Andreas Bulling.*<br>
Eurographics 2018 (Best Paper Honourable Mention Award). [[PDF](https://perceptual.mpi-inf.mpg.de/files/2018/03/wood18_eg.pdf)] 

**GazeGAN: Unpaired Adversarial Image Generation for Gaze Estimation.**<br>
*Matan Sela, Pingmei Xu, Junfeng He, Vidhya Navalpakkam, Dmitry Lagun.*<br>
2017. [[PDF](https://arxiv.org/abs/1711.09767)]

**DeepWarp: Photorealistic Image Resynthesis for Gaze Manipulation.**<br>
*Yaroslav Ganin, Daniil Kononenko, Diana Sungatullina, Victor Lempitsky.*<br>
ECCV 2016. [[PDF](http://sites.skoltech.ru/compvision/projects/deepwarp/files/deepwarp_eccv2016.pdf)] [[Project](http://sites.skoltech.ru/compvision/projects/deepwarp/)]

**Learning to look up: Realtime Monocular Gaze Correction using Machine Learning.**<br>
CVPR 2015. [[PDF](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Kononenko_Learning_To_Look_2015_CVPR_paper.pdf)] 

**Gaze Correction for Home Video Conferencing.**<br>
*C. Kuster, T. Popa, J.C. Bazin, C. Gotsman, M. Gross.*<br>
ACM TOG 2012.  [[PDF](https://cgl.ethz.ch/disclaimer.php?dlurl=/Downloads/Publications/Papers/2012/Kus12/Kus12.pdf)] [[CGL ETHZ](https://cgl.ethz.ch/publications/papers/paperKus12.php)]

**An Eye For An Eye: A Single Camera Gaze-Replacement Method.**<br>
*[Lior Wolf](http://www.cs.tau.ac.il/~wolf/), Ziv Freund, Shai Avidan.*<br>
CVPR 2010. [[PDF](http://www.cs.tau.ac.il/~wolf/papers/eyes_cameraready.pdf)] 

**Eye Gaze Correction with Stereovision For Video-teleconferencing.**<br>
*Ruigang Yang, Zhengyou Zhang.*<br>
ECCV 2004. [[PDF](https://www.microsoft.com/en-us/research/publication/eye-gaze-correction-with-stereovision-for-video-teleconferencing/)]

### Gaze Estimation

**FAZE: Few-Shot Adaptive Gaze Estimation.**<br>
*Seonwook Park, Shalini De Mello, Pavlo Molchanov, Umar Iqbal, Otmar Hilliges, Jan Kautz.*<br>
ICCV 2019. [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Park_Few-Shot_Adaptive_Gaze_Estimation_ICCV_2019_paper.pdf)] [[Preprocess](github.com/swook/faze_preprocess)] [[Github](https://github.com/NVlabs/few_shot_gaze)] [[ETH Zurich](https://ait.ethz.ch/projects/2019/faze/)] [[Nvidia](https://research.nvidia.com/publication/2019-10_Few-Shot-Adaptive-Gaze)]

**Gaze360: Physically Unconstrained Gaze Estimation in the Wild.**<br>
*Petr Kellnhofer*, Adrià Recasens*, Simon Stent, Wojciech Matusik, Antonio Torralba.*<br>
ICCV 2019. [[PDF](http://gaze360.csail.mit.edu/iccv2019_gaze360.pdf)] [[Github](https://github.com/Erkil1452/gaze360)] [[Project](http://gaze360.csail.mit.edu)] [[Dataset](http://gaze360.csail.mit.edu/download.php)]

**Mixed Effects Neural Networks (MeNets) With Applications to Gaze Estimation.**<br>
*Yunyang Xiong, Hyunwoo J. Kim, Vikas Singh.*<br>
CVPR 2019. [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/papers/Xiong_Mixed_Effects_Neural_Networks_MeNets_With_Applications_to_Gaze_Estimation_CVPR_2019_paper.pdf)]

**Deep Pictorial Gaze Estimation.**<br>
*Seonwook Park, Adrian Spurr, Otmar Hilliges.*<br>
ECCV 2018. [[PDF](http://openaccess.thecvf.com/content_ECCV_2018/papers/Seonwook_Park_Deep_Pictorial_Gaze_ECCV_2018_paper.pdf)] 

**RTGENE: Real-Time Gaze Estimation in Natural Environments.**<br>
*Tobias Fischer, Hyung Jin Chang,Yiannis Demiris.*<br>
ECCV 2018. [[PDF](http://openaccess.thecvf.com/content_ECCV_2018/papers/Tobias_Fischer_RT-GENE_Real-Time_Eye_ECCV_2018_paper.pdf)]
[[Github](https://github.com/Tobias-Fischer/rt_gene)]

### Eye Tracking

**Neuro-Inspired Eye Tracking With Eye Movement Dynamics.**<br>
*Kang Wang, Hui Su, Qiang Ji.*<br>
CVPR 2019. [[PDF](http://homepages.rpi.edu/~wangk10/papers/wang2019neural.pdf)]

**Generalizing Eye Tracking With Bayesian Adversarial Learning.**<br>
*Kang Wang, Rui Zhao, Hui Su, Qiang Ji.*<br>
CVPR 2019. [[PDF](https://www.semanticscholar.org/paper/Generalizing-Eye-Tracking-with-Bayesian-Adversarial-Wang-Zhao/77b9b6786699a236aad0c3fa3734730ece4a780f)]

**EyeDiap: A Database For the Development and Evaluation of Gaze Estimation Algorithms from RGB and RGBD Cameras.**<br>
*Kenneth Alberto Funes Mora, Florent Monay, Jeanmarc Odobez.*<br>
ETRA 2014. [[PDF](http://www.idiap.ch/~odobez/publications/FunesMonayOdobez-ETRA2014.pdf)] [[Idiap Research Institute](https://www.idiap.ch)]