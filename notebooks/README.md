# Computer Vision Internship Notebooks

This folder contains the 13 companion Jupyter notebooks for *The Computer Vision Internship*.


The Computer Vision Internship
InternshipInABook™ · Book 3 of 9
---
What Is This?
You are Ngozi Eze-Okafor, junior CV engineer at MediVision AI, Lagos.
Your manager, Dr. Kwame Asante, hands you five datasets across three clinical domains
and twelve weeks to build models that could assist clinical decisions — and audit them
rigorously enough that a hospital ethics board could approve them.
---
The Twelve-Week Arc
Week	Title	Domain	Key Skills
0	Before You See	Setup	PyTorch, MONAI, DICOM loading
1	An Image Is Not a Picture	All domains	Pixel values, CHW format, domain fingerprints
2	Reading Images — EDA on Pixels	Oxford Pets	Class balance, channel histograms, augmentation audit
3	Preprocessing	All domains	Normalisation, custom Dataset classes, stain normalisation, frame sampling
4	Communicating Visual Findings	Oxford Pets	Pyramid Principle, clinical translation, findings-first charts
5	Your First CNN	Oxford Pets	Baseline CNN, DummyClassifier, error analysis
6	Medical Imaging — The Chest X-Ray	NIH CXR14	Multi-label classification, BCEWithLogitsLoss, AUC-ROC
7	Breast Cancer Histopathology	BreakHis	Malignant/benign, magnification domain shift, class weighting
8	Uterine Cancer — Pathology at Scale	TCGA Uterine	Stain normalisation, EfficientNet-B0, per-site evaluation
9	Video — Images in Time	UCF-101	Frame sampling, 2D CNN baseline, temporal pooling
10	Explainable AI	Multi-domain	GradCAM, LIME, SHAP, Integrated Gradients — all in code
11	Fairness Audit	Multi-domain	Sex gap, magnification gap, site gap, threshold adjustment
12	The Capstone	HAM10000	Full pipeline, solo, with fairness audit and model card
---
Datasets
Dataset	Domain	Licence	Weeks
Oxford-IIIT Pets	Natural photos	CC BY 4.0	1–5
NIH Chest X-Ray14	Medical X-ray	CC0	6, 10, 11
BreakHis	Breast cancer	Open research	7, 10, 11
TCGA Uterine	Endometrial cancer	TCIA open	8, 10, 11
UCF-101 (10-class subset)	Video	Open	9
HAM10000	Skin lesion dermoscopy	CC BY-NC 4.0	12
Download scripts are in `datasets/download_scripts/`.
---
Quick Start
```bash
git clone https://github.com/internshipinabook/cv-internship-in-a-book.git
cd cv-internship-in-a-book
pip install -r requirements.txt
jupyter lab
```
Or click the Open in Colab badge at the top of any notebook.
---
Characters
Name	Role
Dr. Kwame Asante	Your manager. Radiologist + AI researcher. Teaches through questions.
Ngozi Eze-Okafor	You. Junior CV engineer. First week at MediVision AI.
Yewande Adeyemi	Senior CV engineer. Knows PyTorch cold. Will tell you to train before you understand.
Nurse Folake Balogun	Clinical lead. Reads outputs, not code. Asks which patients the model fails.
---
Licence
Code: MIT. Book content: © Sakinat Folorunso 2026.
Datasets: varied open licences — see datasets/LICENSE.txt.
internshipinabook.com
