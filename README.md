# Explainable AI (XAI) Research

## Overview

The goal of my research on **Explainable AI (XAI)** was to explore potential uses of XAI methods and assess their performance. I conducted a comprehensive literature review to analyze the pros and cons of XAI and its overall performance. Additionally, I performed an experiment using the **Boston Housing Dataset**, where I trained a Random Forest regression model to predict housing prices based on various neighborhood and housing characteristics.

To interpret the predictions made by the model, I employed two prominent XAI techniques: **LIME** (Local Interpretable Model-agnostic Explanations) and **SHAP** (SHapley Additive exPlanations). These methods allowed me to generate both local and global explanations for the model's predictions.

Through experimentation, I compared the effectiveness and interpretability of LIME and SHAP, noting their respective strengths (such as SHAP’s consistency and theoretical soundness) and limitations (such as computation time). This research reinforces the main takeaways from my literature review and demonstrates the importance of explainability in building trustworthy and transparent AI systems.

## Cited Papers

1. **Angelov, Plamen P., et al.**  
   "Explainable Artificial Intelligence: An Analytical Review."  
   _Wiley Interdisciplinary Reviews: Data Mining and Knowledge Discovery_, vol. 11, no. 5, 2021, Art. ID e1424. DOI: [10.1002/widm.1424](https://doi.org/10.1002/widm.1424)
   
2. **Dwivedi, Rudresh, et al.**  
   "Explainable AI (XAI): Core Ideas, Techniques, and Solutions."  
   _ACM Computing Surveys_, vol. 55, no. 9, Jan. 2023, Art. ID 194. DOI: [10.1145/3561048](https://doi.org/10.1145/3561048)

3. **McNamara, Mike.**  
   "Explainable AI: What Is It? How Does It Work? And What Role Does Data Play?"  
   _NetApp Blog_, 22 Feb. 2022, [NetApp Blog](https://www.netapp.com/artificial-intelligence/)

4. **Srinivasu, Parvathaneni Naga, et al.**  
   "From Blackbox to Explainable AI in Healthcare: Existing Tools and Case Studies."  
   _Mobile Information Systems_, vol. 2022, 13 June 2022, Art. ID 8167821. DOI: [10.1155/2022/8167821](https://doi.org/10.1155/2022/8167821)

---

## Research Steps

1. **Researched LIME and SHAP** for potential datasets.
   - [Link to the code](#) (Coming Soon)

2. **Experimented with LIME and SHAP** to evaluate their pros and cons.

3. **Created a Colab notebook** with a LIME vs SHAP comparison, applied to a model trained to analyze the **Boston Housing Dataset**.
   - Dataset source: [Kaggle - Boston Housing Dataset](https://www.kaggle.com/code/prasadperera/the-boston-housing-dataset)

4. **Created visualizations** of correlations between features and outcomes.

5. **Optimized the Random Forest model** for better predictions.

6. **Applied LIME and SHAP** for model interpretation and explanation.

---

## Conclusion

This research demonstrates that both **LIME** and **SHAP** can be effectively used to analyze features within basic AI models. Specifically:

- **LIME** (TabularExplainer) was effective in providing localized explanations for individual instances, highlighting which features were most influential in each prediction.
- **SHAP** provided global insights into the overall impact of all features, presenting consistent and interpretable visualizations of model outputs.

Both methods have their unique strengths, but ultimately, they emphasize the need for transparency and explainability in AI models.

---

## To Do

- Upload the **Colab notebook** with LIME vs SHAP comparison.
- Provide links to the source code on GitHub.

---

## License

This project is licensed under the Apache 2.0 License
