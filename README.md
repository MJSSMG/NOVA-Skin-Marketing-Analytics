# NOVA Skin — Marketing Analytics Project

## Project Overview

NOVA Skin is a fictional Indian direct-to-consumer (D2C) skincare brand used for an end-to-end marketing analytics project. The project brings together data from multiple marketing channels to understand campaign performance, customer behaviour, website conversions, and revenue generation.

The analysis uses Python to clean, explore, analyse, and visualise data across organic social media, paid advertising, website traffic, email marketing, influencer campaigns, products, and orders.

## Business Objectives

- Evaluate overall sales and revenue performance.
- Understand which marketing channels generate traffic, orders, and revenue.
- Measure organic social media engagement and content performance.
- Analyse paid advertising spend, clicks, conversions, and return on ad spend.
- Evaluate website traffic and the visitor-to-customer conversion funnel.
- Compare email campaign performance.
- Identify high-performing influencer campaigns and platforms.
- Understand product and customer purchasing patterns.
- Turn findings into actionable marketing recommendations.

## Dataset

The project uses eight CSV files:

| File | Description |
|---|---|
| `products.csv` | Product information |
| `campaigns.csv` | Marketing campaign details |
| `orders.csv` | Order-level transaction data |
| `social_posts.csv` | Organic social media post performance |
| `ad_performance.csv` | Paid advertising performance |
| `website_traffic.csv` | Website traffic and funnel data |
| `email_campaigns.csv` | Email campaign performance |
| `influencer_campaigns.csv` | Influencer campaign performance |

## Tools & Technologies

- **Python** — analysis and data processing
- **Pandas** — data cleaning, transformation, and aggregation
- **NumPy** — numerical operations
- **Matplotlib** — data visualisation
- **Seaborn** — statistical visualisation
- **Jupyter Notebook / Google Colab** — development environment

## Project Workflow

1. Load the eight CSV datasets.
2. Inspect dataset structure, data types, missing values, and duplicates.
3. Clean and prepare the data for analysis.
4. Perform exploratory data analysis (EDA).
5. Calculate channel-specific marketing KPIs.
6. Create visualisations to identify trends and performance differences.
7. Compare campaigns, platforms, products, and customer behaviour.
8. Summarise findings and develop data-driven recommendations.

## Key Metrics

Metrics used across the project include:

- **Revenue:** Total sales generated.
- **Orders:** Number of completed orders.
- **Average Order Value (AOV):** Revenue divided by orders.
- **Engagement Rate:** Engagement relative to the relevant audience or reach, according to the dataset's calculation.
- **Click-Through Rate (CTR):** Clicks relative to impressions.
- **Conversion Rate:** Conversions relative to the relevant clicks or visitors.
- **Cost Per Order (CPO):** Marketing spend divided by orders attributed to the campaign.
- **Return on Ad Spend (ROAS):** Attributed revenue divided by advertising spend.
- **Email Open Rate:** Opens relative to delivered emails.
- **Email Click Rate:** Clicks relative to delivered emails.

*Metric definitions should be interpreted using the calculation logic in the notebook and the available source columns.*

## Visual Analysis

The project includes visual analysis of:

1. Revenue and sales performance
2. Organic social media performance
3. Paid marketing performance
4. Email marketing performance
5. Influencer marketing performance

## Influencer Marketing — Example Findings

The influencer analysis in the project notebook reported the following results:

| Metric | Result |
|---|---:|
| Total influencer spend | ₹645,802.34 |
| Attributed revenue | ₹1,524,166.12 |
| Orders | 1,380 |
| Overall ROAS | 2.36x |

Platform comparison:

| Platform | Spend | Revenue | ROAS |
|---|---:|---:|---:|
| Instagram | ₹411,543.45 | ₹721,500.37 | 1.75x |
| YouTube | ₹234,258.89 | ₹802,665.75 | 3.43x |

Additional reported observations:
- Neha Verma recorded the highest ROAS at 4.05x.
- Ananya Singh generated the highest revenue at ₹412,240.05.
- Kavya Sharma recorded the highest engagement rate at 8.18%.
- Aarohi Mehta recorded the highest conversion rate at 21.62%.

These are revenue-efficiency metrics, not measures of net profit. ROAS compares attributed revenue with marketing spend and does not account for product costs, fulfilment, or other operating expenses.

## Repository Structure

A suggested repository layout:

```text
NOVA-Skin-Marketing-Analytics/
│
├── data/
│   ├── products.csv
│   ├── campaigns.csv
│   ├── orders.csv
│   ├── social_posts.csv
│   ├── ad_performance.csv
│   ├── website_traffic.csv
│   ├── email_campaigns.csv
│   └── influencer_campaigns.csv
│
├── notebooks/
│   └── 01_NOVA_Skin_Marketing_Analytics.ipynb
│
├── visualizations/
│   ├── revenue_analysis.jpg
│   ├── social_media_analysis.jpg
│   ├── paid_marketing_analysis.jpg
│   ├── email_marketing_analysis.jpg
│   └── influencer_marketing_dashboard.jpg
│
├── requirements.txt
└── README.md
```

Adjust folder and file names to match the structure you actually upload to GitHub.

## How to Run the Project

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd NOVA-Skin-Marketing-Analytics
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

Launch Jupyter:

```bash
jupyter notebook
```

Or upload the notebook and dataset files to Google Colab.

### 4. Load the datasets

Keep the CSV files in the folder path expected by the notebook, or update the notebook's data-loading path to match your folder structure.

### 5. Run the analysis

Run the notebook cells in order, from top to bottom.

## Business Recommendations

Use the findings from the analysis to guide decisions such as:

- Prioritising channels that generate stronger revenue relative to spend.
- Improving social content based on engagement and audience response.
- Reviewing paid campaigns with high costs and weak conversion performance.
- Optimising website pages and checkout steps where visitors drop off.
- Testing email content and timing to improve engagement and conversions.
- Evaluating influencer partnerships using both conversion and revenue metrics, not reach alone.

Recommendations should be finalised against the actual results and charts in the notebook.

## Limitations

- NOVA Skin is a fictional brand and the dataset is intended for portfolio and learning purposes.
- Marketing attribution in the dataset may not represent a complete multi-touch attribution model.
- ROAS is not the same as profitability.
- Findings depend on the fields, date coverage, and assumptions in the supplied datasets.

## Author

**Manjunath**

Aspiring Data Analyst | Marketing Analytics | Python | SQL | Power BI

This project demonstrates the application of data analytics to digital marketing and business performance questions.
