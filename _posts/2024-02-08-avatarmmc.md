---
layout: post
title:  "AvatarMMC: 3D Head Avatar Generation and Editing with Multi-Modal Conditioning"
date:   2024-02-08 13:00:53 +00:00
image: /images/AvatarMMC.png
categories: research
author: "Pradyumna Reddy"
paper: https://arxiv.org/pdf/2402.05803
website: avatarmmc-sig24.github.io
authors: "Wamiq Reyaz Para, Abdelrahman Eldesokey, Zhenyu Li, Pradyumna Reddy, Jiankang Deng, Peter Wonka"
venue: "Pre-print"
---
We introduce an approach for 3D head avatar generation and editing with multi-modal conditioning based on a 3D Generative Adversarial Network (GAN) and a Latent Diffusion Model (LDM). 3D GANs can generate high-quality head avatars given a single or no condition. However, it is challenging to generate samples that adhere to multiple conditions of different modalities. On the other hand, LDMs excel at learning complex conditional distributions. To this end, we propose to exploit the conditioning capabilities of LDMs to enable multi-modal control over the latent space of a pre-trained 3D GAN. Our method can generate and edit 3D head avatars given a mixture of control signals such as RGB input, segmentation masks, and global attributes. This provides better control over the generation and editing of synthetic avatars both globally and locally. Experiments show that our proposed approach outperforms a solely GAN-based approach both qualitatively and quantitatively on generation and editing tasks. To the best of our knowledge, our approach is the first to introduce multi-modal conditioning to 3D avatar generation and editing. 
