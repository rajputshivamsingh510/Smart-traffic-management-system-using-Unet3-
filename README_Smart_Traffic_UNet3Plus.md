# 🚦 Smart Traffic Management System using U-Net3+

This project implements a deep learning-based image segmentation model using the U-Net3+ architecture to support intelligent traffic management. It focuses on identifying key elements in traffic scenes—such as roads, vehicles, and lane markings—using semantic segmentation.

---

## 📁 Dataset

Images and masks are accessed from Google Drive. The dataset consists of traffic-related scenes with corresponding labeled masks, structured for training and evaluation.

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

- Load and preprocess traffic image data and segmentation masks
- Visualize input images alongside predicted masks
- Build and train a U-Net3+ segmentation model
- Evaluate model using **Mean IoU (Intersection over Union)** for segmentation accuracy

---

## ⚙️ How to Run

1. Open the `1.ipynb` notebook in **Google Colab**
2. Mount Google Drive to access dataset:
   ```python
   from google.colab import drive
   drive.mount('/content/drive/')
   ```
3. Execute the cells to load data, visualize samples, train the model, and evaluate results.

---

## 📊 Evaluation Metric

- **Mean IoU** is used as the primary metric to assess segmentation quality.

---

## 📎 Notes

- Ensure correct dataset path setup in your Google Drive.
- U-Net3+ is selected for its effectiveness in semantic segmentation tasks, especially in structured environments like roads.

---

## 📬 Contact

For any queries or collaboration interests, feel free to connect via GitHub or LinkedIn.
