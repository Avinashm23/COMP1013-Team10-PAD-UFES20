# COMP1013 Project 2.2 — Team 10

Multimodal Skin Lesion Classification Using Clinical Images and Patient Metadata.

## Dataset
PAD-UFES-20:
https://data.mendeley.com/datasets/zr7vgbcyr2/1

## Models
- Metadata-only logistic regression
- Image-only EfficientNet-B0 embeddings with logistic regression
- Early fusion
- Late fusion
- Intermediate metadata-conditioned gated fusion

## How to run
1. Download the PAD-UFES-20 dataset.
2. Place the clinical images inside the images/ folder.
3. Keep metadata.csv and metadata_with_patient_split.csv in the project folder.
4. Install the packages using: pip install -r requirements.txt
5. Open PAD_UFES20_Project_2_2_Final_Submission.ipynb in Jupyter.
6. Run all cells in order.

## Results
Early fusion validation macro-F1: 0.6681
Early fusion held-out test macro-F1: 0.5241

This is a research prototype and must not be used for clinical diagnosis.
