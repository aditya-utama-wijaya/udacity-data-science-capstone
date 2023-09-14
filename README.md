# Starbucks Customer Behavior Analysis
This repository contains an analysis of simulated Starbucks customer data to understand how different demographic groups respond to various offer types sent through the Starbucks mobile app.

## Repository Structure
- `data/`: Contains the datasets used for this analysis.
  - `portfolio.json`: Contains offer ids and meta data about each offer.
  - `profile.json`: Contains demographic data for each customer.
  - `transcript.json`: Contains records for transactions, offers received, viewed, and completed.
- `Starbucks_Customer_Behavior_Analysis.ipynb`: Jupyter notebook containing the analysis, data preprocessing, and modeling.

## Libraries Used
The following python libraries were used in this project.
- pandas==0.23.3
- numpy==1.21.1
- seaborn==0.8.1
- matplotlib==2.1.0
- scikit-learn==0.19.1

## Key Findings
- The majority of users are in the age group 50-70.
- Most users have an income range between $50,000 and $70,000.
- The gender distribution shows more male users than female.
- BOGO (Buy One Get One) and discount offers are the most frequently sent offers.
- A Decision Tree classifier was used to predict whether a user would complete an offer or not, achieving an accuracy of approximately 88.7%.
- You can find the blog post regarding this analysis [here](https://medium.com/@adityautamawijaya/analyzing-customer-responses-to-starbucks-offers-a390336ee2eb).

## Libraries Used
The following python libraries were used in this project.
- pandas==1.3.3
- numpy==1.21.2
- seaborn==0.11.2
- matplotlib==3.4.3

## Author
[Adi Wijaya](https://www.linkedin.com/in/aditya-utama-wijaya/)
