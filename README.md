# Project Overview

SyriaTel is a telecommunications service provider that operates across the globe, including the USA and other countries. In the telecommunications industry, people often switch from one service provider to another. This change in taste and preference is what we refer to as churning. SyriaTel is no exception to this. Through their data, we can understand the pattern behind customer churning, and therefore SyriaTel and other companies in the industry will be able to anticipate customers who are likely to leave.

# Business and Data Understanding

In order to carry out our task sufficiently, we first need an understanding of the business problem and to further understand the data that we will be using.

## Business Understanding

The problem at hand is customer churning, which has a negative outlook on the finances of the business. When customers keep leaving suddenly, it becomes challenging to have an accurate financial long-term plan for the business. Without a forecast on the number of customers you'll retain or lose, you can't plan well. Therefore, by developing a model, we can anticipate future churning and save the business a lot of money.

## Data Understanding

From Kaggle.com, we have obtained a dataset that contains the following details for each customer:

- **state**: The geographical location where the customer is residing.
- **account length**: The duration, measured in days, for which the customer has held their account.
- **area code**: The numeric code associated with the customer's phone number's geographical area.
- **phone number**: The unique phone number of the customer.
- **international plan**: A binary indicator for whether the customer has an international calling plan.
- **voice mail plan**: A binary indicator for whether the customer has a voice mail plan.
- **number vmail messages**: The count of voicemail messages the customer has sent or received.
- **total day minutes**: The total minutes the customer has spent on calls during the daytime.
- **total day calls**: The total number of calls the customer has made during the daytime.
- **total day charge**: The total monetary cost incurred by the customer for daytime calls.
- **total eve minutes**: The total minutes the customer has spent on calls during the evening.
- **total eve calls**: The total number of calls the customer has made during the evening.
- **total eve charge**: The total monetary cost incurred by the customer for evening calls.
- **total night minutes**: The total minutes the customer has spent on calls during the nighttime.
- **total night calls**: The total number of calls the customer has made during the nighttime.
- **total night charge**: The total monetary cost incurred by the customer for nighttime calls.
- **total intl minutes**: The total minutes the customer has spent on international calls.
- **total intl calls**: The total number of international calls the customer has initiated.
- **total intl charge**: The total monetary cost incurred by the customer for international calls.
- **customer service calls**: The count of calls the customer has placed to the customer service department.
- **churn**: A binary indicator for whether the customer has terminated their contract.
