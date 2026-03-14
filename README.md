# Case Study: Biometric Analysis of Predynastic Egyptian Skulls 📊
# Caso de Estudio: Análisis Biométrico de Cráneos Egipcios

### Project Overview | Resumen del Proyecto
This study applies **Inferential Statistics** and **Python** to evaluate morphological changes in archaeological remains. The goal is to determine if there is a significant difference in cranial breadth ($mm$) between early and late predynastic periods.

Este estudio aplica técnicas de **Inferencia Estadística** y **Python** para evaluar cambios morfológicos. El objetivo es determinar si existe una diferencia significativa en la anchura de los cráneos ($mm$) entre los periodos temprano y tardío.

---

### Key Technical Features | Aspectos Técnicos Clave
* **Exploratory Data Analysis (EDA):** Visual interpretation using `Seaborn` boxplots and histograms.
* **Normality Testing:** Validation using **Shapiro-Wilk** and **Kolmogorov-Smirnov**.
* **Hypothesis Testing:**
    * **F-Test (Snedecor):** To verify homoscedasticity (equality of variances).
    * **T-Test (Student):** To compare means between independent samples ($n=30$).

### Main Results | Resultados Principales
The analysis revealed a significant increase in cranial breadth over time.
* **T-score Observed:** $-3.87$
* **Confidence Interval (95%):** $[-1.41, -0.45]$
* **Conclusion:** With a $p$-value $< 0.05$, we reject $H_0$, confirming that skulls became significantly wider in the later period.

---

### Tech Stack | Herramientas
* **Language:** Python
* **Libraries:** `pandas`, `numpy`, `scipy.stats`, `matplotlib`, `seaborn`.
* **Deliverables:** Professional Technical Report (PDF) and Jupyter Notebook.
