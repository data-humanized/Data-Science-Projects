# Gender Classification using Deep Learning

A computer vision project that predicts gender from facial images using a fine-tuned EfficientNetV2-S architecture. The model is trained with image augmentation techniques and optimized using early stopping to improve generalization and reduce overfitting. Performance evaluation includes accuracy metrics, confusion matrix visualization, and classification reporting.

## Dataset

This project uses the Kaggle **Gender Detection and Classification Image Dataset**.

The dataset contains labeled image data organized into:

- `train/men`
- `train/women`
- `test/men`
- `test/women`

Images are provided in JPG format.

The notebook includes commands for automatic dataset download and extraction.

---

## Technologies Used

- Python
- PyTorch
- torchvision
- EfficientNetV2-S
- OpenCV
- Pillow (PIL)
- NumPy
- pandas
- scikit-learn
- matplotlib
- seaborn
- tqdm

---

## Model Performance

| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| Men | 0.96 | 0.89 | 0.93 |
| Women | 0.83 | 0.94 | 0.88 |

**Validation Accuracy:** ~91%

---

## Features

- Transfer learning with EfficientNetV2-S
- Data augmentation pipeline
- Early stopping during training
- Performance visualization
- Confusion matrix generation
- Classification report evaluation

---

## Project Structure

GenderClassification.ipynb
requirements.txt
README.md
