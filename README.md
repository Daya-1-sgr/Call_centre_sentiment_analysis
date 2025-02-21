# Call Centre Customer Service Analysis

## Introduction

Customer service quality can make or break a company’s reputation. Call-centres are often at the frontline of customer interactions, making them a crucial component of customer satisfaction strategies.

To ensure that these interactions meet customer expectations, it’s essential to analyse and understand the factors that contribute to positive or negative experiences.

In this project, we delve into a dataset from a call centre and explore key metrics and uncover insights that can help improve call centre operations and ultimately enhance customer satisfaction.

## Background of the Call-Centre Dataset

This dataset originates from a call centre, focusing on customer interactions and feedback.

The data includes various attributes related to customer service experiences, such as customer satisfaction (CSAT) scores, sentiment analysis of the interactions, call details, and response times.

The primary purpose of this dataset is to assess the performance of the call centre and the quality of customer service.

## Potential Insights from the Data

By analysing the data, one can identify areas for improvement, such as reducing response times, enhancing the efficiency of specific communication channels, and addressing factors that lead to negative sentiments and low CSAT scores.

The dataset is valuable for operational analysis, enabling the call centre management to make informed decisions on training, process optimisation, and resource allocation to enhance customer satisfaction and overall service quality.

## Brief Overview of Key Elements in the Dataset

### Customer Satisfaction (CSAT) Scores
A numerical measure (ranging from 1 to 10) that reflects the customer’s satisfaction with the service provided during the interaction.

### Sentiment Analysis
The sentiment of each interaction is categorized as “Very Negative,” “Negative,” “Neutral,” “Positive,” or “Very Positive.”

This sentiment likely results from analysing the customer’s tone, language, and feedback during the call.

### Call Details
Information such as the reason for the call (e.g., billing inquiries), the city and state of the customer, the channel through which the interaction occurred (e.g., Call-Centre, Chatbot, Web), and the call duration in minutes.

### Response Time
Indicates whether the call was responded to within the Service Level Agreement (SLA), below the SLA, or if the issue was escalated or above SLA. This is crucial for understanding the efficiency of the service provided.

### Call Centre Location
The geographical location of the call centre handling the interaction, which could be important for identifying regional performance trends.

## Exploratory Data Analysis (EDA)

The EDA will include:

- **Summary Statistics**: General statistical overview of the numerical and categorical variables.
- **Distribution Analysis**: Understanding the distribution of key numerical variables.
- **Sentiment Analysis**: Breakdown of sentiments and their relationship with other variables.
- **Channel and Response Time Analysis**: Analysing how different channels and response times impact the CSAT scores and sentiments.

## Summary Statistics

### Numerical Summary Statistics

| Column                | Count | Mean  | Std   | Min | Max |
|-----------------------|-------|-------|-------|-----|-----|
| CSAT Score            | 70    | 5.32  | 2.38  | 1   | 10  |
| Call Duration (Minutes)| 70    | 26.25 | 12.57 | 6   | 45  |

#### Numerical Summary Statistics

- There is a wide range of customer satisfaction scores, with a mean score of approximately 5. This indicates that the distribution might be somewhat balanced but leans slightly towards the lower end.
- The call durations also have a wide range, suggesting that a significant number of calls are longer in duration.

### Categorical Summary Statistics

| Column          | Unique | Top              | Frequency |
|-----------------|--------|------------------|-----------|
| ID              | 70     | PIS-39858047      | 1         |
| Customer Name   | 70     | Frances Gullefant | 1         |
| Sentiment       | 5      | Negative         | 29        |
| Reason          | 3      | Billing Question | 50        |
| City            | 57     | Minneapolis      | 3         |
| State           | 29     | Texas            | 9         |
| Channel         | 4      | Call-Centre      | 23        |
| Response Time   | 3      | Within SLA       | 53        |
| Call Centre     | 4      | Los Angeles/CA   | 30        |

#### Categorical Summary Statistics

- There are 5 unique sentiments, with "Negative" being the most common, occurring 29 times. This suggests a potential area of concern for the call centre.
- The most frequent reason for calls is "Billing Question" (50 out of 70 entries), indicating that billing issues are a primary driver for customer inquiries.
- The most common channel is "Call-Centre" (23 occur


