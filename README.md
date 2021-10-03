# Awesome Weak-Shot Learning  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources including papers, datasets, and relevant links pertaining to weak-shot learning. **In weak-shot learning, all categories are split into non-overlapped base categories and novel categories, in which base categories have full annotations while novel categories only have weak annotations.** In different tasks, weak annotation could be provided in different forms, e.g., noisy label for classification, image label for object detection, image label/bounding box for segmentation. 

**The comparison between weak-shot learning and zero/few-shot learning is illustrated below.** In all three settings, all categories are split into non-overlapped base categories and novel categories. In all three settings, base categories have abundant fully-annotated training samples. In zero-shot learning, novel categories have no training samples, so class-level representations are required to bridge the gap between base categories and novel categories. In few-shot learning, novel categories have limited training samples. In weak-shot leanring, novel categories have abundant weakly-annotated training samples. 
<img src='https://bcmi.sjtu.edu.cn/home/niuli/images/project_weak_shot.jpg' align="center" width=512>
## Contributing

Contributions are welcome.  If you wish to contribute, feel free to send a pull request. If you have suggestions for new sections to be included, please raise an issue and discuss before sending a pull request.

## Table of Contents
+ [Survey](#Survey)
+ [Weak-Shot Classification](#Weak-Shot Classification)
+ [Weak-Shot Object Detection](#Weak-Shot Detection)
+ [Weak-Shot Semantic Segmentation](#Weak-Shot Semantic Segmentation)
+ [Weak-Shot Instance Segmentation](#Weak-Shot Instance Segmentation)

## Survey
+ Li Niu: "*Not Few, But Weak: A Survey on Weak-Shot Learning.*" 

## Weak-Shot Classification
**Base category: clean label; Novel category: noisy label**
+ Junjie Chen, Li Niu, Liu Liu, Liqing Zhang: "*Weak-shot Fine-grained Classification via Similarity Transfer.*" NeurIPS (2021) [[arXiv]](https://arxiv.org/pdf/2009.09197.pdf) [[code]](https://github.com/bcmi/SimTrans-Weak-Shot-Classification)

## Weak-Shot Detection
**Base category: bounding box; Novel category: image label**
+ Yan Li, Junge Zhang, Kaiqi Huang, Jianguo Zhang: "*Mixed Supervised Object Detection with Robust Objectness Transfer.*" T-PAMI (2018) [[paper]](https://ieeexplore.ieee.org/document/8304628) [[arXiv]](https://arxiv.org/pdf/1802.09778.pdf) 
+ Jason Kuen, Federico Perazzi, Zhe Lin, Jianming Zhang, Yap-Peng Tan: "*Scaling Object Detection by Transferring Classification Weights.*" ICCV (2019) [[paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Kuen_Scaling_Object_Detection_by_Transferring_Classification_Weights_ICCV_2019_paper.pdf) [[code]](https://github.com/xternalz/AE-WTN)
+ Yuanyi Zhong, Jianfeng Wang, Jian Peng, Lei Zhang: "*Boosting Weakly Supervised Object Detection with Progressive Knowledge Transfer.*" ECCV (2020) [[paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123710613.pdf) [[arXiv]](https://arxiv.org/pdf/2007.07986.pdf) [[code]](https://github.com/mikuhatsune/wsod_transfer)
+ Yan Liu, Zhijie Zhang, Li Niu, Junjie Chen, Liqing Zhang: "*Mixed Supervised Object Detection by Transferring Mask Prior and Semantic Similarity.*" NeurIPS (2021) [[code]](https://github.com/bcmi/TraMaS-Weak-Shot-Object-Detection)


## Weak-Shot Semantic Segmentation
**Base category: semantic mask; Novel category: image label**
+ Siyuan Zhou, Li Niu, Jianlou Si, Chen Qian, Liqing Zhang: "*Weak-shot Semantic Segmentation by Transferring Semantic Affinity and Boundary.*" 

## Weak-Shot Instance Segmentation
**Base category: instance mask; Novel category: bounding box**
+ Weicheng Kuo, Anelia Angelova, Jitendra Malik, Tsung-Yi Lin: "*ShapeMask: Learning to Segment Novel Objects by Refining Shape Priors.*" ICCV (2019) [[paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Kuo_ShapeMask_Learning_to_Segment_Novel_Objects_by_Refining_Shape_Priors_ICCV_2019_paper.pdf) [[arXiv]](https://arxiv.org/pdf/1904.03239.pdf)







