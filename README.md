# Awesome Weak-Shot Learning  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

In **weak-shot learning**, all categories are split into non-overlapped **base categories** and **novel categories**, in which base categories have **full annotations** while novel categories only have **weak annotations**. In different tasks, weak annotation could be provided in different forms, e.g., noisy label for classification, image label for object detection, image label/bounding box for segmentation. 

The comparison between **weak-shot learning and zero/few-shot learning** is illustrated below. In all three settings, all categories are split into non-overlapped base categories and novel categories. In all three settings, base categories have abundant fully-annotated training samples. In zero-shot learning, novel categories have no training samples, so class-level representations are required to bridge the gap between base categories and novel categories. In few-shot learning, novel categories have limited training samples. In weak-shot leanring, novel categories have abundant weakly-annotated training samples. 

<img src='https://bcmi.sjtu.edu.cn/home/niuli/images/project_weak_shot_small.jpg' align="center" width=512>

## Contributing

Contributions are welcome.  If you wish to contribute, feel free to send a pull request. If you have suggestions for new sections to be included, please raise an issue and discuss before sending a pull request.

## Table of Contents
+ [Survey](#Survey)
+ [Weak-Shot Classification](#Weak-Shot-Classification)
+ [Weak-Shot Object Detection](#Weak-Shot-Detection)
+ [Weak-Shot Semantic Segmentation](#Weak-Shot-Semantic-Segmentation)
+ [Weak-Shot Instance Segmentation](#Weak-Shot-Instance-Segmentation)

## Survey
+ Li Niu: "*Weak Novel Categories without Tears: A Survey on Weak-Shot Learning.*" arXiv preprint arXiv:2110.02651 (2021).  [[arXiv]](https://arxiv.org/pdf/2110.02651.pdf)

## Weak-Shot Classification
**Base category: clean label; Novel category: noisy label** (weak-shot)
+ Junjie Chen, Li Niu, Liu Liu, Liqing Zhang: "*Weak-shot Fine-grained Classification via Similarity Transfer.*" NeurIPS (2021) [[arXiv]](https://arxiv.org/pdf/2009.09197.pdf) [[code]](https://github.com/bcmi/SimTrans-Weak-Shot-Classification)

## Weak-Shot Object Detection
**Base category: bounding box; Novel category: image label** (chaotic names: mixed-supervised, cross-supervised, partially-supervised, weak-shot)
+ Judy Hoffman, Sergio Guadarrama, Eric Tzeng, Ronghang Hu, Jeff Donahue, Ross Girshick, Trevor Darrell, Kate Saenko: "*LSDA: Large Scale Detection Through Adaptation.*" NIPS (2014) [[paper]](https://proceedings.neurips.cc/paper/2014/file/09fb05dd477d4ae6479985ca56c5a12d-Paper.pdf) [[code]](https://github.com/jhoffman/lsda)
+ Mrigank Rochan, Yang Wang: "*Weakly Supervised Localization of Novel Objects Using Appearance Transfer.*" CVPR (2015) [[paper]](https://openaccess.thecvf.com/content_cvpr_2015/papers/Rochan_Weakly_Supervised_Localization_2015_CVPR_paper.pdf)
+ Yuxing Tang, Josiah Wang, Boyang Gao, Emmanuel Dellandrea, Robert Gaizauskas, Liming Chen: "*Large Scale Semi-supervised Object Detection using Visual and Semantic
Knowledge Transfer.*" CVPR (2016) [[paper]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Tang_Large_Scale_Semi-Supervised_CVPR_2016_paper.pdf)
+ Joseph Redmon, Ali Farhadi: "*YOLO9000: Better, Faster, Stronger.*" CVPR (2017) [[paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Redmon_YOLO9000_Better_Faster_CVPR_2017_paper.pdf) [[code]](https://pjreddie.com/darknet/yolo/)
+ Bharat Singh, Hengduo Li, Abhishek Sharma, Larry S. Davis: "*R-FCN-3000 at 30fps: Decoupling detection and classification.*" CVPR (2018) [[paper]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Singh_R-FCN-3000_at_30fps_CVPR_2018_paper.pdf) [[code]](https://github.com/MahyarNajibi/SNIPER)
+ Yan Li, Junge Zhang, Kaiqi Huang, Jianguo Zhang: "*Mixed Supervised Object Detection with Robust Objectness Transfer.*" T-PAMI (2018) [[paper]](https://ieeexplore.ieee.org/document/8304628) [[arXiv]](https://arxiv.org/pdf/1802.09778.pdf) 
+ Jason Kuen, Federico Perazzi, Zhe Lin, Jianming Zhang, Yap-Peng Tan: "*Scaling Object Detection by Transferring Classification Weights.*" ICCV (2019) [[paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Kuen_Scaling_Object_Detection_by_Transferring_Classification_Weights_ICCV_2019_paper.pdf) [[code]](https://github.com/xternalz/AE-WTN)
+ Yuanyi Zhong, Jianfeng Wang, Jian Peng, Lei Zhang: "*Boosting Weakly Supervised Object Detection with Progressive Knowledge Transfer.*" ECCV (2020) [[paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123710613.pdf) [[arXiv]](https://arxiv.org/pdf/2007.07986.pdf) [[code]](https://github.com/mikuhatsune/wsod_transfer)
+ Ye Guo, Yali Li, Shengjin Wang: "*CS-R-FCN: Cross-supervised Learning for Large-scale Object Detection.*" ICASSP (2020) [[arXiv]](https://arxiv.org/pdf/1905.12863.pdf)
+ Zitian Chen, Zhiqiang Shen, Jiahui Yu, Erik Learned-Miller: "*Cross-Supervised Object Detection.*" arXiv preprint arXiv:2006.15056 (2020). [[arXiv]](https://arxiv.org/pdf/2006.15056.pdf)
+ Yan Liu, Zhijie Zhang, Li Niu, Junjie Chen, Liqing Zhang: "*Mixed Supervised Object Detection by Transferring Mask Prior and Semantic Similarity.*" NeurIPS (2021) [[paper]](https://arxiv.org/pdf/2110.14191.pdf) [[code]](https://github.com/bcmi/TraMaS-Weak-Shot-Object-Detection)


## Weak-Shot Semantic Segmentation
**Base category: semantic mask; Novel category: image label** (weak-shot)
+ Siyuan Zhou, Li Niu, Jianlou Si, Chen Qian, Liqing Zhang: "*Weak-shot Semantic Segmentation by Transferring Semantic Affinity and Boundary.*" arXiv preprint arXiv:2110.01519  (2021). [[arXiv]](https://arxiv.org/pdf/2110.01519.pdf)
+ Junjie Chen, Li Niu, Siyuan Zhou, Jianlou Si, Chen Qian, Liqing Zhang: "*Weak-shot Semantic Segmentation via Dual Similarity Transfer.*" NeurIPS (2022) [[code]](https://github.com/bcmi/SimFormer-Weak-Shot-Semantic-Segmentation)

## Weak-Shot Instance Segmentation
**Base category: instance mask; Novel category: bounding box** (partially-supervised)
+ Ronghang Hu, Piotr Dollar, Kaiming He, Trevor Darrell, Ross Girshick: "*Learning to Segment Every Thing.*" CVPR (2018) [[paper]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Hu_Learning_to_Segment_CVPR_2018_paper.pdf) [[code]](https://github.com/ronghanghu/seg_every_thing)
+ Weicheng Kuo, Anelia Angelova, Jitendra Malik, Tsung-Yi Lin: "*ShapeMask: Learning to Segment Novel Objects by Refining Shape Priors.*" ICCV (2019) [[paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Kuo_ShapeMask_Learning_to_Segment_Novel_Objects_by_Refining_Shape_Priors_ICCV_2019_paper.pdf) [[arXiv]](https://arxiv.org/pdf/1904.03239.pdf)
+ Yanzhao Zhou, Xin Wang, Jianbin Jiao, Trevor Darrell, Fisher Yu: "*Learning Saliency Propagation for Semi-Supervised Instance Segmentation.*" CVPR (2020) [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhou_Learning_Saliency_Propagation_for_Semi-Supervised_Instance_Segmentation_CVPR_2020_paper.pdf) [[code]](https://github.com/ucbdrive/ShapeProp)
+ Qi Fan, Lei Ke, Wenjie Pei, Chi-Keung Tang, Yu-Wing Tai: "*Commonality-Parsing Network across Shape and Appearance for Partially Supervised Instance Segmentation.*" ECCV (2020) [[arXiv]](https://arxiv.org/pdf/2007.12387.pdf) [[code]](https://github.com/fanq15/CPMask)
+ David Biertimpel, Sindi Shkodrani, Anil S. Baslamisli, Nora Baka: "*Prior to Segment: Foreground Cues for Weakly Annotated Classes in Partially Supervised Instance Segmentation.*" ICCV (2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Biertimpel_Prior_to_Segment_Foreground_Cues_for_Weakly_Annotated_Classes_in_ICCV_2021_paper.pdf) [[arXiv]](https://arxiv.org/pdf/2011.11787.pdf) [[code]](https://github.com/dbtmpl/OPMask)
+ Vighnesh Birodkar, Zhichao Lu, Siyang Li, Vivek Rathod, Jonathan Huang: "*The Surprising Impact of Mask-head Architecture on Novel Class Segmentation.*" ICCV (2021) [[paper]](http://openaccess.thecvf.com/content/ICCV2021/papers/Birodkar_The_Surprising_Impact_of_Mask-Head_Architecture_on_Novel_Class_Segmentation_ICCV_2021_paper.pdf) [[code]](https://google.github.io/deepmac/#code)







