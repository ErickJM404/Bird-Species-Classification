# Bird-Species-Classification
# 🐦 Bird Species Classification with Deep Learning

This project uses pre-trained convolutional neural networks to classify bird species from the CUB-200-2011 dataset. Models such as **ResNet18**, **AlexNet**, **MobileNetV2**, and **EfficientNet-B0** are fine-tuned and compared based on their performance.

---

## 📂 Dataset

- **Name**: CUB-200-2011 (Caltech-UCSD Birds 200)
- **Classes**: 200 bird species
- **Images**: 11,788 total
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/veeralakrishna/200-bird-species-with-11788-images)

---

## 🧠 Models Used

| Model           | Accuracy (2 Epochs) | Notes                            |
|----------------|---------------------|----------------------------------|
| ResNet18        | ~28%                | Strong general-purpose baseline |
| AlexNet         | ~20%                | Smaller but outdated architecture |
| MobileNetV2     | TBD                 | Lightweight, mobile-friendly    |
| EfficientNet-B0 | TBD                 | High accuracy, good efficiency  |

*Note: Results improve with more epochs.*

---

## 🛠 Features

- ✅ Image preprocessing with `torchvision.transforms`
- ✅ Transfer learning (frozen layers + fine-tuned classifier)
- ✅ Accuracy & loss plots for each model
- ✅ Confusion matrix (limited to top 20 classes)
- ✅ Classification report
- ✅ Inference and prediction visualization for random test images

---

## 🔍 Sample Visualization

<p align="center">
  <img src="sample_confusion_matrix.png" width="600">
</p>

---

## 🚀 How to Use

### 1. Clone the Repo
```bash
git clone https://github.com/YOUR_USERNAME/bird-species-classification.git
