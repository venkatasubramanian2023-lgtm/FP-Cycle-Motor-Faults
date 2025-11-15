FP-GAN + ResNet-18 for Induction Motor Fault Diagnosis Using Thermal Images

This project uses a Feature-Preserving GAN (FP-GAN) to generate synthetic thermal images and balance the dataset for induction motor fault diagnosis. Since real thermal images are limited and imbalanced, the FP-GAN helps create realistic fault-class samples while keeping heat patterns intact. The balanced dataset is then used to train a ResNet-18 model for multi-class classification of 11 fault types.

---

## Folder Structure

dataset/            (sample or README if dataset is large)
src/                (GAN + classifier training code)
models/             (saved FP-GAN + ResNet-18 weights)
results/            (generated images, confusion matrix, metrics)
report/             (IEEE formatted project report)
presentation/       (final PPT slides)

---

 Requirements

Install dependencies using:

pip install -r requirements.txt

---
 How to Run

1. Run preprocessing script in `src/` if needed
2. Train FP-GAN using the notebook
3. Train ResNet-18 using the augmented dataset
4. Check final metrics and generated samples in `results/`

---

Base Paper Used

"Unsupervised Feature-Preserving CycleGAN for Fault Diagnosis of Rolling Bearings Using Unbalanced Infrared Thermal Imaging Sample" (IEEE Access, 2024)

The concept from this paper inspired the idea of feature-preserving GAN-based augmentation.

---

Demo Video

YouTube Link: (to be added)

---

Team

Name: Venkata Subramanian.R  
Register Number: 23MIA1066
 
Name: Raagav Subramanian  
Register Number: 23MIA1052

Name: Thrishan S
Register Number: 23MIA1071

