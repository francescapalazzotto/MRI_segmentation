# Brain MRI Segmentation - Artificial Intelligence & Deep Learning Project

## Project Overview

This project focuses on **Brain MRI segmentation**, analyzing brain MR images
alongside manually created FLAIR abnormality segmentation masks.
Using the **LGG Segmentation Dataset** from **The Cancer Imaging Archive (TCIA)**,
we aim to explore genomic and morphological patterns in lower-grade gliomas,
inspired by studies from Buda, Saha, and Mazurowski (2019) and Mazurowski et al. (2017).

## Dataset

The dataset includes MRI scans from 110 patients from **The Cancer Genome Atlas (TCGA)**
lower-grade glioma collection, each with FLAIR sequence data and genomic cluster information.
This enables an analysis of how tumor shape features,
as identified by deep learning, correlate with genomic subtypes.

The **LGG Segmentation Dataset** contains:

- Brain MRI images with FLAIR (Fluid-Attenuated Inversion Recovery) sequences.

- Manual segmentation masks for abnormal regions.

- Genomic cluster data and patient information in `data.csv`.

This genomic and imaging data facilitates studies into the relationship
between tumor morphology, genomic profiles, and patient outcomes.

## Methodology

The project workflow includes:

1. **Data Preprocessing**: Loading, normalizing, and preparing MRI images and masks for training.

2. **Model Development**: Implementing a convolutional neural network (CNN) or similar deep learning models for segmentation.

3. **Evaluation**: Measuring model performance with metrics like the Dice coefficient and Intersection over Union (IoU).

4. **Analysis**: Examining correlations between segmented tumor shapes and genomic data.

## Results (To be updated)

The results will discuss segmentation accuracy and any observed
associations between tumor shape features and genomic clusters.

## References

- Buda, M., Saha, A., & Mazurowski, M. A. (2019). Association of genomicsubtypes of lower-grade gliomas with shape features automatically extracted by a deep learning algorithm. *Computers in Biology and Medicine*.
- Mazurowski, M. A., Clark, K., Czarnek, N. M., Shamsesfandabadi, P., Peters, K. B., & Saha, A. (2017). Radiogenomics of lower-grade glioma: algorithmically-assessed tumor shape is associated with tumor genomic subtypes and patient outcomes. *Journal of Neuro-Oncology*.
