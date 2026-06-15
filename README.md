<div align="center">
  <h1 style="border-bottom: none;">Dual-Domain Context Interactive Network for Infrared Small Target Detection with Single-Point Supervision</h1>
</div>

<div align="center">
  <p>
    <a href="https://orcid.org/0009-0005-9250-5464" target="_blank">Haiguang Wang</a><sup>1,2</sup>,&nbsp;
    <a>Yunpeng Liu</a><sup>1*</sup>,&nbsp;
    <a>Shuyu Hu</a><sup>1,2</sup>,&nbsp;
    <a>Qinghua Zhang</a><sup>1,2</sup>,&nbsp;
    <a>Zelin Shi</a><sup>1</sup>
  </p>
  <p>
    <sup>1</sup> Shenyang Institute of Automation, Chinese Academy of Sciences
    <br>
    <sup>2</sup> School of Computer Science and Technology, University of Chinese Academy of Sciences
    <br>
    <sup>*</sup> Corresponding author
  </p>
</div>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Paper-Under%20Review-orange.svg"></a>
  <a href="#"><img src="https://img.shields.io/badge/Code-Coming%20Soon-blue.svg"></a>
  <a href="https://github.com/WHG980624"><img src="https://img.shields.io/badge/Homepage-WHG980624-red.svg"></a>
  <a href="#"><img src="https://img.shields.io/badge/python-3.8+-blue.svg"></a>
</p>

## 💥 Abstract

Infrared small target detection plays a vital role in both civilian and military applications, yet it remains challenged by weak target signals, complex background clutter and the difficulty of preserving shape integrity. Current mainstream deep learning methods, mostly relying on pixel-level annotations, have achieved remarkable progress in detection accuracy. However, such approaches heavily depend on large-scale fine-grained annotations, leading to prohibitive labeling costs. To alleviate the annotation burden, some studies have attempted to introduce point-supervised strategies, but the extremely limited supervision information severely degrades detection performance. To address these issues, we propose a novel dual-domain context interactive network (DCI-Net).

Specifically, we first design a dynamic difference convolution (DDC), which adaptively amplifies the feature responses of potential targets while suppressing background clutter by learning to the contribution of difference convolution information. Then, we develop a multi-scale contextual aggregation module (MSCA), which leverages multi-scale gating to aggregate local contextual information and refines features without requiring extra negative annotations, mitigating the false reinforcement of salient background clutter. Finally, we introduce a spatial-frequency interactive module (SFIM), which establishes bidirectional interaction between frequency and spatial domains to encourage target features to exhibit more compact and consistent spatial distribution while remaining distinct from background patterns. Extensive experiments on multiple infrared small target datasets demonstrate that under the point-supervised setting, our DCI-Net achieves superior detection performance compared to existing methods.

## 🚀 Overview

<div align="center">
<br>
  <img width="100%" src="imgs/DCI-Framework-Overview.png" alt="DCI-Net framework overview">
<br>
</div>

## ✅ TODO List

We are preparing the release of the paper and code. Please stay tuned.

- [ ] Release paper.
- [ ] Release training and inference code.

## 📫 Contact

For questions about this work, please contact:

- Haiguang Wang: wanghaiguang@sia.cn
