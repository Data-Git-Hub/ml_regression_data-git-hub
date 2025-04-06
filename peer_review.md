# Peer Review

**Project Reviewed**: David Rodriguez-Mayorquin – Medical Cost Dataset / Regression  
**Notebook**: [regression_davidrm.ipynb](https://github.com/drodmay1/ml_regression_davidrm/blob/main/regression_davidrm.ipynb)  
**Reviewer**: [data-git-hub](https://github.com/Data-Git-Hub)  
**Date**: April 7, 2025  

---

### 1. Clarity & Organization

The notebook is well-structured, with a clean and sequential progression from data inspection through to final evaluation. Markdown cells are used effectively to document each step, allowing readers to easily follow the rationale and methodology. Clear section labeling, appropriately scoped visualizations, and explanation of results contribute to its strong readability and reproducibility—an essential characteristic of quality analytics documentation (Pimentel et al., 2019). <br>

---

### 2. Feature Selection & Justification

David's selection of features—age, BMI, and smoking status—is well-founded, as these variables are recognized as significant predictors of medical insurance costs. Research by Patra et al. (2024) identifies these factors as major contributors to healthcare expenditures, highlighting their predictive value in modeling medical costs. David's approach to encoding categorical variables and analyzing their distributions demonstrates a solid understanding of data preprocessing techniques. Including reflections at each step further supports the empirical basis for modeling decisions.​  <br>

---

### 3. Model Performance & Comparisons

Multiple models are trained and evaluated using appropriate regression metrics (R^2, MAE, RMSE), and the use of pipelines indicates adherence to best practices in machine learning workflows (Pedregosa et al., 2011). The linear regression pipeline is applied cleanly, and model performance is interpreted with clarity. These metrics provide interpretable insights for model evaluation, balancing both goodness-of-fit and error tolerance (Willmott & Matsuura, 2005). <br>

---

### 4. Reflection Quality and Constructive Suggestion

Reflections are present after each major step and demonstrate awareness of data quality, predictive factors, and modeling decisions. The explanations are thoughtful and well-aligned with the project’s goals. <br>

One improvement could be to explore nonlinear models, such as Random Forest Regression or Gradient Boosting, which often outperform linear approaches on medical cost data by capturing complex interactions between predictors (Mehta et al., 2019). Trying such ensemble models would not only strengthen predictive accuracy but also help identify nonlinear relationships that linear regression may overlook. <br>

---

### Summary

This project is a strong demonstration of end-to-end regression modeling, with a clear structure, strong feature selection, and effective use of evaluation metrics. Reflections show maturity in interpretation, and results are well-communicated. By exploring a nonlinear model like gradient boosting or random forests, the author could further enrich the model comparison and potentially enhance performance. <br>

Excellent work overall, and highly reflective of applied machine learning standards. <br>

---

### References

Mehta, P., Reddy, C. K., & Chen, L. (2019). Healthcare cost prediction using gradient boosted decision trees. *BMC Medical Informatics and Decision Making*, *19*(1), 1–10. https://doi.org/10.1186/s12911-019-0911-z <br>

Patra, G. K., et al. (2024). An analysis and prediction of health insurance costs using machine learning. Journal of Data Analysis and Information Processing, 12(4), 567–589. Retrieved from https://www.scirp.org/pdf/jdaip2024124_62870742.pdf <br>

Pedregosa, F., Varoquaux, G., Gramfort, A., Michel, V., Thirion, B., Grisel, O., ... & Duchesnay, É. (2011). Scikit-learn: Machine learning in Python. *Journal of Machine Learning Research*, *12*, 2825–2830. https://www.jmlr.org/papers/v12/pedregosa11a.html <br>

Pimentel, J. F., Murta, L., Braganholo, V., & Freire, J. (2019). A large-scale study about quality and reproducibility of Jupyter notebooks. *Proceedings of the 16th International Conference on Mining Software Repositories*, 507–517. https://doi.org/10.1109/MSR.2019.00074 <br>

Willmott, C. J., & Matsuura, K. (2005). Advantages of the mean absolute error (MAE) over the root mean square error (RMSE) in assessing average model performance. *Climate Research*, *30*(1), 79–82. https://doi.org/10.3354/cr030079 <br>