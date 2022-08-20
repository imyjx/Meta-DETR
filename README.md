# __[T-PAMI' 2022]  Meta-DETR__ <br> (Official PyTorch Implementation)

[![arXiv](https://img.shields.io/badge/arXiv-2208.00219-b31b1b.svg)](https://arxiv.org/abs/2208.00219)
[![Survey](https://github.com/sindresorhus/awesome/blob/main/media/mentioned-badge.svg)](https://github.com/dk-liang/Awesome-Visual-Transformer) 
[![GitHub license](https://badgen.net/github/license/ZhangGongjie/Meta-DETR)](https://github.com/ZhangGongjie/Meta-DETR/blob/master/LICENSE)


This repository is the official PyTorch implementation of the
T-PAMI 2022 paper "[Meta-DETR: Image-Level Few-Shot Detection with Inter-Class Correlation Exploitation](https://arxiv.org/abs/2208.00219)" by _Gongjie Zhang, Zhipeng Luo, Kaiwen Cui, Shijian Lu, and Eric P. Xing_. 


## Introduction

<b> TL;DR </b> &nbsp; Meta-DETR is a state-of-the-art few-shot object detector that performs image-level meta-learning-based prediction and effectively exploits the inter-class correlation to enhance generalization from old knowledge to new classes. Meta-DETR entirely bypasses the proposal quality gap between base and novel classes, thus achieving superior performance than R-CNN-based few-shot object detectors. In addition, Meta-DETR performs meta-learning on a set of support classes at one go, thus effectively leveraging the inter-class correlation for better generalization.


Environment:
Ubuntu 18.04 LTS
Python 3.7
Pytorch 1.7.1
Cuda 10.2
