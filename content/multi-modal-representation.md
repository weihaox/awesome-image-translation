# Multi-modal Representation

This repository is about Multi-modal Representation Learning and Application.

## Table of Contents
- [Unsupervised Visual Representation Learning](#unsupervised-visual-representation-learning)
- [Spatiotemporal Representation Learning](#spatiotemporal-representation-learning)
- [Multi-modal Representation Learning and Application](#multi-modal-representation-learning-and-application)
  * [Multimodal Representation](#multimodal-representation)
  * [Visual Representation Learning](#visual-representation-learning)
  * [Audio Representation](#audio-representation)
  * [Image-Text Matching (Visual-Semantic/Lingustic Embedding)](#image-text-matching--visual-semantic-lingustic-embedding-)
  * [Audio-Visual Learning](#audio-visual-learning)
- [Multi-Modality Translation](#multi-modality-translation)
  * [Others-to-3D](#others-to-3d)
  * [Image-to-Video](#image-to-video)
  * [Text-and-Video](#text-and-video)
  * [Image-to-Text](#image-to-text)
  * [Text-to-Image](#text-to-image)
  * [Speech-and-Text](#speech-and-text)
  * [Image-and-Voice](#image-and-voice)
  * [Voice-to-Voice](#voice-to-voice)
  * [Scene Graph Generation](#scene-graph-generation)
  * [Speech Synthesis](#speech-synthesis)

## Unsupervised Visual Representation Learning

**VideoMoCo: Contrastive Video Representation Learning with Temporally Adversarial Examples.**<br>
*Tian Pan, Yibing Song, Tianyu Yang, Wenhao Jiang, Wei Liu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.05905)]

**Propagate Yourself: Exploring Pixel-Level Consistency for Unsupervised Visual Representation Learning.**<br>
*Zhenda Xie, Yutong Lin, Zheng Zhang, Yue Cao, Stephen Lin, Han Hu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2011.10043)] [[Github](https://github.com/lucidrains/pixel-level-contrastive-learning)]

**VinVL: Making Visual Representations Matter in Vision-Language Models.**<br>
*Pengchuan Zhang, Xiujun Li, Xiaowei Hu, Jianwei Yang, Lei Zhang, Lijuan Wang, Yejin Choi, Jianfeng Gao.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.00529)]

**Learning Spatiotemporal Features via Video and Text Pair Discrimination.**<br>
*Tianhao Li, [Limin Wang](https://wanglimin.github.io/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2001.05691)] [[Github](https://github.com/MCG-NJU/CPD-Video)]

**(BYOL) Bootstrap your own latent: A new approach to self-supervised Learning.**<br>
*Jean-Bastien Grill, Florian Strub, Florent Altché, Corentin Tallec, Pierre H. Richemond, Elena Buchatskaya, Carl Doersch, Bernardo Avila Pires, Zhaohan Daniel Guo, Mohammad Gheshlaghi Azar, Bilal Piot, Koray Kavukcuoglu, Rémi Munos, Michal Valko.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.07733)]

**SimCLRv2: Big Self-Supervised Models are Strong Semi-Supervised Learners.**<br>
*Ting Chen, Simon Kornblith, Kevin Swersky, Mohammad Norouzi, Geoffrey Hinton.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.10029)] [[Github](https://github.com/google-research/simclr)]

**SimCLR: A Simple Framework for Contrastive Learning of Visual Representations.**<br>
*Ting Chen, Simon Kornblith, Mohammad Norouzi, Geoffrey Hinton.*<br>
ICML 2020. [[PDF](https://arxiv.org/abs/2002.05709)] [[Github](https://github.com/google-research/simclr)]

**MoCov3: An Empirical Study of Training Self-Supervised Vision Transformers.**<br>
*Xinlei Chen, Saining Xie, Kaiming He.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2104.02057)]

**MoCov2: Improved Baselines with Momentum Contrastive Learning.**<br>
*Xinlei Chen, Haoqi Fan, Ross Girshick, Kaiming He.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2003.04297)]

**MoCo: Momentum Contrast for Unsupervised Visual Representation Learning.**<br>
*Kaiming He, Haoqi Fan, Yuxin Wu, Saining Xie, Ross Girshick.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/1911.05722)] [[Github](https://github.com/facebookresearch/moco)]

## Spatiotemporal Representation Learning

**SlowFast: A Large-Scale Study on Unsupervised Spatiotemporal Representation Learning.**<br>
*Christoph Feichtenhofer, Haoqi Fan, Bo Xiong, Ross Girshick, Kaiming He.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.14558)] [[Github](https://github.com/facebookresearch/SlowFast)]
  
## Multi-modal Representation Learning and Application

### Multimodal Representation

**VATT: Transformers for Multimodal Self-Supervised Learning from Raw Video, Audio and Text.**<br>
*Hassan Akbari, Linagzhe Yuan, Rui Qian, Wei-Hong Chuang, Shih-Fu Chang, Yin Cui, Boqing Gong.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2104.11178)] 

### Visual Representation Learning

**Unsupervised Visual Representation Learning by Tracking Patches in Video.**<br>
*Guangting Wang, Yizhou Zhou, Chong Luo, Wenxuan Xie, Wenjun Zeng, Zhiwei Xiong.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2105.02545)] [[Github](github.com/microsoft/CtP)]

**SEER: Self-supervised Pretraining of Visual Features in the Wild.**<br>
*Priya Goyal, Mathilde Caron, Benjamin Lefaudeux, Min Xu, Pengchao Wang, Vivek Pai, Mannat Singh, Vitaliy Liptchinsky, Ishan Misra, Armand Joulin, Piotr Bojanowski.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.01988)]

**VirTex: Learning Visual Representations from Textual Annotations.**<br>
*Karan Desai, Justin Johnson.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2006.06666)] [[Github](https://github.com/kdexd/virtex)]

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

### Audio Representation

**Contrastive Learning of Musical Representations.**<br>
*Janne Spijkervet, John Ashley Burgoyne.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.09410)]

**Contrastive Learning of General-Purpose Audio Representations.**<br>
*Aaqib Saeed, David Grangier, Neil Zeghidour.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.10915)]

### Image-Text Matching (Visual-Semantic/Lingustic Embedding)

[a collection of Image-Text Matching (Visual-Semantic/Lingustic Embedding)](https://blog.csdn.net/weixin_42/article/details/104275300)

**Seeing Out of tHe bOx: End-to-End Pre-training for Vision-Language Representation Learning.**<br>
*Zhicheng Huang, Zhaoyang Zeng, Yupan Huang, Bei Liu, Dongmei Fu, Jianlong Fu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.03135)]

**Learning Multimodal Affinities for Textual Editing in Images.**<br>
*Or Perel, Oron Anschel, Omri Ben-Eliezer, Shai Mazor, Hadar Averbuch-Elor.*<br>
SIGGRAPH 2021. [[PDF](https://arxiv.org/abs/2103.10139)]

**Conceptual 12M: Pushing Web-Scale Image-Text Pre-Training To Recognize Long-Tail Visual Concepts.**<br>
*Soravit Changpinyo, Piyush Sharma, Nan Ding, Radu Soricut.*<br>
CVPR 2021. [[PDF](https://arxiv.org/pdf/2102.08981.pdf)]

**ALIGN: Scaling Up Visual and Vision-Language Representation Learning With Noisy Text Supervision.**<br>
*Chao Jia, Yinfei Yang, Ye Xia, Yi-Ting Chen, Zarana Parekh, Hieu Pham, Quoc V. Le, Yunhsuan Sung, Zhen Li, Tom Duerig.*<br>
ICML 2021. [[PDF](https://arxiv.org/abs/2102.05918)] [[Github]()]

**CLIP: Learning Transferable Visual Models From Natural Language Supervision.**<br>
*Alec Radford, Jong Wook Kim, Chris Hallacy, Aditya Ramesh, Gabriel Goh, Sandhini Agarwal, Girish Sastry, Amanda Askell, Pamela Mishkin, Jack Clark, Gretchen Krueger, Ilya Sutskever.*<br>
2021. [[PDF](https://cdn.openai.com/papers/Learning_Transferable_Visual_Models_From_Natural_Language.pdf)] [[Github](https://github.com/openai/CLIP)] [[Blog](https://openai.com/blog/clip/)]

**Less is More: ClipBERT for Video-and-Language Learning via Sparse Sampling.**<br>
*[Jie Lei](http://www.cs.unc.edu/~jielei/), [Linjie Li](https://www.linkedin.com/in/linjie-li/), [Luowei Zhou](https://luoweizhou.github.io/), [Zhe Gan](https://zhegan27.github.io/), [Tamara L. Berg](http://tamaraberg.com/), [Mohit Bansal](http://www.cs.unc.edu/~mbansal/), [Jingjing Liu](https://www.linkedin.com/in/jingjing-liu-65703431/).*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2102.06183)] [[Github](https://github.com/jayleicn/ClipBERT)]

**Learning to Represent Image and Text with Denotation Graph.**<br>
*[Bowen Zhang](https://zbwglory.github.io/), Hexiang Hu, Vihan Jain, Eugene Ie, [Fei Sha](http://www-bcf.usc.edu/~feisha/).*<br>
EMNLP 2020, [[PDF](https://arxiv.org/abs/2010.02949)] [[Project](https://sha-lab.github.io/DG)]

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

**Representation Learning via Invariant Causal Mechanisms.**<br>
*Jovana Mitrovic, Brian McWilliams, Jacob Walker, Lars Buesing, Charles Blundell.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.07922)] 

**Learning Visual Representations for Transfer Learning by Suppressing Texture.**<br>
*Shlok Mishra, Anshul Shah, Ankan Bansal, Jonghyun Choi, Abhinav Shrivastava, Abhishek Sharma, David Jacobs.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.01901)]

### Audio-Visual Learning

**Spoken Moments: Learning Joint Audio-Visual Representations from Video Descriptions.**<br> 
*Mathew Monfort, SouYoung Jin, Alexander Liu, David Harwath, Rogerio Feris, James Glass, Aude Oliva.*<br> 
CVPR 2021. [[PDF](https://arxiv.org/abs/2105.04489)]

**Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation.**<br> 
*Hang Zhou, Yasheng Sun, Wayne Wu, Chen Change Loy, Xiaogang Wang, Ziwei Liu.*<br> 
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.11116)] [[Github](https://github.com/Hangz-nju-cuhk/Talking-Face_PC-AVS)] [[Project](https://hangz-nju-cuhk.github.io/projects/PC-AVS)]

**EVP: Audio-Driven Emotional Video Portraits.**<br> 
*[Xinya Ji](https://jixinya.github.io), [Hang Zhou](https://hangz-nju-cuhk.github.io/), Kaisiyuan Wang, Wayne Wu, Chen Change Loy, Xun Cao, Feng Xu.*<br> 
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.07452)] [[Project](https://jixinya.github.io/projects/evp/)] [[Github](https://github.com/jixinya/EVP/)]

**Looking into Your Speech: Learning Cross-modal Affinity for Audio-visual Speech Separation.**<br> 
*Jiyoung Lee, Soo-Whan Chung, Sunok Kim, Hong-Goo Kang, Kwanghoon Sohn.*<br> 
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.02775)] [[Project](https://caffnet.github.io/)]

**Seeking the Shape of Sound: An Adaptive Framework for Learning Voice-Face Association.**<br> 
*Peisong Wen, Qianqian Xu, Yangbangyan Jiang, Zhiyong Yang, Yuan He, Qingming Huang.*<br> 
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.07293)]

**Strumming to the Beat: Audio-Conditioned Contrastive Video Textures.**<br>
*[Medhini Narasimhan](https://people.eecs.berkeley.edu/~medhini/), [Shiry Ginosar](https://people.eecs.berkeley.edu/~shiry/), [Andrew Owens](http://andrewowens.com/), [Alexei A. Efros](https://people.eecs.berkeley.edu/~efros/), [Trevor Darrell](https://people.eecs.berkeley.edu/~trevor/).*<br>
arxiv 2021. [[PDF](https://medhini.github.io/audio_video_textures/)] [[Project](https://medhini.github.io/audio_video_textures)] [[Github](https://github.com/medhini/audio-video-textures)]

**Localizing Visual Sounds the Hard Way.**<br>
*Honglie Chen, Weidi Xie, Triantafyllos Afouras, Arsha Nagrani, Andrea Vedaldi, Andrew Zisserman.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.02691)] [[Project](http://www.robots.ox.ac.uk/~vgg/research/lvs/)]

**VisualVoice: Audio-Visual Speech Separation with Cross-Modal Consistency.**<br>
*[Ruohan Gao](https://arxiv.org/pdf/2101.03149.pdf), Kristen Grauman.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2101.03149)] [[Project](http://vision.cs.utexas.edu/projects/VisualVoice/)]

**Can audio-visual Integration Strengthen robustness under multimodal attacks?**<br>
*[Yapeng Tian](http://yapengtian.org/) and Chenliang Xu.*<br>
CVPR 2021.  [[PDF](https://arxiv.org/pdf/2104.02000.pdf)]  [[Github](https://github.com/YapengTian/AV-Robustness-CVPR21)]
  
**Cyclic Co-Learning of Sounding Object Visual Grounding and Sound Separation.**<br>
*Yapeng Tian, Di Hu, and Chenliang Xu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.02026)] [[Github](https://github.com/YapengTian/CCOL-CVPR21)]

**Universal MelGAN: A Robust Neural Vocoder for High-Fidelity Waveform Generation in Multiple Domains.**<br>
*Won Jang, Dan Lim, Jaesam Yoon.*<br>
ICASSP 2021. [[PDF](https://arxiv.org/abs/2011.09631)]

**Unsupervised Audiovisual Synthesis via Exemplar Autoencoders.**<br> 
*Kangle Deng, Aayush Bansal, Deva Ramanan.*<br>
ICLR, 2021. [[PDF](https://openreview.net/pdf?id=43VKWxg_Sqr)]

**Visual Speech Enhancement Without A Real Visual Stream.**<br>
*Sindhu B Hegde, K R Prajwal, Rudrabha Mukhopadhyay, Vinay Namboodiri, C.V. Jawahar.*<br>
WACV 2021. [[PDF](https://arxiv.org/abs/2012.10852)] [[Project](http://cvit.iiit.ac.in/research/projects/cvit-projects/visual-speech-enhancement-without-a-real-visual-stream)] [[Github](https://github.com/Sindhu-Hegde/pseudo-visual-speech-denoising)]

**Deep Audio-Visual Learning: A Survey.**<br>
*Hao Zhu, Mandi Luo, Rui Wang, Aihua Zheng, Ran He.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2001.04758)]

**Unsupervised Any-to-Many Audiovisual Synthesis via Exemplar Autoencoders.**<br>
*[Kangle Deng](https://dunbar12138.github.io/), [Aayush Bansal](http://www.cs.cmu.edu/~aayushb/), [Deva Ramanan](https://www.cs.cmu.edu/~deva/).*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2001.04463)] [[Project](https://dunbar12138.github.io/projectpage/Audiovisual/index.html)]

**AudioViewer: Learning to Visualize Sound.**<br>
*Yuchi Zhang, Willis Peng, Bastian Wandt, Helge Rhodin.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.13341)]

**Multi-Instrumentalist Net: Unsupervised Generation of Music from Body Movements.**<br>
*Kun Su, Xiulong Liu, Eli Shlizerman.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2012.03478)] [[Video](https://www.youtube.com/watch?v=yo5OZKBbBh4)]

**Everybody Sign Now: Translating Spoken Language to Photo Realistic Sign Language Video.**<br>
*Ben Saunders, Necati Cihan Camgoz, Richard Bowden.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2011.09846)]

**S2IGAN: Speech-to-Image Generation via Adversarial Learning.**<br>
*Xinsheng Wang, Tingting Qiao, Jihua Zhu, Alan Hanjalic, Odette Scharenborg.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2005.06968)]

**Show and Speak: Directly Synthesize Spoken Description of Images.**<br>
*Xinsheng Wang, Siyuan Feng, Jihua Zhu, Mark Hasegawa-Johnson, Odette Scharenborg.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.12267)]

**Latent Vector Recovery of Audio GANs.**<br>
*Andrew Keyes, Nicky Bayat, Vahid Reza Khazaie, Yalda Mohsenzadeh.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2010.08534)]

**DanceIt: Music-inspired Dancing Video Synthesis.**<br>
*Xin Guo, Jia Li, Yifan Zhao.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2009.08027)]

**Attention-based Residual Speech Portrait Model for Speech to Face Generation.**<br>
*Jianrong Wang, Xiaosheng Hu, Li Liu, Wei Liu, Mei Yu, Tianyi Xu.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2007.04536)]

**Vector Quantized Contrastive Predictive Coding for Template-based Music Generation.**<br>
*Gaëtan Hadjeres, Léopold Crestel.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/2004.10120)] [[Github](https://github.com/SonyCSLParis/vqcpc-bach)]

**Lets Play Music: Audio-driven Performance Video Generation.**<br>
*Hao Zhu, Yi Li, Feixia Zhu, Aihua Zheng, Ran He.*<br>
ICPR 2020. [[PDF](https://arxiv.org/abs/2011.02631)]

**Learning Representations from Audio-Visual Spatial Alignment.**<br>
*Pedro Morgado, Yi Li, Nuno Vasconcelos.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2011.01819)]

**Learning Individual Speaking Styles for Accurate Lip to Speech Synthesis.**<br>
*K R Prajwal, Rudrabha Mukhopadhyay, Vinay Namboodiri, C V Jawahar.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2005.08209)] [[Github](https://github.com/Rudrabha/Lip2Wav)]

**Music Gesture for Visual Sound Separation.**<br>
*Chuang Gan, Deng Huang, Hang Zhao, Joshua B. Tenenbaum, Antonio Torralba.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.09476)] [[Project](http://music-gesture.csail.mit.edu/)]

**Foley Music: Learning to Generate Music from Videos.**<br>
*Chuang Gan, Deng Huang, Peihao Chen, Joshua B. Tenenbaum, Antonio Torralba.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.10984)] [[Project](http://foley-music.csail.mit.edu/)]

**Crossing You in Style: Cross-modal Style Transfer from Music to Visual Arts.**<br>
*Cheng-Che Lee, Wan-Yi Lin, Yen-Ting Shih, Pei-Yi Patricia Kuo, Li Su.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2009.08083)] [[Github](https://github.com/SunnerLi/Cross-you-in-style)][[project](https://sunnerli.github.io/Cross-you-in-style/)] [[Dataset](https://github.com/SunnerLi/Cross-you-in-style#)]

**Co-Separating Sounds of Visual Objects.**<br>
*Ruohan Gao, Kristen Grauman.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1904.07750)] [[Github](https://github.com/rhgao/co-separation)] [[Project](http://vision.cs.utexas.edu/projects/coseparation/)]

**The Sound of Motions.**<br>
*[Hang Zhao](http://people.csail.mit.edu/hangzhao/), Chuang Gan, Wei-Chiu Ma, Antonio Torralba.*<br>
ICCV 2019. [[PDF](https://arxiv.org/pdf/1904.05979.pdf)]

**Vision-Infused Deep Audio Inpainting.**<br>
*[Hang Zhou](https://hangz-nju-cuhk.github.io/), [Ziwei Liu](https://liuziwei7.github.io/), [Xudong Xu](https://sheldontsui.github.io/), [Ping Luo](http://luoping.me/), [Xiaogang Wang](http://www.ee.cuhk.edu.hk/~xgwang/).*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1910.10997)] [[project](https://hangz-nju-cuhk.github.io/projects/AudioInpainting)] [[Github](https://github.com/Hangz-nju-cuhk/Vision-Infused-Audio-Inpainter-VIAI)] [[MUSICES Datasets](https://hangz-nju-cuhk.github.io/projects/audio-inpainting/MUSICES.json)]

**Speech2Face: Learning the Face Behind a Voice.**<br>
*Tae-Hyun Oh, Tali Dekel, Changil Kim, Inbar Mosseri, William T. Freeman, Michael Rubinstein, Wojciech Matusik.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1905.09773)] [[project](https://speech2face.github.io/)] [[Related Work](https://speech2face.github.io/)]

**2.5D Visual Sound.**<br>
*[Ruohan Gao](https://www.cs.utexas.edu/~rhgao/), [Kristen Grauman](http://www.cs.utexas.edu/~grauman/).*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1812.04204)] [[Project](http://vision.cs.utexas.edu/projects/2.5D_visual_sound/https://github.com/facebookresearch/2.5D-Visual-Sound)] [[Github](https://github.com/facebookresearch/2.5D-Visual-Sound)]

**Objects that Sound.**<br>
*Relja Arandjelovi´c, Andrew Zisserman.*<br>
ECCV 2018. [[PDF](https://arxiv.org/pdf/1712.06651.pdf)]

**The Sound of Pixels.**<br>
*Hang Zhao, Chuang Gan, Andrew Rouditchenko, Carl Vondrick, Josh McDermott, Antonio Torralba.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1804.03160)] [[Project](http://sound-of-pixels.csail.mit.edu/)] [[Github](https://github.com/hangzhaomit/Sound-of-Pixels)] [[MUSIC_dataset](https://github.com/roudimit/MUSIC_dataset)]

**Self-Supervised Generation of Spatial Audio for 360 Video.**<br>
*Pedro Morgado, Nuno Vasconcelos, Timothy Langlois, Oliver Wang.*<br>
NIPS 2018. [[PDF](https://arxiv.org/abs/1809.02587)]

**Shape and Material from Sound.**<br>
*Zhoutong Zhang, Qiujia Li, Zhengjia Huang, Jiajun Wu, Joshua B. Tenenbaum, William T. Freeman.*<br>
NeurIPS 2017. [[PDF](https://jiajunwu.com/papers/fastsound_nips.pdf)] [[Project](http://sound.csail.mit.edu/)]

## Multi-Modality Translation

[[Eurus-Holmes/Awesome-Multimodal-Research](https://github.com/Eurus-Holmes/Awesome-Multimodal-Research)]</br>
[[pliang279/awesome-multimodal-ml](https://github.com/pliang279/awesome-multimodal-ml)]</br>

### Music to Dance

**ChoreoMaster: Choreography-Oriented Music-Driven Dance Synthesis.**<br>
*Chen Kang, Zhipeng Tan, Jin Lei, Song-Hai Zhang, Yuan-Chen Guo, Weidong Zhang, Shi-Min Hu.*<br>
SIGGRAPH 2021. [[PDF]()] [[Video](https://www.youtube.com/watch?v=V8MlYa_yhF0)]

**ChoreoNet: Towards Music to Dance Synthesis with Choreographic Action Unit.**<br>
*Zijie Ye, Haozhe Wu, Jia Jia, Yaohua Bu, Wei Chen, Fanbo Meng, Yanfeng Wang.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2009.07637)]

**Self-supervised Dance Video Synthesis Conditioned on Music.**<br>
(**Music-oriented Dance Video Synthesis with Pose Perceptual Loss.**<br>)
*[Xuanchi Ren](https://xuanchiren.com/), Haoran Li, Zijian Huang, Qifeng Chen.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/1912.06606)] [[Github](https://github.com/xrenaa/Music-Dance-Video-Synthesis)]

### Others-to-3D

**Learn to Dance with AIST++: Music Conditioned 3D Dance Generation.**<br>
*Ruilong Li, Shan Yang, David A. Ross, Angjoo Kanazawa.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.08779)] [[Project](https://google.github.io/aichoreographer/)] [[Code](https://google.github.io/aistplusplus_dataset/)]

### Image-to-Video

**Understanding Object Dynamics for Interactive Image-to-Video Synthesis.**<br>
*Andreas Blattmann, Timo Milbich, Michael Dorkenwald, Björn Ommer.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2106.11303)] [[Project](https://bit.ly/3cxfA2L)]

**Image-to-Video Generation via 3D Facial Dynamics.**<br>
*Xiaoguang Tu, Yingtian Zou, Jian Zhao, Wenjie Ai, Jian Dong, Yuan Yao, Zhikang Wang, Guodong Guo, Zhifeng Li, Wei Liu, Jiashi Feng.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2105.14678)]

**Stochastic Image-to-Video Synthesis using cINNs.**<br>
*Michael Dorkenwald, Timo Milbich, Andreas Blattmann, Robin Rombach, Konstantinos G. Derpanis, Björn Ommer.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2105.04551)]

**Dual-MTGAN: Stochastic and Deterministic Motion Transfer for Image-to-Video Synthesis.**<br>
*Fu-En Yang, Jing-Cheng Chang, Yuan-Hao Lee, Yu-Chiang Frank Wang.*<br>
ICPR 2020. [[PDF](https://arxiv.org/abs/2102.13329)]

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

### Text-and-Video

**GODIVA: Generating Open-DomaIn Videos from nAtural Descriptions.**<br>
*Chenfei Wu, Lun Huang, Qianxi Zhang, Binyang Li, Lei Ji, Fan Yang, Guillermo Sapiro, Nan Duan.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2104.14806)]

**The Role of the Input in Natural Language Video Description.**<br>
*Silvia Cascianelli, Gabriele Costante, Alessandro Devo, Thomas A. Ciarfuglia, Paolo Valigi, Mario L. Fravolini.*<br>
TMM 2019. [[PDF](https://arxiv.org/abs/2102.05067)]

**Video Generation From Text.**<br>
*Yitong Li, Martin Renqiang Min, Dinghan Shen, David Carlson, Lawrence Carin.*<br>
arxiv 2020. [[PDF](https://arxiv.org/abs/1710.00421)]

**TiVGAN: Text to Image to Video Generation with Step-by-Step Evolutionary Generator.**<br>
*Doyeon Kim, Donggyu Joo, Junmo Kim.*<br>
IEEE Access 2020. [[PDF](https://arxiv.org/abs/2009.02018)]

**IRC-GAN: Introspective Recurrent Convolutional GAN for Text-to-video Generation.**<br>
*[Kangle Deng](https://dunbar12138.github.io/), Tianyi Fei, Xin Huang, Yuxin Peng.*<br>
IJCAI 2019. [[PDF](https://www.ijcai.org/proceedings/2019/0307.pdf)]

### Image-to-Text

**Dependent Multi-Task Learning with Causal Intervention for Image Captioning.**<br>
*Wenqing Chen, Jidong Tian, Caoyun Fan, Hao He, Yaohui Jin.*<br>
IJCAI 2021. [[PDF](https://arxiv.org/abs/2105.08573)]

**Towards Accurate Text-based Image Captioning with Content Diversity Exploration.**<br>
*Guanghui Xu, Shuaicheng Niu, Mingkui Tan, Yucheng Luo, Qing Du, Qi Wu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2105.03236)]

**Scan2Cap: Context-aware Dense Captioning in RGB-D Scans.**<br>
*Dave Zhenyu Chen, Ali Gholami, Matthias Nießner, Angel X. Chang.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2012.02206)] [[Github](https://github.com/daveredrum/Scan2Cap)] [[Project](https://daveredrum.github.io/Scan2Cap/)] [[Video](https://youtu.be/AgmIpDbwTCY)]

**Automatic Comic Generation with Stylistic Multi-page Layouts and Emotion-driven Text Balloon Generation.**<br>
*Xin Yang, Zongliang Ma, Letian Yu, Ying Cao, Baocai Yin, Xiaopeng Wei, Qiang Zhang, Rynson W.H. Lau.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.11111)]

**VisualGPT: Data-efficient Image Captioning by Balancing Visual Input and Linguistic Knowledge from Pretraining.**<br>
*Jun Chen, Han Guo, Kai Yi, Boyang Li, Mohamed Elhoseiny.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.10407)] [[Github](https://github.com/Vision-CAIR/VisualGPT)]

**SG2Caps: Revisiting Scene Graphs for Image Captioning.**<br>
*Subarna Tripathi, Kien Nguyen, Tanaya Guha, Bang Du, Truong Q. Nguyen.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2102.04990)]

**Vx2Text: End-to-End Learning of Video-Based Text Generation From Multimodal Inputs.**<br>
*Xudong Lin, Gedas Bertasius, Jue Wang, Shih-Fu Chang, Devi Parikh, Lorenzo Torresani.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.12059)]

**CPTR: Full Transformer Network for Image Captioning.**<br>
*Wei Liu, Sihan Chen, Longteng Guo, Xinxin Zhu, Jing Liu.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.10804)]

**ArtEmis: Affective Language for Visual Art.**<br>
*Panos Achlioptas, Maks Ovsjanikov, Kilichbek Haydarov, Mohamed Elhoseiny, Leonidas Guibas.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.07396)] [[Project](https://artemisdataset.org/)]

**XMC-GA: Cross-Modal Contrastive Learning for Text-to-Image Generation.**<br>
*Han Zhang, Jing Yu Koh, Jason Baldridge, Honglak Lee, Yinfei Yang.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2101.04702)]

**Semantic Grouping Network for Video Captioning.**<br>
*Hobin Ryu, Sunghun Kang, Haeyong Kang, Chang D. Yoo.*<br>
AAAI 2021. [[PDF](https://arxiv.org/abs/2102.00831)]

**Dual-Level Collaborative Transformer for Image Captioning.**<br>
*Yunpeng Luo, Jiayi Ji, Xiaoshuai Sun, Liujuan Cao, Yongjian Wu, Feiyue Huang, Chia-Wen Lin, Rongrong Ji.*<br>
AAAI 2021. [[PDF](https://arxiv.org/abs/2101.06462)]

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

**Entangled Transformer for Image Captioning.**<br>
*Guang Li Linchao Zhu Ping Liu Yi Yang.*<br>
ICCV 2019. [[PDF](https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Entangled_Transformer_for_Image_Captioning_ICCV_2019_paper.pdf)]

**Inverse Cooking: Recipe Generation from Food Images.**<br>
*Amaia Salvador, Michal Drozdzal, Xavier Giro-i-Nieto, Adriana Romero.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1812.06164)]

**Intention Oriented Image Captions with Guiding Objects.**<br>
*Yue Zheng, Yali Li, Shengjin Wang.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1811.07662)] 

### Text-to-Image

**Learning by Planning: Language-Guided Global Image Editing.**<br>
*Jing Shi, Ning Xu, Yihang Xu, Trung Bui, Franck Dernoncourt, Chenliang Xu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2106.13156)]

**MOC-GAN: Mixing Objects and Captions to Generate Realistic Images.**<br>
*Tao Ma, Yikang Li.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2106.03128)]

**Language-Driven Image Style Transfer.**<br>
*Tsu-Jui Fu, Xin Eric Wang, William Yang Wang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/pdf/2106.00178.pdf)]

**CogView: Mastering Text-to-Image Generation via Transformers.**<br>
*Ming Ding, Zhuoyi Yang, Wenyi Hong, Wendi Zheng, Chang Zhou, Da Yin, Junyang Lin, Xu Zou, Zhou Shao, Hongxia Yang, Jie Tang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2105.13290)] [[Github](https://github.com/THUDM/CogView)] [[Demo](https://lab.aminer.cn/cogview/index.html)]

**Paint by Word.**<br>
*David Bau, Alex Andonian, Audrey Cui, YeonHwan Park, Ali Jahanian, Aude Oliva, Antonio Torralba.*<br>
arxiv 2021. [[PDF](https://arxiv.org/pdf/2103.10951)]

**StyleCLIP: Text-Driven Manipulation of StyleGAN Imagery.**<br>
*Or Patashnik, Zongze Wu, Eli Shechtman, Daniel Cohen-Or, Dani Lischinski.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.17249)] [[Github](https://github.com/orpatashnik/StyleCLIP)]

**RefContrast: Understanding Synonymous Referring Expressions via Contrastive Features.**<br>
*Yi-Wen Chen, Yi-Hsuan Tsai, Ming-Hsuan Yang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2104.10156)] [[Github](https://github.com/wenz116/RefContrast)]

**ClawCraneNet: Leveraging Object-level Relation for Text-based Video Segmentation.**<br>
*Chen Liang, Yu Wu, Yawei Luo, Yi Yang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2103.10702)]

**Towards More Flexible and Accurate Object Tracking with Natural Language: Algorithms and Benchmark.**<br>
*Xiao Wang, Xiujun Shu, Zhipeng Zhang, Bo Jiang, Yaowei Wang, Yonghong Tian, Feng Wu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.16746)]

**DALL-E: Zero-Shot Text-to-Image Generation.**<br>
*Aditya Ramesh, Mikhail Pavlov, Gabriel Goh, Scott Gray, Chelsea Voss, Alec Radford, Mark Chen, Ilya Sutskever.*<br>
ICML 2021. [[PDF](https://arxiv.org/abs/2102.12092)] [[Blog](https://openai.com/blog/dall-e/)] [[Github](https://github.com/openai/DALL-E)]

**Semantic Object Accuracy for Generative Text-to-Image Synthesis.**<br>
*Tobias Hinz, Stefan Heinrich, Stefan Wermter.*<br>
TPAMI 2020. [[PDF](https://ieeexplore.ieee.org/document/9184960/authors#authors)] [[Github](https://github.com/tohinz/semantic-object-accuracy-for-generative-text-to-image-synthesis)]

**Adversarial Text-to-Image Synthesis: A Review.**<br>
*Stanislav Frolov, Tobias Hinz, Federico Raue, Jörn Hees, Andreas Dengel.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.09983)]

**Cross-Modal Contrastive Learning for Text-to-Image Generation.**<br>
*Han Zhang, Jing Yu Koh, Jason Baldridge, Honglak Lee, Yinfei Yang.*<br>
arxiv 2021. [[PDF](https://arxiv.org/abs/2101.04702)]

**TediGAN: Text-Guided Diverse Image Generation and Manipulation.**<br>
*Weihao Xia, Yujiu Yang, Jing-Hao Xue, Baoyuan Wu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2012.03308)] [[Data](https://github.com/weihaox/Multi-Modal-CelebA-HQ)] [[Github](https://github.com/weihaox/TediGAN)]

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

**Flowtron: an Autoregressive Flow-based Generative Network for Text-to-Speech Synthesis.**<br>  
*Rafael Valle, Kevin J. Shih, Ryan Prenger, Bryan Catanzaro.*<br> 
ICLR 2021. [[PDF](https://openreview.net/pdf?id=Ig53hpHxS4)]

**Bidirectional Variational Inference for Non-Autoregressive Text-to-Speech.**<br>  
*Yoonhyung Lee, Joongbo Shin, Kyomin Jung.*<br> 
ICLR 2021. [[PDF](https://openreview.net/pdf?id=o3iritJHLfO)]

**FastSpeech 2: Fast and High-Quality End-to-End Text to Speech.**<br> 
*Yi Ren, Chenxu Hu, Xu Tan, Tao Qin, Sheng Zhao, Zhou Zhao, Tie-Yan Liu.*<br>
ICLR 2021. [[PDF](https://openreview.net/pdf?id=piLPYqxtWuA)]

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

See Audio-Visual Representations

**Voice2Mesh: Cross-Modal 3D Face Model Generation from Voices.**<br>
*Cho-Ying Wu, Ke Xu, Chin-Cheng Hsu, Ulrich Neumann.*<br>
arxiv 2201. [[PDF](https://arxiv.org/abs/2104.10299)] [[Project](https://choyingw.github.io/works/Voice2Mesh/index.html)]

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

### Speech Synthesis

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