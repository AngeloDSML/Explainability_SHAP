### Quick Tutorial - Model Explainability using SHAP (SHapley Additive exPlanations)

In the previous tutorials **[Intro to Machine Learning for Residential Appraisers, Part 1](https://github.com/AngeloDSML/Home_Valuation_Part_1)** and **[Intro to Machine Learning for Residential Appraisers, Part 2](https://github.com/AngeloDSML/Home_Valuation_Part_2)**, we covered data collection, data wrangling/cleaning, visualizations, and data modeling. Then we ran predictions using four different models: Linear Regression, Decision Tree Regression, Extreme Gradient Boosting (XGBoost), and Random Forest.
&nbsp;

Next, we are going to explore a model explainability tool called SHAP (SHapley Additive exPlanations). [Here](https://github.com/AngeloDSML/Explainability_SHAP/blob/main/Tutorial_Shap.ipynb) is the link to the notebook.
&nbsp;
&nbsp; 


### What is SHAP?

From the SHAP documentation: https://shap.readthedocs.io/ 
&nbsp;

"SHAP (SHapley Additive exPlanations) is a game theoretic approach to explain the output of any machine learning model. It connects optimal credit allocation with local explanations using the classic Shapley values from game theory and their related extensions (see **[papers](https://github.com/slundberg/shap#citations)** for details and citations)."

