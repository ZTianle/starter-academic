---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An Online Learning Algorithm for Voice Activation Detection Based on a Pretrained
  Online Extreme Learning Machine
subtitle: ''
summary: ''
authors:
- Tianle Zhang
- Muzhou Hou
- Futian Weng
- Yunlei Yang
- Hongli Sun
- Zheng Wang
- Zhong Gao
- Jianshu Luo
tags: []
categories: []
date: '2018-01-01'
lastmod: 2020-10-26T06:23:33Z
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-10-26T06:23:32.906981Z'
publication_types: '1'
abstract: 'There is often a difference between the training library and the test library in the inclusion of noise, which affects the practical application of speech endpoint detection. We propose to use a generalized regularized online sequential extreme learning machine with forgetting factor (GR-OSELM-FF) for voice activation detection to adapt to the difference between test and training samples. Practical usability is our driving motivation; the proposed model should be easily adapted to new conditions. When a new voice stream arrives in the test or the actual application phase, the proposed model can directly adjust the output weight. To overcome the weakness of ELM's vulnerability to random hidden layer parameters, we use an extreme learning machine-based autoencoder (ELM-AE) to initialize the model parameters instead of using random initialization. The experimental results show that the pretrained models achieve better performance with ELM-AE, which can obtain the potential information from the data. The experimental results also show that the proposed algorithm maintains good accuracy and omission rates in different SNR noise environments and real-world voice samples.'

publication: '*Proceedings of the 2nd International Conference on Computer Scienceand Application Engineering*'
---
