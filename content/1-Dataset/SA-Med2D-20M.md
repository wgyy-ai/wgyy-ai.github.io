---
dataset_entry: true
dataset_name: "SA-Med2D-20M"
dataset_path: "1-Dataset/SA-Med2D-20M.md"
dimensions: "2D"
modality: "Medical image"
task_type: "Segmentation"
anatomical_structures: "Segmentation masks across constituent public datasets"
anatomical_area: "Multi-region"
number_of_categories: ""
data_volume: "20M masks (16M currently released)"
file_format: ".png, .json"
source_url: "https://huggingface.co/datasets/OpenGVLab/SA-Med2D-20M"
publication_date: "2023"
tags:
  - dataset
---

# SA-Med2D-20M

## Dataset Information

SA-Med2D-20M is a large benchmark dataset for 2D medical image segmentation. The dataset card describes it as the largest benchmark dataset for segmentation in medical imaging and explains that, because of privacy and ethics constraints, the currently released portion contains 16M samples rather than the full planned 20M-scale resource.

The repository provides paired `images` and `masks` folders, along with class-mapping and path-index JSON files. It uses a naming convention that preserves source dataset name, modality, slice direction, and class-instance identifiers.

## Dataset Meta Information

| Dimensions | Modality | Task Type | Anatomical Structures | Anatomical Area | Number of Categories | Data Volume | File Format |
|------------|----------|-----------|-----------------------|-----------------|----------------------|-------------|-------------|
| 2D | Medical image | Segmentation | Segmentation masks across constituent public datasets | Multi-region | TBD | 20M masks (16M currently released) | .png, .json |

## Source Information

Official Website: https://huggingface.co/datasets/OpenGVLab/SA-Med2D-20M

Download Link: https://huggingface.co/datasets/OpenGVLab/SA-Med2D-20M

Article Address: https://arxiv.org/abs/2311.11969

Publication Date: 2023

## Citation

```bibtex
@misc{ye2023samed2d20m,
  title={SA-Med2D-20M Dataset: Segment Anything in 2D Medical Imaging with 20 Million Masks},
  author={Jin Ye and Junlong Cheng and Jianpin Chen and Zhongying Deng and Tianbin Li and Haoyu Wang and Yanzhou Su and Ziyan Huang and Jilong Chen and Lei Jiang and Hui Sun and Min Zhu and Shaoting Zhang and Junjun He and Yu Qiao},
  year={2023},
  eprint={2311.11969},
  archivePrefix={arXiv},
  primaryClass={eess.IV}
}
```
