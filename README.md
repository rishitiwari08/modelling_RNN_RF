# Modelling RNN and Random Forest for Predictive Measurements

## 📌 Overview

This project was conducted as a **case study during the 3rd semester** of my **Master’s program**, in collaboration with **MAN Energy Solutions**. The primary focus was to **replace computationally expensive simulations** used in turbocharger vibration analysis with more scalable and efficient machine learning models — specifically, **Recurrent Neural Networks (RNN)** and **Random Forest (RF)**.

Turbochargers experience internal vibrations during high-speed operations, which are traditionally monitored using physical strain gauges. However, due to spatial limitations and the high cost of simulations, there is a need for a predictive surrogate model. This project leverages deep learning and ensemble methods to predict **nominal vibration amplitudes** using measurable operational parameters, reducing reliance on physical instrumentation and simulations.

> ⚠️ **Note**: The dataset used in this project is **confidential** and has **not been uploaded** to this repository.

---

## 🧠 Project Objectives

- Develop an **RNN-based predictive model** to estimate nominal vibration amplitudes in turbochargers.
- Implement a **Random Forest model** as a complementary approach, particularly effective in higher frequency ranges.
- Perform **Exploratory Data Analysis (EDA)** and **feature engineering** to extract influential input parameters.
- Evaluate and compare the performance of both models using metrics like **Mean Squared Error (MSE)**.
- Propose a **hybrid modeling strategy** using RNN for lower-frequency predictions and RF for higher-frequency ranges to improve accuracy.
- Demonstrate how AI can serve as a **surrogate for simulation**, enabling faster and more efficient vibration monitoring.


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