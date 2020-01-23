# [MoNuSAC grand-challenge](https://monusac-2020.grand-challenge.org/) organized at [ISBI 2020](http://2020.biomedicalimaging.org/)

This repository contains my implementations of the algorithms which MoNuSAC participants could use for data preparation to train their models at ISBI 2020

| **File name** | **Description** |
| ------------- | ------------- |
| [Binary mask_generation](https://github.com/ruchikaverma-iitg/MoNuSAC/blob/master/Mask_generation.ipynb) | Use H&E stained images(.svs) along with associated xml files to generate binary masks of each annotated cell-type|
| [n-ary mask_generation](https://github.com/ruchikaverma-iitg/MoNuSAC/blob/master/Binary_mask_generation.ipynb) | Use H&E stained images(.svs) along with associated xml files to generate n-ary masks of each annotated cell-type|
| [Cell_counting](https://github.com/ruchikaverma-iitg/MoNuSAC/blob/master/n-ary_mask_generation.ipynb) | Script to count cells (by type) in each image and store in an excel file|
