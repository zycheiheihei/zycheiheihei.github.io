---
title: "Exploring the Transferability of Visual Prompting for Multimodal Large Language Models"
collection: publications
permalink: /publication/zhang2024exploring
excerpt: 'Although Multimodal Large Language Models (MLLMs) have demonstrated promising versatile capabilities, their performance is still inferior to specialized models on downstream tasks, which makes adaptation necessary to enhance their utility. However, fine-tuning methods require independent training for every model, leading to huge computation and memory overheads. In this paper, we propose a novel setting where we aim to improve the performance of diverse MLLMs with a group of shared parameters optimized for a downstream task. To achieve this, we propose Transferable Visual Prompting (TVP), a simple and effective approach to generate visual prompts that can transfer to different models and improve their performance on downstream tasks after trained on only one model. We introduce two strategies to address the issue of cross-model feature corruption of existing visual prompting methods and enhance the transferability of the learned prompts, including 1) Feature Consistency Alignment: which imposes constraints to the prompted feature changes to maintain task-agnostic knowledge; 2) Task Semantics Enrichment: which encourages the prompted images to contain richer task-specific semantics with language guidance. We validate the effectiveness of TVP through extensive experiments with 6 modern MLLMs on a wide variety of tasks ranging from object recognition and counting to multimodal reasoning and hallucination correction.'
date: 2024-06-19
venue: 'IEEE/CVF Conference on Computer Vision and Pattern Recognition <strong>(CVPR)</strong>, Seattle, USA'
authorlist: 'Yichi Zhang, Yinpeng Dong, Siyuan Zhang, Tianzan Min, Hang Su, Jun Zhu'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_Exploring_the_Transferability_of_Visual_Prompting_for_Multimodal_Large_Language_CVPR_2024_paper.pdf'
year: '2024'
code: 'https://github.com/zycheiheihei/Transferable-Visual-Prompting'
picture: 'zhang2024exploring.png'
award: 'Highlight, ~2.8%'
---
