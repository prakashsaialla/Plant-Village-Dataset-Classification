
---

# 🌱 PlantVillage Dataset Classification

This project focuses on **classifying plant leaf diseases** using the **PlantVillage dataset**. The dataset contains images of healthy and diseased leaves across multiple plant species. The goal is to build and evaluate deep learning models to automatically detect plant diseases, which can support farmers and researchers in improving crop health and yield.

## 🚀 Features

* Preprocessing of PlantVillage dataset images
* Data augmentation for improved generalization
* Deep learning classification using **TensorFlow/Keras**
* Training with optimizers such as **Adam** and **RMSprop**
* Model evaluation with accuracy and confusion matrix visualization
* Experiments with clustering and image morphology techniques

## 📂 Dataset

The dataset used is the **PlantVillage dataset**, which contains labeled images of plant leaves. You can download it from:
🔗 [PlantVillage Dataset (Kaggle)](https://www.kaggle.com/datasets/emmarex/plantdisease)

## 🛠️ Tech Stack

* **Python 3.x**
* **TensorFlow / Keras** – for deep learning models
* **scikit-learn** – clustering & evaluation
* **OpenCV / scikit-image** – image preprocessing
* **Matplotlib / Seaborn** – visualization
* **Pandas / NumPy** – data handling

## 📊 Workflow

1. **Data Loading & Preprocessing**

   * Read images and resize them for consistency
   * Apply augmentation (rotation, flip, zoom, etc.)
   * Normalize pixel values

2. **Model Building**

   * Implement CNNs using Keras Sequential API
   * Use layers like **Conv2D, BatchNormalization, MaxPooling, Dense**
   * Train with optimizers **Adam / RMSprop**

3. **Model Evaluation**

   * Accuracy and loss plots
   * Confusion matrix for detailed performance
   * Cluster analysis for feature exploration

## 📈 Results

* Achieved high accuracy in distinguishing healthy vs. diseased leaves
* Robust model performance across multiple plant categories
* Visualization of predictions helps in better interpretability

## ▶️ How to Run

1. Clone this repository

   ```bash
   git clone https://github.com/prakashsaialla/plantvillage-dataset-classification.git
   cd plantvillage-classification
   ```

2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook

   ```bash
   jupyter notebook plantvillage-dataset-classification.ipynb
   ```

## 📌 Future Improvements

* Deploy as a **web app** for real-time leaf disease detection
* Optimize models with **transfer learning (e.g., ResNet, EfficientNet)**
* Extend to multi-disease detection per leaf

## 📜 License

This project is licensed under the MIT License – feel free to use and modify.

---

