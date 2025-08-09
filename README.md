# NSAP_ML

---

# NSAP Eligibility Prediction – IBM SkillsBuild Internship Project

## 📌 Project Overview

This repository contains the **"Predicting Eligibility for National Social Assistance Program (NSAP) using Machine Learning"** project developed during the **IBM SkillsBuild 4-Week Internship on AI & Cloud Technologies** conducted by **Edunet Foundation** in collaboration with **AICTE**.

The goal of this project is to automate the process of identifying the correct NSAP welfare scheme for an applicant based on demographic and socio-economic data using **IBM Cloud** and **Machine Learning**.

---

## 🏛 Internship Details

* **Internship Title:** IBM SkillsBuild 4-Weeks Internship on AI & Cloud Technologies
* **Organization:** Edunet Foundation in collaboration with AICTE & IBM
* **Duration:** 15th July 2025 – 7th August 2025
* **Focus Areas:** Cloud Computing, Artificial Intelligence, Data Analytics, Machine Learning, Chatbots, AutoAI
* **Certification:** IBM SkillsBuild & Edunet Foundation

---

## 🎯 Problem Statement

The **National Social Assistance Program (NSAP)** provides financial aid to elderly citizens, widows, and persons with disabilities from Below Poverty Line (BPL) households.
Manual verification of applications is slow, error-prone, and may result in delays or incorrect scheme allocation.
This project aims to use **Machine Learning** to predict the most suitable NSAP scheme for an applicant.

---

## 💡 Proposed Solution

* Collect **district-wise pension data** and applicant demographics.
* Preprocess data by cleaning, handling missing values, encoding categorical features, and normalizing values.
* Train a **Snap Random Forest Classifier** in **IBM Watson Studio** to classify applicants into schemes like:

  * **IGNDPS** – Indira Gandhi National Disability Pension Scheme
  * **IGNOAPS** – Indira Gandhi National Old Age Pension Scheme
  * **IGNWPS** – Indira Gandhi National Widow Pension Scheme
* Deploy the model.

---

## 🛠 Technologies Used

### **Languages & Libraries**

* Python 3.7+
* pandas, numpy – Data processing
* scikit-learn – Preprocessing, model training
* xgboost – Optional advanced modeling
* matplotlib / seaborn – Data visualization

### **IBM Cloud Services**

* IBM Watsonx.ai Studio
* IBM Watson Machine Learning
* IBM Cloud Object Storage
* SPSS Modeler Flow (Snap Random Forest)

---

## ⚙️ System Requirements

**Hardware**

* Minimum 8 GB RAM, Intel i5 or higher
* Stable internet connection

**Software**

* Python 3.7+ environment
* Web browser (Chrome / Firefox)
* IBM Cloud account access

---

## 📊 Algorithm & Deployment

1. **Algorithm:** Snap Random Forest Classifier (Ensemble Learning)
2. **Training:** Dataset split into training/testing sets inside SPSS Modeler.
3. **Deployment:** Hosted in IBM Watson Machine Learning as a REST API.
4. **Usage:** Accepts new applicant data (manual/CSV/JSON) → returns predicted scheme with confidence score.

---

## 📈 Results

* The model accurately classified applicants into the correct NSAP schemes.
* Preprocessing handled missing values and improved prediction reliability.
* Real-time prediction capability.

<img width="1534" height="863" alt="image" src="https://github.com/user-attachments/assets/3d4b0671-f455-415a-87e5-c3e86be1cd2f" />



<img width="1524" height="858" alt="image" src="https://github.com/user-attachments/assets/f722bc32-e34f-490d-9d11-f426fe3e2e2e" />

---

## 🔮 Future Scope

* Add more demographic and socio-economic features (income, household size, location).
* Experiment with **Gradient Boosting** and **Deep Learning** models.
* Integrate with real-time data pipelines and edge devices for faster offline predictions.



