# 📺 Netflix Content Analysis Dashboard

### Power BI Dashboard Project

![Netflix Dashboard](sandbox:/mnt/data/Netflix.JPG)

---

# 📌 Project Overview

The **Netflix Content Analysis Dashboard** is an interactive **Power BI** dashboard developed to analyze Netflix's content library. It provides insights into movies and TV shows based on genres, ratings, countries, release years, and content type.

The dashboard helps users quickly understand Netflix's content distribution, popularity trends, geographical presence, and content classification through interactive visualizations.


# 🎯 Project Objectives

* Analyze Netflix's Movies and TV Shows.
* Compare Movies vs TV Shows.
* Identify the most common content ratings.
* Analyze genre distribution.
* Visualize content availability across countries.
* Study release year trends.
* Provide a clean and interactive dashboard for business insights.


# 🛠 Tools & Technologies Used

| Tool            | Purpose                               |
| --------------- | ------------------------------------- |
| Power BI        | Dashboard Development & Visualization |
| Microsoft Excel | Dataset Storage                       |
| Power Query     | Data Cleaning & Transformation        |
| DAX             | Measures & Calculations               |


# 📂 Dataset Information

### Dataset Name

**Netflix Titles Dataset**

### Dataset Format

Excel (.xlsx)

### Dataset Features

| Column       | Description                         |
| ------------ | ----------------------------------- |
| show_id      | Unique ID for each title            |
| type         | Movie or TV Show                    |
| title        | Name of the content                 |
| director     | Director name                       |
| cast         | Cast members                        |
| country      | Country of production               |
| date_added   | Date added to Netflix               |
| release_year | Original release year               |
| rating       | Content maturity rating             |
| duration     | Movie duration or number of seasons |
| listed_in    | Genre(s)                            |
| description  | Short description of the content    |

# 📊 Dashboard KPIs

The dashboard displays the following key performance indicators:

| KPI                         | Value     |
| --------------------------- | --------- |
| Total Titles                | **8,799** |
| Total Ratings               | **18**    |
| Total Genres                | **514**   |
| Earliest Release Year       | **1925**  |
| Latest Release Year         | **2021**  |
| Total Locations (Countries) | **7,976** |


# 📈 Dashboard Visualizations

## 1. KPI Cards

Displays overall statistics including:

* Total Titles
* Total Ratings
* Total Genres
* Start Year
* End Year
* Total Locations


## 2. Genres by Total Titles

**Visualization:** Horizontal Bar Chart

Shows the most popular genres available on Netflix.

### Insights

* Drama is the most common genre.
* Documentaries have a strong presence.
* Stand-Up Comedy is among the top categories.
* Independent Movies and Comedy are widely available.


## 3. Ratings by Total Titles

**Visualization:** Horizontal Bar Chart

Displays the distribution of titles by maturity rating.

### Key Insights

* **TV-MA** has the highest number of titles.
* **TV-14** is the second most common rating.
* Family-friendly ratings such as **TV-Y** and **PG** have fewer titles.


## 4. Count of Shows by Country

**Visualization:** Filled Map

Displays Netflix content production across different countries.

### Insights

* Content is distributed globally.
* North America and Asia contribute significantly.
* European countries also have strong representation.


## 5. Movies vs TV Shows

**Visualization:** Donut Chart

Shows the proportion of Movies and TV Shows.

### Dashboard Result

* **Movies:** 6.13K (69.62%)
* **TV Shows:** 2.68K (30.38%)

### Insight

Netflix's catalog contains considerably more Movies than TV Shows.


## 6. Total Movies and TV Shows by Release Year

**Visualization:** Line Chart

Shows yearly content release trends.


# 📌 Key Business Insights

* Netflix hosts **8,799** titles in the dataset.
* Movies account for nearly **70%** of the catalog.
* TV Shows represent approximately **30%**.
* Drama is the dominant genre.
* TV-MA is the most frequent content rating.
* Netflix content has expanded rapidly since 2010.
* Content originates from thousands of country entries, highlighting Netflix's global reach.
* Recent years show a sharp increase in original and licensed content.


# 📋 Data Cleaning & Preparation

The following preprocessing steps were performed before creating the dashboard:

* Removed duplicate records (if any).
* Handled missing values.
* Standardized column names.
* Converted date fields to proper date format.
* Created calculated measures using DAX.
* Verified data types.
* Optimized the dataset for Power BI performance.


# 📐 Dashboard Features

* Interactive visuals
* KPI summary cards
* Country-wise geographical analysis
* Genre analysis
* Rating analysis
* Movie vs TV Show comparison
* Release year trend analysis
* Clean Netflix-inspired theme
* Easy-to-understand layout


# 📊 Business Value

This dashboard helps:

* Analyze Netflix's content library.
* Understand customer-targeted ratings.
* Discover popular genres.
* Identify content growth over time.
* Compare Movies and TV Shows.
* Explore global content distribution.
* Support data-driven entertainment and business decisions.


# 📁 Project Structure

```text
Netflix Dashboard/
│
├── Netflix.pbix                 # Power BI dashboard
├── netflix_titles.xlsx          # Dataset
├── README.md                    # Project documentation
├── Dashboard.png                # Dashboard screenshot
└── Assets/
    └── Netflix Logo
```

# 📸 Dashboard Preview

The dashboard includes:

* 📊 KPI Cards
* 📚 Genre Analysis
* ⭐ Rating Distribution
* 🌍 Country-wise Map
* 🍿 Movies vs TV Shows Comparison
* 📈 Release Year Trend


# 📌 Conclusion

The **Netflix Content Analysis Dashboard** provides a comprehensive view of Netflix's content catalog through interactive Power BI visualizations. It highlights key metrics, genre popularity, audience ratings, geographical distribution, and release trends, enabling users to gain meaningful insights into Netflix's global content strategy. The dashboard is designed to be visually appealing, easy to navigate, and valuable for both learning Power BI and performing exploratory data analysis.




