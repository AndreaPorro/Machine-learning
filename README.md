# 🍄 Mushroom Edibility: Supervised Learning & XAI Optimization

This repository contains a high-stakes machine learning project developed for the **"Machine Learning"** course as part of the MSc in Data Science at the **University of Milan-Bicocca (UNIMIB)**.

The project demonstrates a professional hybrid workflow, combining **Low-Code Visual Programming** for the analytical pipeline with **Python** for advanced Explainable AI (XAI).

## 🎯 Project Objectives & Syllabus Alignment
The study addresses the binary classification of mushrooms (edible vs poisonous) by implementing a robust pipeline focused on safety-critical decision-making:
* **Data Exploration & Pre-Processing:** Advanced handling of categorical attributes, variance analysis, and data encoding.
* **Supervised Classification:** Comparison of **Decision Trees**, **Naive Bayes**, and **Random Forest** to identify the most robust learner.
* **Performance Evaluation:** Implementation of **Cost-Sensitive Learning** to eliminate False Negatives (poisonous mushrooms labeled as edible).
* **Interpretability (XAI):** Applying **SHAP (SHapley Additive exPlanations)** to extract biological drivers of toxicity from ensemble models.

## 🛠️ Tech Stack & Hybrid Workflow
This project utilizes a unique combination of tools to maximize efficiency and depth:
* **KNIME Analytics Platform:** Used for the core end-to-end pipeline, including data cleaning, feature selection, model training, and performance comparison via visual workflows.
* **Python (Integration):** Used specifically for **Explainable AI**. By integrating Python scripts within the KNIME environment, `SHAP` was used to calculate and visualize feature contributions.




## 📈 Key Insights & Strengths
* **Safety-First Calibration:** By adjusting the classification threshold, the model achieved **zero false negatives**, prioritizing human safety over overall accuracy.
* **Hybrid Efficiency:** Using KNIME allowed for rapid prototyping and clear data lineage, while Python provided the flexibility for deep interpretability.
* **Model Explainability:** SHAP analysis identified **"Odor"** and **"Spore-print-color"** as the primary indicators of toxicity, providing a transparent "Why" behind the Random Forest's predictions.
* **Methodological Rigor:** The project follows a complete ML lifecycle: from Exploratory Data Analysis (EDA) and data encoding to model selection and post-hoc interpretability.
* **Performance:** The Random Forest ensemble reached nearly **100% accuracy**, demonstrating high robustness to categorical variance.


## 📂 Repository Structure
* `Final project of ML.knwf.zip`: The KNIME workflow file. 
* `Project - XAI focus.ipynb`: The Python script used for SHAP interpretability.
* `Analytic report of the project.pdf`: Comprehensive technical report covering methodology and results.
* `mushrooms_decoded.csv`: Original dataset with 22 categorical morphological features.

## Contributors

- [@ilaria-cesa](https://github.com/ilaria-cesa)
- [@mezza04](https://github.com/mezza04)

---
*Developed by Andrea Porro, Ilaria Cesaratto, and Chiara Mezzanzanica.*
