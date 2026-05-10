# Keratoconus Eye Disease Detection Using CNN

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat-square&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=flat-square&logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red?style=flat-square&logo=keras)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-yellow?style=flat-square&logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)

> A deep learning solution to assist in early detection of Keratoconus — a progressive corneal eye disease — using Convolutional Neural Networks (CNNs), with a comparative study on the effect of oversampling on model performance.

---

## Project Highlights

- Medical AI application targeting real-world clinical screening needs
- Dual-experiment design — with and without oversampling for a controlled comparison
- Class imbalance handling using oversampling to improve minority-class recall
- Full evaluation pipeline — Accuracy, Precision, Recall, F1-Score, Confusion Matrix
- Built entirely from scratch using Python, TensorFlow/Keras, and Jupyter Notebook

---

## Problem Statement

**Keratoconus** is a non-inflammatory eye condition where the cornea progressively thins and bulges into a cone shape, causing distorted and blurred vision. If undetected early, it can lead to severe visual impairment requiring surgical intervention.

Traditional diagnosis depends on expensive equipment and specialist review — making it inaccessible in many settings. This project explores how **deep learning can automate and democratize early screening**, flagging high-risk cases before significant damage occurs.

---

## Repository Structure

```
keratoconus-cnn-detection/
 |-- dataset/                                         # Corneal topography images (Normal vs Keratoconus)
 |-- models/                                          # Saved trained model weights
 |-- keratoconus-detection-deep-learning.ipynb        # Main model — with oversampling
 |-- keratoconus-detection-without-oversampling.ipynb # Baseline model — without oversampling
 |-- README.md
```

---

## Tech Stack

| Tool | Purpose |
|---|---|
| Python 3.8+ | Core language |
| TensorFlow / Keras | CNN model building and training |
| NumPy / Pandas | Data manipulation |
| Matplotlib / Seaborn | Data visualization and result plots |
| scikit-learn | Evaluation metrics and preprocessing |
| Jupyter Notebook | Interactive experimentation |

---

## Model Architecture and Approach

The CNN was designed to classify corneal images into two categories: **Normal** and **Keratoconus**.

**Pipeline:**
1. Image preprocessing and normalization
2. Data augmentation to improve generalization
3. CNN architecture — multiple Conv2D, MaxPooling, Dropout, and Dense layers
4. Binary classification with sigmoid output

**Two experimental tracks:**

| Track | Description |
|---|---|
| With Oversampling | Addresses class imbalance; improves recall on minority class |
| Without Oversampling | Baseline model for direct performance comparison |

This side-by-side design demonstrates critical thinking about data quality and its downstream impact on model fairness and reliability.

---

## Results

| Metric | With Oversampling | Without Oversampling |
|---|---|---|
| Accuracy | _update after run_ | _update after run_ |
| Precision | _update after run_ | _update after run_ |
| Recall | _update after run_ | _update after run_ |
| F1-Score | _update after run_ | _update after run_ |

> Replace the placeholders above with your actual notebook output values before sharing with recruiters.

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/keratoconus-cnn-detection.git
cd keratoconus-cnn-detection
```

### 2. Install Dependencies

```bash
pip install tensorflow numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 3. Run the Notebook

```bash
# Main model (with oversampling)
jupyter notebook keratoconus-detection-deep-learning.ipynb

# Baseline model (without oversampling)
jupyter notebook keratoconus-detection-without-oversampling.ipynb
```

---

## Key Learnings

- Applying CNNs to medical image classification for a socially impactful use case
- Handling class imbalance in healthcare datasets using oversampling
- Designing controlled experiments to isolate the effect of data preprocessing
- End-to-end deep learning workflow: data, model, evaluation, and interpretation

---

## License

This project is licensed under the [MIT License](LICENSE) — free to use, modify, and distribute with attribution.

---

## Author

**Your Name**  
your.email@example.com  
[LinkedIn](https://linkedin.com/in/yourprofile) | [GitHub](https://github.com/yourusername) | [Portfolio](https://yourportfolio.com)

---

*This project was built to explore the intersection of deep learning and medical diagnostics — with the belief that AI can make quality healthcare screening more accessible.*
