---
dataset_entry: true
dataset_name: "MedVision"
dataset_path: "1-Dataset/MedVision.md"
dimensions: "2D, 3D"
modality: "CT, MRI, X-ray, ultrasound, PET"
task_type: "Quantitative medical image analysis, detection, segmentation, measurement"
anatomical_structures: "Multi-anatomy quantitative annotations"
anatomical_area: "Multi-region"
number_of_categories: "22 public datasets"
data_volume: "30.8M image-annotation pairs"
file_format: "annotation repo + source-linked raw images"
source_url: "https://huggingface.co/datasets/YongchengYAO/MedVision"
publication_date: "2025"
tags:
  - dataset
---

# MedVision

## Dataset Information

MedVision is a large-scale benchmark dataset for quantitative medical image analysis. Public sources around the dataset and the associated MedVision-V0 model describe it as containing 30.8 million image-annotation pairs aggregated from 22 public datasets, focused on detection, lesion-size estimation, and angle/distance measurement tasks.

The Hugging Face dataset page indicates that the repository distributes annotations and loading code rather than all raw images directly. Users download source data separately, while the MedVision scripts handle acquisition and preprocessing.

## Dataset Meta Information

| Dimensions | Modality | Task Type | Anatomical Structures | Anatomical Area | Number of Categories | Data Volume | File Format |
|------------|----------|-----------|-----------------------|-----------------|----------------------|-------------|-------------|
| 2D, 3D | CT, MRI, X-ray, ultrasound, PET | Quantitative medical image analysis, detection, segmentation, measurement | Multi-anatomy quantitative annotations | Multi-region | 22 public datasets | 30.8M image-annotation pairs | annotation repo + source-linked raw images |

## Source Information

Official Website: https://huggingface.co/datasets/YongchengYAO/MedVision

Download Link: https://huggingface.co/datasets/YongchengYAO/MedVision

Article Address: https://arxiv.org/abs/2511.18676

Publication Date: 2025

## Citation

```bibtex
@article{yao2025medvision,
  title={MedVision: Benchmarking Quantitative Medical Image Analysis},
  author={Yao, Yongcheng and Zong, Yongshuo and Dutt, Raman and Yang, Yongxin and Tsaftaris, Sotirios A and Hospedales, Timothy},
  journal={arXiv preprint arXiv:2511.18676},
  year={2025}
}
```
