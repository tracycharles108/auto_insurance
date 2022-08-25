# auto_insurance

Created by Tracy Charles

## Description

An introductory project on a dataset of auto insurance claims, which includes fields such as deductible, total claim amount, and reported fraud. Please note that this project is still ongoing. So far, this repo only includes Python code for data cleaning and a Power BI report in PDF format.

This project includes a machine learning component, i.e. predicting annual premiums. I am using a GLM with a Tweedie Regressor for this purpose and will update the repo once it is complete.

## Dataset

The dataset is public on Kaggle and can be found here: https://www.kaggle.com/datasets/buntyshah/auto-insurance-claims-data

## Learning Goals and Outcomes

I created this project with the following goals:

1. Become familiar with auto insurance data
2. Develop more actuarial knowledge and analytical skills
3. Learn how to use Power BI and create a report
4. Know how to create ML models commonly used in insurance and modeling

## Future Work

As mentioned, I am working on a GLM to predict annual premiums, where the target variable is `policy_annual_premium`. I'd also like to expand and use a different model (possibly KNN) and stack the models together and observe the output. If time permits, I'd also like to do another machine learning model to predict fraud detection, with `fraud_reported` as the target variable.

I also plan to add more visualizations and sentences to the Power BI report for a more comprehensive outlook on the data.

## Resources Used

This is my first project using Power BI. The main resource for learning it is the LinkedIn Learning Power BI Essential Training course.

For machine learning and actuarial resources, I use these:
1. https://www.casact.org/sites/default/files/database/monographs_papers_05-goldburd-khare-tevet.pdf
2. https://scikit-learn.org/stable/auto_examples/linear_model/plot_tweedie_regression_insurance_claims.html#pure-premium-modeling-via-a-product-model-vs-single-tweedieregressor

## License

MIT License
