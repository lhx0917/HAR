# Awesome Human Action Recognition 🔥

A curated list of Human Action Recognition (HAR) projects, papers, and codes, organized by methods and datasets.

本仓库用于整理 Human Action Recognition 相关的开源项目，方便快速查阅与学习。

---

## 📂 Table of Contents

- [1. Transformer-based Methods](#1-transformer-based-methods)
- [2. 3D CNN-based Methods](#2-3d-cnn-based-methods)
- [3. Skeleton-based Methods](#3-skeleton-based-methods)
- [4. Self-supervised Learning](#4-self-supervised-learning)
- [5. Datasets & Benchmarks](#5-datasets--benchmarks)

---

## 1. Transformer-based Methods

- [ActionFormer (ECCV 2022)](https://github.com/happyharrycn/actionformer_release)  
  用于时序动作定位的Transformer方法，提出了一个基于token pyramid的结构。

- [TimesFormer (NeurIPS 2021)](https://github.com/facebookresearch/TimeSformer)  
  早期将ViT扩展到视频动作识别任务的工作。

---

## 2. 3D CNN-based Methods

- [I3D (CVPR 2017)](https://github.com/deepmind/kinetics-i3d)  
  使用3D卷积处理时空特征，经典工作，基于Inception结构。

- [SlowFast (ICCV 2019)](https://github.com/facebookresearch/SlowFast)  
  提出slow/fast两个路径捕捉不同时间分辨率信息。

---

## 3. Skeleton-based Methods

- [ST-GCN (AAAI 2018)](https://github.com/yysijie/st-gcn)  
  图卷积方法，使用骨骼关键点建图识别动作。

- [CTR-GCN (CVPR 2021)](https://github.com/UshioX/CTR-GCN)  
  一种更灵活的图构建方法用于Skeleton数据。

---

## 4. Self-supervised Learning

- [ActCLR (CVPR 2023)](https://github.com/GuangmingZhu/ActCLR)  
  动作剪辑层次对比学习，利用时序结构进行自监督训练。

- [CoCLR (CVPR 2021)](https://github.com/tencent-ailab/CoCLR)  
  基于时序一致性的视频对比学习方法。

---

## 5. Datasets & Benchmarks

- [Kinetics](https://deepmind.com/research/open-source/kinetics) - 大规模动作识别数据集。
- [NTU RGB+D](https://rose1.ntu.edu.sg/dataset/actionRecognition/) - 骨骼动作识别经典数据集。
- [UCF101](https://www.crcv.ucf.edu/data/UCF101.php) - 早期的视频动作数据集。

---

## ✅ How to Contribute

欢迎提交 PR 添加更多项目！也可以开 Issue 推荐你喜欢的项目。


