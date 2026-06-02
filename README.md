# Prediction-of-Coronary-Heart-Disease---Logistic-Analysis

This project analyzes data from the Framingham Heart Study (4,133 participants) to predict 10-year coronary heart disease (CHD) risk using logistic regression in R. Key predictors explored include age, gender, smoking status, diabetes, BMI, and blood pressure.

After variable selection and multicollinearity testing, the final model retained gender, age, current smoker status, diabetes, and systolic blood pressure as significant predictors. The dataset's class imbalance, only 18% of participants were at-risk, initially inflated model accuracy while masking poor predictions for the minority class. SMOTE (Synthetic Minority Oversampling Technique) was applied to address this, improving at-risk prediction by 46.3%, with a final AUC of 0.75.

Key findings confirm that older age, male gender, smoking, diabetes, and elevated systolic blood pressure each significantly increase CHD risk. The model highlights the challenges of imbalanced medical datasets and the trade-offs between overall accuracy and sensitivity for high-risk individuals. Future improvements would benefit from collecting more at-risk participant data.
