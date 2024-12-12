# Financial Services CTA Optimization Project

## Project Overview

This project aims to optimize call-to-action (CTA) strategies for Financial Services to maximize revenue per user. The analysis involves exploring user interactions, behavior patterns, and developing a predictive model to identify the most effective CTA combinations.

## Key Objectives

- Analyze CTA performance across different placements and text variations
- Understand user behaviors and their impact on revenue
- Develop a predictive model to recommend optimal CTA strategies

## Key Findings

### CTA Performance
- Best performing CTA: "First Time? We've Made it Easy to Find the Best Mortgage Rate" placed at the bottom of the page
- Potential incremental revenue: $87,488.55 by adopting the optimal CTA strategy

### User Behavior Insights
- 60% of users browse the site on mobile devices
- Only 5.5% of users schedule appointments
- Strong correlation between scheduled appointments and revenue generation

## Technical Approach

### Data Preprocessing
- Handled missing values
- Encoded categorical variables
- Created derived features like income groups and scroll engagement

### Model Development
- Used RandomForestRegressor with GridSearchCV
- Feature selection using SelectKBest
- Scaled features using StandardScaler

### Model Performance
- R-Squared: 0.9424 (94.24% variance explained)
- Mean Absolute Error: 2.43

## Most Important Features for Revenue
1. Scheduled Appointment
2. Estimated Annual Income
3. CTA Combination
4. Page URL

## Recommendations
- Focus on encouraging appointment scheduling
- Optimize CTAs for first-time mortgage seekers
- Target higher-income user segments
- Improve content on key landing pages

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Getting Started
1. Clone the repository
2. Install requirements: `pip install -r requirements.txt`
3. Run the analysis notebook

## Author
Melchizedek Ackah-Blay
