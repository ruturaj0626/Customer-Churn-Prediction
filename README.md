# Telecom Churn Prediction

## Overview

This notebook covers the process of data preparation for training neural networks, which includes one-hot encoding categorical features and standardizing numeric features. It focuses on Customer Churn Prediction, a crucial task for businesses to identify and retain customers.

Losing customers can be costly, and predicting customer churn early on can help businesses offer incentives to retain them. This notebook explores the use of machine learning (ML) to automate the identification of unhappy customers and deals with the financial implications of prediction errors.

## Data

The dataset used in this project contains information from a US mobile operator and includes the following attributes:

- **State**: The US state in which the customer resides, indicated by a two-letter abbreviation (e.g., OH or NJ).
- **Account Length**: The number of days that the account has been active.
- **Area Code**: The three-digit area code of the corresponding customer’s phone number.
- **Phone**: The remaining seven-digit phone number.
- **Int’l Plan**: Whether the customer has an international calling plan (yes/no).
- **VMail Plan**: Whether the customer has a voice mail feature (yes/no).
- **VMail Message**: Presumably, the average number of voice mail messages per month.
- **Day Mins**: The total number of calling minutes used during the day.
- **Day Calls**: The total number of calls placed during the day.
- **Day Charge**: The billed cost of daytime calls.
- **Eve Mins, Eve Calls, Eve Charge**: The billed cost for calls placed during the evening.
- **Night Mins, Night Calls, Night Charge**: The billed cost for calls placed during nighttime.
- **Intl Mins, Intl Calls, Intl Charge**: The billed cost for international calls.
- **CustServ Calls**: The number of calls placed to Customer Service.
- **Churn?**: Whether the customer left the service (true/false).

The target attribute is "Churn?", and the goal of the ML model is binary prediction (churn or no churn).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This dataset is sourced from [Add Data Science to Your Resume with These 5 Projects](https://towardsdatascience.com/add-data-science-to-your-resume-with-these-5-projects-3b2af6f617a4).
- Special thanks to the data science community for valuable insights and resources.
