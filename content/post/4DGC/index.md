---
title: '[CVPR 2025]4DGC: Rate-Aware 4D Gaussian Compression for Efficient Streamable Free-Viewpoint Video'
date: 2025-05-24
image: 
  focal_point: 'top'

---
<!--more-->
3D Gaussian Splatting (3DGS) has substantial potential for enabling photorealistic Free-Viewpoint Video (FVV) experiences. However, the vast number of Gaussians and their associated attributes poses significant challenges for storage and transmission. Existing methods typically handle dynamic 3DGS representation and compression separately, neglecting motion information and the rate-distortion (RD) trade-off during training, leading to performance degradation and increased model redundancy. To address this gap, we propose 4DGC, a novel rate-aware 4D Gaussian compression framework that significantly reduces storage size while maintaining superior RD performance for FVV. Specifically, 4DGC introduces a motion-aware dynamic Gaussian representation that utilizes a compact motion grid combined with sparse compensated Gaussians to exploit inter-frame similarities. This representation effectively handles large motions, preserving quality and reducing temporal redundancy. Furthermore, we present an end-to-end compression scheme that employs differentiable quantization and a tiny implicit entropy model to compress the motion grid and compensated Gaussians efficiently. The entire framework is jointly optimized using a rate-distortion trade-off. Extensive experiments demonstrate that 4DGC supports variable bitrates and consistently outperforms existing methods in RD performance across multiple datasets.'
