# [MoNuSAC grand-challenge](https://monusac-2020.grand-challenge.org/) organized at [ISBI 2020](https://biomedicalimaging.org/2020/wp-content/uploads/static-html-to-wp/data/dff0d41695bbae509355435cd32ecf5d/challenges.html)

Please cite the following paper if you use this repository-

[Verma, Ruchika, et al. "MoNuSAC2020: A Multi-organ Nuclei Segmentation and Classification Challenge." IEEE Transactions on Medical Imaging (2021)](https://ieeexplore.ieee.org/abstract/document/9446924)

| **File name** | **Description** |
| ------------------------ | ------------- |
| [Cell_counting](https://github.com/ruchikaverma-iitg/MoNuSAC/blob/master/Cell_counting.ipynb) | Script to count cells (by type) in each image and store in an excel file|
| [Binary_mask_generation](https://github.com/ruchikaverma-iitg/MoNuSAC/blob/master/Binary_mask_generation.ipynb) | Use H&E stained images(.svs) along with associated xml files to generate binary masks of each annotated cell-type|
| [n-ary_mask_generation](https://github.com/ruchikaverma-iitg/MoNuSAC/blob/master/n-ary_mask_generation.ipynb) | Use H&E stained images(.svs) along with associated xml files to generate n-ary masks of each annotated cell-type|
| [Compute_PQ_metric](https://github.com/ruchikaverma-iitg/MoNuSAC/blob/master/PQ_metric.ipynb) | Script to compute Panoptic Quality metric for each n-ary mask image, and store image names and respective PQ values in an excel file |

