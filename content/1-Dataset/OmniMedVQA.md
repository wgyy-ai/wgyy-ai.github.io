---
dataset_entry: true
dataset_name: "OmniMedVQA"
dataset_path: "1-Dataset/OmniMedVQA.md"
dimensions: "2D"
modality: "Medical image, text"
task_type: "Medical visual question answering benchmark"
anatomical_structures: "Questions over 73 source datasets"
anatomical_area: "20+ anatomical regions"
number_of_categories: "12 modalities"
data_volume: "127,995 QA items / 118,010 images"
file_format: "benchmark annotations, image references"
source_url: "https://openxlab.org.cn/datasets/GMAI/OmniMedVQA"
publication_date: "2024"
tags:
  - dataset
---

# OmniMedVQA

## Dataset Information

OmniMedVQA is a large-scale medical VQA benchmark introduced for evaluating medical large vision-language models on authentic medical imagery rather than narrowly scoped or synthetic benchmarks. Public mirrors and the associated paper describe it as being collected from 73 medical datasets, covering 12 imaging modalities and more than 20 anatomical regions.

The benchmark contains 118,010 images and 127,995 QA items. Its released task formulation is primarily closed-ended multiple-choice VQA, created from source medical datasets through curated and template-based conversion.

## Dataset Meta Information

| Dimensions | Modality | Task Type | Anatomical Structures | Anatomical Area | Number of Categories | Data Volume | File Format |
|------------|----------|-----------|-----------------------|-----------------|----------------------|-------------|-------------|
| 2D | Medical image, text | Medical visual question answering benchmark | Questions over 73 source datasets | 20+ anatomical regions | 12 modalities | 127,995 QA items / 118,010 images | benchmark annotations, image references |

## Source Information

Official Website: https://openxlab.org.cn/datasets/GMAI/OmniMedVQA

Download Link: https://openxlab.org.cn/datasets/GMAI/OmniMedVQA

Article Address: https://arxiv.org/abs/2402.09181

Publication Date: 2024

## Citation

```bibtex
@article{hu2024omnimedvqa,
  title={OmniMedVQA: A New Large-Scale Comprehensive Evaluation Benchmark for Medical LVLM},
  author={Hu, Yutao and Li, Tianbin and Lu, Quanfeng and Shao, Wenqi and He, Junjun and Qiao, Yu and Luo, Ping},
  journal={arXiv preprint arXiv:2402.09181},
  year={2024}
}
```
