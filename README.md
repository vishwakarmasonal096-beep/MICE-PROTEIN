## Introduction 

This project applies classical machine learning techniques to classify different types of mice based on protein expression data collected from their brain tissues. The study leverages real-world biomedical data and explores the relationship between genotype, treatment, behavior, and protein activity to understand the effects of neurological conditions like Down Syndrome.

---

## 🧠 Project Overview

The goal of this project is to classify mice into **8 biological classes** formed by combinations of:
- **Genotype**: Control or Trisomic (Down Syndrome model - Ts65Dn)
- **Treatment**: Saline or Memantine
- **Behavioral Task**: Context-Shock or Shock-Context

Using protein expression levels as input features, we trained and evaluated multiple machine learning models to predict the biological class of a given mouse.

---

## 🎯 Problem Statement

Can we classify a mouse into one of the 8 predefined biological classes using only its protein expression data?

By solving this problem, we aim to:
- Support biomedical research and drug testing
- Improve understanding of Down Syndrome models
- Identify proteins that could be potential **biomarkers**

---

## 📊 Dataset Information

- **Source**: Real-world neuroscience experiment
- **Samples**: ~1080 mouse brain samples
- **Features**:  
  - 77 Protein expression levels (e.g., CaNA_N, Tau_N, Ubiquitin_N)  
  - Categorical variables: Genotype, Treatment, Behavior  
- **Target Variable**: `class` (8-class classification problem)

---

## 🛠 Technologies Used

| Category         | Tools/Libraries                               |
|------------------|-----------------------------------------------|
| Programming      | Python 3.13                                   |
| Data Handling    | Pandas, NumPy                                 |
| Visualization    | Matplotlib, Seaborn                           |
| Machine Learning | Scikit-learn (KNN, Random Forest, etc.)       |
| Feature Selection| SelectKBest with ANOVA F-test                 |
| IDE & Deployment | Jupyter Notebook, GitHub, Streamlit (optional)|

---

## 🧪 Steps Involved

1. Data Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Selection  
4. Model Training  
5. Model Evaluation  
6. Interpretation & Insights  
7. Conclusion

---

## 🔍 Key Learning & Insights

- Top proteins such as **CaNA_N**, **Tau_N**, and **Ubiquitin_N** were biologically relevant and consistent across classes.
- Protein patterns varied across genotype and treatment, aligning with Down Syndrome research.
- The model revealed that protein data is **naturally clusterable**, making KNN an ideal choice.
- Developed a high-performing classifier for protein-based mouse classification.
- The project demonstrates that ML can reduce time and cost in bioinformatics.
- Identified protein biomarkers that may help in early diagnosis or treatment evaluation.
- The model is generalizable and scalable to similar biological datasets.

---

## 📚 Conclusion

The Mice Protein Classification project showcases how machine learning can power biological discovery.  
Using KNN and feature selection, we built a highly accurate and interpretable model that could support biomedical research, especially in Down Syndrome and neuroscience.  
With more domain collaboration, this model could be adapted for **human clinical applications**, making it a powerful tool in the future of bioinformatics.

---

## 👨‍💻 Author

**Sufiyan Zamindar**  
Machine Learning & Data Science Enthusiast  
GitHub: [sufiyan-zamindar](https://github.com/sufiyan-zamindar)  
LinkedIn: [Sufiyan Zamindar](https://www.linkedin.com/in/sufiyan-zamindar/)

---

