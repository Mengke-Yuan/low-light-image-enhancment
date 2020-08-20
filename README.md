# low-light-image-enhancment
Related paper and code list

This repository is the collection of low light image enhancement methods and resources. 

We will focus on papers with new perspectives/tools/datasets/records. 

Feel free to contribute to this list, recommend readed paper/code/resources and share your comments.

## Category
- [Methods](#Methods)
    - [Representative Methods with Codes](#)
    - [Beneficial References](#)
- [Datasets]()
- [People/Groups](#People/Groups)
- [Sorted by venue and publication time]
    - [Conference]
    - [Journal]
- [Related topics and resources]()
    - [Image denoising]
    - [Open datasets]


## Methods

### Representative Methods with Codes
- LIME: Low-light Image Enhancement viaIllumination Map Estimation [[Code](https://sites.google.com/view/xjguo/lime), [Paper](http://www.dabi.temple.edu/~hbling/publication/LIME-tip.pdf)]
    - Xiaojie Guo, Yu Li, and Haibin Ling. IEEE Transactions on image processing (TIP). 2016.
- Learning to See in the Dark [[Project](https://cchen156.github.io/SID.html), [Code](https://github.com/cchen156/Learning-to-See-in-the-Dark), [Paper](https://cchen156.github.io/paper/18CVPR_SID.pdf)]
    - Chen Chen, Qifeng Chen, Jia Xu and Vladlen Koltun. IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2018
- Learning a Deep Single Image Contrast Enhancer from Multi-Exposure Images (SICE) [[Code](https://github.com/csjcai/SICE), [Paper](http://www4.comp.polyu.edu.hk/~cslzhang/paper/SICE.pdf)]
    - Jianrui Cai, Shuhang Gu, Lei Zhang, IEEE TRANSACTIONS ON IMAGE PROCESSING(TIP), 2018
- Deep Retinex Decomposition for Low-Light Enhancement (RetinexNet) [[Project](https://daooshee.github.io/BMVC2018website/), [Code](https://github.com/weichen582/RetinexNet), [Paper](https://github.com/daooshee/BMVC2018website/blob/master/chen_bmvc18.pdf)]
    - Chen Wei,Wenjing Wang,Wenhan Yang,Jiaying Liu,The British Machine Vision Conference (BMVC), 2018
- MBLLEN: Low-light Image/Video Enhancement Using CNNs [[Project](http://phi-ai.org/project/MBLLEN/default.htm), [Code](https://github.com/Lvfeifan/MBLLEN), [Paper](http://bmvc2018.org/contents/papers/0700.pdf)]
    - Feifan Lv, Feng Lu, Jianhua Wu and Chongsoon Lim, BMVC,2018
- Kindling the Darkness: a Practical Low-light Image Enhancer [[Code](https://github.com/zhangyhuaee/KinD_plus), [Paper](https://dl.acm.org/doi/10.1145/3343031.3350926)]
    - Yonghua Zhang, Jiawan Zhang, Xiaojie Guo, ACM MultiMedia(MM), 2019
- EnlightenGAN: Deep Light Enhancement without Paired Supervision [[Code](https://github.com/VITA-Group/EnlightenGAN), [Paper](https://arxiv.org/abs/1906.06972)]
    - Yifan Jiang, Xinyu Gong, Ding Liu, Yu Cheng, Chen Fang, Xiaohui Shen, Jianchao Yang, Pan Zhou, Zhangyang Wang, arXiv, 2019

- Underexposed Photo Enhancement Using Deep Illumination Estimation (DeepUPE) [[Code](https://github.com/wangruixing/DeepUPE), [Paper](https://drive.google.com/file/d/1CCd0NVEy0yM2ulcrx44B1bRPDmyrgNYH/view)]
    - Ruixing Wang, Qing Zhang, Chi-Wing Fu, Xiaoyong Shen, Wei-Shi Zheng, Jiaya Jia, CVPR, 2019

- Zero-Reference Deep Curve Estimation for Low-Light Image Enhancement (DCE-Net) [[Project](https://li-chongyi.github.io/Proj_Zero-DCE.html), [Code](https://github.com/Li-Chongyi/Zero-DCE), [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Guo_Zero-Reference_Deep_Curve_Estimation_for_Low-Light_Image_Enhancement_CVPR_2020_paper.pdf)]
    - Chunle Guo, Chongyi Li,Jichang Guo, Chen Change Loy, Junhui Hou, Sam Kwong, Runmin Cong, CVPR, 2020

### Beneficial References
- Structure-Revealing Low-Light Image Enhancement Via Robust Retinex Model [[Code](https://github.com/martinli0822/Low-light-image-enhancement) (p file), [Paper](https://ieeexplore.ieee.org/document/8304597)]
    -  Mading Li,Jiaying Liu, Wenhan Yang, Xiaoyan Sun, Zongming Guo, TIP, 2018 

- 2020
- Attention-Based Network For Low-Light Image Enhancement [[Paper](https://ieeexplore.ieee.org/document/9102774)] 
    -  Cheng Zhan, Qingsen Yan, Yu Zhu, Xianjun Li, Jinqiu Sun, Yanning Zhang, ICME,2020
-  An Experiment-Based Review of Low-Light Image Enhancement Methods [[Paper](https://ieeexplore.ieee.org/document/9088214)], IEEE Access, 2020
- Unsupervised Real-world Low-light Image Enhancement with Decoupled Networks [[Paper](https://arxiv.org/abs/2005.02818)], Arxiv, 2020
- LR3M: Robust Low-Light Enhancement via Low-Rank Regularized Retinex Model [[Paper](https://ieeexplore.ieee.org/document/9056796)]
    - Xutong Ren, Wenhan Yang, Wen-Huang Cheng, and Jiaying Liu, TIP, 2020
- Visual Perception Model for Rapid and AdaptiveLow-light Image Enhancement, [[Paper](https://arxiv.org/abs/2005.07343)], arxiv, submit to TCVST, 2020

## Datasets
- NPE (Naturalness preserved enhancement) 84 images [[Naturalness Preserved Enhancement Algorithm for Non-Uniform Illumination Images](https://ieeexplore.ieee.org/document/6512558)]
- LIME 10 images [[LIME: Low-light Image Enhancement viaIllumination Map Estimation](http://www.dabi.temple.edu/~hbling/publication/LIME-tip.pdf)]
- MEF  17 images [[Perceptual Quality Assessment for Multi-Exposure Image Fusion](https://ieeexplore.ieee.org/document/7120119)]
- DICM 64 images [[Contrast Enhancement Based on Layered Difference Representation of 2D Histograms](https://ieeexplore.ieee.org/document/6615961) TIP 2013]
- VV [[Link](https://sites.google.com/site/vonikakis/datasets)] 24 images
- See-in-the-Dark (SID) [[Learning to See in the Dark](https://cchen156.github.io/paper/18CVPR_SID.pdf)]
    - 5094 raw short exposure reference image with a corresponding long-exposure reference image.
- Single Image Contrast Enhancer (SICE) [[Link](https://github.com/csjcai/SICE)]
    - 589 sequences, 4413 multi-exposre images, image resolution 3000\*2000-6000\*4000
- DARK FACE [[Link](https://flyywh.github.io/CVPRW2019LowLight/)]
    - 789 paired low-light/normal-light images, 9,000 unlabeled low-light images


## People/Groups

- Qifeng Chen, Intel [[Homepage](https://cqf.io/)]
- Wenhan Yang [[Homepage](https://flyywh.github.io/index.html)], Jiaying Liu, PKU [[STRUCT Group Website](http://39.96.165.147/)]
- Jiaya Jia [[Homepage](http://jiaya.me/)], Xiaoyong Shen [[Homepage](http://xiaoyongshen.me/)], CUHK
- Qing Zhang [[Homepage](http://zhangqing-home.net/)], Weishi Zheng [[Homepage](https://www.isee-ai.cn/~zhwshi/)], Sun Yat-sen University 
- Chongyi Li [[Homepage](https://li-chongyi.github.io/)], Chen Change (Cavan) Loy[[Homepage](http://personal.ie.cuhk.edu.hk/~ccloy/index.html)], Nanyang Technological University (NTU)
- Xiejie Guo [[Homepage](https://sites.google.com/view/xjguo)], TianJing U


