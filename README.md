# 🌸 Week 3 Assignment – PLP AI for Software Engineering

Welcome to our Week 3 project submission. This repository includes both theoretical understanding and hands-on implementation using various tools like Scikit-learn, TensorFlow, PyTorch, and spaCy.

---

## 📘 Contents

- [Theoretical Understanding](#theoretical-understanding)
 
- [Practical Implementation](#practical-implementation)
 
  - [A. Classical ML with Scikit-learn](#a-classical-ml-with-scikit-learn)
    
  - [B. Deep Learning with TensorFlow](#b-deep-learning-with-tensorflow)
    
  - [C. NLP with spaCy](#c-nlp-with-spacy)
    
- [Ethics & Optimization](#ethics--optimization)
  
- [Bonus Task (Optional)](#bonus-task-optional)
  
- [Submission Items](#submission-items)

---

## 🧠 Theoretical Understanding

- ✅ Short Answer Questions:
  - Explained key differences between TensorFlow and PyTorch.
  - Use case scenarios for each framework.

- ✅ Comparative Analysis:
  - Scikit-learn vs TensorFlow:
    - 📌 Target applications (classical ML vs deep learning)
    - 🎯 Ease of use for beginners
    - 🌍 Community support

See the full answers in [`report.pdf`](./report.pdf).

---

## 🔧 Practical Implementation

### A. Classical ML with Scikit-learn

- **Dataset**: Iris Species Dataset
- **Tasks**:
  - Handled missing values and label encoding
  - Trained a Decision Tree Classifier
  - Evaluated the model using accuracy, precision, and recall

> 📁 File: `notebooks/iris_decision_tree.ipynb`  
> 📷 Output screenshots: `screenshots/iris_metrics.png`

---

### B. Deep Learning with TensorFlow

- **Dataset**: MNIST Handwritten Digits
- **Goal**:
  - Built a CNN to classify handwritten digits
  - Achieved >95% test accuracy
  - Visualized predictions on 5 sample images

> 📁 File: `notebooks/mnist_cnn_tensorflow.ipynb`  
> 📷 Sample predictions: `screenshots/mnist_predictions.png`

---

### C. NLP with spaCy

- **Text Data**: Amazon Product Reviews
- **Goal**:
  - Named Entity Recognition to extract product names and brands
  - Rule-based sentiment analysis (positive/negative)

> 📁 File: `notebooks/amazon_reviews_spacy.ipynb`  
> 📷 NER & sentiment result: `screenshots/spacy_ner_output.png`

---

## 🌐 Ethics & Optimization

- **Bias Analysis**:
  - Identified potential model biases in MNIST and Amazon datasets
  - Proposed mitigation using TensorFlow Fairness Indicators and spaCy rules

- **Troubleshooting Challenge**:
  - Debugged TensorFlow script (fixed dimension mismatch, loss function)
  - ✅ [Fixed Script](troubleshooting/fixed_tensorflow_script.py)

---

## 🏆 Bonus Task (Optional)

- Built a Streamlit web app for the MNIST classifier
- Hosted locally for demo

> 📁 Code: `bonus/streamlit_app.py`  
> 🖼 Screenshot: `bonus/mnist_web_demo.png`  
> 🔗 Live demo: *Coming soon / Optional*

---

## 📦 Submission Items

| Item                         | Location                          |
|------------------------------|-----------------------------------|
| Code Notebooks               | `notebooks/`                      |
| Ethical Troubleshooting Fix  | `troubleshooting/fixed_tensorflow_script.py` |
| Output Screenshots           | `screenshots/`                    |
| PDF Report                   | [`report.pdf`](./report.pdf)      |
| Bonus Task (Optional)        | `bonus/`                          |
| Video Presentation           | [Shared on Community Platform]    |

---

## 👥 Contributors

- Joyce Nyambura
- Gos
- [Group Members if applicable]

---

Thank you for reviewing our submission. Kindly check the PDF report for full answers and model output details.


