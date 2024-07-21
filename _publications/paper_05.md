---
title: "Learning Adaptive Fusion Bank for Multi-modal Salient Object Detection (TCSVT 2024)"
collection: publications
permalink: /publication/paper_05
excerpt: "Kunpeng Wang, **Zhengzheng Tu**,** Chenglong Li, Cheng Zhang, Bin Luo"
# date: 2009-10-01
# venue: "Journal 1"
# slidesurl: "http://academicpages.github.io/files/slides1.pdf"
# paperurl: "http://academicpages.github.io/files/paper1.pdf"
# citation: "Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1)."
---

Kunpeng Wang, **Zhengzheng Tu**,\*\* Chenglong Li, Cheng Zhang, Bin Luo

**Abstract:** Multi-modal salient object detection (MSOD) aims to boost saliency detection performance by integrating visible sources with depth or thermal infrared ones. Existing methods generally design different fusion schemes to handle certain issues or challenges. Although these fusion schemes are effective at addressing specific issues or challenges, they may struggle to handle multiple complex challenges simultaneously. To solve this problem, we propose a novel adaptive fusion bank that makes full use of the complementary benefits from a set of basic fusion schemes to handle different challenges simultaneously for robust MSOD. We focus on handling five major challenges in MSOD, namely center bias, scale variation, image clutter, low illumination, and thermal crossover or depth ambiguity. The fusion bank proposed consists of five representative fusion schemes, which are specifically designed based on the characteristics of each challenge, respectively. The bank is scalable, and more fusion schemes could be incorporated into the bank for more challenges. To adaptively select the appropriate fusion scheme for multi-modal input, we introduce an adaptive ensemble module that forms the adaptive fusion bank, which is embedded into hierarchical layers for sufficient fusion of different source data. Moreover, we design an indirect interactive guidance module to accurately detect salient hollow objects via the skip integration of high-level semantic information and low-level spatial details. Extensive experiments on three RGBT datasets and seven RGBD datasets demonstrate that the proposed method achieves the outstanding performance compared to the state-of-the-art methods.

**DOI:** https://ieeexplore.ieee.org/document/10464332
