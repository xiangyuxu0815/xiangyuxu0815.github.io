---
title: 'DDM-NET: End-to-end learning of keypoint feature Detection, Description and
  Matching for 3D localization'
authors:
- Xiangyu Xu
- Li Guan
- Enrique Dunn
- Haoxiang Li
- Gang Hua
date: '2022-01-01'
publishDate: '2025-01-25T22:12:06.310718Z'
publication_types: ["article"]
publication: '*arXiv preprint arXiv:2212.04575*'

abstract: In this paper, we propose an end-to-end framework that jointly learns keypoint detection, descriptor representation and cross-frame matching for the task of image-based 3D localization. Prior art has tackled each of these components individually, purportedly aiming to alleviate difficulties in effectively train a holistic network. We design a self-supervised image warping correspondence loss for both feature detection and matching, a weakly-supervised epipolar constraints loss on relative camera pose learning, and a directional matching scheme that detects key-point features in a source image and performs coarse-to-fine correspondence search on the target image. We leverage this framework to enforce cycle consistency in our matching module. In addition, we propose a new loss to robustly handle both definite inlier/outlier matches and less-certain matches. The integration of these learning mechanisms enables end-to-end training of a single network performing all three localization components. Bench-marking our approach on public data-sets, exemplifies how such an end-to-end framework is able to yield more accurate localization that out-performs both traditional methods as well as state-of-the-art weakly supervised methods.

tags:
- Feature Detection, Extraction and Matching. 
- Camera Localization
- Self-supervision

links:
url_pdf: https://arxiv.org/pdf/2212.04575

image:
  caption: ''
  focal_point: ""
  preview_only: false
---
