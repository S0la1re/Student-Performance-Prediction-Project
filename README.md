# Student-Performance-Prediction-Project

## Project Overview
This project is focused on predicting student performance based on various academic and behavioral factors using a robust multiple linear regression model.
The project includes several stages:
1. Data Cleaning,
2. Regression Analysis,
3. Testing Regression Assumptions,
4. Building a Regression Model.

Please be aware that this dataset is synthetic and has been created for illustrative purposes only. The relationships between the variables and the performance index may not accurately represent real-world scenarios. You can find the source of the data [here](https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression).

## Dataset

The dataset includes the following variables:

- **Hours Studied**: The total number of hours spent studying;
- **Previous Scores**: The scores obtained by students in previous assessments;
- **Extracurricular Activities**: Whether the student participated in extracurricular activities;
- **Sleep Hours**: The average number of hours of sleep per night;
- **Sample Question Papers Practiced**: The number of sample question papers practiced;
- **Performance Index**: A measure of the overall performance of the student.

## Regression Analysis

Regression analysis was performed using Excel's Data Analysis Toolpak.

![image](https://github.com/user-attachments/assets/27ef87ac-3c24-40ca-8963-5f50f9cc11e6)

After conducting the analysis, the following conclusions were drawn:
1. The ANOVA table tests the overall significance of the regression model and shows an extremely low p-value (0.000), indicating that the model is highly significant.
2. The high R-squared (0.9887) suggests that the model explains nearly 99% of the variance in academic performance, implying that it is highly effective in predicting students' scores.
3. Based on the p-values, all independent variables (predictors) are significant.

## Regression Assumptions

To ensure the validity of the model, all six key regression assumptions were tested using residual plots:
- **Linearity**: Confirmed correct functional form;
- **Homoscedasticity**: Checked for constant error variance (no heteroskedasticity);
- **Independence**: Ensured independent error terms (no autocorrelation);
- **Normality**: Verified normally distributed errors;
- **No Multicollinearity**: Ensured truly independent predictor variables;
- **Exogeneity**: Checked for no omitted variable bias.

## Regression Model

Once all necessary assumptions were met, the final regression model was built. The model demonstrated that variables such as previous scores and hours studied are key predictors of student performance. The final model and all supporting data can be reviewed by downloading the Excel file.
