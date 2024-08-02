# Retinal-Glaucoma-Classification

## Problem Statement
Design and develop an automated retinal glaucoma classification system to achieve early diagnosis in medical images.

## Abstract
Glaucoma, a prevalent optic neuropathy, poses a significant threat to vision and requires accurate and timely detection for effective management. Traditional diagnostic approaches face limitations, prompting the integration of advanced technologies such as deep learning models.

Employing advanced deep learning models—GoogLeNet (Inception V3), VGG16, and ResNet50—we achieve individual accuracies of 99%, 99%, and 98% respectively on Combined Datasets, Acrima, Drishti-GS1, HRF, ORIGA-LIGHT, and Rim-One. The study further explores the synergy of these models through soft voting ensemble techniques, resulting in a remarkable combined accuracy of 99%.

## Objectives
- Implement InceptionV3, VGG16, and ResNet50 for accurate feature extraction in retinal images.
- Develop a robust glaucoma classification method that ensures accurate diagnoses by effectively leveraging identified features.
- Assess the generalization capability of the implemented models by evaluating their performance on novel retinal images that were not part of the training dataset.

## Data Description
**Datasets:**
- Acrima
- Drishti-GS1
- HRF
- ORIGA-LIGHT
- Rim-One

**Combined Dataset:**
- **Total Images:** 21,957
- **Class Distribution:**
  - **Training:**
    - Images: 17,565
    - Class Distribution: 10,327 normal, 7,238 glaucoma
  - **Validation:**
    - Images: 2,196
    - Class Distribution: 1,291 normal, 905 glaucoma
  - **Test:**
    - Images: 2,196
    - Class Distribution: 1,291 normal, 905 glaucoma
  - **Total Class Distribution:**
    - 12,909 normal, 9,048 glaucoma

**Dataset Link:**
[Glaucoma Detection Dataset on Kaggle](https://www.kaggle.com/datasets/hindsaud/datasets-higancnn-glaucoma-detection)

## Conclusion
In this research, advanced deep learning models—InceptionV3, VGG16, and ResNet50—were employed for glaucoma detection, achieving impressive individual accuracies of 99%, 99%, and 98% respectively across diverse datasets.

The study explored the synergies of these models through soft voting ensemble techniques, yielding a remarkable combined accuracy of 99%. This method underscores the effectiveness of ensemble methodologies in medical image analysis.

This research paves the way for continued innovation in medical image analysis, emphasizing the transformative potential of collaborative model approaches in complex healthcare applications.
