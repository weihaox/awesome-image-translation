# <p align=center>`awesome data bias and efficiency papers`</p>

Fewer Data for Better Results: improve Robustness, Transferability, Fairness, and Generalization from the lab to real-world applications.

markdown format:
``` markdown
**Here is the Paper Name.**<br>
*[Author 1](homepage), Author 2, and Author 3.*<br>
Conference or Journal Year. [[PDF](link)] [[Project](link)] [[Github](link)] [[Video](link)] [[Data](link)]
```

## Table of Contents
- [Related Workshop and Tutorial](#related-workshop-and-tutorial)
- [Fairness, Accountability, Privacy, Transparency, and Ethics](#fairness-accountability-privacy-transparency-and-ethics)
- [Neural Network Interpretability](#neural-network-interpretability)
- [Data Efficiency](#data-efficiency)
- [Data Bias](#data-bias)
- [Data Memorization](#data-memorization)
- [Data Imputation](#data-imputation)
- [Open-World and Out-of-Distribution Dataset](#open-world-and-out-of-distribution-dataset)
- [Long-Tailed and Class-Imbalanced Dataset](#long-tailed-and-class-imbalanced-dataset)
- [Hard or Unfamiliar Example](#hard-or-unfamiliar-example)
- [Domain Generalization](#domain-generalization)
- [Domain Adaptation](#domain-adaptation)

## Related Workshop and Tutorial

**Open World Vision.**<br>
CVPR 2021 Workshop. [[Homepage])(http://www.cs.cmu.edu/~shuk/open-world-vision.html#competition)]

**L2ID: Learning from Limited and Imperfect Data.**<br>
*[Zsolt Kira](https://www.cc.gatech.edu/~zk15/), [Shuai (Kyle) Zheng](https://kylezheng.org/), [Noel C. F. Codella](https://www.linkedin.com/in/noel-c-f-codella-ph-d-1b1b1723/), [Yunchao Wei](https://weiyc.github.io/), [Ming-Ming Cheng](https://mmcheng.net/cmm/), [Judy Hoffman](https://www.cc.gatech.edu/~judy/), [Tatiana Tommasi](http://www.tatianatommasi.com/), [Antonio Torralba](http://web.mit.edu/torralba/www/), [Xiaojuan Qi](https://xjqi.github.io/), [Sadeep Jayasumana](https://www.robots.ox.ac.uk/~sadeep/), [Hang Zhao](http://www.mit.edu/~hangzhao/), Liwei Wang, [Yunhui Guo](https://yunhuiguo.github.io/), Lin-Zhuo Chen.*<br>

**IPCV: Imbalance Problems in Computer Vision.**<br>
*[Emre Akbas](https://user.ceng.metu.edu.tr/~emre/), Baris Can Cam, Sinan Kalkan, Kemal Oksuz, Nuno Vasconcelos.*<br>
ECCV 2020 Workshop. [[Homepage])(https://sites.google.com/view/ipcv2020/home)]

## Fairness, Accountability, Privacy, Transparency, and Ethics

### Fairness

**Embracing Uncertainty: Decoupling and De-bias for Robust Temporal Grounding.**<br> 
*Hao Zhou, Chongyang Zhang, Yan Luo, Yanjun Chen, Chuanping Hu.*<br> 
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.16848)]

**Fair Mixup: Fairness via Interpolation.**<br> 
*Ching-Yao Chuang, Youssef Mroueh.*<br> 
ICLR 2021. [[PDF](https://arxiv.org/pdf/2103.06503.pdf)] [[Github](https://github.com/chingyaoc/fair-mixup)]

**FairBatch: Batch Selection for Model Fairness.**<br> 
*Yuji Roh, Kangwook Lee, Steven Euijong Whang, Changho Suh.*<br> 
ICLR 2021. [[PDF](https://openreview.net/pdf?id=YNnpaAKeCfx)]

**Fair Attribute Classification through Latent Space De-biasing.**<br>
*Vikram V. Ramaswamy, Sunnie S. Y. Kim, Olga Russakovsky.*<br>
CVPR 2021. [[PDF](https://arxiv.org/pdf/2012.01469.pdf)] [[Github](https://github.com/princetonvisualai/gan-debiasing)]

**On the Fairness of Generative Adversarial Networks (GANs).**<br>
*Patrik Joslin Kenfack, Daniil Dmitrievich Arapovy, Rasheed Hussain, S.M. Ahsan Kazmi, Adil Mehmood Khan.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.00950)]

**Explaining Quantitative Measures of Fairness.**<br>
*[Scott Lundberg](https://scottlundberg.com/).*<br>
Fair & Responsible AI Workshop, CHI2020. [[PDF](https://scottlundberg.com/files/fairness_explanations.pdf)] [[Github](https://github.com/slundberg/shap/blob/master/notebooks/overviews/Explaining%20quantitative%20measures%20of%20fairness.ipynb)]

**Fair for All: Best-effort Fairness Guarantees for Classification.**<br>
*[Anilesh K. Krishnaswamy](https://users.cs.duke.edu/~anilesh/), [Zhihao Jiang](https://sites.google.com/view/zhihaojiang/home), [Kangning Wang](), [Yu Cheng](http://homepages.math.uic.edu/~yucheng/), [Kamesh Munagala](https://www.kameshmunagala.org/).*<br>
AISTATS 2021. [[PDF](https://arxiv.org/abs/2012.10216)]

**FairGen: Improving the Fairness of Deep Generative Models without Retraining.**<br>
*[Shuhan Tan](https://ariostgx.github.io/), Yujun Shen, Bolei Zhou.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.04842)] [[Project](https://genforce.github.io/fairgen/)] [[Github](https://github.com/genforce/fairgen)]

**FairGen: Fair Generative Modeling via Weak Supervision.**<br>
*[Kristy Choi](http://kristychoi.com/), [Aditya Grover](http://aditya-grover.github.io/), [Trisha Singh](https://profiles.stanford.edu/trisha-singh), [Rui Shu](http://ruishu.io/about/), [Stefano Ermon](https://cs.stanford.edu/~ermon/).*<br>
ICML 2020. [[PDF](https://arxiv.org/abs/1910.12008)] [[Github](https://github.com/ermongroup/fairgen)]

**Inclusive GAN: Improving Data and Minority Coverage in Generative Models.**<br>
*Ning Yu, Ke Li, Peng Zhou, Jitendra Malik, Larry Davis, Mario Fritz.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2004.03355)] [[Github](https://github.com/ningyu1991/InclusiveGAN)]

**When Samples Are Strategically Selected.**<br>
*[Hanrui Zhang](https://users.cs.duke.edu/~hrzhang), [Yu Cheng](http://homepages.math.uic.edu/~yucheng/).*<br> 
ICML 2019. [[PDF](https://users.cs.duke.edu/~conitzer/strategicsamples18.pdf)]

**Bias and Generalization in Deep Generative Models: An Empirical Study.**<br>
*Shengjia Zhao, Hongyu Ren, Arianna Yuan, Jiaming Song, Noah Goodman, [Stefano Ermon](https://cs.stanford.edu/~ermon/).*<br>
NeurIPS 2018. [[PDF](https://arxiv.org/abs/1811.03259)] [[Blog](https://ermongroup.github.io/blog/bias-and-generalization-dgm/)] [[Github](https://github.com/ermongroup/BiasAndGeneralization)]

### Security

Attack (Adversarial Attack, Data Poisoning Attack, *etc*) and Defense

**Capsule Network is Not More Robust than Convolutional Network.**<br> 
*Jindong Gu, Volker Tresp, Han Hu.*<br> 
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.15459)]

**Stabilized Medical Image Attacks.**<br> 
*Gege Qi, Lijun Gong, Yibing Song, Kai Ma, Yefeng Zheng.*<br> 
ICLR 2021. [[PDF](https://arxiv.org/abs/2103.05232)]

**BASAR: Black-box Attack on Skeletal Action Recognition.**<br> 
*Yunfeng Diao, Tianjia Shao, Yong-Liang Yang, Kun Zhou, He Wang.*<br> 
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.05266)]

**Dual Attention Suppression Attack: Generate Adversarial Camouflage in Physical World.**<br> 
*Jiakai Wang, Aishan Liu, Zixin Yin, Shunchang Liu, Shiyu Tang, Xianglong Liu.*<br> 
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.01050)] [[Github](https://github.com/nlsde-safety-team/DualAttentionAttack)]

**Deep Model Intellectual Property Protection via Deep Watermarking.**<br> 
*Jie Zhang, Dongdong Chen, Jing Liao, Weiming Zhang, Huamin Feng, Gang Hua, Nenghai Yu.*<br> 
TPAMI 2021. [[PDF](https://arxiv.org/abs/2103.04980)]

**Vulnerability-Aware Poisoning Mechanism for Online RL with Unknown Dynamics.**<br> 
*Yanchao Sun, Da Huo, Furong Huang.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=9r30XCjf5Dt)]

**Improving VAEs' Robustness to Adversarial Attack.**<br>
*Matthew JF Willetts, Alexander Camuto, Tom Rainforth, S Roberts, Christopher C Holmes.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=-Hs_otp2RB)]

**Dataset Inference: Ownership Resolution in Machine Learning.**<br>
*Pratyush Maini, Mohammad Yaghini, Nicolas Papernot.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=hvdKKV2yt7T)]

**Deep Leakage from Gradients.**<br>
*Ligeng Zhu, Zhijian Liu, Song Han.*<br>
NeurIPS 2019. [[PDF](https://arxiv.org/pdf/1906.08935.pdf)]

**Defensive Quantization: When Efficiency Meets Robustness**<br>
*Ji Lin, Chuang Gan, [Song Han](http://songhan.mit.edu/).*<br>
ICLR 2019. [[PDF](https://arxiv.org/pdf/1904.08444.pdf)] [[Poster](https://www.dropbox.com/s/ugpcz41z8eosbd8/ICLR%20poster.pdf?dl=0)]

### Privacy

Membership Inference, Federated Learning, Differential Privacy, *etc*.

**ArtFlow: Unbiased Image Style Transfer via Reversible Neural Flows.**<br> 
*Jie An, Siyu Huang, Yibing Song, Dejing Dou, Wei Liu, Jiebo Luo.*<br> 
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.16877)] [[Github](https://github.com/pkuanjie/ArtFlow)]

**Is Medical Chest X-ray Data Anonymous?**<br>
*Kai Packhäuser, Sebastian Gündel, Nicolas Münster, Christopher Syben, Vincent Christlein, Andreas Maier.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.08562)]

**DP-Image: Differential Privacy for Image Data in Feature Space.**<br>
*Bo Liu, Ming Ding, Hanyu Xue, Tianqing Zhu, Dayong Ye, Li Song, Wanlei Zhou.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.07073)]

**PECAM: Privacy-Enhanced Video Streaming and Analytics via Securely-Reversible Transformation.**<br>
*Hao Wu, Xuejin Tian, Minghao Li, Yunxin Liu, Ganesh Ananthanarayanan, Fengyuan Xu, and Sheng Zhong.*<br>
MobiCom 2021. [[PDF](https://www.msra.cn/wp-content/uploads/2021/03/mobicom21-pecam.pdf)]

**Information Laundering for Model Privacy.**<br>
*Xinran Wang, Yu Xiang, Jun Gao, Jie Ding.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=dyaIRud1zXg)]

**Private Image Reconstruction from System Side Channels Using Generative Models.**<br>
*Yuanyuan Yuan, Shuai Wang, Junping Zhang.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=y06VOYLcQXa)] [[Github](https://github.com/genSCA/genSCA)]

**Differentially Private Learning with Small Public Data.**<br>
*Jun Wang, Zhi-Hua Zhou.*<br>
AAAI 2020. [[PDF](https://ojs.aaai.org//index.php/AAAI/article/view/6088)]

**Limits of Private Learning with Access to Public Data.**<br>
*Noga Alon, Raef Bassily, Shay Moran.*<br>
NeurIPS 2019. [[PDF](https://papers.nips.cc/paper/2019/file/9a6a1aaafe73c572b7374828b03a1881-Paper.pdf)]

**Do Not Let Privacy Overbill Utility: Gradient Embedding Perturbation for Private Learning.**<br>
*Da Yu, Huishuai Zhang, Wei Chen, Tie-Yan Liu.*<br>
ICLR 2021. [[PDF](https://arxiv.org/abs/2102.12677)] [[Github](https://github.com/dayu11/Gradient-Embedding-Perturbation)]

**How Does Data Augmentation Affect Privacy in Machine Learning?**<br>
*Da Yu, Huishuai Zhang, Wei Chen, Jian Yin, Tie-Yan Liu.*<br>
AAAI 2021. [[PDF](https://arxiv.org/abs/2007.10567)] [[Github](https://github.com/dayu11/MI_with_DA)]

**Federated f-Differential Privacy.**<br>
*Qinqing Zheng, Shuxiao Chen, Qi Long, Weijie J. Su.*<br>
AISTATS 2021. [[PDF](https://arxiv.org/abs/2102.11158)]

**TIPRDC: Task-Independent Privacy-Respecting Data Crowdsourcing Framework for Deep Learning with Anonymized Intermediate Representations.**<br>
*Ang Li, Yixiao Duan, Huanrui Yang, Yiran Chen, Jianlei Yang.*<br>
KDD 2020 Best Student Paper. [[PDF](https://arxiv.org/pdf/2005.11480.pdf)]

**Decentralized Privacy-Preserving Proximity Tracing.**<br>
*Carmela Troncoso, Mathias Payer, Jean-Pierre Hubaux, Marcel Salathé, James Larus, Edouard Bugnion, Wouter Lueks, Theresa Stadler, Apostolos Pyrgelis, Daniele Antonioli, Ludovic Barman, Sylvain Chatel, Kenneth Paterson, Srdjan Čapkun, David Basin, Jan Beutel, Dennis Jackson, Marc Roeschlin, Patrick Leu, Bart Preneel, Nigel Smart, Aysajan Abidin, Seda Gürses, Michael Veale, Cas Cremers, Michael Backes, Nils Ole Tippenhauer, Reuben Binns, Ciro Cattuto, Alain Barrat, Dario Fiore, Manuel Barbosa, Rui Oliveira, José Pereira.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2005.12273)] [[Github](https://github.com/DP-3T/documents)]

**Strangers in the Room: Unpacking Perceptions of 'Smartness' and Related Ethical Concerns in the Home.**<br>
*William Seymour, Reuben Binns, Petr Slovak, Max Van Kleek, Nigel Shadbolt.*<br>
ACM Conference on Designing Interactive Systems (DIS) 2020. [[PDF](https://arxiv.org/abs/2005.00284)]

**Single Run Action Detector over Video Stream -- A Privacy Preserving Approach.**<br>
*Anbumalar Saravanan, Justin Sanchez, Hassan Ghasemzadeh, Aurelia Macabasco-O'Connell, Hamed Tabkhi.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.03391)]

**Privacy-Preserving Video Classification with Convolutional Neural Networks.**<br>
*Sikha Pentyala, Rafael Dowsley, Martine De Cock.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.03513)]

**Unlearnable Examples: Making Personal Data Unexploitable.**<br>
*Hanxun Huang, Xingjun Ma, Sarah Monazam Erfani, James Bailey, [Yisen Wang](https://sites.google.com/site/csyisenwang/).*<br>
ICLR 2021. [[PDF](https://arxiv.org/abs/2101.04898)]  [[Github](https://github.com/HanxunH/Unlearnable-Examples)]

**Data Impressions: Mining Deep Models to Extract Samples for Data-free Applications.**<br>
*Gaurav Kumar Nayak, Konda Reddy Mopuri, Saksham Jain, Anirban Chakraborty.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.06069)]

**Intriguing Properties of Neural Networks.**<br>
*Christian Szegedy, Wojciech Zaremba, Ilya Sutskever, Joan Bruna, Dumitru Erhan, Ian Goodfellow, Rob Fergus.*<br>
ICLR 2014. [[PDF](https://arxiv.org/pdf/1312.6199.pdf)]

**This Face Does Not Exist ... But It Might Be Yours! Identity Leakage in Generative Models.**<br>
*Patrick Tinsley, Adam Czajka, Patrick Flynn.*<br>
WACV 2021. [[PDF](https://arxiv.org/abs/2101.05084)]

**DataMix: Efficient Privacy-Preserving Edge-Cloud Inference.**<br>
*[Zhijian Liu](http://zhijianliu.com/), [Zhanghao Wu](https://zhanghaowu.me/), Chuang Gan, Ligeng Zhu, and Song Han.*<br>
ECCV 2020. [[PDF](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123560562.pdf)]

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

**Transferable Semantic Augmentation for Domain Adaptation.**<br> 
*Shuang Li, Mixue Xie, Kaixiong Gong, Chi Harold Liu, Yulin Wang, Wei Li.*<br> 
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.12562)] [[Github](https://github.com/BIT-DA/TSA)]

**MetaSAug: Meta Semantic Augmentation for Long-Tailed Visual Recognition.**<br> 
*Shuang Li, Kaixiong Gong, Chi Harold Liu, Yulin Wang, Feng Qiao, Xinjing Cheng.*<br> 
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.12579)] [[Github](https://github.com/BIT-DA/TSA)]

**Explaining the Efficacy of Counterfactually Augmented Data.**<br> 
*Divyansh Kaushik, Amrith Setlur, Eduard H Hovy, Zachary Chase Lipton.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=HHiiQKWsOcV)]

**Model Patching: Closing the Subgroup Performance Gap with Data Augmentation.**<br>  
*Karan Goel, Albert Gu, Yixuan Li, Christopher Re.*<br> 
ICLR 2021. [[PDF](https://openreview.net/pdf?id=9YlaeLfuhJF)]

**MODALS: Modality-agnostic Automated Data Augmentation in the Latent Space.**<br> 
*Tsz-Him Cheung, Dit-Yan Yeung.*<br> 
ICLR 2021. [[PDF](https://openreview.net/pdf?id=XjYgR6gbCEc)]

**Negative Data Augmentation.**<br> 
*Abhishek Sinha, Kumar Ayush, Jiaming Song, Burak Uzkent, Hongxia Jin, Stefano Ermon.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=Ovp8dvB8IBH)]

**How Does Mixup Help With Robustness and Generalization?**<br>
*Linjun Zhang, Zhun Deng, Kenji Kawaguchi, Amirata Ghorbani, James Zou.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=hvdKKV2yt7T)]

**Image Augmentation Is All You Need: Regularizing Deep Reinforcement Learning from Pixels.**<br>
*Denis Yarats, Ilya Kostrikov, Rob Fergus.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=GY6-6sTvGaf)]

**Data Augmentation for Object Detection via Differentiable Neural Rendering.**<br>
*Guanghan Ning, Guang Chen, Chaowei Tan, Si Luo, Liefeng Bo, Heng Huang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.02852)]

**AutoMix: Unveiling the Power of Mixup.**<br>
*Zicheng Liu, Siyuan Li, Di Wu, Zhiyuan Chen, Lirong Wu, Jianzhu Guo, Stan Z. Li.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.13027)]

**Fixing Data Augmentation to Improve Adversarial Robustness.**<br>
*Sylvestre-Alvise Rebuffi, Sven Gowal, Dan A. Calian, Florian Stimberg, Olivia Wiles, Timothy Mann.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.01946)]

**On Interaction Between Augmentations and Corruptions in Natural Corruption Robustness.**<br>
*Eric Mintun, Alexander Kirillov, Saining Xie.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.11273)] [[Github](https://github.com/facebookresearch/augmentation-corruption)]

**Contrastive Learning Inverts the Data Generating Process.**<br>
*Roland S. Zimmermann, Yash Sharma, Steffen Schneider, Matthias Bethge, Wieland Brendel.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.08850)] [[Github](https://brendel-group.github.io/cl-ica)]

**Data Augmentation Using Pre-trained Transformer Models.**<br>
*Varun Kumar, Ashutosh Choudhary, Eunah Cho.*<br>
ACL 2020. [[PDF](https://www.aclweb.org/anthology/2020.lifelongnlp-1.3.pdf)] [[Github](https://github.com/amazon-research/transformers-data-augmentation)]

**Negative Data Augmentation.**<br>
*Abhishek Sinha, Kumar Ayush, Jiaming Song, Burak Uzkent, Hongxia Jin, Stefano Ermon.*<br>
ICLR 2021. [[PDF](https://arxiv.org/abs/2102.05113)]

**Co-Mixup: Saliency Guided Joint Mixup with Supermodular Diversity.**<br>
*JangHyun Kim, Wonho Choo, Hosan Jeong, Hyun Oh Song.*<br>
ICLR 2021. [[PDF](https://openreview.net/forum?id=gvxJzw8kW4b)] [[Github](https://github.com/snu-mllab/Co-Mixup)]

**Puzzle Mix: Exploiting Saliency and Local Statistics for Optimal Mixup.**<br>
*Jang-Hyun Kim, Wonho Choo, Hyun Oh Song.*<br>
ICML 2020. [[PDF](https://arxiv.org/abs/2009.06962)] [[Github](https://github.com/vikasverma1077/manifold_mixup/tree/master/supervised)]

**Manifold Mixup: Better Representations by Interpolating Hidden States.**<br>
*Vikas Verma, Alex Lamb, Christopher Beckham, Amir Najafi, Ioannis Mitliagkas, Aaron Courville, David Lopez-Paz, Yoshua Bengio.*<br>
ICL 2019. [[PDF](https://arxiv.org/abs/1806.05236)] [[Github](https://github.com/vikasverma1077/manifold_mixup)]

**Towards Universal Representation Learning for Deep Face Recognition.**<br>
*[Yichun Shi](https://seasonsh.github.io/), Xiang Yu, Kihyuk Sohn, Manmohan Chandraker, Anil K. Jain.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2002.11841)]

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

**Representation Learning via Invariant Causal Mechanisms.**<br>
*Jovana Mitrovic, Brian McWilliams, Jacob Walker, Lars Buesing, Charles Blundell.*<br>
NeurIPS 2020. [Workshop](https://sslneuips20.github.io/pages/Accepted%20Paper.html): Self-Supervised Learning - Theory and Practice. [[PDF](https://arxiv.org/abs/2010.07922)]

**FeatMatch: Feature-Based Augmentation for Semi-Supervised Learning.**<br>
*[Chia-Wen Kuo](https://sites.google.com/view/chiawen-kuo/home), [Chih-Yao Ma](https://chihyaoma.github.io/), [Jia-Bin Huang](https://filebox.ece.vt.edu/~jbhuang/), [Zsolt Kira](https://www.cc.gatech.edu/~zk15/).*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.08505)] [[Project](https://sites.google.com/view/chiawen-kuo/home/featmatch)] [[Github](https://github.com/GT-RIPL/FeatMatch)]

**Feature Space Augmentation for Long-Tailed Data.**<br>
*Peng Chu, Xiao Bian, Shaopeng Liu, Haibin Ling.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.03673)]

**Augmentation Inside the Network.**<br>
*Maciej Sypetkowski, Jakub Jasiulewicz, Zbigniew Wojna.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.10769)]

**Joint Search of Data Augmentation Policies and Network Architectures.**<br>
*Taiga Kashima, Yoshihiro Yamada, Shunta Saito.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.09407)]

**Distribution Augmentation for Generative Modeling.**<br>
*Heewoo Jun, Rewon Child, Mark Chen, John Schulman, Aditya Ramesh, Alec Radford, Ilya Sutskever.*<br>
ICML 2020. [[PDF](https://proceedings.icml.cc/static/paper_files/icml/2020/6095-Paper.pdf)] [[Github](https://github.com/openai/distribution_augmentation)]

**ISDA: Implicit Semantic Data Augmentation for Deep Networks.**<br>
*Yulin Wang, Xuran Pan, Shiji Song, Hong Zhang, Cheng Wu, Gao Huang.*<br>
NeurIPS 2019. [[PDF](https://arxiv.org/abs/1909.12220)] [[Github](https://github.com/blackfeather-wang/ISDA-for-Deep-Networks)]

**CutMix: Regularization Strategy to Train Strong Classifiers with Localizable Features.**<br>
*Sangdoo Yun, Dongyoon Han, Seong Joon Oh, Sanghyuk Chun, Junsuk Choe, Youngjoon Yoo.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1905.04899)] [[Github](https://github.com/clovaai/CutMix-PyTorch)]

### Knowledge Transfer

transfer learning, domain adaptation, *etc*.

**Domain Generalization with MixStyle.**<br> 
*Kaiyang Zhou, Yongxin Yang, Yu Qiao, Tao Xiang.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=6xHJ37MVxxp)]

**Domain Generalization Needs Stochastic Weight Averaging for Robustness on Domain Shifts.**<br>
*Junbum Cha, Hancheol Cho, Kyungjae Lee, Seunghyun Park, Yunsung Lee, Sungrae Park.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.08604)]

**cGANTransfer: Efficient Conditional GAN Transfer with Knowledge Propagation across Classes.**<br>
*Mohamad Shahbazi, Zhiwu Huang, Danda Pani Paudel, Ajad Chhatkuli, Luc Van Gool.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2102.06696)] [[Github](https://github.com/mshahbazi72/cGANTransfer)]

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

**One-Shot GAN: Learning to Generate Samples from Single Images and Videos.**<br> 
*Vadim Sushko, Juergen Gall, Anna Khoreva.*<br> 
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.13389)]

**GAN2GAN: Generative Noise Learning for Blind Denoising with Single Noisy Images.**<br> 
*Sungmin Cha, Taeeon Park, Byeongjoon Kim, Jongduk Baek, Taesup Moon.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=SHvF5xaueVn)]

**Morphologic-structure-aware Generative Learning from a Single Image.**<br>
*Jinshu Chen, Qihui Xu, Qi Kang, MengChu Zhou.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.02997)] [[Github](https://github.com/JinshuChen/MOGAN)]

**ConSinGAN: Improved Techniques for Training Single-Image GANs.**<br>
*Tobias Hinz, Matthew Fisher, Oliver Wang, Stefan Wermter.*<br>
WACV 2021. [[PDF](https://arxiv.org/abs/2003.11512)]  [[Github](https://github.com/tohinz/ConSinGAN)]

**Hierarchical Patch VAE-GAN: Generating Diverse Videos from a Single Sample.**<br>
*[Shir Gur](http://www.gurshir.com/), [Sagie Benaim](https://sagiebenaim.github.io/), [Lior Wolf](http://www.cs.tau.ac.il/~wolf/).*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.12226)] [[Project](https://shirgur.github.io/hp-vae-gan/)] [[Github](https://github.com/shirgur/hp-vae-gan)]

**Blind Motion Deblurring through SinGAN Architecture.**<br>
*Harshil Jain, Rohit Patil, Indra Deep Mastan, Shanmuganathan Raman.*<br>
ECCV 2020 Workshop. [[PDF](https://arxiv.org/abs/2011.03705)]

**TuiGAN: Learning Versatile Image-to-Image Translation with Two Unpaired Images.**<br>
*Jianxin Lin, Yingxue Pang, Yingce Xia, Zhibo Chen, Jiebo Luo.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2004.04634)] [[Github](https://github.com/linjx-ustc1106/TuiGAN-PyTorch)]

**MSG-GAN: Multi-Scale Gradient GAN for Stable Image Synthesis.**<br>
*Animesh Karnewar, Oliver Wang.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1903.06048)] [[Github](https://github.com/akanimax/msg-stylegan-tf)]

**InGAN: Capturing and Retargeting the DNA of a Natural Image.**<br>
ICCV 2019. [[PDF](http://www.wisdom.weizmann.ac.il/~vision/ingan/resources/ingan.pdf)] [[Project](http://www.wisdom.weizmann.ac.il/~vision/ingan/)] [[Github](https://github.com/assafshocher/InGAN)] 

**SinGAN: Learning a Generative Model from a Single Natural Image.**<br>
*Tamar Rott Shaham, Tali Dekel, Tomer Michaeli.*<br>
ICCV 2019 (Best Paper). [[PDF](https://arxiv.org/abs/1905.01164)] [[UnOfficial](github.com/FriedRonaldo/SinGAN)] [[Official](github.com/tamarott/SinGAN)]

### Others

**Learning Representational Invariances for Data-Efficient Action Recognition.**<br>
*Yuliang Zou, Jinwoo Choi, Qitong Wang, Jia-Bin Huang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.16565)] [[Github](https://yuliang.vision/video-data-aug)]

**Ultra-Data-Efficient GAN Training: Drawing A Lottery Ticket First, Then Training It Toughly.**<br>
*Tianlong Chen, Yu Cheng, Zhe Gan, Jingjing Liu, Zhangyang Wang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.00397)]

**Diversifying Sample Generation for Accurate Data-Free Quantization.**<br>
*Xiangguo Zhang, Haotong Qin, Yifu Ding, Ruihao Gong, Qinghua Yan, Renshuai Tao, Yuhang Li, Fengwei Yu, Xianglong Liu.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.01049)]

## Data Bias

*ML systems are biased when data is biased.* --Yann LeCun

active learning, metric learning, contrastive learning, label learning, *etc*.

**Permuted AdaIN: Reducing the Bias Towards Global Statistics in Image Classification.**<br>
*Oren Nuriel, Sagie Benaim, Lior Wolf.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2010.05785)] [[Github](https://github.com/onuriel/PermutedAdaIN)]

**Shape-Texture Debiased Neural Network Training.**<br> 
*Yingwei Li, Qihang Yu, Mingxing Tan, Jieru Mei, Peng Tang, Wei Shen, Alan Yuille, cihang xie.*<br> 
ICLR 2021. [[PDF](https://openreview.net/pdf?id=Db4yerZTYkz)]

**Training GANs with Stronger Augmentations via Contrastive Discriminator.**<br> 
*Jongheon Jeong, Jinwoo Shin.*<br> 
ICLR 2021. [[PDF](https://openreview.net/pdf?id=eo6U4CAwVmg)]

**FairFil: Contrastive Neural Debiasing Method for Pretrained Text Encoders.**<br> 
*Pengyu Cheng, Weituo Hao, Siyang Yuan, Shijing Si, Lawrence Carin.*<br> 
ICLR 2021. [[PDF](https://openreview.net/pdf?id=N6JECD-PI5w)]

**On Statistical Bias In Active Learning: How and When to Fix It.**<br> 
*Sebastian Farquhar, Yarin Gal, Tom Rainforth.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=JiYq3eqTKY)]

**VisualGPT: Data-efficient Image Captioning by Balancing Visual Input and Linguistic Knowledge from Pretraining.**<br>
*Jun Chen, Han Guo, Kai Yi, Boyang Li, Mohamed Elhoseiny.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.10407)] [[Github](https://github.com/Vision-CAIR/VisualGPT)]

**Bridging the Gap Between Adversarial Robustness and Optimization Bias.**<br>
*Fartash Faghri, Cristina Vasconcelos, David J. Fleet, Fabian Pedregosa, Nicolas Le Roux.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.08868)] [[Github](https://github.com/fartashf/robust_bias)]

**Unbiased Teacher for Semi-Supervised Object Detection.**<br>
*Yen-Cheng Liu, Chih-Yao Ma, Zijian He, Chia-Wen Kuo, Kan Chen, Peizhao Zhang, Bichen Wu, Zsolt Kira, Peter Vajda.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=MJIve1zgR_)]

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

**A Note on Data Biases in Generative Models.**<br>
*[Patrick Esser](https://github.com/pesser), [Robin Rombach](https://github.com/rromb), [Björn Ommer](https://hci.iwr.uni-heidelberg.de/Staff/bommer).*<br>
NeurIPS 2020 Workshop on Machine Learning for Creativity and Design. [[PDF](https://arxiv.org/abs/2012.02516)] [[Github](https://github.com/CompVis/net2net)]

**Making Sense of CNNs: Interpreting Deep Representations & Their Invariances with Invertible Neural Networks.**<br>
*[Robin Rombach](https://github.com/rromb), [Patrick Esser](https://github.com/pesser), [Björn Ommer](https://hci.iwr.uni-heidelberg.de/Staff/bommer).*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.01777)] [[Project](https://compvis.github.io/invariances/)] [[Github](https://compvis.github.io/invariances/)]

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

## Data Memorization

Memorization is the tendency to memorize the labels of the training data.

**The Low-Rank Simplicity Bias in Deep Networks.**<br>
*[Minyoung Huh](http://minyounghuh.com/), Hossein Mobahi, Richard Zhang, Brian Cheung, Pulkit Agrawal, Phillip Isola.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.10427)] [[Github](https://github.com/minyoungg/overparam)] [[Project](https://minyoungg.github.io/overparam/)]

**What Neural Networks Memorize and Why: Discovering the Long Tail via Influence Estimation.**<br>
*Vitaly Feldman, Chiyuan Zhang.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2008.03703)] [[Github](https://github.com/google-research/heldout-influence-estimation)] [[Project](https://pluskid.github.io/influence-memorization/)]

**Characterizing Structural Regularities of Labeled Data in Overparameterized Models.**<br>
*Ziheng Jiang, Chiyuan Zhang, Kunal Talwar, Michael C. Mozer.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2002.03206)] [[Github](https://github.com/google-research/heldout-influence-estimation)] [[Project](https://pluskid.github.io/structural-regularity/)]

**Identity Crisis: Memorization and Generalization under Extreme Overparameterization.**<br>
*Chiyuan Zhang, Samy Bengio, Moritz Hardt, Michael C. Mozer, Yoram Singer.*<br>
ICLR 2020. [[PDF](https://arxiv.org/abs/1902.04698)]

**Does Learning Require Memorization? A Short Tale about a Long Tail.**<br>
*Vitaly Feldman.*<br>
STOC 2020. [[PDF](https://arxiv.org/abs/1906.05271)]

## Data Imputation

**SMIL: Multimodal Learning with Severely Missing Modality.**<br>
*Mengmeng Ma, Jian Ren, Long Zhao, Sergey Tulyakov, Cathy Wu, Xi Peng.*<br>
AAAI 2021. [[PDF](https://arxiv.org/abs/2103.05677)] [[Github](https://github.com/mengmenm/SMIL)]

**Delving into Deep Imbalanced Regression.**<br>
*Yuzhe Yang, Kaiwen Zha, Ying-Cong Chen, Hao Wang, Dina Katabi.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.09554)] [[Code and Data](https://github.com/YyzHarry/imbalanced-regression)]

**Imputation of Missing Data with Class Imbalance using Conditional Generative Adversarial Networks.**<br>
*Saqib Ejaz Awan, Mohammed Bennamoun, Ferdous Sohel, Frank M Sanfilippo, Girish Dwivedi.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.00220)]

**Heteroskedastic and Imbalanced Deep Learning with Adaptive Regularization.**<br>
*Kaidi Cao, Yining Chen, Junwei Lu, Nikos Arechiga, Adrien Gaidon, Tengyu Ma.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.15766)]

**Identifying and Compensating for Feature Deviation in Imbalanced Deep Learning.**<br>
*Han-Jia Ye, Hong-You Chen, De-Chuan Zhan, Wei-Lun Chao.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2001.01385)]

**A Survey of Missing Data Imputation Using Generative Adversarial Networks.**<br>
*Jaeyoon Kim, Donghyun Tae, Junhee Seok.*<br>
International Conference on Artificial Intelligence in Information and Communication (ICAIIC) 2020. [[PDF](https://ieeexplore.ieee.org/document/9065044)]

**GAMIN: Generative Adversarial Multiple Imputation Network for Highly Missing Data.**<br>
*Seongwook Yoon, Sanghoon Sull.*<br>
CVPR 2020. [[PDF](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yoon_GAMIN_Generative_Adversarial_Multiple_Imputation_Network_for_Highly_Missing_Data_CVPR_2020_paper.pdf)]

**IFGAN: Missing Value Imputation using Feature-specific Generative Adversarial Networks.**<br>
*Wei Qiu, Yangsibo Huang, Quanzheng Li.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.12581)]

**CollaGAN: Collaborative GAN for Missing Image Data Imputation.**<br>
*Dongwook Lee, Junyoung Kim, Won-Jin Moon, Jong Chul Ye.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1901.09764)]

**GAIN: Missing Data Imputation using Generative Adversarial Nets.**<br>
*Jinsung Yoon, James Jordon, Mihaela van der Schaar.*<br>
ICML 2018. [[PDF](https://arxiv.org/abs/1806.02920)] [[Github](https://github.com/jsyoon0823/GAIN)]

## Open-World and Out-of-Distribution Dataset

**Bilevel Online Adaptation for Out-of-Domain Human Mesh Reconstruction.**<br> 
*Shanyan Guan, Jingwei Xu, Yunbo Wang, Bingbing Ni, Xiaokang Yang.*<br> 
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.16449)] [[Github](https://sites.google.com/view/humanmeshboa)]

**Benchmarking Representation Learning for Natural World Image Collections.**<br> 
*Grant Van Horn, Elijah Cole, Sara Beery, Kimberly Wilber, Serge Belongie, Oisin Mac Aodha.*<br> 
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.16483)]

**Learning Placeholders for Open-Set Recognition.**<br> 
*Da-Wei Zhou, Han-Jia Ye, De-Chuan Zhan.*<br> 
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.15086)]

**OWOD: Towards Open World Object Detection.**<br> 
*K J Joseph, Salman Khan, Fahad Shahbaz Khan, Vineeth N Balasubramanian.*<br> 
CVPR 2021 (oral). [[PDF](https://arxiv.org/abs/2103.02603)] [[Github](https://github.com/JosephKJ/OWOD)]

**Few-shot Open-set Recognition by Transformation Consistency.**<br>
*Minki Jeong, Seokeon Choi, Changick Kim.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.01537)]

**Understanding the failure modes of out-of-distribution generalization.**<br>
*Vaishnavh Nagarajan, Anders Andreassen, Behnam Neyshabur.*<br> 
ICLR 2021. [[PDF](https://openreview.net/pdf?id=fSTD6NFIW_b)]

**Removing Undesirable Feature Contributions Using Out-of-Distribution Data.**<br> 
*Saehyung Lee, Changhwa Park, Hyungyu Lee, Jihun Yi, Jonghyun Lee, Sungroh Yoon.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=eIHYL6fpbkA)]

**OWOD: Towards Open World Object Detection.**<br>
*K J Joseph, Salman Khan, Fahad Shahbaz Khan, Vineeth N Balasubramanian.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.02603)] [[Github](https://github.com/JosephKJ/OWOD)]

**Counterfactual Zero-Shot and Open-Set Visual Recognition.**<br>
*Zhongqi Yue, Tan Wang, Hanwang Zhang, Qianru Sun, Xian-Sheng Hua.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.00887)] [[Github](https://github.com/yue-zhongqi/gcm-cf)]

**Open-World Semi-Supervised Learning.**<br>
*Kaidi Cao, Maria Brbic, Jure Leskovec.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.03526)]

**In-N-Out: Pre-Training and Self-Training using Auxiliary Information for Out-of-Distribution Robustness.**<br>
*[Sang Michael Xie](https://cs.stanford.edu/~eix/), [Ananya Kumar](https://ananyakumar.wordpress.com/), [Robbie Jones](https://robbiejones96.github.io/), [Fereshte Khani](https://fereshte.people.stanford.edu/), [Tengyu Ma](https://ai.stanford.edu/~tengyuma/), [Percy Liang](https://cs.stanford.edu/~pliang/).*<br>
ICLR 2021. [[PDF](https://arxiv.org/abs/2012.04550)]

**DecGAN: Transductive Zero-Shot Learning by Decoupled Feature Generation.**<br>
*Federico Marmoreo, Jacopo Cavazza, Vittorio Murino.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.03266)]

**SelfNorm and CrossNorm for Out-of-Distribution Robustness.**<br>
*Zhiqiang Tang, Yunhe Gao, Yi Zhu, Zhi Zhang, Mu Li, Dimitris Metaxas.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.02811)]

**Towards Inheritable Models for Open-Set Domain Adaptation.**<br>
*Jogendra Nath Kundu, Naveen Venkat, Ambareesh Revanur, Rahul M V, R. Venkatesh Babu.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.04388)] [[Github](https://github.com/val-iisc/inheritune)]

**Open-World Learning Without Labels.**<br>
*Mohsen Jafarzadeh, Akshay Raj Dhamija, Steve Cruz, Chunchun Li, Touqeer Ahmad, Terrance E. Boult.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.12906)]

## Long-Tailed and Class-Imbalanced Dataset

**Improving Calibration for Long-Tailed Recognition.**<br>
*Zhisheng Zhong, Jiequan Cui, Shu Liu, Jiaya Jia.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.00466)]

**Distribution Alignment: A Unified Framework for Long-tail Visual Recognitionv.**<br>
*Songyang Zhang, Zeming Li, Shipeng Yan, Xuming He, Jian Sun.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.16370)]

**Contrastive Learning based Hybrid Networks for Long-Tailed Image Classification.**<br>
*Peng Wang, Kai Han, Xiu-Shen Wei, Lei Zhang, Lei Wang.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.14267)]

**Learning to Recombine and Resample Data For Compositional Generalization.**<br>
*Ekin Akyürek, Afra Feyza Akyürek, Jacob Andreas.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=PS3IMnScugk)]

**FASA: Feature Augmentation and Sampling Adaptation for Long-Tailed Instance Segmentation.**<br>
*Yuhang Zang, Chen Huang, Chen Change Loy.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.12867)]

**Conceptual 12M: Pushing Web-Scale Image-Text Pre-Training To Recognize Long-Tail Visual Concepts.**<br>
*Soravit Changpinyo, Piyush Sharma, Nan Ding, Radu Soricut.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.08981)]

**Delving into Deep Imbalanced Regression.**<br>
*Yuzhe Yang, Kaiwen Zha, Ying-Cong Chen, Hao Wang, Dina Katabi.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.09554)] [[Code and Data](https://github.com/YyzHarry/imbalanced-regression)]

**CReST: A Class-Rebalancing Self-Training Framework for Imbalanced Semi-Supervised Learning.**<br>
*Chen Wei, Kihyuk Sohn, Clayton Mellina, Alan Yuille, Fan Yang.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2102.09559)]

**A Mixed Focal Loss Function for Handling Class Imbalanced Medical Image Segmentation.**<br>
*Michael Yeung, Evis Sala, Carola-Bibiane Schönlieb, Leonardo Rundo.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.04525)]

**Semantic Segmentation with Labeling Uncertainty and Class Imbalance.**<br>
*Patrik Olã Bressan, José Marcato Junior, José Augusto Correa Martins, Diogo Nunes Gonçalves, Daniel Matte Freitas, Lucas Prado Osco, Jonathan de Andrade Silva, Zhipeng Luo, Jonathan Li, Raymundo Cordero Garcia, Wesley Nunes Gonçalves.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.04566)]

**Algorithms for Heavy-Tailed Statistics: Regression, Covariance Estimation, and Beyond.**<br>
*Yeshwanth Cherapanamjeri, Samuel B. Hopkins, Tarun Kathuria, Prasad Raghavendra, Nilesh Tripuraneni.*<br>
STOC 2020. [[PDF](https://arxiv.org/abs/1912.11071)]

**BalaGAN: Image Translation Between Imbalanced Domains via Cross-Modal Transfer.**<br>
*Or Patashnik, Dov Danon, Hao Zhang, Daniel Cohen-Or.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.02036)]

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

**M2M: Imbalanced Classification via Major-to-Minor Translation.**<br>
*Jaehyung Kim, Jongheon Jeong, Jinwoo Shin.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.00431)]

**Rethinking the Value of Labels for Improving Class-Imbalanced Learning.**<br>
*Yuzhe Yang, Zhi Xu.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.07529)] [[Github](https://github.com/YyzHarry/imbalanced-semi-self)]

**OSLNet: Deep Small-Sample Classification with an Orthogonal Softmax Layer.**<br>
*Xiaoxu Li, Dongliang Chang, Zhanyu Ma, Zheng-Hua Tan, Jing-Hao Xue, Jie Cao, Jingyi Yu, Jun Guo.*<br>
TIP 2020. [[PDF](https://arxiv.org/abs/2004.09033)] [[Github](https://github.com/dongliangchang/OSLNet)] 

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

## Hard or Unfamiliar Example

**Contrastive Learning with Hard Negative Samples.**<br> 
*Joshua David Robinson, Ching-Yao Chuang, Suvrit Sra, Stefanie Jegelka.*<br>
ICLR. 2021. [[PDF](https://openreview.net/pdf?id=CZ8Y3NzuVzO)]

**Improving memory banks for unsupervised learning with large mini-batch,consistency and hard negative mining.**<br>
*[Adrian Bulat](https://www.adrianbulat.com/), Enrique Sanchez, [Georgios Tzimiropoulos](http://www.cs.nott.ac.uk/~pszyt/).*<br>
ICASSP 2021. [[PDF](https://arxiv.org/abs/2102.04442)]

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

## Domain Generalization

**Progressive Domain Expansion Network for Single Domain Generalization.**<br>
*Lei Li, Ke Gao, Juan Cao, Ziyao Huang, Yepeng Weng, Xiaoyue Mi, Zhengze Yu, Xiaoya Li, Boyang xia.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.16050)]

**Uncertainty-guided Model Generalization to Unseen Domains.**<br> 
*Fengchun Qiao, Xi Peng.*<br> 
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.07531)]

**In Search of Lost Domain Generalization.**<br> 
*Ishaan Gulrajani, David Lopez-Paz.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=lQdXeXDoWtI)]

**Generalizing to Unseen Domains: A Survey on Domain Generalization.**<br>
*Jindong Wang, Cuiling Lan, Chang Liu, Yidong Ouyang, Tao Qin.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.03097)]

**Domain Generalization: A Survey.**<br>
*Kaiyang Zhou, Ziwei Liu, Yu Qiao, Tao Xiang, Chen Change Loy.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.02503)]

**Domain Generalization via Inference-time Label-Preserving Target Projections.**<br>
*Prashant Pandey, Mrigank Raman, Sumanth Varambally, Prathosh AP.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.01134)]

**FSDR: Frequency Space Domain Randomization for Domain Generalization.**<br>
*Jiaxing Huang, Dayan Guan, Aoran Xiao, Shijian Lu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.02370)]

**Domain Generalization Needs Stochastic Weight Averaging for Robustness on Domain Shifts.**<br>
*Junbum Cha, Hancheol Cho, Kyungjae Lee, Seunghyun Park, Yunsung Lee, Sungrae Park.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.08604)]

**How does the Combined Risk Affect the Performance of Unsupervised Domain Adaptation Approaches?**<br>
*Li Zhong, Zhen Fang, Feng Liu, Jie Lu, Bo Yuan, Guangquan Zhang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.01104)]

**Style Normalization and Restitution for Domain Generalization and Adaptation.**<br>
*Xin Jin, Cuiling Lan, Wenjun Zeng, Zhibo Chen.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.00588)] [[Github](https://github.com/microsoft/SNR)]

**Frustratingly Simple Domain Generalization via Image Stylization.**<br>
*[Nathan Somavarapu](https://nathansomavarapu.github.io/), Chih-Yao Ma, Zsolt Kira.*<br>
arxiv 2020. [[PDF](https://arxiv.org/pdf/2006.11207.pdf)] [[Github](https://github.com/GT-RIPL/DomainGeneralization-Stylization)]

**Closing the Generalization Gap in One-Shot Object Detection.**<br>
*Claudio Michaelis, Matthias Bethge, Alexander S. Ecker.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.04267)]

**Learning to Balance Specificity and Invariance for In and Out of Domain Generalization.**<br>
*[Prithvijit Chattopadhyay](https://prithv1.xyz/), Yogesh Balaji, Judy Hoffman.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.12839)]

**Zero Shot Domain Generalization.**<br>
*Udit Maniyar, Joseph K J, Aniket Anand Deshmukh, Urun Dogan, Vineeth N Balasubramanian.*<br>
BMVC 2020. [[PDF](https://arxiv.org/abs/2008.07443)]

**Domain Generalization with Optimal Transport and Metric Learning.**<br>
*Fan Zhou, Zhuqing Jiang, Changjian Shui, Boyu Wang, Brahim Chaib-draa.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.10573)]

**Learning to Learn with Variational Information Bottleneck for Domain Generalization.**<br>
*Yingjun Du, Jun Xu, Huan Xiong, Qiang Qiu, Xiantong Zhen, Cees G. M. Snoek, Ling Shao.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.07645)]

**Learning to Generate Novel Domains for Domain Generalization.**<br>
*Kaiyang Zhou, Yongxin Yang, Timothy Hospedales, Tao Xiang.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.03304)]

**Self-Challenging Improves Cross-Domain Generalization.**<br>
*Zeyi Huang, Haohan Wang, Eric P. Xing, Dong Huang.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.02454)]

**Automated Synthetic-to-Real Generalization.**<br>
*Wuyang Chen, Zhiding Yu, Zhangyang Wang, Anima Anandkumar.*<br>
ICML 2020. [[PDF](https://arxiv.org/abs/2007.06965)]

## Domain Adaptation

**Dynamic Domain Adaptation for Efficient Inference.**<br>
*Shuang Li, Jinming Zhang, Wenxuan Ma, Chi Harold Liu, Wei Li.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.16403)]

**From Synthetic to Real: Unsupervised Domain Adaptation for Animal Pose Estimation.**<br>
*Chen Li, Gim Hee Lee.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.14843)]

**Unsupervised Robust Domain Adaptation without Source Data.**<br>
*Peshal Agarwal, Danda Pani Paudel, Jan-Nico Zaech, Luc Van Gool.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.14577)]

**DRANet: Disentangling Representation and Adaptation Networks for Unsupervised Cross-Domain Adaptation.**<br>
*Seunghun Lee, Sunghyun Cho, Sunghoon Im.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.13447)]

**MetaAlign: Coordinating Domain Alignment and Classification for Unsupervised Domain Adaptation.**<br>
*Guoqiang Wei, Cuiling Lan, Wenjun Zeng, Zhibo Chen.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.13575)]

**Gradient Regularized Contrastive Learning for Continual Domain Adaptation.**<br>
*Shixiang Tang, Peng Su, Dapeng Chen, Wanli Ouyang.*<br>
AAAI 2021. [[PDF](https://arxiv.org/abs/2103.12294)]

**Generalized Domain Conditioned Adaptation Network.**<br>
*Shuang Li, Binhui Xie, Qiuxia Lin, Chi Harold Liu, Gao Huang, Guoren Wang.*<br>
TPAMI 2021. [[PDF](https://arxiv.org/abs/2103.12339)] [[Github](https://github.com/BIT-DA/GDCAN)]

**Dynamic Transfer for Multi-Source Domain Adaptation.**<br>
*Yunsheng Li, Lu Yuan, Yinpeng Chen, Pei Wang, Nuno Vasconcelos.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.10583)]

**MetaCorrection: Domain-aware Meta Loss Correction for Unsupervised Domain Adaptation in Semantic Segmentation.**<br>
*Xiaoqing Guo, Chen Yang, Baopu Li, Yixuan Yuan.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.05254)]

**Domain Adaptation for Learning Generator from Paired Few-Shot Data.**<br>
*Chun-Chih Teng, Pin-Yu Chen, Wei-Chen Chiu.*<br>
ICASSP 2021. [[PDF](https://arxiv.org/abs/2102.12765)]

**Domain Impression: A Source Data Free Domain Adaptation Method.**<br>
*Vinod K Kurmi, Venkatesh K Subramanian, Vinay P Namboodiri.*<br>
WACV 2021. [[PDF](https://arxiv.org/abs/2102.09003)]

**BA3US: A Balanced and Uncertainty-aware Approach for Partial Domain Adaptation.**<br>
*[Jian Liang](https://liangjian.xyz/), Yunbo Wang, Dapeng Hu, Ran He, Jiashi Feng.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2003.02541)] [[Github](https://github.com/tim-learn/BA3US)]

**SHOT: Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation.**<br>
*Jian Liang, Dapeng Hu, Jiashi Feng.*<br>
ICML 2020. [[PDF](https://arxiv.org/abs/2002.08546)] [[Github](https://github.com/tim-learn/SHOT)]

**Learning to Balance Specificity and Invariance for In and Out of Domain Generalization.**<br>
*[Prithvijit Chattopadhyay](https://prithv1.xyz/), Yogesh Balaji, Judy Hoffman.*<br>
ECCV 2020. [[PDF](https://prithv1.xyz/data/0790.pdf)] [[Github](https://github.com/prithv1/DMG)]

**Heuristic Domain Adaptation.**<br>
*Shuhao Cui, Xuan Jin, Shuhui Wang, Yuan He, Qingming Huang.*<br>
NeurIPS 2020. [[PDF](https://papers.nips.cc/paper/2020/file/555d6702c950ecb729a966504af0a635-Paper.pdf)]

**FixBi: Bridging Domain Spaces for Unsupervised Domain Adaptation.**<br>
*Jaemin Na, Heechul Jung, HyungJin Chang, Wonjun Hwang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.09230)]

**Interventional Domain Adaptation.**<br>
*Jun Wen, Changjian Shui, Kun Kuang, Junsong Yuan, Zenan Huang, Zhefeng Gong, Nenggan Zheng.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.03737)]

**Domain Agnostic Learning for Unbiased Authentication.**<br>
J*ian Liang, Yuren Cao, Shuang Li, Bing Bai, Hao Li, Fei Wang, Kun Bai.*<br>
arxiv 2020. [[](https://arxiv.org/abs/2010.05250)]

**Unveiling Class-Labeling Structure for Universal Domain Adaptation.**<br>
*Yueming Yin, Zhen Yang, Xiaofu Wu, Haifeng Hu.*<br>
arxiv 2020. [[](https://arxiv.org/abs/2010.04873)]

**The MECCANO Dataset: Understanding Human-Object Interactions from Egocentric Videos in an Industrial-like Domain.**<br>
*Francesco Ragusa, Antonino Furnari, Salvatore Livatino, Giovanni Maria Farinella.*<br>
arxiv 2020. [[](https://arxiv.org/abs/2010.05654)] [[Project](https://iplab.dmi.unict.it/MECCANO)]

**Robust Optimal Transport with Applications in Generative Modeling and Domain Adaptation.**<br>
*Yogesh Balaji, Soheil Feizi.*<br>
NeurIPS 2020. [[PDF](arxiv.org/abs/2010.05862)] [[Github](https://github.com/yogeshbalaji/robustOT)]

**Domain Adaptation Through Task Distillation.**<br>
*Brady Zhou, Nimit Kalra, Philipp Krähenbühl.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.11911)]

**Unsupervised Domain Adaptation via Discriminative Manifold Propagation.**<br>
*You-Wei Luo, Chuan-Xian Ren, Dao-Qing Dai, Hong Yan.*<br>
TPAMI 2020. [[PDF](https://arxiv.org/abs/2008.10030)]

**CSCL: Critical Semantic-Consistent Learning for Unsupervised Domain Adaptation.**<br>
*Jiahua Dong, Yang Cong, Gan Sun, Yuyang Liu, Xiaowei Xu.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.10464)]

**HCRPL: Hard Class Rectification for Domain Adaptation.**<br>
*Zhang Yunlong, Jing Changxing, Lin Huangxing, Chen Chaoqi, Huang Yue, Ding Xinghao, Zou Yang.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2008.03455)]

**Class-Incremental Domain Adaptation.**<br>
*Jogendra Nath Kundu, Rahul Mysore Venkatesh, Naveen Venkat, Ambareesh Revanur, R. Venkatesh Babu.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.01389)]

**Adversarial Bipartite Graph Learning for Video Domain Adaptation.**<br>
*Yadan Luo, Zi Huang, Zijian Wang, Zheng Zhang, Mahsa Baktashmotlagh.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2007.15829)]

**High Resolution Zero-Shot Domain Adaptation of Synthetically Rendered Face Images.**<br>
*Stephan J. Garbin, Marek Kowalski, Matthew Johnson, Jamie Shotton.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2006.15031)]

**Domain2Vec: Domain Embedding for Unsupervised Domain Adaptation.**<br>
*Xingchao Peng, Yichen Li, Kate Saenko.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.09257)]

**Continuously Indexed Domain Adaptation.**<br>
*Hao Wang, Hao He, Dina Katabi.*<br>
ICML 2020.[[PDF](https://arxiv.org/abs/2007.01807)]

**Domain Adaptation without Source Data.**<br>
*Youngeun Kim, Sungeun Hong, Donghyeon Cho, Hyoungseob Park, Priyadarshini Panda.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.01524)] [[Github](https://github.com/youngryan1993/SFDA-Domain-Adaptation-without-Source-Data)]

**Few-Shot Learning as Domain Adaptation: Algorithm and Analysis.**<br>
*Jiechao Guan, Zhiwu Lu, Tao Xiang, Ji-Rong Wen.*<br>
ICML 2020. [[PDF](https://arxiv.org/abs/2002.02050)] [[Github](https://github.com/JiechaoGuan/FSL-DAPNA)]

**AINDNet: Transfer Learning from Synthetic to Real-Noise Denoising with Adaptive Instance Normalization.**<br>
*Yoonsik Kim, Jae Woong Soh, Gu Yong Park, Nam Ik Cho.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2002.11244)] [[Github](https://github.com/terryoo/AINDNet)]

**Ear2Face: Deep Biometric Modality Mapping.**<br>
*Dogucan Yaman, Fevziye Irem Eyiokur, Hazım Kemal Ekenel.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2006.01943)] [[Github](https://github.com/yamand16/ear2face)]

**Domain Conditioned Adaptation Network.**<br>
*Shuang Li, Chi Harold Liu, Qiuxia Lin, Binhui Xie, Zhengming Ding, Gao Huang, Jian Tang.*<br>
AAAI 2020. [[PDF](https://arxiv.org/abs/2005.06717)] [[Github](https://github.com/wvangansbeke/Unsupervised-Classification)]

**Unsupervised Intra-domain Adaptation for Semantic Segmentation through Self-Supervision.**<br>
*Fei Pan, Inkyu Shin, Francois Rameau, Seokju Lee, In So Kweon.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.07703)] [[Github](https://github.com/feipan664/IntraDA)]

**Learning Texture Invariant Representation for Domain Adaptation of Semantic Segmentation.**<br>
*Myeongjin Kim, Hyeran Byun.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.00867)]