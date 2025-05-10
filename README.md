# Wolt Data Analysis Project

## Overview
This repository contains a comprehensive data analysis of machine generated Wolt user behavior, purchasing patterns, and platform usage across different countries. The analysis explores customer conversion rates, spending behaviors, device preferences, and engagement metrics to derive actionable business insights.

## Project Highlights
- **Multi-dimensional analysis** of user behavior across different countries
- **Customer segmentation** based on spending patterns
- **Device usage analysis** and its correlation with user activity
- **Restaurant preference analysis** to understand cuisine popularity
- **Temporal patterns** in ordering behavior

## Key Findings

### User Engagement & Conversion
- 54.72% overall customer conversion rate
- 65.26% customer retention rate
- Significant country-based variation in user activation rates:
  - Denmark: 61.84%
  - Finland: 53.20%
  - Greece: 50.53%

### Spending Behavior
- Customer segmentation:
  - 16.30% high spenders
  - 67.30% medium spenders
  - 16.40% low spenders
- Denmark has the highest proportion of high spenders (51.9%)
- Finland leads in medium spenders (48.1%)
- Correlation between purchase frequency and days between orders

### Restaurant & Cuisine Preferences
- American cuisine is the most preferred (39.53% of preferences)
- Top cuisines by preference:
  1. American (1,054 votes)
  2. Italian (517 votes)
  3. Japanese (476 votes)
- Restaurant-type purchases dominate across all countries

### Device Usage Patterns
- iOS users show higher activity rates than Android users
- Finland has significant inactive Android users
- Web platform usage correlates with higher conversion countries

### Daily Usage Patterns
- Meal-time distribution:
  - Dinner: 40.70%
  - Lunch: 31.90%
  - Breakfast: 18.10%
  - Evening: 6.60%
  - Late night: 2.60%
- Delivery dominates over takeaway (>90% across countries)

## Data Description
The analysis was performed on a dataset containing:
- User registration information
- Purchase history
- Device usage data
- Country-specific information
- Restaurant/store type preferences
- Temporal ordering patterns

## Technologies Used
- **Python** for data analysis and processing
- **Pandas** for data manipulation
- **NumPy** for numerical computations
- **Matplotlib/Seaborn** for data visualization
- **Jupyter Notebooks** for interactive analysis


## Getting Started

### Prerequisites
- Python 3.8+
- pip package manager

### Installation
1. Clone this repository:
```bash
git clone https://github.com/yourusername/wolt-data-analysis.git
cd wolt-data-analysis
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

### Running the Analysis
1. Place your data files in the `data/raw/` directory
2. Run the data processing script:
```bash
python scripts/data_cleaning.py
```

3. Open and run the Jupyter notebooks in sequence:
```bash
jupyter notebook notebooks/
```

## Key Recommendations

### Business Strategy
- Target countries with high registration but low conversion rates
- Apply Denmark's successful strategies to other markets
- Improve Android app experience to increase engagement
- Leverage peak purchase hours for targeted promotions

### Customer Engagement
- Address immediate customer churn after first purchase
- Enhance restaurant offerings with popular cuisines
- Implement time-based campaigns based on peak hours
- Optimize delivery services based on demand patterns

### Platform Development
- Improve Android app experience in Finland where most users are inactive
- Enhance web platform to attract more users globally
- Collect user journey data to understand drop-off points

## Future Work
- Deeper analysis of restaurant ratings and review data
- Geographic analysis of delivery times and distances
- Predictive modeling for user churn prevention
- Basket analysis to identify complementary items


## Acknowledgments
- Wolt for providing the machine generated dataset for analysis

---

*Note: This project was created for analytical purposes and the insights derived are based on the available data at the time of analysis.*
