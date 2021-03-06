# AtrialGeneral

## Overview
The repository contains the core codes of "[AtrialGeneral: Domain Generalization for Left Atrial Segmentation of Multi-Center LGE MRIs](https://link.springer.com/chapter/10.1007/978-3-030-87231-1_54)".
The code includes four baseline models (U-Net, U-Net++, DeepLab v3+ and MAnet) and three model generalization schemes.
The schemes include histogram matching (HM), mutual information based disentangled representation, and random style transfer.

## Dataset
The dataset employed in this work is from:
[ISBI 2012: Left Atrium Fibrosis and Scar Segmentation Challenge](http://atriaseg2018.cardiacatlas.org/) and
[MICCAI 2018: Atrial Segmentation Challenge](http://www.cardiacatlas.org/challenges/left-atrium-fibrosis-and-scar-segmentation-challenge/)

## Cite
If this code is useful for you, please kindly cite this work via:

@InProceedings{conf/MICCAI/li2021,  
  title={Atrial{G}eneral: Domain Generalization for Left Atrial Segmentation of Multi-Center {LGE MRI}s},  
  author={Li, Lei and Zimmer, Veronika A and Schnabel, Julia A and Zhuang, Xiahai},     
  booktitle={Medical Image Computing and Computer Assisted Intervention},   
  pages={557--566},  
  year={2021}  
}  

If you have any questions, please contact lilei.sky@sjtu.edu.cn.
