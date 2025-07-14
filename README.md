# 🔍 COMPAS Recidivism Bias Analysis using AI Fairness 360

Welcome to the **COMPAS Bias Analysis** project! This repository investigates racial bias in the COMPAS recidivism dataset using IBM’s ⚖️ [AI Fairness 360 Toolkit (AIF360)](https://aif360.mybluemix.net/). The goal is to identify and mitigate algorithmic bias in criminal justice risk assessment systems.

---

## 📁 Project Structure

-- AI Fairness.ipynb # Main analysis script
-- Fair AI Systems.pdf # Project report
-- README.md # You're here!
-- Compas-scores-two-years # Dependencies



---

## 🚀 What’s Inside

### ✅ **Bias Detection**
- Uses the COMPAS dataset published by ProPublica.
- Filters dataset based on legal & ethical guidelines (e.g., removing low-level charges, incomplete data).
- Encodes categorical variables and defines `race_binary` attribute for fairness analysis.

### 📊 **Fairness Metrics**
- **Mean Difference**: Measures how favorable outcomes differ across racial groups.
- **Disparate Impact**: Evaluates if outcomes are proportionate between privileged (Caucasian) and unprivileged groups.

### 🛠️ **Remediation Steps**
- Dataset reweighing 🧮
- Fair classifier training 🤖
- Visualization of disparities 📉

---

## 🧠 Key Findings

> 📉 Disparate Impact ~ 0.76  
> ⚠️ Mean Difference ~ -0.19  
These suggest measurable racial bias disadvantaging non-Caucasian individuals in risk predictions.

---

## 📌 Requirements

```bash
!pip install aif360
!pip install pandas numpy scikit-learn matplotlib seaborn
```

### 🙌 Acknowledgements
ProPublica for the original dataset.

IBM Research for the AIF360 toolkit.

PLP for the course content

### ✨ Contribute
Want to help make AI fairer?
Feel free to fork, star ⭐, or open a pull request!


