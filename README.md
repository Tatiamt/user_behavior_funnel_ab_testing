# User Behavior Funnel A/A/B Testing

## Project Overview
This project analyzes user behavior in a mobile application through funnel analysis and A/A/B testing.

The main goal is to evaluate user progression through the purchase funnel and determine whether a design change (new font) affected user behavior.

## Objectives
- Analyze the event funnel
- Measure user conversion across key stages
- Validate the control groups through A/A testing
- Evaluate the impact of the new font through A/B testing

## Dataset
After data filtering, the final dataset contains:

- 243,329 events
- 7,542 unique users
- Average of 32.26 events per user

The analysis considers data from **2019-07-31 onward**, since earlier records showed incomplete activity.

## Funnel Stages
The main funnel was defined as:

1. MainScreenAppear
2. OffersScreenAppear
3. CartScreenAppear
4. PaymentScreenSuccessful

## Key Findings

### Funnel Analysis
- 55% of users move from the main screen to the offers screen
- 41% move from offers to cart
- 27% of users who reach the cart complete payment
- Overall conversion rate: **6.1%**

The largest drop-off occurs early in the journey, between the main screen and the offers screen.

### A/A Test
The comparison between control groups **246** and **247** showed no statistically significant differences, confirming that the experimental split was correctly implemented.

### A/B Test
The comparison between the test group **248** and the control groups showed no statistically significant differences across the analyzed funnel events.

This indicates that the new font did not affect user engagement, navigation, or conversion.

## Final Recommendation
The new font can be implemented safely, since no evidence was found that it negatively impacts user behavior.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Plotly
- Statsmodels
- Jupyter Notebook

## Files
- `user_behavior_funnel_ab_testing.ipynb` — full project notebook
- `logs_exp_us.csv` — dataset used in the analysis

## Author
Tatiana Torres 
Data Analyst 

- LinkedIn: [https://www.linkedin.com/in/tatianamartinstorres/](https://www.linkedin.com/in/tatianamartinstorres/)
- GitHub: [https://github.com/Tatiamt]
