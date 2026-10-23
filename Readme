# Acute Lymphoblastic Leukemia Detection Using CNN

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-orange.svg)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-CNN-purple.svg)
![Computer Vision](https://img.shields.io/badge/Domain-Computer%20Vision-green.svg)

## About the Project

This project demonstrates a **Convolutional Neural Network (CNN)** approach for classifying microscopic blood-cell images into two categories: **Benign** and **Malignant**.

The project uses an Acute Lymphoblastic Leukemia (ALL) blood-cell image dataset. The original dataset categories are grouped into two classes, and a CNN learns visual patterns from the preprocessed images to predict their assigned category.

This project is developed for academic learning and demonstrates the fundamental workflow of deep learning-based medical image classification.

---

## Project Highlights

- CNN-based microscopic blood-cell image classification
- Binary classification: Benign vs Malignant
- Image resizing to 128 × 128 pixels
- Pixel-value normalization
- Training, validation, and testing workflow
- Adam optimizer and categorical cross-entropy loss
- Training and validation performance visualization
- Evaluation using accuracy, precision, recall, F1-score, and a confusion matrix

> **Note:** Final performance metrics should be added only after successful execution of the notebook. No accuracy value is claimed here.

---

## Dataset

**Dataset:** Blood Cell Cancer (ALL 4-Class)

**Source:** [Kaggle — Blood Cell Cancer (ALL 4-Class)](https://www.kaggle.com/datasets/mohammadamireshraghi/blood-cell-cancer-all-4class)

The dataset contains microscopic blood-cell images organized into four original categories.

### Class Mapping

| Original Dataset Folder | Assigned Class | Label |
|---|---|---:|
| Benign | Benign | 0 |
| `[Malignant] early Pre-B` | Malignant | 1 |
| `[Malignant] Pre-B` | Malignant | 1 |
| `[Malignant] Pro-B` | Malignant | 1 |

The three malignant subcategories are combined into one class for binary classification.

---

## Methodology

The project follows these stages:

1. **Dataset Loading** — Load microscopic blood-cell images from the dataset directory.
2. **Label Assignment** — Map the original folders to Benign and Malignant classes.
3. **Image Preprocessing** — Resize images to 128 × 128 pixels and normalize pixel values.
4. **Dataset Splitting** — Divide the data into training, validation, and testing subsets.
5. **CNN Model Development** — Build convolutional, pooling, and classification layers.
6. **Model Training** — Train the CNN using the Adam optimizer and categorical cross-entropy loss.
7. **Model Evaluation** — Evaluate predictions using classification metrics.
8. **Visualization** — Generate training graphs and evaluation outputs when available.

### CNN Architecture

The model's main components include:

- Input layer for 128 × 128 RGB images
- Convolutional and max-pooling layers
- Global average pooling
- Dense layer
- Dropout layer
- Softmax output layer for two classes

---

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| TensorFlow / Keras | CNN development and training |
| NumPy | Numerical operations and array processing |
| Matplotlib | Visualization of training results |
| scikit-learn | Dataset splitting and evaluation metrics |
| Google Colab | Notebook-based development and execution |

---

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Premraj-3390/Leukimia_Blood_classification.git
cd Leukimia_Blood_classification
```

### 2. Install the required libraries

```bash
pip install tensorflow numpy matplotlib scikit-learn
```

Install any additional packages required by the notebook if they are not already available.

### 3. Download the dataset

Download the dataset from [Kaggle](https://www.kaggle.com/datasets/mohammadamireshraghi/blood-cell-cancer-all-4class) and make sure the notebook's dataset path points to the extracted folders.

### 4. Run the notebook

Open the project notebook in **Google Colab** or a compatible Jupyter environment. Configure the dataset path, execute the cells in order, and review the training and evaluation outputs.

---

## Evaluation Metrics

The model can be evaluated using the following metrics:

- **Accuracy:** Overall proportion of correctly classified images.
- **Precision:** Proportion of positive predictions that are correct according to the dataset labels.
- **Recall:** Proportion of actual positive-class images correctly identified.
- **F1-score:** Harmonic mean of precision and recall.
- **Confusion Matrix:** Summary of correct and incorrect predictions for both classes.

Add the actual test results and generated figures after the notebook runs successfully.

---

## Repository Structure

The exact filenames may vary depending on the files included in the repository.

```text
Leukimia_Blood_classification/
│
├── notebook.ipynb
├── README.md
└── other project files
```

Update this structure to reflect the actual folders and filenames in your GitHub repository.

---

## Future Improvements

- Evaluate the model on a larger and more diverse dataset.
- Investigate techniques to reduce overfitting.
- Compare different CNN architectures.
- Perform evaluation on an independent dataset.
- Explore classification of individual malignant subcategories.
- Improve reproducibility through documented dataset splits and training settings.

---

## Disclaimer

This project is intended **for educational and academic purposes only**. It is an experimental image-classification system and has not been established as a clinically validated diagnostic tool. Its predictions must not be used as a substitute for laboratory testing or professional medical advice.

---

## Authors

- **Premraj R** — 24AD153
- **Sandeep Bharathi B** — 24AD175
- **Sakthivishal T** — 24AD173
- **Mohamed Irfan S** — 24AD122

**Department:** Artificial Intelligence and Data Science

**Institution:** Sri Shakthi Institute of Engineering and Technology

**GitHub:** [Premraj-3390](https://github.com/Premraj-3390)
