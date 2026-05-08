# 🚴 TAMS Bicycle Accident Fault Detection

> Deep Learning based intelligent system for predicting bicycle accident fault using a **Temporal Attention Multi-Sensor Vision Network (TAMS)**.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 Project Overview

Road accidents involving bicycles often require manual investigation to determine fault responsibility. This project introduces an AI-powered framework that predicts accident fault using structured crash metadata and deep learning.

The system uses a hybrid neural architecture combining:

* Temporal CNN
* Non-Stationary Attention
* Parallel Neural Network

to learn complex crash patterns and make accurate fault predictions.

---

## 🎯 Objectives

* Automate bicycle accident fault detection
* Improve road safety analytics
* Reduce manual investigation effort
* Build a deployable real-time AI model

---

## 🧠 Model Architecture

TAMS combines multiple advanced deep learning modules:

1. **Temporal CNN** – captures feature relationships
2. **Attention Mechanism** – focuses on critical factors
3. **Parallel Dense Layers** – improves classification learning
4. **Final Binary Classifier** – predicts fault / no-fault

---

## 📊 Dataset

Used the **CycleCrash Dataset**

Features include:

* Object involved
* Cyclist direction
* Time of collision
* Right of way
* Severity score
* Vulnerability score
* Age
* Camera position

---

## ⚙️ Technologies Used

* Python
* PyTorch
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Plotly
* OpenCV

---

## 📈 Performance

| Metric   | Score  |
| -------- | ------ |
| Accuracy | 98.48% |
| F1 Score | 98.48% |
| MCC      | 96.87% |
| AUC      | 99.50% |

---

## 🚀 How to Run

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Sarika-21/TAMS-Bicycle-Accident-Fault-Detection.git
cd TAMS-Bicycle-Accident-Fault-Detection
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Notebook

```bash
jupyter notebook
```

Open:

```text
TAMS_Bicycle_Accident_Fault_Detection.ipynb
```

---

## 📂 Project Structure

```text
TAMS-Bicycle-Accident-Fault-Detection/
│── notebook.ipynb
│── report.pdf
│── requirements.txt
│── README.md
│── screenshots/
│── model/
```
## 📊 Outputs and Results

### Confusion Matrix
![Confusion Matrix](screenshots/confusion_matrix.png)

### ROC Curve
![ROC Curve](screenshots/roc_curve.png)

### Accuracy Graph
![Accuracy](screenshots/accuracy_graph.png)

### Final output
![Dashboard](screenshots/final_output.png)

---

## 🌍 Future Enhancements

* Real-time CCTV integration
* Video-based accident reasoning
* Mobile deployment
* Explainable AI dashboard
* Multi-class fault analysis

---

## 👩‍💻 Author

**Sarika Kamala**
Computer Science Engineering Student

GitHub: https://github.com/Sarika-21
