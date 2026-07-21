---
dataset_entry: true
dataset_name: "UniMed-5M"
dataset_path: "1-Dataset/UniMed-5M.md"
dimensions: "2D"
modality: "Medical image, text"
task_type: "Visual question answering, image-text-to-text, text-to-image, multimodal generation"
anatomical_structures: "8 imaging modalities in UniMedVL training data"
anatomical_area: "Multi-region"
number_of_categories: "3 parts"
data_volume: "5M+ samples"
file_format: "parquet"
source_url: "https://huggingface.co/datasets/General-Medical-AI/UniMed-5M"
publication_date: "2025"
tags:
  - dataset
---

# UniMed-5M

## Dataset Information

UniMed-5M is the multimodal training dataset introduced together with UniMedVL. Public Hugging Face materials describe the released repository as `UniMedVL-5M`, a unified medical multimodal dataset used for medical image generation and understanding across eight medical imaging modalities.

The dataset is organized into multiple parts covering generation/synthesis tasks, evaluation benchmarks, and broader multimodal understanding/generation resources. The public card states that the data are distributed mainly as Parquet metadata, with some subsets requiring users to obtain original source images separately.

## Dataset Meta Information

| Dimensions | Modality | Task Type | Anatomical Structures | Anatomical Area | Number of Categories | Data Volume | File Format |
|------------|----------|-----------|-----------------------|-----------------|----------------------|-------------|-------------|
| 2D | Medical image, text | Visual question answering, image-text-to-text, text-to-image, multimodal generation | 8 imaging modalities in UniMedVL training data | Multi-region | 3 parts | 5M+ samples | parquet |

## Source Information

Official Website: https://huggingface.co/datasets/General-Medical-AI/UniMed-5M

Download Link: https://huggingface.co/datasets/General-Medical-AI/UniMedVL-5M

Article Address: https://arxiv.org/abs/2510.15710

Publication Date: 2025

## Citation

```bibtex
@article{ning2025unimedvl,
  title={Unimedvl: Unifying medical multimodal understanding and generation through observation-knowledge-analysis},
  author={Ning, Junzhi and Li, Wei and Tang, Cheng and Lin, Jiashi and Ma, Chenglong and Zhang, Chaoyang and Liu, Jiyao and Chen, Ying and Gao, Shujian and Liu, Lihao and others},
  journal={arXiv preprint arXiv:2510.15710},
  year={2025}
}
```
