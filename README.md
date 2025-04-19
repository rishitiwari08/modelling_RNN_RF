# Modelling RNN and Random Forest for Time Series Prediction

## 📌 Overview

This project was conducted as a **case study during the 3rd semester of my Master’s program**, in collaboration with **MAN Energy Systems**. The aim was to evaluate and compare the effectiveness of **Recurrent Neural Networks (RNN)** and **Random Forest (RF)** in forecasting time series data derived from real-world operational datasets.

> ⚠️ **Note**: The dataset used in this project is **confidential** and is therefore **not uploaded to this repository**.

---

## 🧠 Project Objectives

- Implement and train an RNN model for time series forecasting.
- Implement and train a Random Forest model for the same task.
- Evaluate and compare the performance of both models using appropriate metrics.
- Analyze the strengths and limitations of each approach in the context of the specific dataset.

---

## 📁 Repository Structure

```arduino
modelling_RNN_RF/
├── src/
│   ├── Modelling of RNN and RF.ipynb
├── Report_Presentation/
│   ├── Case Study.pptx
│   └── Report.pdf
├── README.md
└── requirements.txt
```



## ⚙️ Setup Instructions

1. **Clone the repository:**

```bash
git clone https://github.com/rishitiwari08/modelling_RNN_RF.git
cd modelling_RNN_RF
```

2. **(Optional) Create a virtual environment:**
```bash
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate
```
3. **Install dependencies:**
```bash 
pip install -r requirements.txt
```

4. **Add your dataset:**

Place your confidential dataset in the appropriate location and ensure paths in the notebooks or utility files are updated accordingly.

## 📊 Results
Output plots showing predicted vs. actual values for both models are stored in the `jupyter_notebok`. These visualizations help compare model accuracy and interpretability.