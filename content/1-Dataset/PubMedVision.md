---
dataset_entry: true
dataset_name: "PubMedVision"
dataset_path: "1-Dataset/PubMedVision.md"
dimensions: "2D"
modality: "Image, text"
task_type: "Medical VQA, instruction tuning, caption alignment"
anatomical_structures: "Multi-organ and multi-modality medical concepts"
anatomical_area: "Multi-region"
number_of_categories: "4 subsets"
data_volume: "1,294,062 medical VQAs"
file_format: ".json, .zip"
source_url: "https://huggingface.co/datasets/FreedomIntelligence/PubMedVision"
publication_date: "2024"
tags:
  - dataset
---

# PubMedVision

## Dataset Information

PubMedVision is a large-scale medical VQA dataset built from PubMed image-text pairs and reformatted with GPT-4V to improve multimodal quality. The dataset card describes it as supporting both alignment and instruction-tuning settings for medical multimodal LLMs.

The public card lists four subsets, including `PubMedVision_Alignment_VQA`, `PubMedVision_InstructionTuning_VQA`, a Chinese version, and original captions. It reports 1,294,062 VQA items across the two main VQA subsets and a total file size of 59.5 GB.

## Dataset Meta Information

| Dimensions | Modality | Task Type | Anatomical Structures | Anatomical Area | Number of Categories | Data Volume | File Format |
|------------|----------|-----------|-----------------------|-----------------|----------------------|-------------|-------------|
| 2D | Image, text | Medical VQA, instruction tuning, caption alignment | Multi-organ and multi-modality medical concepts | Multi-region | 4 subsets | 1,294,062 medical VQAs | .json, .zip |

## Source Information

Official Website: https://huggingface.co/datasets/FreedomIntelligence/PubMedVision

Download Link: https://huggingface.co/datasets/FreedomIntelligence/PubMedVision

Article Address: https://arxiv.org/abs/2406.19280

Publication Date: 2024

## Citation

```bibtex
@misc{chen2024huatuogptvisioninjectingmedicalvisual,
  title={HuatuoGPT-Vision, Towards Injecting Medical Visual Knowledge into Multimodal LLMs at Scale},
  author={Junying Chen and Ruyi Ouyang and Anningzhe Gao and Shunian Chen and Guiming Hardy Chen and Xidong Wang and Ruifei Zhang and Zhenyang Cai and Ke Ji and Guangjun Yu and Xiang Wan and Benyou Wang},
  year={2024},
  eprint={2406.19280},
  archivePrefix={arXiv},
  primaryClass={cs.CV},
  url={https://arxiv.org/abs/2406.19280}
}
```
