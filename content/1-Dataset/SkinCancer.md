---
dataset_entry: true
dataset_name: "SkinCancer"
dataset_path: "1-Dataset/SkinCancer.md"
dimensions: ""
modality: ""
task_type: ""
anatomical_structures: ""
anatomical_area: ""
number_of_categories: ""
data_volume: ""
file_format: ""
source_url: "https://heidata.uni-heidelberg.de/dataset.xhtml?persistentId=doi:10.11588/data/7QCR8S"
publication_date: "2023-03"
tags:
  - dataset
---
# SkinCancer

<div align="center">
    <a href="https://github.com/openmedlab/"><img width="700px" height="auto" src="appendix/SkinCancer_0.png"></a>
</div>
<p style="text-align:center;font-size:10px;"><em></em></p>

## Dataset Information

The **SkinCancer dataset** is designed for the classification of skin pathology images, containing high-resolution annotated images of common skin tumors and non-tumorous anatomical tissues. The dataset comprises **386 cases**, covering the most prevalent types of skin tumors: **Basal Cell Carcinoma (BCC)**, **Squamous Cell Carcinoma (SqCC)**, and **Melanoma**, along with various non-tumorous tissues. The pathological slide images have undergone rigorous multi-level manual annotation, identifying **16 distinct tissue categories**, including structures such as epidermis, dermis, subcutaneous tissue, hair follicles, nerves, and sweat glands.

The dataset's slide images were sourced from the **Institute of Pathology at Heidelberg University (Germany)**, the **Trier Center for Cytological and Molecular Diagnostics**, and the **Hannover Institute of Dermatopathology**. All diagnoses follow the **World Health Organization (WHO) classification for skin tumors**. Slides containing tumor regions were scanned using automated slide scanners, and after quality review, a total of **129,364 image patches** were generated. These patches provide ample data for model training and evaluation, enabling researchers to develop, validate, and optimize deep learning models to support and enhance the pathology diagnostic workflow.

## Dataset Meta Information

| Dimensions | Modality  | Task Type      | Anatomical Structures | Number of Categories | Data Volume    | File Format |
|------------|-----------|----------------|-----------------------|----------------------|----------------|-------------|
| 2D         | Pathology | Classification | Skin                  | 16                   | 129,364        | JPG         |


### Resolution Details

| Dataset Statistics | spacing (渭m) | size        |
|--------------------|--------------|-------------|
| min                | (100, 100)   | (395, 395)  |
| median             | (100, 100)   | (395, 395)  |
| max                | (100, 100)   | (395, 395)  |

## Label Information Statistics

<div align="center">
    <a href="https://github.com/openmedlab/"><img width="700px" height="auto" src="appendix/SkinCancer_1.png"></a>
</div>
<p style="text-align:center;font-size:10px;"><em></em></p>

The Chinese and English categories correspond to:
槌炵姸缁嗚優鐧?Squamous cell carcinoma;
鍩哄簳缁嗚優鐧?Basal cell carcinoma;
榛戣壊绱犵槫 Melanoma;
鐥?Naevi;
琛ㄧ毊 Epidermis;
杞缁勭粐 Chondral tissue;
鐪熺毊 Dermis;
绁炵粡 Nerves;
鍧忔 Necrosis;
楠ㄩ鑲?Skeletal muscle;
姣涘泭 Hair follicles;
姹楄吅/灏忔睏鑵?Sweat glands/Eccrine glands;
鐨剛鑵?Sebaceous glands;
琛€绠?Vessels;
鐨笅缁勭粐 Subcutis;
寮瑰姏绾ょ淮閫€鍖?Elastosis

## Visualization

<div align="center">
    <a href="https://github.com/openmedlab/"><img width="700px" height="auto" src="appendix/SkinCancer_0.png"></a>
</div>
<p style="text-align:center;font-size:10px;"><em>Original paper visualization. Squamous cell carcinoma (A), basal cell carcinoma (B), melanoma (C), nevus (D), epidermis (E), cartilage (F), dermis (G), nerve (H), necrosis (I), skeletal muscle (J), hair follicle (K), sweat/eccrine glands (L), sebaceous glands (M), blood vessels (N), subcutaneous tissue (O), and elastic fiber degeneration (P).</em></p>

## File Structure

``` 
data
|--  class_dict.json
|--  tiles_v2.csv
|--  tiles/
|--  nontumor_skin_chondraltissue_chondraltissue
|--  nontumor_skin_dermis_dermis
|--  nontumor_skin_elastosis_elastosis
|--  nontumor_skin_chondraltissue_chondraltissu
`--  ...
```

## Authors and Institutions

Katharina Kriegsmann (Department of Hematology, Oncology and Rheumatology, Heidelberg University)

Frithjof Lobers (Department of Clinical Immunology, Medical Faculty, University of Leipzig)

Christiane Zgorzelski  (Institute of Pathology, Heidelberg University)

J枚rg Kriegsmann  (MVZ Histology, Cytology and Molecular Diagnostics Trier & Proteopath Trier )

Charlotte Jan脽en (Center for Industrial Mathematics (ZeTeM), University of Bremen)

Rolf R眉dinger Meli脽  (Center for Industrial Mathematics (ZeTeM), University of Bremen)

Thomas Muley (Translational Lung Research Centre (TLRC) Heidelberg, Member of the German Centre for Lung Research (DZL))

Ulrich Sack  (Department of Clinical Immunology, Medical Faculty, University of Leipzig)

Georg Steinbuss (Department of Hematology, Oncology and Rheumatology, Heidelberg University)

Mark Kriegsmann (Institute of Pathology, Heidelberg University)

## Source Information

Official Website: https://heidata.uni-heidelberg.de/dataset.xhtml?persistentId=doi:10.11588/data/7QCR8S

Download Link: https://heidata.uni-heidelberg.de/dataset.xhtml?persistentId=doi:10.11588/data/7QCR8S

Article Address: https://www.frontiersin.org/journals/oncology/articles/10.3389/fonc.2022.1022967/full

Publication Date: 2023-03

## Citation

``` 
@article{kriegsmann2022deep,
  title={Deep learning for the detection of anatomical tissue structures and neoplasms of the skin on scanned histopathological tissue sections},
  author={Kriegsmann, Katharina and Lobers, Frithjof and Zgorzelski, Christiane and Kriegsmann, J{\"o}rg and Jan{\ss}en, Charlotte and Meli{\ss}, Rolf R{\"u}dinger and Muley, Thomas and Sack, Ulrich and Steinbuss, Georg and Kriegsmann, Mark},
  journal={Frontiers in Oncology},
  volume={12},
  pages={1022967},
  year={2022},
  publisher={Frontiers Media SA}
}
```

Original introduction article is [here](https://zhuanlan.zhihu.com/p/6015868509).
