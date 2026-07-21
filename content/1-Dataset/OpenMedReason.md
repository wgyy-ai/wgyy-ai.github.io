---
dataset_entry: true
dataset_name: "OpenMedReason"
dataset_path: "1-Dataset/OpenMedReason.md"
dimensions: "2D"
modality: "Medical image, text"
task_type: "Medical multiple-choice VQA, reasoning supervision"
anatomical_structures: "Biomedical figures and radiology-style questions"
anatomical_area: "Multi-region"
number_of_categories: ""
data_volume: "150,246 train / 1,150 test"
file_format: "parquet"
source_url: "https://huggingface.co/datasets/neginb/OpenMedReason"
publication_date: "2026"
tags:
  - dataset
---

# OpenMedReason

## Dataset Information

OpenMedReason is a medical vision-language reasoning dataset for image-grounded multiple-choice QA. The dataset card describes each example as pairing a biomedical image with a multiple-choice question and a structured reference reasoning trace that progresses from visual evidence to medical knowledge to clinical reasoning.

The public card reports 150,246 training examples and 1,150 held-out test examples, with the test split additionally including rubric units for evaluating perception, knowledge, and rationale quality rather than answer accuracy alone.

## Dataset Meta Information

| Dimensions | Modality | Task Type | Anatomical Structures | Anatomical Area | Number of Categories | Data Volume | File Format |
|------------|----------|-----------|-----------------------|-----------------|----------------------|-------------|-------------|
| 2D | Medical image, text | Medical multiple-choice VQA, reasoning supervision | Biomedical figures and radiology-style questions | Multi-region | TBD | 150,246 train / 1,150 test | parquet |

## Source Information

Official Website: https://huggingface.co/datasets/neginb/OpenMedReason

Download Link: https://huggingface.co/datasets/neginb/OpenMedReason

Article Address: https://arxiv.org/abs/2606.12169

Publication Date: 2026

## Citation

```bibtex
@article{baghbanzadeh2026openmedreason,
  title={OpenMedReason: Scientific Reasoning Supervision for Medical Vision-Language Models},
  author={Baghbanzadeh, Negin and Sarkar, Pritam and Colacci, Michael and Badawi, Abeer and Fallahpour, Adibvafa and Afkanpour, Arash and Sigal, Leonid and Etemad, Ali and Dolatabadi, Elham},
  journal={arXiv preprint arXiv:2606.12169},
  year={2026}
}
```
