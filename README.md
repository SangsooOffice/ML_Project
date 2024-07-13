# Project Title
Prediction of drought scores based on weather and soil data. This project was conducted during the Machine learning class in the first semester of 2023.

# Why I do this project?
Due to the recent drought, the area of forest dead areas has increased significantly, which has created an environment in which forest fires can spread rapidly. It is causing serious ecological and economic damage along with forest destruction. In addition, the worsening of global warming is making the drought worse as the average temperature rises. So, in order to minimize the damage by predicting such drought, we selected the topic of drought score prediction.


# Project Process
**Preprocessing**
- The drought score exists every week, but the rest of the data exists every day. So, the rest of the data was grouped in 7-day increments and converted into one column.
- Reducing variable dimensions with multicollinearity problems.
- Perform feature selection to avoid overfitting
- Equalize the number of data for each drought score

**Modeling**
- Class classification was conducted using Random Forest, AdaBoost, XGBoost, LightGBM, and stacking method

**XAI**
- Shap (XAI) was used for the interpretation of the results.

# Result
- After Modeling Result <img src="https://github.com/user-attachments/assets/46c61eea-3264-4341-bc4b-a8109fe800cb" alt="After Modeling Result" style="display: inline; margin-left: 10px;"/>

# contribution
- Early warning system and disaster preparedness.
- Respond quickly to climate change.
- Systematic planning of agriculture and increasing productivity.

# Difficult Point
- How to handle drought scores on a 7-week cycle