---
title: "MultiTrust: A Comprehensive Benchmark Towards Trustworthy Multimodal Large Language Models"
collection: publications
permalink: /publication/zhang2024benchmarking
excerpt: 'Despite the superior capabilities of Multimodal Large Language Models (MLLMs) across diverse tasks, they still face significant trustworthiness challenges. Yet, current literature on the assessment of trustworthy MLLMs remains limited, lacking a holistic evaluation to offer thorough insights into future improvements. In this work, we establish MultiTrust, the first comprehensive and unified benchmark on the trustworthiness of MLLMs across five primary aspects: truthfulness, safety, robustness, fairness, and privacy. Our benchmark employs a rigorous evaluation strategy that addresses both multimodal risks and cross-modal impacts, encompassing 32 diverse tasks with self-curated datasets. Extensive experiments with 21 modern MLLMs reveal some previously unexplored trustworthiness issues and risks, highlighting the complexities introduced by the multimodality and underscoring the necessity for advanced methodologies to enhance their reliability. For instance, typical proprietary models still struggle with the perception of visually confusing images and are vulnerable to multimodal jailbreaking and adversarial attacks; MLLMs are more inclined to disclose privacy in text and reveal ideological and cultural biases even when paired with irrelevant images in inference, indicating that the multimodality amplifies the internal risks from base LLMs. Additionally, we release a scalable toolbox for standardized trustworthiness research, aiming to facilitate future advancements in this important field. Code and resources are publicly available at: <a href="https://multi-trust.github.io">this https URL</a>.'
date: 2024-09-28
venue: 'The Datasets and Benchmarks track in the 38th Conference on Neural Information Processing Systems <strong>(NeurIPS)</strong>, Vancouver, Canada, 2024'
authorlist: '<strong>Yichi Zhang$^\ast$</strong>, Yao Huang$^\ast$, Yitong Sun, Chang Liu, Zhe Zhao, Zhengwei Fang, Yifan Wang, Huanran Chen, Xiao Yang, Xingxing Wei, Hang Su, Yinpeng Dong, Jun Zhu'
paperurl: 'https://arxiv.org/pdf/2406.07057'
year: '2024'
code: 'https://github.com/thu-ml/MMTrustEval'
project: 'https://multi-trust.github.io'
data: 'https://huggingface.co/datasets/thu-ml/MultiTrust'
picture: "zhang2024benchmarking.png"
---
