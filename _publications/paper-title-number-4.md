---
title: "Multimodal Representations for Teacher-Guided Compositional Visual Reasoning"
collection: publications
category: conferences
permalink: /publication/paper-title-number-4
date: 2023-08-23
venue: 'Advanced Concepts for Intelligent Vision Systems: 21st International Conference, ACIVS 2023 Kumamoto, Japan, August 21–23, 2023 Proceedings'
paperurl: 'https://hal.science/hal-04252818v1/document'
slidesurl: 'https://wafaaissaa.github.io/wafaaissa.github.io//files/slides_acivs_TF.pdf'
citation: 'Wafa Aissa, Marin Ferecatu, Michel Crucianu. Multimodal Representations for Teacher-Guided Compositional Visual Reasoning. Advanced Concepts for Intelligent Vision Systems, 21st International Conference (ACIVS 2023), Aug 2023, Kumamoto, Japan. pp.357-369, ff10.1007/978-3-031-45382-3_30ff.'
---

Neural Module Networks (NMN) are a compelling method for visual question answering, enabling the translation of a question into a program consisting of a series of reasoning sub-tasks that are sequentially executed on the image to produce an answer. NMNs provide enhanced explainability compared to integrated models, allowing for a better understanding of the underlying reasoning process. To improve the
effectiveness of NMNs we propose to exploit features obtained by a largescale cross-modal encoder. Also, the current training approach of NMNs
relies on the propagation of module outputs to subsequent modules, leading to the accumulation of prediction errors and the generation of false
answers. To mitigate this, we introduce an NMN learning strategy involving scheduled teacher guidance. Initially, the model is fully guided
by the ground-truth intermediate outputs, but gradually transitions to an autonomous behavior as training progresses. This reduces error accumulation, thus improving training efficiency and final performance. We demonstrate that by incorporating cross-modal features and employing
more effective training techniques for NMN, we achieve a favorable balance between performance and transparency in the reasoning process.
