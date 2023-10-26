# Dataset 
This repository contains the dataset used on the paper

## Image and Scalar-Based Approaches in Preconditioner Selection`
### Abstract
Within high-performance computing (HPC), solving large sparse linear systems efficiently remains paramount, with iterative methods being the predominant choice. However, the performance of these methods is tightly coupled to the aptness of the chosen preconditioner. The multifaceted nature of sparse matrices makes the universal prescription of preconditioners elusive. Notably, the key attribute of sparsity is not precisely captured by scalar metrics such as bandwidth or matrix dimensions. Advancing prior methodologies, this research introduces matrix sparsity depiction via RGB images. Utilizing a convolutional neural network (CNN), the task of preconditioner selection transforms into a multi-class classification problem. Extensive tests on 126 SuiteSparse matrices emphasize the enhanced prowess of the CNN model, noting a 32\% boost in accuracy and a 25\% reduction in computational slowdown.

### Key-words: 
High-Performance Computing (HPC), Sparse Linear Systems, Iterative Methods, Preconditioner, Matrix Sparsity, Scalar Attributes, RGB Image Representation, Convolutional Neural Network (CNN), Multi-class Classification, SuiteSparse Matrix Collection, Preconditioner Selection.

# Contents

|File|Description|
|:---|:---|
|`README.md`|This file|
|`dbML.xlsx`|Data file with the optimal preconditioners and scalar attributes of each matrix|
|`dbTIME.xlsx`|Data file with the execution times of each matrix|

The `images` directory contains the RGB images of the SuiteSparse matrices.
