# Netflix Customer Churn & Engagement Analytics

**Team Name:** Netflix Watchers
**Team Members:** Kirsten Perez, Mahek Kothari

## Overview

This project analyzes customer churn for a simulated Netflix subscriber base of 5,000 users, using demographic, behavioral, and subscription data to identify which customers are most likely to cancel their subscription and why.

## Problem Statement

Which subscribers are most likely to cancel their Netflix subscription, and what behavioral or account level factors best explain why? Can these risk factors be made into retention strategies?

## Goal

Build a churn-risk product consisting of:
- A trained classification model that scores subscribers by churn probability
- An interpretability layer explaining why a given subscriber is flagged as at-risk
- A dashboard for exploring churn drivers by segment (plan tier, region, payment method, engagement level)

## Dataset

- **Source:** [Netflix Customer Churn & Engagement Analytics](https://www.kaggle.com/datasets/zeyadmohamed26/netflix-customer-churn-and-engagement-analytics) (Kaggle, CC0 license)
- **Size:** 5,000 rows × 14 columns, no missing values
- **Key fields:** age, gender, subscription_type, watch_hours, last_login_days, region, device, monthly_fee, churned, payment_method, number_of_profiles, avg_watch_time_per_day, favorite_genre

The raw CSV is not committed to this repo (see `.gitignore`). Download instructions are in [`data/README.md`](data/README.md).

## Repository Structure

```
├── README.md          # Project overview 
├── data/              # Download instructions for the raw dataset
├── notebooks/         # Exploratory analysis and modeling notebooks
├── src/               # Source code (data processing, modeling, dashboard)
└── .gitignore
```

## Setup

1. Clone the repo:
   ```
   git clone https://github.com/<your-username>/netflixwatchers-churn-analytics.git
   cd netflixwatchers-churn-analytics
   ```
2. Create a virtual environment and install dependencies:
   ```
   python -m venv .venv
   source .venv/bin/activate   # Windows: .venv\Scripts\activate
   pip install -r requirements.txt
   ```
3. Download the dataset following the instructions in `data/README.md` and place it in the `data/` folder.

## Potential Users

Subscription-business analysts, product managers, and customer retention/marketing teams.