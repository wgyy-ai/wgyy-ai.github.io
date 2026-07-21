---
dataset_entry: true
dataset_name: "Corneal Nerve Tortuosity Dataset"
dataset_path: "1-Dataset/Corneal_Nerve_Tortuosity.md"
dimensions: "2D"
modality: "Microscopy Images"
task_type: "Classification"
anatomical_structures: "Eye"
anatomical_area: "Head"
number_of_categories: "3"
data_volume: "30"
file_format: ".tif"
source_url: "http://bioimlab.dei.unipd.it/Corneal%20Nerve%20Tortuosity%20Data%20Set.htm"
publication_date: "2011-08"
tags:
  - dataset
---
# Corneal Nerve Tortuosity Dataset

<div align="center">
    <a href="https://github.com/openmedlab/"><img width="500px" height="auto" src="appendix/Corneal_Nerve_Tortuosity_0.avif"></a>
</div>
<p style="text-align:center;font-size:10px;"><em> </em></p>

## Dataset Information

This dataset contains 30 confocal laser scanning microscopy images of sub-basal corneal nerve plexus. Each image in the dataset comes from different subjects, specifically including patients with diabetes, pseudoexfoliation syndrome, keratoconus, or healthy individuals. In each image, the corneal nerves have been categorized by medical experts into one of three levels of tortuosity: low, medium, or high. The sub-basal corneal nerve structure provides important clinical information about human aging, eye diseases, and more, and a key characteristic of the sub-basal corneal nerve structure is its degree of nerve tortuosity. The provided Corneal Nerve Tortuosity dataset can assist researchers in developing corresponding algorithmic models to evaluate the degree of tortuosity in sub-basal corneal nerves.

## Dataset Meta Information

| Dimensions | Modality | Task Type       | Anatomical Structures | Anatomical Area | Number of Categories | Data Volume | File Format |
|------------|----------|-----------------|-----------------------|-----------------|----------------------|-------------|-------------|
| 2D         | Microscopy Images       | Classification  | Eye                   | Head            | 3                    | 30          | .tif        |


### Resolution Details

| Dataset Statistics | size        |
|--------------------|-------------|
| min                | [384,384]  |
| median             | [384,384]  |
| max                | [384,384]  |

## Label Information Statistics

| Category            | Number |
|---------------------|--------|
| Distortion - Low    | 10     |
| Distortion - Middle | 10     |
| Distortion - High   | 10     |

## Visualization

<div align="center">
    <a href="https://github.com/openmedlab/"><img width="700px" height="auto" src="appendix/Corneal_Nerve_Tortuosity_1.webp"></a>
</div>
<p style="text-align:center;font-size:10px;"><em> Distortion - Low Example. </em></p>

<div align="center">
    <a href="https://github.com/openmedlab/"><img width="700px" height="auto" src="appendix/Corneal_Nerve_Tortuosity_2.webp"></a>
</div>
<p style="text-align:center;font-size:10px;"><em> Distortion - Middle Example. </em></p>

<div align="center">
    <a href="https://github.com/openmedlab/"><img width="700px" height="auto" src="appendix/Corneal_Nerve_Tortuosity_3.webp"></a>
</div>
<p style="text-align:center;font-size:10px;"><em> Distortion - High Example. </em></p>

## File Structure

The dataset's file structure is as follows, containing 30 .tif images and a PDF file that provides the corresponding labels for all the images.

``` 
Corneal Nerve Tortuosity Dataset
|--  image01.tif
|--  image02.tif
|--   ...
|--  Manual grading table.pdf
```

## Authors and Institutions

Fabio Scarpa锛圲niversity of Padua, Italy锛?
Xiaodong Zheng锛圗hime University School of Medicine, Japan锛?
Yuichi Ohashi锛圗hime University School of Medicine, Japan锛?
Alfredo Ruggeri锛圲niversity of Padua, Italy锛?

## Source Information

Official Website: http://bioimlab.dei.unipd.it/Corneal%20Nerve%20Tortuosity%20Data%20Set.htm

Download Link: http://bioimlab.dei.unipd.it/Corneal%20Nerve%20Tortuosity%20Data%20Set.htm

Article Address: https://iovs.arvojournals.org/article.aspx?articleid=2187659

Publication Date: 2011-08

## Citation

``` 
@article{scarpa2011automatic,
  title={Automatic evaluation of corneal nerve tortuosity in images from in vivo confocal microscopy},
  author={Scarpa, Fabio and Zheng, Xiaodong and Ohashi, Yuichi and Ruggeri, Alfredo},
  journal={Investigative ophthalmology \& visual science},
  volume={52},
  number={9},
  pages={6404--6408},
  year={2011},
  publisher={The Association for Research in Vision and Ophthalmology}
}
```

Original introduction article is [here](https://zhuanlan.zhihu.com/p/667442146).
