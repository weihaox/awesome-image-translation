# awesome image-to-image translation papers [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of resources on image-to-image translation. 

This repository is organized chronologically by conferences (constantly updating).
There is another one organized in terms of **catrgory**, which is also [available](https://github.com/xiaweihao/awesome-image-translation/blob/master/README_.md). 

## Contributing

If you think I have missed out on something (or) have any suggestions (papers, implementations and other resources), feel free to [pull a request](https://github.com/xiaweihao/awesome-image-translation/pulls)

Feedback and contributions are welcome!

## Table of Contents
- [Year 2020](#year-2020)
  * [CVPR 2020](#cvpr-2020)
  * [AAAI 2020](#aaai-2020)
  * [Others 2020](#others-2020)
- [Year 2019](#year-2019)
  * [NeurIPS 2019](#neurips-2019)
  * [ICCV 2019](#iccv-2019)
  * [CVPR 2019](#cvpr-2019)
  * [ICLR 2019](#iclr-2019)
  * [AAAI 2019](#aaai-2019)
  * [ACM MM 2019](#acm-mm-2019)
  * [Journal 2019](#journal-2019)
  * [Others 2019](#others-2019)
- [Before 2018](#before-2018)

## Year 2020

### CVPR 2020
[[accepted paper list](http://openaccess.thecvf.com/CVPR2020.py)]

**SMIS: Semantically Multi-modal Image Synthesis.**[[PDF](https://arxiv.org/abs/2003.12697)] [[Project](http://seanseattle.github.io/SMIS)] [[Github](https://github.com/Seanseattle/SMIS)]<br> 
*[Zhen Zhu](https://zzhu.vision/), Zhiliang Xu, Ansheng You, [Xiang Bai](http://cloud.eic.hust.edu.cn:8071/~xbai/).*<br>

**CoCosNet: Cross-domain Correspondence Learning for Exemplar-based Image Translation.**[[PDF](https://arxiv.org/abs/2004.05571)][[Project](https://panzhang0212.github.io/CoCosNet/)]<br>
*[Pan Zhang](panzhang0212.github.io), [Bo Zhang](https://www.microsoft.com/en-us/research/people/zhanbo/), Dong Chen, Lu Yuan, Fang Wen.*<br>
<details>
  <summary> Comment </summary>
  CoCosNet = <a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Deep_Exemplar-Based_Video_Colorization_CVPR_2019_paper">DEVC</a> + <a href="https://github.com/NVlabs/SPADE">SPADE</a>
</details>

**Intuitive, Interactive Beard and Hair Synthesis with Generative Models.**[[PDF](https://arxiv.org/abs/2004.06848)]<br>
*Kyle Olszewski, Duygu Ceylan, Jun Xing, Jose Echevarria, Zhili Chen, Weikai Chen, Hao Li.*<br>

**Semantic Image Manipulation Using Scene Graphs.**[[PDF](https://arxiv.org/abs/2004.03677)]<br>
*Helisa Dhamo, Azade Farshad, Iro Laina, Nassir Navab, Gregory D. Hager, Federico Tombari, Christian Rupprecht.*<br>

**Guided Variational Autoencoder for Disentanglement Learning.**[[PDF](https://arxiv.org/abs/2004.01255)]<br>
*Zheng Ding, Yifan Xu, Weijian Xu, Gaurav Parmar, Yang Yang, Max Welling, Zhuowen Tu.*<br>

**Semi-supervised Learning for Few-shot Image-to-Image Translation.**[[PDF](https://arxiv.org/abs/2003.13853)] [[Github](https://github.com/yaxingwang/SEMIT)]<br>
*Yaxing Wang, Salman Khan, Abel Gonzalez-Garcia, Joost van de Weijer, Fahad Shahbaz Khan.*<br>

**Augmenting Colonoscopy using Extended and Directional CycleGAN for Lossy Image Translation.**[[PDF](https://arxiv.org/abs/2003.12473)]<br>
*Shawn Mathew, Saad Nadeem, Sruti Kumari, Arie Kaufman.*<br>

**ADGAN: Controllable Person Image Synthesis with Attribute-Decomposed GAN.**[[PDF](https://menyifang.github.io/projects/ADGAN/ADGAN_files/Paper_ADGAN_CVPR2020.pdf)] [[Project](https://menyifang.github.io/projects/ADGAN/ADGAN.html)]  [[Github](https://github.com/menyifang/ADGAN)]<br>
*[Yifang Men](https://menyifang.github.io/), [Yiming Mao](https://mtroym.github.io/), Yuning Jiang, Wei-Ying Ma, Zhouhui Lian.*<br>

**LGGAN: Local Class-Specific and Global Image-Level Generative Adversarial Networks for Semantic-Guided Scene Generation.** [[PDF](https://arxiv.org/abs/1912.12215)] [[Github](https://github.com/Ha0Tang/LGGAN)]<br> 
*[Hao Tang](http://disi.unitn.it/~hao.tang/), Dan Xu, Yan Yan, Philip H. S. Torr, Nicu Sebe.*<br> 

**StarGAN v2: Diverse Image Synthesis for Multiple Domains.**[[PDF](https://arxiv.org/abs/1912.01865)] [[GitHub](https://github.com/clovaai/stargan-v2)]<br> 
*Yunjey Choi, Youngjung Uh, Jaejun Yoo, Jung-Woo Ha. Clova AI Research, NAVER Corp.*<br> 

**GAN Compression: Efficient Architectures for Interactive Conditional GANs.**[[PDF](https://arxiv.org/abs/2003.08936)] [[Demo](https://tinyurl.com/r474uca)] [[Github](https://github.com/mit-han-lab/gan-compression/)]<br>
*[Muyang Li](https://lmxyy.me/), Ji Lin, Yaoyao Ding, Zhijian Liu, Jun-Yan Zhu, and [Song Han](https://songhan.mit.edu/).*<br>

**HiDT: High-Resolution Daytime Translation Without Domain Labels.**[[PDF](https://arxiv.org/abs/2003.08791)]<br>
*Ivan Anokhin, Pavel Solovev, Denis Korzhenkov, Alexey Kharlamov, Taras Khakhulin, Gleb Sterkin, Alexey Silvestrov, Sergey Nikolenko, Victor Lempitsky.*<br>

**NICE: Reusing Discriminators for Encoding: Towards Unsupervised Image-to-Image Translation.** [[PDF](https://arxiv.org/abs/2003.00273)] [[Github](https://github.com/alpc91/NICE-GAN-pytorch)]<br>
*Runfa Chen, Wenbing Huang, Binghui Huang, Fuchun Sun, Bin Fang.*<br>

### AAAI 2020 
[[accepted paper list](https://aaai.org/Conferences/AAAI-20/wp-content/uploads/2020/01/AAAI-20-Accepted-Paper-List.pdf)]

**Distilling Portable Generative Adversarial Networks for Image Translation.** [[PDF](https://arxiv.org/abs/2003.03519)] <br>
*Hanting Chen, Yunhe Wang, Han Shu, Changyuan Wen, Chunjing Xu, Boxin Shi, Chao Xu, Chang Xu.*<br>

**Fast and Robust Face-to-Parameter Translation for Game Character Auto-Creation.**[[PDF](https://arxiv.org/pdf/1909.01064.pdf)]<br>
*Tianyang Shi, Zhengxia Zou, Yi Yuan, Changjie Fan.*<br>

**Learning to Transfer: Unsupervised Domain Translation via Meta-Learning.**[[PDF](https://arxiv.org/abs/1906.00181)] [[Github](https://github.com/linjx-ustc1106/MT-GAN-PyTorch)]<br>
*Jianxin Lin, Yijun Wang, [Zhibo Chen](http://staff.ustc.edu.cn/~chenzhibo/publi.html), Tianyu He.*<br>

**Go From the General to the Particular: Multi-Domain Translation with Domain Transformation Networks.**[[PDF](https://arxiv.org/abs/1911.09912)]<br>
*Yong Wang, Longyue Wang, Shuming Shi, Victor Li, Zhaopeng Tu.*<br>

**Generating Diverse Translation by Manipulating Multi-Head Attention.**[[PDF](https://arxiv.org/abs/1911.09333v1)]<br>
*Zewei Sun, Shujian Huang, Hao-Ran Wei, Xin-yu Dai, Jiajun Chen.*<br>

**Benign Examples: Imperceptible Changes Can Enhance Image Translation Performance.**[[PDF](http://iphome.hhi.de/samek/pdf/SriAAAI20.pdf)]<br>
*Vignesh Srinivasan, Klaus-Robert Müller, [Wojciech Samek](http://iphome.hhi.de/samek/), Shinichi Nakajima.*<br>

**Multimodal Structure-Consistent Image-to-Image Translation.**<br>
*Che-Tsung Lin, Yen-Yi Wu, Po-Hao Hsu, Shang-Hong Lai.*<br>

**GAN-Based Unpaired Chinese Character Image Translation via Skeleton Transformation and Stroke Rendering.**<br>
*Yiming Gao, Jiangqin Wu.*<br>

### Others 2020

**U-GAT-IT: Unsupervised Generative Attentional Networks with Adaptive Layer-Instance Normalization for Image-to-Image Translation.**<br>
*Junho Kim, Minjae Kim, Hyeonwoo Kang, Kwanghee Lee.*<br>
[ICLR 2020](https://openreview.net/group?id=ICLR.cc/2020/Conference). [[PDF](https://arxiv.org/abs/1907.10830)] [[Official Tensorflow](https://github.com/taki0112/UGATIT)] [[Pytorch](https://github.com/znxlwm/UGATIT-pytorch)]

**GANILLA: Generative Adversarial Networks for Image to Illustration Translation.**<br>
*Samet Hicsonmez, Nermin Samet, Emre Akbas, Pinar Duygulu.*<br>
Image and Vision Computing 2020. [[PDF](https://arxiv.org/abs/2002.05638)] [[Github](https://github.com/giddyyupp/ganilla)]

**Image-to-Image Translation with Text Guidance.**<br>
*Bowen Li, Xiaojuan Qi, Philip H. S. Torr, Thomas Lukasiewicz.*<br>
arxiv, 12 Feb 2020. [[PDF](https://arxiv.org/abs/2002.05235)]

**Multi-Channel Attention Selection GANs for Guided Image-to-Image Translation.**<br>
*Hao Tang, Dan Xu, Yan Yan, Jason J. Corso, Philip H.S. Torr, Nicu Sebastie.*<br>
arxiv, 3 Feb 2020. (An extended version of [SelectionGAN](https://arxiv.org/abs/1904.06807) published in CVPR2019) 
[[PDF](https://arxiv.org/abs/2002.01048)]
[[Githtub](https://github.com/Ha0Tang/SelectionGAN)]

**Deformation-aware Unpaired Image Translation for Pose Estimation on Laboratory Animals.**<br>
*Siyuan Li, [Semih Günel](https://semihgunel.com/), Mirela Ostrek, Pavan Ramdya, [Pascal Fua](https://people.epfl.ch/pascal.fua/bio?lang=en), [Helge Rhodin](http://helge.rhodin.de/).*<br>
arxiv, 23 Jan 2020. [[PDF](https://arxiv.org/abs/2001.08601)]

**CDGAN: Cyclic Discriminative Generative Adversarial Networks for Image-to-Image Transformation.**<br>
*Kancharagunta Kishan Babu, Shiv Ram Dubey.*<br>
arxiv, 15 Jan 2020. [[PDF](https://arxiv.org/abs/2001.05489)]

## Year 2019

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

**FUNIT: Few-Shot Unsupervised Image-to-Image Translation.** [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/html/Liu_Few-Shot_Unsupervised_Image-to-Image_Translation_ICCV_2019_paper.html)]<br>
*Ming-Yu Liu, Xun Huang, Arun Mallya, Tero Karras, Timo Aila, Jaakko Lehtinen, Jan Kautz.*

**InGAN: Capturing and Retargeting the "DNA" of a Natural Image.** [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/html/Shocher_InGAN_Capturing_and_Retargeting_the_DNA_of_a_Natural_Image_ICCV_2019_paper.html)]<br>
*Assaf Shocher, Shai Bagon, Phillip Isola, Michal Irani.*

**Liquid Warping GAN: A Unified Framework for Human Motion Imitation, Appearance Transfer and Novel View Synthesis.** [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/html/Liu_Liquid_Warping_GAN_A_Unified_Framework_for_Human_Motion_Imitation_ICCV_2019_paper.html)]<br>
*Wen Liu, Zhixin Piao, Jie Min, Wenhan Luo, Lin Ma, Shenghua Gao.*

**SMIT: Stochastic Multi-Label Image-to-Image Translation.**<br>
*Andrés Romero, Pablo Arbeláez, Luc Van Gool, Radu Timofte.*<br>
ICCV Workshops 2019. [[PDF](https://arxiv.org/abs/1812.03704)] [[Github](https://github.com/BCV-Uniandes/SMIT)]

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

**Image-To-Image Translation via Group-Wise Deep Whitening-And-Coloring Transformation.** [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/html/Cho_Image-To-Image_Translation_via_Group-Wise_Deep_Whitening-And-Coloring_Transformation_CVPR_2019_paper.html)] [[Github](https://github.com/WonwoongCho/GDWCT)]<br>
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

**Diversity-Sensitive Conditional Generative Adversarial Networks.**[[PDF](https://arxiv.org/abs/1901.09024)]<br> 
*Dingdong Yang, Seunghoon Hong, Yunseok Jang, Tianchen Zhao, Honglak Lee.*<br>

**InstaGAN: Instance-aware Image-to-Image Translation.** [[PDF](https://openreview.net/forum?id=ryxwJhC9YX)] [[Github](https://github.com/sangwoomo/instagan)]<br>
*Sangwoo Mo, Minsu Cho, Jinwoo Shin.*<br>

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

### ACM MM and SIGGRAPH 2019

**VR Facial Animation via Multiview Image Translation.**<br>
*Shih-En Wei, Jason Saragih, Tomas Simon, Adam W. Harley, Stephen Lombardi, Michal Perdoch, Alexander Hypes, Dawei Wang, Hernan Badino, Yaser Sheikh.*<br>
SIGGRAPH 2019. [[PDF](https://research.fb.com/publications/vr-facial-animation-via-multiview-image-translation/)]

**Stylizing Video by Example.**<br> 
*Ondřej Jamriška, Šárka Sochorová, Ondřej Texler, Michal Lukáč, Jakub Fišer, Jingwan Lu, Eli Shechtman, Daniel Sýkora.*<br>
SIGGRAPH 2019. [[PDF](https://dcgi.fel.cvut.cz/home/sykorad/Jamriska19-SIG.pdf)]

**VR Facial Animation via Multiview Image Translation.**<br>
*Shih-En Wei, Jason Saragih, Tomas Simon, Adam W. Harley, Stephen Lombardi, Michal Perdoch, Alexander Hypes, Dawei Wang, Hernan Badino, Yaser Sheikh.*<br>
SIGGRAPH 2019. [[PDF](https://research.fb.com/publications/vr-facial-animation-via-multiview-image-translation/)]

**C2-GAN: Cycle In Cycle Generative Adversarial Networks for Keypoint-Guided Image Generation.**<br>
*[Hao Tang](http://disi.unitn.it/~hao.tang/), [Dan Xu](http://www.robots.ox.ac.uk/~danxu/), [Gaowen Liu](https://dblp.uni-trier.de/pers/hd/l/Liu:Gaowen), [Wei Wang](https://weiwangtrento.github.io/), [Nicu Sebe](https://scholar.google.com/citations?user=stFCYOAAAAAJ&hl=en), [Yan Yan](https://scholar.google.com/citations?user=zhi-j1wAAAAJ&hl=en).*<br>
ACM MM 2019. [[PDF](https://arxiv.org/abs/1908.00999)] [[Project](http://disi.unitn.it/~hao.tang/project/C2GAN.html)] [[Github](https://github.com/Ha0Tang/C2GAN)]

**Towards Automatic Face-to-Face Translation.**<br>
*Prajwal Renukanand, Rudrabha Mukhopadhyay, Jerin Philip, Abhishek Jha, Vinay Namboodiri and C.V. Jawahar.*<br>
ACM MM 2019. [[PDF](https://dl.acm.org/doi/10.1145/3343031.3351066)] [[Github](https://github.com/Rudrabha/LipGAN)] [[Project](http://cvit.iiit.ac.in/research/projects/cvit-projects/facetoface-translation)]

**Preserving Semantic and Temporal Consistency for Unpaired Video-to-Video Translation.**<br>
*Kwanyong Park, Sanghyun Woo, Dahun Kim, Donghyeon Cho, In So Kweon.*<br>
ACM MM 2019. [[PDF](https://arxiv.org/abs/1908.07683)]

**Mocycle-GAN: Unpaired Video-to-Video Translation.**<br> 
*Yang Chen, Yingwei Pan, Ting Yao, Xinmei Tian, Tao Mei.*<br> 
ACM MM 2019. [[PDF](https://arxiv.org/abs/1908.09514)]

### Journal 2019

**DosGAN: Exploring Explicit Domain Supervision for Latent Space Disentanglement in Unpaired Image-to-Image Translation.**<br>
*[Jianxin Lin](http://home.ustc.edu.cn/~linjx/), [Zhibo Chen](http://staff.ustc.edu.cn/~chenzhibo/), Yingce Xia, Sen Liu, Tao Qin, Jiebo Luo.*<br>
TPAMI 2019. [[PDF](https://arxiv.org/abs/1902.03782)] [[Github](https://github.com/linjx-ustc1106/DosGAN-PyTorch)]

**DRIT++: Diverse Image-to-Image Translation via Disentangled Representations.**<br>
*Hsin-Ying Lee, Hung-Yu Tseng, Qi Mao, Jia-Bin Huang, Yu-Ding Lu, Maneesh Singh, Ming-Hsuan Yang.*<br>
IJCV 2019. [[PDF](https://arxiv.org/abs/1905.01270)] [[Project](http://vllab.ucmerced.edu/hylee/DRIT_pp/)] [[Github](https://github.com/HsinYingLee/MDMM)]

**Show, Attend and Translate: Unsupervised Image Translation with Self-Regularization and Attention.**<br>
*Chao Yang, Taehwan Kim, Ruizhe Wang, Hao Peng, C.-C. Jay Kuo.*<br>
TIP 2019. [[PDF](https://arxiv.org/abs/1806.06195)]

**AttGAN: Facial Attribute Editing by Only Changing What You Want.**<br> 
*Zhenliang He, Wangmeng Zuo, Meina Kan, Shiguang Shan, Xilin Chen.*<br>
TIP 2019. [[PDF](https://arxiv.org/abs/1711.10678)] [[Github](https://github.com/LynnHo/AttGAN-Tensorflow)]

### Others 2019

**Deliberation Learning for Image-to-Image Translation.**<br>
*Tianyu He, Yingce Xia, Jianxin Lin, Xu Tan, Di He, Tao Qin, Zhibo Chen.*<br>
IJCAI 2019. [[PDF](https://www.ijcai.org/Proceedings/2019/0345.pdf)]

**RL-GAN: Transfer Learning for Related Reinforcement Learning Tasks via Image-to-Image Translation.**<br>
*Shani Gamrian, Yoav Goldberg.*<br>
ICML 2019. [[accepted paper list](http://proceedings.mlr.press/v97/)] [[PDF](https://arxiv.org/abs/1806.07377)] [[Supplementary PDF](http://proceedings.mlr.press/v97/fujimoto19a/fujimoto19a-supp.pdf)] [[Github](https://github.com/ShaniGam/RL-GAN)]

**CartoonRenderer: An Instance-based Multi-Style Cartoon Image Translator.**<br>
*Yugang Chen, Muchun Chen, Chaoyue Song, Bingbing Ni.*<br>
International Conference on Multimedia Modeling (MMM2020). [[PDF](https://arxiv.org/abs/1911.06102)] 

**AttentionGAN: Attention-Guided Generative Adversarial Networks for Unsupervised Image-to-Image Translation.**<br>
*Hao Tang, Dan Xu, Nicu Sebe, Yan Yan.*<br>
IJCNN 2019. [[Github](https://github.com/Ha0Tang/AttentionGAN)]

**Image-to-Image Translation with Multi-Path Consistency Regularization.**<br>
*Jianxin Lin, Yingce Xia, Yijun Wang, Tao Qin, Zhibo Chen.*<br>
IJCAI 2019. [[PDF](https://arxiv.org/abs/1905.12498)]

**Asymmetric Generative Adversarial Networks for Image-to-Image Translation.**<br>
*Hao Tang, Dan Xu, Hong Liu, Nicu Sebe.*<br>
arxiv, 14 Dec 2019 (ACCV 2018 Extension) [[PDF](https://arxiv.org/abs/1912.06931)] [[GitHub](​​​https://github.com/Ha0Tang/AsymmetricGAN)]

**PPN2V: Fully Unsupervised Probabilistic Noise2Void.**<br>
*Mangal Prakash, Manan Lalit, Pavel Tomancak, Alexander Krull, Florian Jug.*<br>
arxiv, 27 Nov 2019. [[PDF](https://arxiv.org/abs/1911.12291)] [[GitHub](https://github.com/juglab/ppn2v)] [[MPI-CBG: Max-Planck Institute of Molecular Cell Biology and Genetics](https://www.mpi-cbg.de/home/)]

**CrossNet: Latent Cross-Consistency for Unpaired Image Translation.**<br>
*Omry Sendik, Dani Lischinski, [Daniel Cohen-Or](https://danielcohenor.com/).*<br>
WACV, 2020. [[PDF](https://arxiv.org/abs/1901.04530)]

**Cross-Domain Cascaded Deep Feature Translation.**<br>
*Oren Katzir, Dani Lischinski, Daniel Cohen-Or.*<br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1906.01526)]

**Implicit Pairs for Boosting Unpaired Image-to-Image Translation.**<br>
*Yiftach Ginger, Dov Danon, Hadar Averbuch-Elor, Daniel Cohen-Or.*<br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1904.06913)]

**PN2V:Probabilistic Noise2Void: Unsupervised Content-Aware Denoising.**<br>
*Alexander Krull, Tomas Vicar, Florian Jug.*<br>
arxiv, 3 Jun 2019. [[PDF](https://arxiv.org/abs/1906.00651)] [[Github](https://github.com/juglab/pn2v)]

**Unpaired Image Translation via Adaptive Convolution-based Normalization.**<br>
*Wonwoong Cho, Kangyeol Kim, Eungyeup Kim, Hyunwoo J. Kim, Jaegul Choo.*<br>
arxiv, 29 Nov 2019. [[PDF]( https://arxiv.org/abs/1911.13271)]

**EDIT: Exemplar-Domain Aware Image-to-Image Translation.**<br>
*Yuanbin Fu, Jiayi Ma, Lin Ma, Xiaojie Guo.*<br>
arxiv, 24 Nov 2019. [[PDF](https://arxiv.org/abs/1911.10520)] [[GitHub](http://t.cn/AigvDwW3)]

**Council-GAN: Breaking the cycle - Colleagues are all you need.**<br>
*Ori Nizan, Ayellet Tal.*<br>
arxiv, 24 Nov 2019. [[PDF](https://arxiv.org/abs/1911.10538)]

**injectionGAN: Toward Learning a Unified Many-to-Many Mapping for Diverse Image Translation.**<br>
*Wenju Xu, Shawn Keshmiri, Guanghui Wang.*<br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1905.08766)]

**AGUIT: Attribute Guided Unpaired Image-to-Image Translation with Semi-supervised Learning.**<br>
*Xinyang Li, Jie Hu, Shengchuan Zhang, Xiaopeng Hong, Qixiang Ye, Chenglin Wu, Rongrong Ji.*<br>
arxiv 2019. [[PDF](https://arxiv.org/abs/1904.12428)] [[Github](https://github.com/imlixinyang/aguit)]

## Before 2018

**pix2pix: Image-to-Image Translation with Conditional Adversarial Networks.**<br>
*Phillip Isola, Jun-Yan Zhu, Tinghui Zhou, Alexei A. Efros.*<br>
CVPR 2017. [[Project](https://phillipi.github.io/pix2pix/)] [[Github](https://github.com/phillipi/pix2pix)] [[PDF](https://arxiv.org/pdf/1611.07004.pdf)]

**BicycleGAN: Toward Multimodal Image-to-Image Translation.**<br>
*Jun-Yan Zhu, Richard Zhang, Deepak Pathak, Trevor Darrell, Alexei A. Efros, Oliver Wang, Eli Shechtman.*<br>
NIPS 2017. [[PDF](https://arxiv.org/abs/1711.11586)] [[Project](https://junyanz.github.io/BicycleGAN/)] [[Github](https://github.com/junyanz/BicycleGAN)] [[TensorFlow](https://github.com/gitlimlab/BicycleGAN-Tensorflow)]

**CycleGAN: Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks.**<br>
*Jun-Yan Zhu, Taesung Park, Phillip Isola, Alexei A. Efros.*<br>
ICCV 2017. [[Project](https://junyanz.github.io/CycleGAN/)] [[Github](https://github.com/junyanz/CycleGAN)] [[pytorch-CycleGAN-and-pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)] [[PDF](https://arxiv.org/pdf/1703.10593.pdf)]

**DualGAN: Unsupervised Dual Learning for Image-to-Image Translation.**<br>
*Zili Yi, Hao Zhang, Ping Tan, Minglun Gong.*<br>
ICCV 2017. [[Github](https://github.com/duxingren14/DualGAN)] [[PDF](https://arxiv.org/abs/1704.02510)]

**DiscoGAN: Learning to Discover Cross-Domain Relations with Generative Adversarial Networks.**<br>
*Taeksoo Kim, Moonsu Cha, Hyunsoo Kim, Jung Kwon Lee, Jiwon Kim.*<br>
ICML 2017. [[Github](https://github.com/carpedm20/DiscoGAN-pytorch)] [[PDF](https://arxiv.org/abs/1703.05192)]

**StarGAN: Unified Generative Adversarial Networks for Multi-Domain Image-to-Image Translation.**<br>
*Yunjey Choi, Minje Choi, Munyoung Kim, Jung-Woo Ha, Sunghun Kim, Jaegul Choo.*<br>
CVPR 2018. [[Github](https://github.com/yunjey/StarGAN)] [[PDF](https://arxiv.org/abs/1711.09020)]

**UNIT: Unsupervised Image-to-Image Translation Networks.**<br>
*Ming-Yu Liu, Thomas Breuel, Jan Kautz.*<br>
NIPS 2017. [[PDF](https://arxiv.org/abs/1703.00848)] [[Github](https://github.com/mingyuliutw/UNIT)]

**DTN: Unsupervised Cross-Domain Image Generation.**<br>
*Yaniv Taigman, Adam Polyak, Lior Wolf.*<br>
arxiv 2016. [[PDF](https://arxiv.org/abs/1611.02200)] [[Github](https://github.com/yunjey/domain-transfer-network)] 

**Fader Networks: Manipulating Images by Sliding Attributes.**<br>
*Guillaume Lample, Neil Zeghidour, Nicolas Usunier, Antoine Bordes, Ludovic Denoyer, Marc'Aurelio Ranzato.*<br>
NIPS 2017.  [[Github](https://github.com/facebookresearch/FaderNetworks)] [[PDF](https://arxiv.org/abs/1706.00409)]

**IcGAN: Invertible Conditional GANs for Image Editing.**<br>
*Guim Perarnau, Joost van de Weijer, Bogdan Raducanu, Jose M. Álvarez.*<br>
NIPS 2016 Workshop on Adversarial Training. [[Github](https://github.com/Guim3/IcGAN)] [[PDF](https://arxiv.org/abs/1611.06355)]

**GeneGAN: Learning Object Transfiguration and Attribute Subspace from Unpaired Data.**<br>
*Shuchang Zhou, Taihong Xiao, Yi Yang, Dieqiao Feng, Qinyao He, Weiran He.*<br>
BMVC 2017. [[Github](https://github.com/Prinsphield/GeneGAN)] [[PDF](https://arxiv.org/abs/1705.04932)]

**Face-Age-cGAN: Face Aging With Conditional Generative Adversarial Networks.**<br>
*Grigory Antipov, Moez Baccouche, Jean-Luc Dugelay.*<br>
ICIP 2017. [[PDF](https://arxiv.org/abs/1702.01983)]


## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
