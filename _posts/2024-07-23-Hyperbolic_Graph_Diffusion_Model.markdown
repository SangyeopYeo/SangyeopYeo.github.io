---
layout: post
title: "(AAAI 2024) Hyperbolic Graph Diffusion Model"
date: 2024-07-23 23:15:10
author: Sangyeop
categories:
- Hyperbolic Space
img: post_ICML.jpg
thumb: thumb_ICML.jpg
---
Paper link:

# Abstract
<!-- diffusion models은 이미지와 그래프 생성에서 눈에 띄는 성능을 보여준다. 하지만, 현실 세계의 graph (e.g., social networks, molecular graphs, traffic graphs)는 일반적으로 non-Euclidan topologies와 hidden hierarchies를 가진다. 예를들어 graphs의 degree distributions은 대부분 power-law distribution을 따른다. 현재의 latent diffusion model은 hierarchical dat를 Euclidean space에 embedding한다. 이것은 distortions을 만들고 distribution modeling에 개입한다. 대신에 hyperbolic space는 exponential growth property 덕분에 복잡한 hierachical structures를 표현하는데 더 적합하다. diffusion models의 data generation 능력과 latent hierarchical distributions을 추출하기 위한 hyperbolic embeddings의 능력을 동시에 활용하기 위해서 우리는 Hyperbolic Graph Diffusion Model (HGDM)이라는 새로운 graph generation method를 제안한다. HGDM은 nodes를 successive hyperbolic embeddings로 encoding하기 위한 auto-encoder와 hyperbolic latent spcae에서 동작하는 diffusion generative models로 이루어져 있다. HGDM은 edge information을 포함하는 hyperbolic potential node space를 구성함으로써 graph struture distributions을 잘 잡는다. 다양한 실험 결과는 HGDM이 generic graph와 molecule generation에서 더 좋은 성능을 달성한 것을 보여준다. -->