---
layout: project
title:  "(ECCV 2024) Nickel and Diming Your GAN: A Dual-Method Approach to Enhancing GAN Efficiency via Knowledge Distillation"
date:   2024-05-19 17:09:43
author: Sangyeop Yeo, Yoojin Jang, Jaejun Yoo
categories:
- ECCV 2024
img: nickel_and_dime.gif
thumb: nickel_and_dime_thumb.gif
carousel:
- single01.jpg
- single02.jpg
- single03.jpg
tagged: Network compression, Generative models, Efficient GANs
website: https://sangyeopyeo.github.io/Nickel_and_Diming_Your_GAN/
---
#### Abstract
In this paper, we address the challenge of compressing generative adversarial networks (GANs) for deployment in resource-constrained environments by proposing two novel methodologies: Distribution Matching for Efficient compression (DiME) and Network Interactive Compression via Knowledge Exchange and Learning (NICKEL). DiME employs foundation models as embedding kernels for efficient distribution matching, leveraging maximum mean discrepancy to facilitate effective knowledge distillation. Simultaneously, NICKEL employs an interactive compression method that enhances the communication between the student generator and discriminator, achieving a balanced and stable compression process. Our comprehensive evaluation on the StyleGAN2 architecture with the FFHQ dataset shows the effectiveness of our approach, with NICKEL & DiME achieving FID scores of 10.45 and 15.93 at compression rates of 95.73% and 98.92%, respectively. Remarkably, our methods sustain generative quality even at an extreme compression rate of 99.69%, surpassing the previous state-of-the-art performance by a large margin. These findings not only demonstrate our methodologies' capacity to significantly lower GANs' computational demands but also pave the way for deploying high-quality GAN models in settings with limited resources. Our code will be released soon.

