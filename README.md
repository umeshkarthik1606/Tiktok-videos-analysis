# TikTok Project

## Overview
This project explores user engagement and content performance on TikTok by analyzing the relationship between account verification status, video view counts, and user behavior. It incorporates statistical testing, regression modeling, and classification analysis to derive actionable insights.

## Objectives
### Objective 1: Two-Sample T-Test
- **Hypotheses**:
  - **Null Hypothesis (H₀):** There is no significant difference in video view counts between verified and non-verified users.
  - **Alternative Hypothesis (H₁):** There is a significant difference in video view counts between verified and non-verified users.
- **Insight Goal**: Understand the impact of verification status on video viewership.

### Objective 2: Regression Modeling
- **Goal**: Develop a regression model to analyze user behavior within verified accounts.
- **Use Case**: Identify patterns and factors influencing user engagement among verified creators.

### Objective 3: Classification Modeling
- **Goal**: Create classification models to distinguish between claims and opinions in TikTok comments and videos.
- **Use Case**: Enhance content moderation and insight extraction by accurately categorizing user-generated content.

## Methodology
### Data Preparation
- Import essential libraries and prepare the dataset for analysis.
- Clean and preprocess data, ensuring consistency and quality.

### Analysis and Modeling
1. **Two-Sample T-Test**:
   - Compare video view counts between verified and non-verified users.
   - Perform hypothesis testing to determine statistical significance.

2. **Regression Modeling**:
   - Perform exploratory data analysis (EDA) to identify key predictors.
   - Train and validate the regression model on the verified user subset.
     
![3 1](https://github.com/user-attachments/assets/a4c95e88-db4d-4df8-85f3-003969d10646)

3. **Classification Modeling**:
   - Used machine learning techniques to classify comments and video content into claims or opinions.
   - Evaluated models based on accuracy, precision, recall, and F1 scores.
   - Utilized confusion matrices to visualize model results
    
![1 1](https://github.com/user-attachments/assets/3b17b691-02ff-4324-9e40-b2e8776fefc9)

   - Utilized roc and calibration curves to visualize model results

![3 2](https://github.com/user-attachments/assets/7123a8d2-bd5c-4b89-a8c5-e6b2cb837813)

### Feature Importance
- Generated visualizations to showcase the most impactful variables in each model.
  
![Image](https://github.com/user-attachments/assets/7f7160f0-8af8-41a8-926d-b64608a4fb07)

## Results
- **T-Test Analysis**: Determined the impact of verification status on video performance.
- **Regression Insights**: Identified user behavior trends among verified accounts.
- **Classification Accuracy**: Developed a robust model to differentiate claims from opinions in user comments.
