---
title: 'CLIP-FLow: Contrastive learning by semi-supervised iterative pseudo labeling
  for optical flow estimation'
authors:
- Zhiqi Zhang
- Nitin Bansal
- Changjiang Cai
- Pan Ji
- Qingan Yan
- Xiangyu Xu
- Yi Xu
date: '2022-01-01'
publishDate: '2025-01-25T22:12:06.304422Z'
publication_types:
- article-journal
publication: '*arXiv preprint arXiv:2210.14383*'

abstract: Synthetic datasets are often used to pretrain end-to-end optical flow networks, due to the lack of a large amount of labeled, real-scene data. But major drops in accuracy occur when moving from synthetic to real scenes. How do we better transfer the knowledge learned from synthetic to real domains? To this end, we propose CLIP-FLow, a semi-supervised iterative pseudo-labeling framework to transfer the pretraining knowledge to the target real domain. We leverage large-scale, unlabeled real data to facilitate transfer learning with the supervision of iteratively updated pseudo-ground truth labels, bridging the domain gap between the synthetic and the real. In addition, we propose a contrastive flow loss on reference features and the warped features by pseudo ground truth flows, to further boost the accurate matching and dampen the mismatching due to motion, occlusion, or noisy pseudo labels. We adopt RAFT as the backbone and obtain an F1-all error of 4.11%, i.e. a 19% error reduction from RAFT (5.10%) and ranking 2 place at submission on the KITTI 2015 benchmark. Our framework can also be extended to other models, e.g. CRAFT, reducing the F1-all error from 4.79% to 4.66% on KITTI 2015 benchmark.

tags:
- Optical Flow
- Semi-supervised Learning
- Contrastive Loss

links:
url_pdf: https://arxiv.org/pdf/2210.14383

image:
  caption: ''
  focal_point: ""
  preview_only: false

---
