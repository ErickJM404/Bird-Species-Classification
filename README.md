# Bird-Species-Classification
# 🐦 Bird Species Classification with Deep Learning

This project uses pre-trained convolutional neural networks to classify bird species from the CUB-200-2011 dataset. Models such as **ResNet18**, **AlexNet**, **MobileNetV2**, and **EfficientNet-B0** are fine-tuned and compared based on their performance.

---

## 📋 Instructions

1. 📥 **Download the Notebook**  
   Clone the repository or download the `bird_species_classification_final.ipynb` file to your local machine or upload it directly to [Google Colab](https://colab.research.google.com/).

2. ⚠️ **Disclaimer**  
   This project was developed and tested using **Google Colab**. It is recommended to run the notebook in Colab for the smoothest experience.

3. ⚙️ **Enable GPU Acceleration**  
   Before running any cells in Colab, go to  
   `Runtime` → `Change runtime type` → Set **Hardware accelerator** to **GPU** → Click **Save**.

4. 📦 **Install Required Libraries**  
   All required Python packages are listed and installed at the beginning of the notebook using `pip`. Run the first few cells to ensure dependencies are installed.

---

## 📂 Dataset

- **Name**: CUB-200-2011 (Caltech-UCSD Birds 200)
- **Classes**: 200 bird species
- **Images**: 11,788 total
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/veeralakrishna/200-bird-species-with-11788-images)

---

## 🧠 Models Used

| Model           | Final Accuracy (Top-1) | Notes                              |
|----------------|------------------------|------------------------------------|
| ResNet18        | 33.67%                 | Strong general-purpose baseline    |
| AlexNet         | 19.08%                 | Smaller but outdated architecture  |
| MobileNetV2     | 39.57%                 | Lightweight, mobile-friendly       |
| EfficientNet-B0 | 29.86%                 | High accuracy, good efficiency     |

---

## 🏆 Top-5 Accuracy

| Model           | Top-5 Accuracy |
|----------------|----------------|
| ResNet18        | 61.32%         |
| AlexNet         | 42.15%         |
| MobileNetV2     | 66.79%         |
| EfficientNet-B0 | 54.28%         |

---

## 🛠 Features

- ✅ Image preprocessing with `torchvision.transforms`
- ✅ Transfer learning (frozen layers + fine-tuned classifier)
- ✅ Accuracy & loss plots for each model
- ✅ Confusion matrix (limited to top 20 classes)
- ✅ Classification report
- ✅ Inference and prediction visualization for random test images

---
