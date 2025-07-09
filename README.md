# Airbnb-EDA-project
<h1 align="center">Exploratory Data Analysis on Airbnb Listings</h1>

<p align="center"> 
<img src="https://upload.wikimedia.org/wikipedia/commons/6/69/Airbnb_Logo_Bélo.svg" alt="Airbnb Logo" height="120px">
</p>

## 📚 Table Of Contents

- 📋 **Project Description**
- 💾 **Project Files Description**
- 🧾 **Dataset Contents**
- 📊 **Variable Details**
- ❓ **Problem Statement**
- 🛠 **Technologies Used**
- 🔍 **Steps Involved**
- 📌 **Key Insights**
- 🎯 **Conclusion**

---

## 📋 Project Description

This project performs an in-depth Exploratory Data Analysis (EDA) on Airbnb listings data to uncover meaningful insights about pricing, availability, location trends, and host activity. The goal is to identify factors that influence listing prices and customer satisfaction, and highlight patterns across neighborhoods, room types, and host behavior.

---

## 💾 Project Files Description

- `Airbnb_EDA_Project_Akshit_Singh.ipynb`: Main notebook containing code for EDA, data preprocessing, and visualization.
- Dataset: Airbnb listing dataset (CSV file, not included here).
- Visuals: Charts and plots embedded in the notebook.
- `README.md`: This file.

---

## 🧾 Dataset Contents

The dataset contains detailed information about Airbnb listings, including prices, locations, host information, and review scores. It represents a snapshot of listings data collected from a popular city/region.

---

## 📊 Variable Details

| Variable Name             | Description                                             |
|---------------------------|---------------------------------------------------------|
| id                        | Unique identifier for each listing                      |
| name                      | Name/title of the listing                               |
| host_id                   | Unique ID of the host                                   |
| neighbourhood_group       | Grouping of neighborhoods (if applicable)               |
| neighbourhood             | Specific neighborhood of the listing                   |
| latitude, longitude       | Geolocation coordinates                                 |
| room_type                 | Type of room (Entire home, Private room, etc.)          |
| price                     | Price per night                                         |
| minimum_nights            | Minimum nights required to book                         |
| number_of_reviews         | Total number of reviews                                 |
| reviews_per_month         | Average number of reviews per month                     |
| availability_365          | Number of days available in a year                      |
| calculated_host_listings_count | Listings count by the host                         |

---

## ❓ Problem Statement

With the growing popularity of Airbnb, both hosts and guests need insights to make data-driven decisions. This project explores:

- What features affect the price of listings?
- Which neighborhoods are most popular or most expensive?
- What trends are visible in host activity and review patterns?
- Can we identify potential anomalies or areas of improvement for Airbnb listings?

---

## 🛠 Technologies Used

- **Language:** Python
- **Libraries:**
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn`, `plotly` – Visualization
  - `missingno` – Visualizing missing data
  - `folium` – Geospatial mapping
  - `wordcloud` – Text data visualization

---

## 🔍 Steps Involved

1. **Loading and Cleaning Data**
   - Removed nulls and duplicates
   - Converted data types where necessary

2. **Univariate and Bivariate Analysis**
   - Histograms, boxplots, and bar charts to understand distributions

3. **Geospatial Mapping**
   - Used Folium to map high-price and high-availability listings

4. **Outlier Detection**
   - Identified and filtered listings with abnormal price and night values

5. **Correlation Analysis**
   - Explored relationships between price, reviews, and availability

6. **Text Analysis**
   - WordCloud created using listing names to analyze popular terms

---

## 📌 Key Insights

- Most listings are concentrated in popular neighborhoods with tourist attractions.
- Entire homes are generally priced higher but are more preferred by users.
- Listings with extreme prices and minimum nights skew the data — filtering helps in gaining realistic insights.
- There is a visible correlation between review counts and pricing in specific areas.

---

## 🎯 Conclusion

The Airbnb dataset provides a rich source for uncovering insights related to pricing, availability, and listing quality. Through EDA, we:

- Identified key drivers of price
- Mapped out location-based listing trends
- Highlighted the impact of room type and availability
- Built a foundation for future predictive modeling (e.g., price prediction)

This project helps Airbnb stakeholders—hosts, guests, and analysts—understand market dynamics and improve decision-making using data.

---

