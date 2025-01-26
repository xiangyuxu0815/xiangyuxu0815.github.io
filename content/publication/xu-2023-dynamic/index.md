---
title: Dynamic voxel grid optimization for high-fidelity rgb-d supervised surface
  reconstruction
authors:
- Xiangyu Xu
- Lichang Chen
- Changjiang Cai
- Huangying Zhan
- Qingan Yan
- Pan Ji
- Junsong Yuan
- Heng Huang
- Yi Xu
date: '2023-01-01'
publishDate: '2025-01-25T22:12:06.316793Z'
publication_types: ["article"]
publication: '*arXiv preprint arXiv:2304.06178*'

abstract: Direct optimization of interpolated features on multi-resolution voxel grids has emerged as a more efficient alternative to MLP-like modules. However, this approach is constrained by higher memory expenses and limited representation capabilities. In this paper, we introduce a novel dynamic grid optimization method for high-fidelity 3D surface reconstruction that incorporates both RGB and depth observations. Rather than treating each voxel equally, we optimize the process by dynamically modifying the grid and assigning more finer-scale voxels to regions with higher complexity, allowing us to capture more intricate details. Furthermore, we develop a scheme to quantify the dynamic subdivision of voxel grid during optimization without requiring any priors. The proposed approach is able to generate high-quality 3D reconstructions with fine details on both synthetic and real-world data, while maintaining computational efficiency, which is substantially faster than the baseline method NeuralRGBD.

tags:
- NeRF
- 3D Surface Reconstruction
- Dynamic Voxel grids
- RGB-D

links:
url_pdf: https://arxiv.org/pdf/2304.06178

image:
  caption: ''
  focal_point: ""
  preview_only: false
---
