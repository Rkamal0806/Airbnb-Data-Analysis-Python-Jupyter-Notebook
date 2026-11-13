# New York Airbnb Market Analysis

## 🎯 Project Objectives

The primary objective of this project is to perform an Exploratory Data Analysis (EDA) of the New York Airbnb market to uncover meaningful patterns, pricing trends, and hosting behaviors.

The project aims to:

1. **Analyze Room Categories, Pricing & Availability:** Examine the distribution of room types, rental prices, and listing availability across different neighborhoods.
2. **Explore Hosting Trends:** Understand hosting patterns and how Airbnb listings are managed over time.
3. **Identify Pricing Anomalies:** Detect unusual or extreme pricing values that may indicate potential outliers or anomalies.
4. **Generate Business Insights:** Provide data-driven recommendations to support better decision-making for both travelers and property owners.

---

## 📊 Dataset Overview

The dataset consists of **20,765 records and 22 features**, containing information about Airbnb listings across New York.

### Key Features

| Feature | Description |
|---|---|
| `name` | Title of the Airbnb listing |
| `host_name` | Name of the property host |
| `neighborhood_group` | Group (borough) where the listing is located |
| `latitude` / `longitude` | Geographical coordinates of the listings |
| `price` | Nightly rental price |
| `room_type` | Type of accommodation (e.g., entire home, private room) |
| `reviews_per_month` | Average number of reviews received per month |
| `availability_365` | Number of days the listing is available throughout the year |

---

## ⚙️ Steps & Workflow

### 1. Data Cleaning & Preprocessing

Prepared the dataset for analysis by addressing data quality issues and improving consistency.

- **Handling Missing Values:** Identified and handled missing values in important columns, including `price`, `neighborhood`, and `beds`.
- **Data Type Conversion:** Converted the `last_review` column into a proper datetime format for time-based analysis.
- **Outlier Treatment:** Capped listing prices above $1,000 to minimize the impact of extreme values and improve visualization clarity.

### 2. Exploratory Data Analysis (EDA)

Performed exploratory analysis to understand the distribution, relationships, and patterns within the Airbnb dataset.

- **Room Type Distribution:** Used bar charts to analyze the frequency of different accommodation categories. Identified Entire home/apt as the most common room type.
- **Neighborhood Group Analysis:** Compared rental prices across different boroughs and identified Manhattan as having the highest average listing prices.
- **Availability Analysis:** Explored availability patterns and used heatmaps to examine correlations among price, availability_365, number_of_reviews, and beds.
- **Price Distribution Analysis:** Used histograms to understand rental price distribution, with the majority of listings priced between $50 and $300.
- **Host Listing Analysis:** Examined hosts managing multiple listings using boxplots to identify key contributors to the Airbnb market.
- **Review Behavior Analysis:** Used pair plots to explore relationships between number of reviews, price, and availability.

### 3. Data Visualization

Applied different visualization techniques to identify patterns, compare variables, and communicate analytical findings effectively.

| Visualization | Purpose |
|---|---|
| **Pair Plot** | Explore relationships among price, availability, and number of reviews. |
| **Correlation Heatmap** | Examine correlations among numerical features. |
| **Histograms & Boxplots** | Understand price distributions and identify extreme values. |
| **Bar Charts** | Compare room type and neighborhood group distributions. |

---

## 🔍 Key Findings & Insights

### 1. Price Trends
- Manhattan has the highest average listing prices, followed by Brooklyn.
- Entire homes/apartments are significantly more expensive than private or shared rooms.

### 2. Room Type Distribution
- Entire homes/apartments represent the most common accommodation category.
- Private rooms provide more budget-friendly accommodation options for travelers.

### 3. Pricing Outliers
- A small number of listings with prices exceeding $10,000 were identified.
- These extreme values highlight the importance of outlier detection and appropriate price treatment during analysis.

### 4. Availability Patterns
- Listings with higher availability tend to have lower prices and more reviews, potentially indicating better guest experiences.

### 5. Host Behavior
- Some hosts manage multiple Airbnb listings, suggesting a trend toward more professional hosting operations.

---

## 💡 Business Recommendations

### For Guests
- Prioritize listings with higher availability and positive reviews to make more informed booking decisions.
- Explore private rooms in Brooklyn for more affordable accommodation options compared to Manhattan.

### For Hosts
- Improve listing availability and review response rates to attract more potential bookings.
- Adopt effective pricing strategies to remain competitive within their respective boroughs.

---

## 📝 Conclusion

This project provides a data-driven overview of the New York Airbnb market by examining pricing patterns, room type distributions, neighborhood-level variations, availability trends, and host behavior.

Through data cleaning, exploratory data analysis, and visualization techniques, the project uncovers meaningful market insights and translates them into actionable recommendations for both travelers and property owners.

These findings demonstrate how data analytics can support informed decision-making in the short-term rental market.

### 🚀 Future Scope

Future enhancements may include advanced analytics and predictive modeling to further explore pricing behavior, listing performance, and market trends.
