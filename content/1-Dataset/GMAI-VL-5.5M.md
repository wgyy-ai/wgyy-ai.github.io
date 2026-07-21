---
dataset_entry: true
dataset_name: "GMAI-VL-5.5M"
dataset_path: "1-Dataset/GMAI-VL-5.5M.md"
dimensions: "2D"
modality: "Image, Text, Tabular"
task_type: "Visual Question Answering, Image-Text-to-Text, Medical QA"
anatomical_structures: "Multiple organs, lesions, tissues, and clinical concepts"
anatomical_area: "Multi-region"
number_of_categories: "5 subsets"
data_volume: "5.5M QA pairs"
file_format: ".jsonl, .zip"
source_url: "https://huggingface.co/datasets/General-Medical-AI/GMAI-VL-5.5M"
publication_date: "2026"
tags:
  - dataset
---

# GMAI-VL-5.5M

## Dataset Information

GMAI-VL-5.5M is a large-scale medical vision-language dataset designed for training general medical multimodal foundation models. According to the Hugging Face dataset card, it contains more than 5.5 million high-quality multimodal question-answering pairs constructed from hundreds of medical classification, segmentation, and detection datasets.

The repository combines open-source and non-open-source portions under a single Hugging Face dataset. The open-source split includes redistributable image data and annotations, while the non-open-source split provides annotation files only; users must separately obtain the restricted source images from the original dataset providers and place them in the expected local directory structure.

The dataset is organized into five task-oriented subsets: `GMAI-MM-Caption` (1.7M), `GMAI-MM-Percept` (1.3M), `GMAI-MM-Instrunct` (0.9M), `GMAI_Text_Single` (1M), and `GMAI_Text_Multi` (0.7M). The dataset card states that all entries follow a LLaVA-style conversation format for direct multimodal training integration.

## Dataset Meta Information

| Dimensions | Modality | Task Type | Anatomical Structures | Anatomical Area | Number of Categories | Data Volume | File Format |
|------------|----------|-----------|-----------------------|-----------------|----------------------|-------------|-------------|
| 2D | Image, Text, Tabular | Visual Question Answering, Image-Text-to-Text, Medical QA | Multiple organs, lesions, tissues, and clinical concepts | Multi-region | 5 subsets | 5.5M QA pairs | .jsonl, .zip |

## Label Information Statistics

| Subset | Size | Type | Description |
|--------|------|------|-------------|
| GMAI-MM-Caption | 1.7M | Multimodal | High-quality medical image captions |
| GMAI-MM-Percept | 1.3M | Multimodal | Medical image classification and segmentation labels |
| GMAI-MM-Instrunct | 0.9M | Multimodal | Medical image analysis instruction QA |
| GMAI_Text_Single | 1.0M | Text-only | Single-turn medical text QA |
| GMAI_Text_Multi | 0.7M | Text-only | Multi-turn medical text QA |

## Visualization

The Hugging Face dataset card does not expose a working dataset viewer at the time of access. It provides an example LLaVA-style record with an `image` field and a `conversations` list containing human and model turns.

## File Structure

The dataset card describes the repository layout as follows:

```text
General-Medical-AI/GMAI-VL-5.5M/
├── GMAI-VL-5.5M-NonOpenSource/
│   └── annotations/
│       ├── GMAI-MM-Caption-1.7M.jsonl
│       ├── GMAI-MM-Instrunct-0.9M.jsonl
│       └── GMAI-MM-Percept-1.3M.jsonl
└── GMAI-VL-5.5M-OpenSource/
    ├── annotations/
    │   ├── GMAI-MM-Caption-1.7M.jsonl
    │   ├── GMAI-MM-Instrunct-0.9M.jsonl
    │   ├── GMAI-MM-Percept-1.3M.jsonl
    │   ├── GMAI_Text_Multi_0.7M.jsonl
    │   └── GMAI_Text_Single_1M.jsonl
    ├── zips/
    │   ├── images_chunk_001.zip
    │   ├── images_chunk_002.zip
    │   └── ...
    ├── download_and_prepare.py
    ├── README.md
    └── README_zh-CN.md
```

## Authors and Institutions

The dataset card citation lists the following leading authors:

Tianbin Li  
Yanzhou Su  
Wei Li  
Bin Fu  
Zhe Chen  
Ziyan Huang  
Guoan Wang  
Chenglong Ma  
Ying Chen  
Ming Hu  
and others

The Hugging Face dataset card page accessed here does not clearly enumerate institutional affiliations.

## Source Information

Official Website: https://huggingface.co/datasets/General-Medical-AI/GMAI-VL-5.5M

Download Link: https://huggingface.co/datasets/General-Medical-AI/GMAI-VL-5.5M

Article Address: https://arxiv.org/abs/2411.14522

Publication Date: 2026

## Citation

```bibtex
@inproceedings{li2026gmai,
  title={Gmai-vl \& gmai-vl-5.5 m: A large vision-language model and a comprehensive multimodal dataset towards general medical ai},
  author={Li, Tianbin and Su, Yanzhou and Li, Wei and Fu, Bin and Chen, Zhe and Huang, Ziyan and Wang, Guoan and Ma, Chenglong and Chen, Ying and Hu, Ming and others},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={40},
  number={28},
  pages={23177--23185},
  year={2026}
}
```

Original source page: [Hugging Face dataset card](https://huggingface.co/datasets/General-Medical-AI/GMAI-VL-5.5M).
