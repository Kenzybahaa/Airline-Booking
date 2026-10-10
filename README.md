
# ✈️ Airline Booking Data Analysis

## 📌 Project Overview

This project analyzes airline booking data to identify booking trends, understand customer preferences, and evaluate travel-related patterns and operational metrics.

Using Microsoft Excel, Python, and SQL Server, the project follows a data analytics workflow from data cleaning and transformation to exploratory data analysis (EDA), visualization, and business insights.

## 🎯 Objectives

- Analyze booking trends across sales channels and trip types.
- Understand customer preferences for baggage, preferred seats, and in-flight meals.
- Examine purchase lead time and booking patterns.
- Identify countries with the highest number of bookings.
- Explore flight durations and passenger-related metrics.
- Transform raw data into meaningful business insights.

## 🛠️ Tools & Technologies

- **Microsoft Excel:** Initial data inspection, PivotTables, charts, and dashboard development.
- **Python:** Data cleaning, transformation, exploratory analysis, and visualization.
- **Pandas & NumPy:** Data manipulation and numerical operations.
- **Matplotlib & Seaborn:** Charts and statistical visualizations.
- **SQL Server:** Data querying, aggregation, and analytical analysis.

## 📊 Dataset Overview

The dataset contains approximately **25,000 airline booking records**, including passenger, booking, and trip-related information.

The analysis explores booking behavior, customer preferences, flight timing, geographic patterns, and travel characteristics.

## 🧹 Data Cleaning & Preparation

The following checks and transformations were performed:

- Checked for duplicate records.
- Validated data types.
- Inspected potential outliers.
- Handled missing values in the country field by replacing them with `"Egypt"`, based on the project's preparation rules.
- Converted binary fields (0/1) into readable Yes/No categories.
- Standardized text categories for consistency.
- Created additional analytical features.

## 🔄 Feature Engineering

The following derived columns were created:

| Feature | Description |
|---|---|
| `trip_duration_category` | Groups trips into Short, Medium, and Long categories. |
| `day_type` | Classifies travel dates as Weekday or Weekend. |
| `day_period` | Groups flight times into Morning, Afternoon, Evening, and Night. |
| `purchase_lead_group` | Groups bookings by purchase lead time. |
| `booking` | Categorizes records into Complete and Non-Complete groups. |

## 🔍 Key Business Questions

1. Which sales channel generates the most bookings?
2. What percentage of customers request extra baggage, preferred seats, or meals?
3. What is the average purchase lead time?
4. Which countries account for the highest number of bookings?
5. Which days and times show the highest booking activity?
6. How do flight durations differ across trip categories?
7. What is the average number of passengers per booking?

## 📈 Analysis & Visualization

### Excel Analysis
- PivotTables for sales channel, trip type, and country analysis.
- Column, pie, and line charts.
- Dashboard summarizing key booking metrics.

### Python Analysis
- Sales channel distribution using a bar chart.
- Trip type distribution using a pie chart.
- Flight day vs. flight hour booking patterns using a heatmap.
- Flight duration comparisons across trip categories using a boxplot.

### SQL Server Analysis
- Filtering and aggregating booking records.
- Grouping data by relevant business dimensions.
- Calculating metrics to support business questions.
- Cross-checking analytical results.

## 💡 Key Findings

The initial analysis reported the following findings:

- **Sales Channel:** Online bookings represented approximately 91.7% of bookings.
- **Customer Preferences:** Approximately 78.4% requested baggage, 48.5% requested meals, and 30.9% requested preferred seats.
- **Travel Timing:** Monday was identified as the most frequent departure day.
- **Geographic Patterns:** Australia, Malaysia, and South Korea were identified among the leading origin countries.
- **Flight Duration:** Average durations were approximately 5.7 hours for Medium trips and 8.42 hours for Long trips.
- **Passengers:** The average was approximately 1.4 passengers per booking.

*Note: These findings reflect the initial project analysis and should be verified against the final dataset and calculations before publication.*

## 🔁 Project Workflow

1. **Excel:** Initial inspection and exploratory summaries.
2. **Python (Pandas):** Data cleaning and feature engineering.
3. **SQL Server:** Analytical queries and aggregations.
4. **Python (Matplotlib & Seaborn):** Data visualization.
5. **Excel Dashboard:** Presentation of key metrics and findings.

## 📁 Project Structure

```text
airline-booking-data-analysis/
│
├── data/
│   └── README.md
├── excel/
│   └── README.md
├── python/
│   └── README.md
├── sql/
│   └── README.md
├── images/
│   └── README.md
└── README.md
```

*Replace the placeholder files and folders with the actual project files as they become available.*

## 🚀 Skills Demonstrated

- Data Cleaning and Validation
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Excel PivotTables and Dashboards
- Python Data Analysis
- SQL Querying and Aggregation
- Data Visualization
- Business Insight Generation

## 👩‍💻 Author

**Kenzy Bahaa Ghoneim**

Aspiring Data Analyst | Business Intelligence | Artificial Intelligence Graduate

- LinkedIn: [Add your LinkedIn profile URL]
- GitHub: [Add your GitHub profile URL]

---

⭐ If you find this project useful, feel free to explore the repository.
