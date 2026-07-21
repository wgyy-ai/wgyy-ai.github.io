---
dataset_entry: true
dataset_name: "MedTrinity-25M"
dataset_path: "1-Dataset/MedTrinity-25M.md"
dimensions: "2D, 3D"
modality: "Multi-modality medical imaging, text"
task_type: "Captioning, report-style alignment, classification, segmentation, multimodal pretraining"
anatomical_structures: "65+ diseases and region annotations"
anatomical_area: "Multi-region"
number_of_categories: "10 modalities"
data_volume: "25M+ images"
file_format: "metadata.jsonl, image files"
source_url: "https://huggingface.co/datasets/UCSC-VLAA/MedTrinity-25M"
publication_date: "2024"
tags:
  - dataset
---

# MedTrinity-25M

## Dataset Information

MedTrinity-25M is a large-scale multimodal medical dataset covering more than 25 million images across 10 imaging modalities, with multigranular annotations for over 65 diseases. The dataset card emphasizes both global textual information and local region annotations, including bounding boxes and segmentation masks, and positions the resource for large-scale pretraining of medical multimodal foundation models.

The repository is gated on Hugging Face and includes a license table for constituent datasets. The card states that MedTrinity-25M aggregates multiple public medical datasets and preserves their original licensing requirements.

## Dataset Meta Information

| Dimensions | Modality | Task Type | Anatomical Structures | Anatomical Area | Number of Categories | Data Volume | File Format |
|------------|----------|-----------|-----------------------|-----------------|----------------------|-------------|-------------|
| 2D, 3D | Multi-modality medical imaging, text | Captioning, report-style alignment, classification, segmentation, multimodal pretraining | 65+ diseases and region annotations | Multi-region | 10 modalities | 25M+ images | metadata.jsonl, image files |

## Source Information

Official Website: https://huggingface.co/datasets/UCSC-VLAA/MedTrinity-25M

Download Link: https://huggingface.co/datasets/UCSC-VLAA/MedTrinity-25M

Article Address: https://arxiv.org/abs/2408.02900

Publication Date: 2024

## Citation

```bibtex
@misc{xie2024medtrinity25mlargescalemultimodaldataset,
  title={MedTrinity-25M: A Large-scale Multimodal Dataset with Multigranular Annotations for Medicine},
  author={Yunfei Xie and Ce Zhou and Lang Gao and Juncheng Wu and Xianhang Li and Hong-Yu Zhou and Sheng Liu and Lei Xing and James Zou and Cihang Xie and Yuyin Zhou},
  year={2024},
  eprint={2408.02900},
  archivePrefix={arXiv},
  primaryClass={cs.CV},
  url={https://arxiv.org/abs/2408.02900}
}
```
