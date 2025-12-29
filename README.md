# U-Mamba
This repo contains the implementation of SSM-Mamba layer at different blocks of U-Net architecture

## Dataset Description
The <bold>CVC-ClinicDB dataset</bold> is a publicly available
benchmark designed for the evaluation of computer-aided
diagnosis (CAD) systems in colonoscopy image analysis.
It comprises a collection of colonoscopy images extracted
from clinical procedures, where each image is accompanied
by expert-annotated ground truth segmentation masks that
highlight polyp regions. The dataset was developed by the
Computer Vision Center (CVC) at the Universitat Autònoma
de Barcelona (UAB) and has been widely used for training
and evaluating segmentation algorithms. The CVC-ClinicDB
dataset contains 612 frames from colonoscopy videos, sourced
from 25 different video studies, with at least one sequence
per study featuring a polyp. The dataset includes 29 distinct
sequences, with frames selected to show various viewpoints
of the polyps. Each frame is paired with a ground truth mask
indicating the polyp region for segmentation

## Avg Dice and IOU scores
<img width="1008" height="693" alt="image" src="https://github.com/user-attachments/assets/7b921e75-e304-431b-a249-f5ebee656870" />

## Kaggle Link
[U-Mamba code implementation](https://www.kaggle.com/code/shashwatmishra140706/u-mamba-on-polyp-dataset)

## Device Specifications
1) Local, gtx 1650, 4GB VRAM
2) Local, rtx 3050, 4GB VRAM
