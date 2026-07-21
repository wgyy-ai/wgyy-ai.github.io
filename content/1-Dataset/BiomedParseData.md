---
dataset_entry: true
dataset_name: "BiomedParseData"
dataset_path: "1-Dataset/BiomedParseData.md"
dimensions: "2D"
modality: "Biomedical image"
task_type: "Segmentation, detection, recognition"
anatomical_structures: "Biomedical objects across nine modalities"
anatomical_area: "Multi-region"
number_of_categories: "9 modalities"
data_volume: "6M+ image-mask-text triples"
file_format: ".png, processed ZIP subsets"
source_url: "https://huggingface.co/datasets/microsoft/BiomedParseData"
publication_date: "2025"
tags:
  - dataset
---

# BiomedParseData

## Dataset Information

BiomedParseData is the official processed dataset repository for BiomedParse, a biomedical foundation model for joint segmentation, detection, and recognition across nine imaging modalities. The dataset card states that each instance contains a 1024x1024 PNG image, a textual description of the target, and a binary ground-truth mask.

The associated Nature Methods paper reports that the training data comprises over 6 million triples of image, segmentation mask, and textual description derived from public biomedical datasets.

## Dataset Meta Information

| Dimensions | Modality | Task Type | Anatomical Structures | Anatomical Area | Number of Categories | Data Volume | File Format |
|------------|----------|-----------|-----------------------|-----------------|----------------------|-------------|-------------|
| 2D | Biomedical image | Segmentation, detection, recognition | Biomedical objects across nine modalities | Multi-region | 9 modalities | 6M+ image-mask-text triples | .png, processed ZIP subsets |

## Source Information

Official Website: https://huggingface.co/datasets/microsoft/BiomedParseData

Download Link: https://huggingface.co/datasets/microsoft/BiomedParseData

Article Address: https://doi.org/10.1038/s41592-024-02499-w

Publication Date: 2025

## Citation

```bibtex
@article{zhao2025foundation,
  title={A foundation model for joint segmentation, detection and recognition of biomedical objects across nine modalities},
  author={Zhao, Theodore and Gu, Yu and Yang, Jianwei and Usuyama, Naoto and Lee, Ho Hin and Kiblawi, Sid and Naumann, Tristan and Gao, Jianfeng and Crabtree, Angela and Abel, Jacob and others},
  journal={Nature Methods},
  volume={22},
  number={1},
  pages={166--176},
  year={2025}
}
```
