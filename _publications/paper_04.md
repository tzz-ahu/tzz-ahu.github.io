---
title: "Alignment-Free RGBT Salient Object Detection: Semantics-Guided Asymmetric Correlation Network and a Unified Benchmark (TMM 2024)"
collection: publications
permalink: /publication/paper_04
excerpt: "Kunpeng Wang, Danying Lin, Chenglong Li, **Zhengzheng Tu**, Bin Luo"
# date: 2009-10-01
# venue: "Journal 1"
# slidesurl: "http://academicpages.github.io/files/slides1.pdf"
# paperurl: "http://academicpages.github.io/files/paper1.pdf"
# citation: "Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1)."
---

Kunpeng Wang, Danying Lin, Chenglong Li, **Zhengzheng Tu**, Bin Luo

**Abstract:** RGB and Thermal (RGBT) Salient Object Detection (SOD) aims to achieve high-quality saliency prediction by exploiting the complementary information of visible and thermal image pairs, which are initially captured in an unaligned manner. However, existing methods are tailored for manually aligned image pairs, which are labor-intensive, and directly applying these methods to original unaligned image pairs could significantly degrade their performance. In this paper, we make the first attempt to address RGBT SOD for initially captured RGB and thermal image pairs without manual alignment. Specifically, we propose a Semantics-guided Asymmetric Correlation Network (SACNet) that consists of two novel components: 1) an asymmetric correlation module utilizing semantics-guided attention to model cross-modal correlations specific to unaligned salient regions; 2) an associated feature sampling module to sample relevant thermal features according to the corresponding RGB features for multi-modal feature integration. In addition, we construct a unified benchmark dataset called UVT2000, containing 2000 RGB and thermal image pairs directly captured from various real-world scenes without any alignment, to facilitate research on alignment-free RGBT SOD. Extensive experiments on both aligned and unaligned datasets demonstrate the effectiveness and superior performance of our method. The dataset and code are available at https://github.com/Angknpng/SACNet.

**DOI:** https://ieeexplore.ieee.org/document/10551543
