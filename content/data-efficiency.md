# Data Bias and Efficiency

Fewer Data for Better Results: improve Robustness, Transferability, Fairness, and Generalization from the lab to real-world applications.

## Table of Contents
- [Fairness, Accountability, Privacy, Transparency and Ethics](#fairness--accountability--privacy--transparency-and-ethics)
- [Neural Network Interpretability](#neural-network-interpretability)
- [Data Efficiency](#data-efficiency)
  * [Data or Distribution Augmentation](#data-or-distribution-augmentation)
  * [Knowledge Transfer](#knowledge-transfer)
  * [Single-Image Training](#single-image-training)
- [Dataset Bias](#dataset-bias)
- [Hard or Unfamiliar Example](#hard-or-unfamiliar-example)
- [Long-Tailed, Open Set, and Class-Imbalanced Dataset](#long-tailed--open-set--and-class-imbalanced-dataset)

## Fairness, Accountability, Privacy, Transparency, and Ethics

### Fairness

**FairGen: Improving the Fairness of Deep Generative Models without Retraining.**<br>
*[Shuhan Tan](https://ariostgx.github.io/), Yujun Shen, Bolei Zhou.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.04842)] [[Project](https://genforce.github.io/fairgen/)] [[Github](https://github.com/genforce/fairgen)]

**Inclusive GAN: Improving Data and Minority Coverage in Generative Models.**<br>
*Ning Yu, Ke Li, Peng Zhou, Jitendra Malik, Larry Davis, Mario Fritz.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2004.03355)] [[Github](https://github.com/ningyu1991/InclusiveGAN)]

**FairGen: Fair Generative Modeling via Weak Supervision.**<br>
*Kristy Choi, Aditya Grover, Trisha Singh, Rui Shu, Stefano Ermon.*<br>
ICML 2020. [[PDF](https://arxiv.org/abs/1910.12008)] [[Github](https://github.com/ermongroup/fairgen)]

**Bias and Generalization in Deep Generative Models: An Empirical Study.**<br>
*Shengjia Zhao, Hongyu Ren, Arianna Yuan, Jiaming Song, Noah Goodman, [Stefano Ermon](https://cs.stanford.edu/~ermon/).*<br>
NeurIPS 2018. [[PDF](https://arxiv.org/abs/1811.03259)] [[Blog](https://ermongroup.github.io/blog/bias-and-generalization-dgm/)] [[Github](https://github.com/ermongroup/BiasAndGeneralization)]

### Privacy

Federated Learning, Differential Privacy, Attack (Adversarial Attack, Data Poisoning Attack, *etc*) and Defense.

**Data Impressions: Mining Deep Models to Extract Samples for Data-free Applications.**<br>
*Gaurav Kumar Nayak, Konda Reddy Mopuri, Saksham Jain, Anirban Chakraborty.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.06069)]

**Intriguing Properties of Neural Networks.**<br>
*Christian Szegedy, Wojciech Zaremba, Ilya Sutskever, Joan Bruna, Dumitru Erhan, Ian Goodfellow, Rob Fergus.*<br>
ICLR 2014. [[PDF](https://arxiv.org/pdf/1312.6199.pdf)]

**Unlearnable Examples: Making Personal Data Unexploitable.**<br>
*Hanxun Huang, Xingjun Ma, Sarah Monazam Erfani, James Bailey, Yisen Wang.*<br>
ICLR 2021. [[PDF](https://arxiv.org/abs/2101.04898)]

**This Face Does Not Exist ... But It Might Be Yours! Identity Leakage in Generative Models.**<br>
*Patrick Tinsley, Adam Czajka, Patrick Flynn.*<br>
WACV 2021. [[PDF](https://arxiv.org/abs/2101.05084)]

**DataMix: Efficient Privacy-Preserving Edge-Cloud Inference.**<br>
*[Zhijian Liu](http://zhijianliu.com/), [Zhanghao Wu](https://zhanghaowu.me/), Chuang Gan, Ligeng Zhu, and Song Han.*<br>
ECCV 2020. [[PDF](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123560562.pdf)]

**Deep Leakage from Gradients**<br>
*Ligeng Zhu, Zhijian Liu, Song Han.*<br>
NeurIPS 2019. [[PDF](https://arxiv.org/pdf/1906.08935.pdf)]

**Defensive Quantization: When Efficiency Meets Robustness**<br>
*Ji Lin, Chuang Gan, [Song Han](http://songhan.mit.edu/).*<br>
ICLR 2019. [[PDF](https://arxiv.org/pdf/1904.08444.pdf)] [[Poster](https://www.dropbox.com/s/ugpcz41z8eosbd8/ICLR%20poster.pdf?dl=0)]

### Ethics

**Toward Trustworthy AI Development: Mechanisms for Supporting Verifiable Claims.**
*Miles Brundage et al.*
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.07213)]

## Neural Network Interpretability

**A Survey on Neural Network Interpretability.**<br>
*Yu Zhang, Peter Tiňo, Aleš Leonardis, Ke Tang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2012.14261)]

**Deep Learning and the Global Workspace Theory.**<br>
*Rufin VanRullen, Ryota Kanai.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.10390)]

## Data Efficiency

### Data or Distribution Augmentation

**Your GAN is Secretly an Energy-based Model and You Should use Discriminator Driven Latent Sampling.**<br>
*Tong Che, Ruixiang Zhang, Jascha Sohl-Dickstein, Hugo Larochelle, Liam Paull, Yuan Cao, Yoshua Bengio.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2003.06060)]

**Regularizing Deep Networks with Semantic Data Augmentation.**<br>
*Yulin Wang, Gao Huang, Shiji Song, Xuran Pan, Yitong Xia, Cheng Wu.*<br>
TPAMI 2020. [[PDF](https://arxiv.org/abs/2007.10538)]

**Free Lunch for Few-shot Learning:  Distribution Calibration.**<br>
*Shuo Yang, Lu Liu, Min Xu.*<br>
ICLR 2021. [[PDF](https://openreview.net/forum?id=JWOiYxMG92s)] [[Github](https://github.com/ShuoYang-1998/ICLR2021-Oral_Distribution_Calibration)]

**SnapMix: Semantically Proportional Mixing for Augmenting Fine-grained Data.**<br>
*Shaoli Huang, Xinchao Wang, Dacheng Tao.*<br>
AAAI 2021. [[PDF](https://arxiv.org/abs/2012.04846)] [[Github](https://github.com/Shaoli-Huang/SnapMix.git)]

**StyleGAN2-Ada: Training Generative Adversarial Networks with Limited Data.**<br>
*Tero Karras, Miika Aittala, Janne Hellsten, Samuli Laine, Jaakko Lehtinen, Timo Aila.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.06676)] [[Github](https://github.com/NVlabs/stylegan2-ada)] [[Steam StyleGAN2-ADA](https://github.com/woctezuma/steam-stylegan2-ada)]

**Differentiable Augmentation for Data-Efficient GAN Training.**<br>
*[Shengyu Zhao](https://scholar.google.com/citations?user=gLCdw70AAAAJ), [Zhijian Liu](http://zhijianliu.com/), [Ji Lin](http://linji.me/), [Jun-Yan Zhu](https://www.cs.cmu.edu/~junyanz/), [Song Han](https://songhan.mit.edu/).*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.10738)] [[Project](https://data-efficient-gans.mit.edu/)] [[Github](https://github.com/mit-han-lab/data-efficient-gans)] [[Video](https://www.youtube.com/watch?v=SsqcjS6SVM0)]

**Differentiable Augmentation for Data-Efficient GAN Training.**<br>
*Shengyu Zhao, Zhijian Liu, Ji Lin, Jun-Yan Zhu, Song Han.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.10738)] [[Project](https://hanlab.mit.edu/projects/data-efficient-gans/)] [[Github](https://github.com/mit-han-lab/data-efficient-gans)]

**Representation Learning via Invariant Causal Mechanisms.**<br>
*Jovana Mitrovic, Brian McWilliams, Jacob Walker, Lars Buesing, Charles Blundell.*<br>
NeurIPS 2020. [Workshop](https://sslneuips20.github.io/pages/Accepted%20Paper.html): Self-Supervised Learning - Theory and Practice. [[PDF](https://arxiv.org/abs/2010.07922)]

**Feature Space Augmentation for Long-Tailed Data.**<br>
*Peng Chu, Xiao Bian, Shaopeng Liu, Haibin Ling.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.03673)]

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

**ISDA: Implicit Semantic Data Augmentation for Deep Networks.**<br>
*Yulin Wang, Xuran Pan, Shiji Song, Hong Zhang, Cheng Wu, Gao Huang.*<br>
NeurIPS 2019. [[PDF](https://arxiv.org/abs/1909.12220])] [[Github](https://github.com/blackfeather-wang/ISDA-for-Deep-Networks)]

### Knowledge Transfer

transfer learning, domain adaptation, *etc*.

**DeiT: Training Data-Efficient Image Transformers & Distillation Through Attention.**<br>
*Hugo Touvron, Matthieu Cord, Matthijs Douze, Francisco Massa, Alexandre Sablayrolles, Hervé Jégou.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.12877)] [[Github](https://github.com/facebookresearch/deit)]

**YuruGAN: Yuru-Chara Mascot Generator Using Generative Adversarial Networks With Clustering Small Dataset.**<br>
*Yuki Hagiwara, Toshihisa Tanaka.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.08066)]

**ForkGAN: Seeing into the Rainy Night.**<br>
*Zheng Ziqiang, Wu Yang, Han Xinran, Shi Jianbo.*<br>
ECCV 2020. [[PDF](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123480154.pdf)] [[Github](https://github.com/zhengziqiang/ForkGAN)]

**MineGAN: Effective Knowledge Transfer From GANs to Target Domains With Few Images.**<br>
*Yaxing Wang, Abel Gonzalez-Garcia, David Berga, Luis Herranz, Fahad Shahbaz Khan, Joost van de Weijer.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.05270)] [[Github](https://github.com/yaxingwang/MineGAN)]

**FastGAN: Towards Faster and Stabilized GAN Training for High-fidelity Few-shot Image Synthesis.**<br>
*Bingchen Liu, Yizhe Zhu, Kunpeng Song, Ahmed Elgammal.*<br>
ICLR 2021. [[PDF](https://arxiv.org/abs/2101.04775)] [[Data and Code](https://github.com/odegeasslbc/FastGAN-pytorch)]

**VirTex: Learning Visual Representations from Textual Annotations.**<br>
*Karan Desai, Justin Johnson.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.06666)] [[Github](https://github.com/kdexd/virtex)]

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

## Dataset Bias

active learning, metric learning, contrastive learning, label learning, *etc*.

**Removing Undesirable Feature Contributions Using Out-of-Distribution Data.**<br>
*Saehyung Lee, Changhwa Park, Hyungyu Lee, Jihun Yi, Jonghyun Lee, Sungroh Yoon.*<br>
ICLR 2021. [[PDF](https://arxiv.org/abs/2101.06639)]

**Shortcut Learning in Deep Neural Networks.**<br>
*Robert Geirhos, Jörn-Henrik Jacobsen, Claudio Michaelis, Richard Zemel, Wieland Brendel, Matthias Bethge, Felix A. Wichmann.*<br>
Nature Machine Intelligence 2020. [[PDF](https://arxiv.org/abs/2004.07780)] [[Github](https://github.com/rgeirhos/shortcut-perspective)]

**CGN: Counterfactual Generative Networks.**<br>
*[Axel Sauer](https://axelsauer.com/), [Andreas Geiger](http://www.cvlibs.net/).*<br>
ICLR 2021. [[PDF](https://arxiv.org/abs/2101.06046)] [[Github](https://github.com/autonomousvision/counterfactual_generative_networks)]

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

**Unbiased Look at Dataset Bias.**<br>
*Antonio Torralba, Alexei A. Efros.*<br>
CVPR 2011. [[PDF](https://people.csail.mit.edu/torralba/publications/datasets_cvpr11.pdf)]

## Hard or Unfamiliar Example

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

## Long-Tailed, Open Set, and Class-Imbalanced Dataset

**Class-imbalanced Domain Adaptation: An Empirical Odyssey.**<br>
*Shuhan Tan, Xingchao Peng, Kate Saenko.*<br>
ECCV TASK-CV Workshop 2020. [[PDF](https://arxiv.org/pdf/1910.10320.pdf)]

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

**Rethinking the Value of Labels for Improving Class-Imbalanced Learning.**<br>
*Yuzhe Yang, Zhi Xu.*<br>
NeurlPS 2020. [[PDF](https://arxiv.org/abs/2006.07529)] [[Github](https://github.com/YyzHarry/imbalanced-semi-self)]

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