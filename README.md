# KidLM

This is the official repository for our paper, titled ["KidLM: Advancing Language Models for Children – Early Insights and Future Directions,"](https://aclanthology.org/2024.emnlp-main.277/) published at the 2024 Conference on Empirical Methods in Natural Language Processing (EMNLP 2024).





## Abstract

> Recent studies highlight the potential of large language models in creating educational tools for children, yet significant challenges remain in maintaining key child-specific properties such as linguistic nuances, cognitive needs, and safety standards. In this paper, we explore foundational steps toward the development of child-specific language models, emphasizing the necessity of high-quality pre-training data. We introduce a novel user-centric data collection pipeline that involves gathering and validating a corpus specifically written for and sometimes by children. Additionally, we propose a new training objective, Stratified Masking, which dynamically adjusts masking probabilities based on our domain-specific child language data, enabling models to prioritize vocabulary and concepts more suitable for children. Experimental evaluations demonstrate that our model excels in understanding lower grade-level text, maintains safety by avoiding stereotypes, and captures children’s unique preferences. Furthermore, we provide actionable insights for future research and development in child-specific language modeling.


## KidLM (corpus)

The KidLM corpus consists of high-quality, child-appropriate content specifically written for children and occasionally by them. This content has been meticulously reviewed and validated by website editors or moderators to ensure suitability and to eliminate any inappropriate content or sensationalism. Our user-centric data collection pipeline with quality filtering is comprehensive, diverse, and carefully tailored for developing language models aimed at young audiences. 


Our corpus is available here: 🤗 [KidLM (corpus)](https://huggingface.co/datasets/tafseer-nayeem/KidLM-corpus)



## Licensing Information

Contents of this repository are restricted to only non-commercial research purposes under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/). Copyright of the dataset contents belongs to the original copyright holders.

---

## Citation Information

If you use any of the resources or it's relevant to your work, please cite our [EMNLP 2024 paper](https://aclanthology.org/2024.emnlp-main.277/). 

```
@inproceedings{nayeem-rafiei-2024-kidlm,
    title = "{K}id{LM}: Advancing Language Models for Children {--} Early Insights and Future Directions",
    author = "Nayeem, Mir Tafseer  and
      Rafiei, Davood",
    editor = "Al-Onaizan, Yaser  and
      Bansal, Mohit  and
      Chen, Yun-Nung",
    booktitle = "Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2024",
    address = "Miami, Florida, USA",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.emnlp-main.277",
    pages = "4813--4836",
    abstract = "Recent studies highlight the potential of large language models in creating educational tools for children, yet significant challenges remain in maintaining key child-specific properties such as linguistic nuances, cognitive needs, and safety standards. In this paper, we explore foundational steps toward the development of child-specific language models, emphasizing the necessity of high-quality pre-training data. We introduce a novel user-centric data collection pipeline that involves gathering and validating a corpus specifically written for and sometimes by children. Additionally, we propose a new training objective, Stratified Masking, which dynamically adjusts masking probabilities based on our domain-specific child language data, enabling models to prioritize vocabulary and concepts more suitable for children. Experimental evaluations demonstrate that our model excels in understanding lower grade-level text, maintains safety by avoiding stereotypes, and captures children{'}s unique preferences. Furthermore, we provide actionable insights for future research and development in child-specific language modeling.",
}
```