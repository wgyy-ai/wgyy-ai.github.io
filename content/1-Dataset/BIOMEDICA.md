---
dataset_entry: true
dataset_name: "BIOMEDICA"
dataset_path: "1-Dataset/BIOMEDICA.md"
dimensions: "2D"
modality: "Biomedical image, text"
task_type: "Image-caption pretraining corpus"
anatomical_structures: "Biomedical figures from open scientific literature"
anatomical_area: "Multi-region"
number_of_categories: "27+ metadata fields"
data_volume: "24M image-caption pairs"
file_format: "WebDataset"
source_url: "https://huggingface.co/datasets/BIOMEDICA/biomedica_webdataset_24M"
publication_date: "2025"
tags:
  - dataset
---

# BIOMEDICA

## Dataset Information

BIOMEDICA is an open biomedical image-caption archive derived from the PubMed Central Open Access subset. The dataset card states that it contains over 24 million image-caption pairs and 30 million image references drawn from 6 million unique open-source articles, with rich article-level and image-level metadata.

The Hugging Face release `biomedica_webdataset_24M` is a WebDataset-serialized version optimized for streaming and large-scale model development. The project page positions BIOMEDICA as a biomedical analogue to large open-domain vision-language corpora.

## Dataset Meta Information

| Dimensions | Modality | Task Type | Anatomical Structures | Anatomical Area | Number of Categories | Data Volume | File Format |
|------------|----------|-----------|-----------------------|-----------------|----------------------|-------------|-------------|
| 2D | Biomedical image, text | Image-caption pretraining corpus | Biomedical figures from open scientific literature | Multi-region | 27+ metadata fields | 24M image-caption pairs | WebDataset |

## Source Information

Official Website: https://huggingface.co/datasets/BIOMEDICA/biomedica_webdataset_24M

Download Link: https://huggingface.co/datasets/BIOMEDICA/biomedica_webdataset_24M

Article Address: https://arxiv.org/abs/2501.07171

Publication Date: 2025

## Citation

```bibtex
@misc{lozano2025biomedicaopenbiomedicalimagecaption,
  title={BIOMEDICA: An Open Biomedical Image-Caption Archive, Dataset, and Vision-Language Models Derived from Scientific Literature},
  author={Alejandro Lozano and Min Woo Sun and James Burgess and Liangyu Chen and Jeffrey J Nirschl and Jeffrey Gu and Ivan Lopez and Josiah Aklilu and Austin Wolfgang Katzer and Collin Chiu and Anita Rau and Xiaohan Wang and Yuhui Zhang and Alfred Seunghoon Song and Robert Tibshirani and Serena Yeung-Levy},
  year={2025},
  eprint={2501.07171},
  archivePrefix={arXiv},
  primaryClass={cs.CV},
  url={https://arxiv.org/abs/2501.07171}
}
```
