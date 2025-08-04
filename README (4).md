# 🔍 Image Segmentation using Deep Learning

This project performs image segmentation using deep learning techniques with TensorFlow and OpenCV. It is aimed at training and evaluating a model capable of identifying specific segments in images.

---

## 📁 Dataset

The dataset is accessed from Google Drive and includes input images and their corresponding segmentation masks. The project assumes a proper folder structure in the drive for training and testing data.

---

## 🧰 Tech Stack & Libraries

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Google Colab

---

## 🚀 Features

- Load and preprocess images for segmentation
- Visualize input images and their corresponding masks
- Train a segmentation model
- Evaluate model using **Mean IoU** (Intersection over Union)

---

## ⚙️ How to Run

1. Open the notebook (`1.ipynb`) in **Google Colab**.
2. Mount Google Drive to load the dataset:
   ```python
   from google.colab import drive
   drive.mount('/content/drive/')
   ```
3. Follow the code cells to load data, visualize, train, and evaluate the model.

---

## 📊 Evaluation Metric

The primary evaluation metric used is:

- **Mean IoU (Intersection over Union)** – useful for semantic segmentation tasks.

---

## 📎 Notes

- Make sure your dataset is structured correctly within your Google Drive.
- You may need to adjust the path variables based on your Drive’s folder structure.

---

## 📬 Contact

For any questions or feedback, feel free to reach out via GitHub or LinkedIn.

