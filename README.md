# 1MD049 – Task 3
## *Group A*

## Authors
Joel, Dilmi, Khalifa

## Overview

This repository contains our work for Task 3 of the 1MD049 course.  
We experiment with *DINOv3*, a vision foundation model released by Meta AI. While our group focuses on depth estimation using the DINOv3/DINOv3 Depther model, the potential usecases of this architecture is endless.

The goal of this repo is to explore and experiment with the feature representations produced by DINOv3 and to, both qualitatively and quantitatively, evaluate the performance of its depth estimation capabilities.

## Contents

The repo contains several files:

- **`Dinov3.ipynb`**  
  Structured in two parts:

  1. *Path Encoding and Similarity Analysis*
     We inspect DINOv3 patch encodings and visualize their similarity.

  2. *Depth Estimation (Depther Model)* 
     The DINOv3 Depther model is imported and run on a selection of images to generate depth maps. **This part is highly memory intensive.**

  *This notebook is "optimized" for the colab-environment, running on an A100 GPU. If ran on colab, cloning repositorys and importing libraries should be no problem.*
- **Next ipynb here!**
  
## Model

DINOv3 is a self-supervised vision transformer developed by *Meta AI*.  
The **Depther** variant extends the model for monocular depth estimation, enabling depth prediction from a single RGB image.

## References

- Meta AI – DINOv3 GitHub Repository

  https://github.com/facebookresearch/dinov3

- DINOv3 Paper  
  *DINOv3: Learning Robust Visual Features without Supervision*
  
  https://arxiv.org/abs/2508.10104, https://ai.meta.com/dinov3/

## Notes

This repository is intended for educational and experimental purposes as part of the 1MD049 course.  
All credit for the model architecture and pre-trained weights belongs to Meta AI.
