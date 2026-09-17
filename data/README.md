# Data

This folder holds the raw dataset used in this project. The CSV itself is **not** committed to the repo (see the root `.gitignore`) — download it manually and place it here.

## Download Instructions

1. Go to the Kaggle dataset page:
   [Netflix Customer Churn & Engagement Analytics](https://www.kaggle.com/datasets/zeyadmohamed26/netflix-customer-churn-and-engagement-analytics)
2. Click **Download** (you'll need a free Kaggle account, and Kaggle may ask you to accept the dataset's terms).
3. Unzip the download and place the CSV in this folder as:
   ```
   data/netflix_customer_churn.csv
   ```

## File

| File | Rows | Columns | Size | Description |
|---|---|---|---|---|
| `netflix_customer_churn.csv` | 5,000 | 14 | ~546 KB | Subscriber-level churn, engagement, and demographic data |

## Columns

| Column | Type | Description |
|---|---|---|
| `customer_id` | string | Unique anonymous subscriber ID (UUID) |
| `age` | integer | Customer age (18–70) |
| `gender` | string | Female, Male, Other |
| `subscription_type` | string | Basic, Standard, Premium |
| `watch_hours` | float | Total cumulative monthly streaming hours |
| `last_login_days` | integer | Days since last login |
| `region` | string | Africa, Asia, Europe, North America, Oceania, South America |
| `device` | string | Desktop, Laptop, Mobile, TV, Tablet |
| `monthly_fee` | float | Monthly fee in USD (8.99, 13.99, 17.99) |
| `churned` | integer | Target variable: 0 = Active, 1 = Churned |
| `payment_method` | string | Credit Card, Crypto, Debit Card, Gift Card, PayPal |
| `number_of_profiles` | integer | Active profiles on the account (1–5) |
| `avg_watch_time_per_day` | float | Average daily streaming hours |
| `favorite_genre` | string | Action, Comedy, Drama, Horror, Romance, Sci-Fi, Thriller |

## License

CC0 1.0 Public Domain — free to use for academic, personal, or commercial purposes.