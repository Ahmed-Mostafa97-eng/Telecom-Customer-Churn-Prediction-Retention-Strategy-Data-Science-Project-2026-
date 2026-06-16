# Data

The raw dataset is **not included** in this repository because it is proprietary
assignment data.

To run the analysis, place the two CSV files in a `telecom/` folder at the
project root:

```
telecom/
├── Client.csv     # one row per customer: tenure, plan, equipment, demographics
└── Record.csv     # one row per customer: usage, billing, call-quality, churn
```

Both tables are joined on `Customer_ID`. After the join the working table has
100,000 rows × 100 columns, with a roughly balanced `churn` target.
