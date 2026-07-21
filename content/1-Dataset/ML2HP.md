---
dataset_entry: true
dataset_name: "ML2HP"
dataset_path: "1-Dataset/ML2HP.md"
dimensions: ""
modality: ""
task_type: ""
anatomical_structures: ""
anatomical_area: ""
number_of_categories: ""
data_volume: ""
file_format: ""
source_url: "https://www.nature.com/articles/s41597-024-03968-9?_gl=1*ikljf0*_up*MQ..&gclid=Cj0KCQjwpvK4BhDUARIsADHt9sTKeJdkTiVgts02Lx7tkFajPSGA9upeXML9AePHRgmojqIZejtL75kaAktZEALw_wcB"
publication_date: "2024-09"
tags:
  - dataset
---
# ML2HP

<div align="center">
    <a href="https://github.com/openmedlab/"><img width="700px" height="auto" src="appendix/ML2HP_0.webp"></a>
</div>
<p style="text-align:center;font-size:10px;"><em></em></p>

## Dataset Information

**Hand pose recognition based on computer vision** is a fascinating component of human-computer interface design. It enables the identification and understanding of hand configurations and movements. This field can be framed within the broader context of **human activity recognition**, a domain where vision-based methods have attracted significant interest and exploration. These methods aim to understand and interpret human behaviors and actions through visual data. Specifically, hand pose recognition spans a diverse range of applications, from **virtual reality (VR)** and **augmented reality (AR)** to **sign language recognition** and **gesture-based interfaces**. At its core, hand pose recognition seeks to bridge the gap between human communication methods and digital systems, enabling seamless interaction between users and technology through natural hand gestures and movements.

### **Limitations of Existing Datasets**
To advance the field of hand pose recognition, several notable datasets have been developed, each presenting interesting features and certain limitations. Most existing datasets focus on **sign language recognition tasks**, while others include general hand poses for human-computer interaction applications. While valuable for training multi-view hand pose estimation models due to their large number of instances, these datasets often rely heavily on **synthetic data**. This reliance can limit the applicability of the datasets in real-world scenarios, as they may fail to fully capture the complexity and variability of real human hands. This critical limitation affects the generalization capabilities of models trained on such datasets. Additionally, existing datasets often include a limited number of instances and artificially substitute sets with random backgrounds, providing hand poses in constrained environments.

### **Proposed Dataset: ML2HP**
To address these limitations, the proposed dataset introduces a **multi-view dataset recorded using the Leap Motion Controller 2**, a cutting-edge device capable of capturing both accurate hand landmarks and images simultaneously. This dual capability allows for the creation of a richly detailed dataset, offering comprehensive visual data and precise landmark information that is crucial for developing and testing advanced hand pose recognition systems. By using this new device, the dataset ensures unmatched accuracy in capturing the nuances of hand movements and poses, enhancing its value for research and applications in various technical fields.

The **dual-view setup** of the device mitigates ambiguities that may arise from a single viewpoint by capturing details that might be occluded in one view but visible in another. This allows for more accurate detection of hand poses. The dataset offers a new opportunity to address challenges such as **pose variations** and **occlusions**, effectively leveraging the information from two cameras. Furthermore, its versatility extends to scenarios where only a single camera viewpoint is available, enabling the evaluation of hand pose recognition systems under constrained conditions. This dual functionality not only enhances the robustness and adaptability of recognition models but also provides valuable insights into the trade-offs between multi-view and single-view approaches.

### **Key Contributions**
1. **Introduction of the ML2HP Dataset**:  
   - A novel **multi-view Leap2 hand pose dataset**, the first dataset captured using a **Leap Motion Controller 2** multi-view recording setup.  
   - It comprehensively covers diverse hand poses from different angles.

2. **Data Collection with Leap Motion Controller 2**:  
   - The dataset leverages the capabilities of the Leap Motion Controller 2, including **images** and **precise frame-level automatic hand attributes**, enhancing its richness and usability.

3. **Balanced Variability Across Subjects, Hand Poses, and Usage**:  
   - The dataset features diverse subjects, hand poses, and hand usage (right or left hand), ensuring variability, balance, and richness in recorded instances.  
   - This variability supports the development of robust and generalized hand pose recognition models trained on the dataset.

## Dataset Meta Information

| Dimension | Modality       | Task Type | Anatomical Structure | Number of Classes | Quantity | File Format   |
|-----------|----------------|-----------|-----------------------|-------------------|----------|---------------|
| 2D        | Multimodal: RGB + Text | Classification | Hand                 | 17                | 714,000  | .bmp, .csv    |

| ID  | Label (English)                                                                                                          | Label (Chinese)                  |
|-----|--------------------------------------------------------------------------------------------------------------------------|----------------------------------|
| 0   | Open Palm, where all fingers are extended and spread apart.                                                              | 寮犲紑鎵嬫帉锛屾墍鏈夋墜鎸囦几灞曞苟鍒嗗紑銆?                 |
| 1   | Closed Fist, with all fingers clenched into the palm.                                                                    | 鎻℃嫵锛屾墍鏈夋墜鎸囩揣鎻″湪鎵嬫帉涓€?                  |
| 2   | One, where only the index finger is extended with the other fingers clenched.                                            | 鏁板瓧涓€锛屽彧鏈夐鎸囦几灞曪紝鍏朵粬鎵嬫寚绱ф彙銆?              |
| 3   | Two, with the index and middle fingers extended together and the remaining fingers clenched.                             | 鏁板瓧浜岋紝椋熸寚鍜屼腑鎸囦竴璧蜂几灞曪紝鍏朵綑鎵嬫寚绱ф彙銆?           |
| 4   | Three, where the index, middle, and ring fingers are extended.                                                           | 鏁板瓧涓夛紝椋熸寚銆佷腑鎸囧拰鏃犲悕鎸囦竴璧蜂几灞曪紝鑰屽皬鎸囧拰鎷囨寚绱ф彙銆?     |
| 5   | Four, with all fingers except the thumb extended and held together.                                                      | 鏁板瓧鍥涳紝闄や簡鎷囨寚澶栨墍鏈夋墜鎸囦几灞曞苟鎷€?              |
| 6   | Stop, involving the hand held with the palm facing outward and all fingers extended together, resembling a stop gesture. | 鍋滄鎵嬪娍锛屾墜鎺屽悜澶栵紝鎵€鏈夋墜鎸囦竴璧蜂几灞曪紝绫讳技浜庡仠姝㈢殑鎵嬪娍銆?    |
| 7   | Like, featuring the thumb extended upward with the other fingers clenched into a fist.                                   | 鐐硅禐锛屾媷鎸囧悜涓婁几灞曪紝鍏朵粬鎵嬫寚绱ф彙鎴愭嫵銆?             |
| 8   | Dislike, with the thumb extended downward and the other fingers clenched into a fist.                                    | 涓嶅枩娆紝鎷囨寚鍚戜笅浼稿睍锛屽叾浠栨墜鎸囩揣鎻℃垚鎷炽€?            |
| 9   | Call, where the thumb and pinky fingers are extended.                                                                    | 鎵撶數璇濓紝鎷囨寚鍜屽皬鎸囦几灞曘€?                    |
| 10  | OK Sign, with the thumb and index finger forming a circle while the other fingers are extended.                          | OK鎵嬪娍锛屾媷鎸囧拰椋熸寚褰㈡垚涓€涓渾鍦堬紝鑰屽叾浠栨墜鎸囦几灞曘€?       |
| 11  | Spiderman, where the fist is clenched while the thumb, index, and pinky are extended.                                    | 铚樿洓渚犳墜鍔匡紝鎷冲ご绱ф彙锛屾媷鎸囥€侀鎸囧拰灏忔寚浼稿睍銆?          |
| 12  | Rock, where the fist is clenched while the index and pinky are extended.                                                 | 鐭冲ご鎵嬪娍锛屾嫵澶寸揣鎻★紝椋熸寚鍜屽皬鎸囦几灞曘€?              |
| 13  | Tiger, with all fingers extended and slightly curled, emphasizing the nails.                                             | 鑰佽檸鎵嬪娍锛屾墍鏈夋墜鎸囦几灞曞苟鐣ュ井寮洸锛屽己璋冩寚鐢层€?          |
| 14  | Spok, with the middle and ring fingers separated, creating a "V" shape, while the thumb is extended away from the palm.  | 鐡﹁偗鎵嬪娍锛屼腑鎸囧拰鏃犲悕鎸囧垎寮€锛屽舰鎴愪竴涓€淰鈥濆舰锛屾媷鎸囪繙绂绘墜鎺屼几灞曘€?|
| 15  | L, where the thumb and index finger are extended perpendicular to each other forming an L shape.                         | L褰㈡墜鍔匡紝鎷囨寚鍜岄鎸囦几灞曞苟鍨傜洿浜庡郊姝わ紝褰㈡垚涓€涓狶褰€?      |
| 16  | C, with the thumb and rest of fingers curved to form a C shape.                                                          | C褰㈡墜鍔匡紝鎷囨寚鍜屽叾浣欐墜鎸囧集鏇插舰鎴愪竴涓狢褰€?           |


## Data Visualizatin

<div align="center">
    <a href="https://github.com/openmedlab/"><img width="700px" height="auto" src="appendix/ML2HP_1.png"></a>
</div>
<p style="text-align:center;font-size:10px;"><em>Figure 1. Samples of each gesture.</em></p>

<div align="center">
    <a href="https://github.com/openmedlab/"><img width="700px" height="auto" src="appendix/ML2HP_2.png"></a>
</div>
<p style="text-align:center;font-size:10px;"><em>Figure 2. An example of information about finger joints and coordinates of finger landmarks.</em></p>

<div align="center">
    <a href="https://github.com/openmedlab/"><img width="700px" height="auto" src="appendix/ML2HP_3.png"></a>
</div>
<p style="text-align:center;font-size:10px;"><em>Figure 3. Example images and 2D landmark representations of different categories acquired using both devices.</em></p>

## File Structure

``` 
MultiViewLeap2_Dataset
|--  subjects_info.csv
|--  001
|--  Right_Hand
|    |    |--  OpenPalm
|    |    |    |--  Horizontal
|    |    |    |    |--  hand_properties.csv
|    |    |    |    `--  images
|    |    |    |        |--  001_left.bmp
|    |    |    |        |--  001_right.bmp
|    |    |    |        |--  ...
|    |    |    |        `--  1000_right.bmp
|    |    |    |--  Vertical
|    |    |        |--  hand_properties.csv
|    |    |        `--  images
|    |    |            |--  001_left.bmp
|    |    |            |--  001_right.bmp
|    |    |            |--  ...
|    |    |            `--  1000_right.bmp
|    |    |--  ClosedFist
|    |    |    `--  ...
|    |    |--  One
|    |    |    `--  ...
|    |    |--  Two
|    |    |    `--  ...
|    |    |--  Three
|    |    |    `--  ...
|    |    |--  Four
|    |    |    `--  ...
|    |    |--  Stop
|    |    |    `--  ...
|    |    |--  Like
|    |    |    `--  ...
|    |    |--  Dislike
|    |    |    `--  ...
|    |    |--  Call
|    |    |    `--  ...
|    |    |--  OK
|    |    |    `--  ...
|    |    |--  Spiderman
|    |    |    `--  ...
|    |    |--  Rock
|    |    |    `--  ...
|    |    |--  Tiger
|    |    |    `--  ...
|    |    |--  Spok
|    |    |    `--  ...
|    |    |--  L
|    |    |    `--  ...
|    |    |--  C
|    |        `--  ...
|--  Left_Hand
`--  ...
|--  002
`--  ...
|--  ...
`--  021
`--  ...
```

## Authors and Institutions

- Manuel Gil-Mart铆n (Universidad Polit茅cnica de Madrid)  

- Marco Raoul Marini (Sapienza University)  

- Rub茅n San-Segundo (Universidad Polit茅cnica de Madrid)  

- Luigi Cinque (Sapienza University)  

## Source Information

Official Website: https://www.nature.com/articles/s41597-024-03968-9?_gl=1*ikljf0*_up*MQ..&gclid=Cj0KCQjwpvK4BhDUARIsADHt9sTKeJdkTiVgts02Lx7tkFajPSGA9upeXML9AePHRgmojqIZejtL75kaAktZEALw_wcB

Download Link: https://edatos.consorciomadrono.es/dataset.xhtml?persistentId=doi:10.21950/ZKWE6Z

Article Address: https://www.nature.com/articles/s41597-024-03968-9.pdf?_gl=1*wlvrzr*_up*MQ..&gclid=Cj0KCQjwpvK4BhDUARIsADHt9sTKeJdkTiVgts02Lx7tkFajPSGA9upeXML9AePHRgmojqIZejtL75kaAktZEALw_wcB

Publication Date: 2024-09

## Citation

``` 
@article{gil2024dual,
  title={Dual Leap Motion Controller 2: A Robust Dataset for Multi-view Hand Pose Recognition},
  author={Gil-Mart{\'\i}n, Manuel and Marini, Marco Raoul and San-Segundo, Rub{\'e}n and Cinque, Luigi},
  journal={Scientific Data},
  volume={11},
  number={1},
  pages={1102},
  year={2024},
  publisher={Nature Publishing Group UK London}
}
```

Original introduction article is [here](https://zhuanlan.zhihu.com/p/3343880507).
