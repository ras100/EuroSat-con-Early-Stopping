# EuroSAT Land Use Classification with Early Stopping


This project applies deep learning techniques for classifying land use and land cover using the EuroSAT dataset, which is based on Sentinel-2 satellite images. It explores the use of transfer learning and early stopping to enhance model performance and avoid overfitting.

## 💡 Personal Motivation
This project is part of my ongoing exploration into the intersection between environmental sciences and artificial intelligence.
With a background in Natural Sciences and current work in geospatial data analysis, my goal is to apply machine learning methods to understand and monitor natural systems more effectively.

## 🧪 Requirements

Make sure to have the following packages installed:

- Python 3.8+
- torch
- torchvision
- numpy
- matplotlib
- scikit-learn
- jupyter

You can install them with:

``bash
pip install torch torchvision numpy matplotlib scikit-learn jupyter


## 🛰️ Dataset

- **EuroSAT**: 10 classes of land use (residential, industrial, forest, etc.) based on Sentinel-2 satellite images.
- Resolution: 64x64 RGB images.
- Source: [EuroSAT dataset](https://github.com/phelber/eurosat)

> ⚠️ Note: Dataset must be downloaded and stored locally under the directory path specified in the notebook (e.g., `EuroSAT/2750`). Make sure to update the path if needed.

## 🧠 Model & Training

- **Framework**: PyTorch
- **Pre-trained model**: ResNet (from `torchvision.models`)
- **Key techniques**:
  - Transfer learning
  - Data augmentation (with `torchvision.transforms`)
  - Early stopping to avoid overfitting
  - Evaluation with precision, recall, F1-score, and confusion matrix

## 🗂️ Project structure

- `EuroSAT con Early stopping reordenado.ipynb`: Jupyter notebook with the full pipeline (data loading, training, evaluation).
- No additional scripts or requirements file provided (assumes a working PyTorch environment).

## ▶️ How to run

1. Download the EuroSAT dataset and store it locally in the expected path.
2. Open the notebook in Jupyter or VS Code.
3. Run all cells to execute the full training and evaluation process.

## ✍️ Author

**Florencia Gómez Osuna**  
Currently working in geospatial data analysis and with a background in natural sciences.

## 📄 CV

You can find my academic and professional background in my [Resume](./Resume.pdf).

## 📬 Contact

📧 flor.gosuna@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/florencia-gomez-osuna)  
🔗 [GitHub](https://github.com/ras100)

