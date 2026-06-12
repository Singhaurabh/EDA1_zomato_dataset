# 🍽️ Zomato Dataset (EDA)

This repository contains an **Exploratory Data Analysis (EDA)** of the Zomato restaurant dataset. 
The analysis focuses on restaurant distribution, ratings, cuisines, online delivery availability, country-wise presence, and city-level trends.

---

## 📂 Repository Structure

```text
Zomato Dataset (EDA)
│── charts
├── countries.csv
├── zomato.csv
├── zomato_dataset.ipynb
├── required.txt
└── README.md
---

## 📊 Dataset Overview

The dataset contains:

- **9,551 rows** (restaurant records)
- **22 columns** (features describing restaurants, ratings, cuisines, locations, services, etc.)
- Restaurants spread across **14 different countries**

The dataset helps analyze customer preferences, restaurant ratings, cuisine popularity, and service availability across countries.

---

## 🌍 Country-wise Distribution

Zomato has restaurants listed across **14 countries**, but the majority of records come from **India**.

| Country | Percentage of Total Records |
|----------|---------------------------|
| India | **94.39%** |
| United States | **4.73%** |
| United Kingdom | **0.87%** |
| Remaining 11 Countries | **< 1% combined** |

### Key Insight
- India dominates the dataset with more than **94% of all restaurant records**.
- The United States contributes around **4.73%**.
- The United Kingdom contributes approximately **0.87%**.
- Other countries collectively represent a very small portion of the dataset.

---

## ⭐ Rating Analysis

Restaurant ratings in the dataset approximately follow a **normal distribution**, where most restaurants receive average ratings and very few receive extremely low or extremely high ratings.

### Rating Distribution

<img width="1307" height="653" alt="image" src="https://github.com/user-attachments/assets/b13f92bb-11c5-4fd9-b46d-f7f3ca35fb60" />


### Insights

- Most ratings lie between **3.0 and 4.0**.
- Ratings peak around **3.2 – 3.5**, indicating average customer satisfaction.
- Very few restaurants receive ratings below **2.0** or above **4.8**.
- The distribution resembles a bell-shaped curve (normal distribution).

---

## 🚫 Countries with Maximum 0 Ratings

The following countries contain the highest number of restaurants with **0 ratings** (restaurants not yet rated).

| Country | Count of 0 Ratings |
|----------|------------------|
| India | **2139** |
| Brazil | **5** |
| United States | **3** |
| United Kingdom | **1** |

### Observation

India accounts for the overwhelming majority of unrated restaurants due to the large number of restaurants listed on the platform.

---

## 🚚 Online Delivery Analysis

Out of the **14 countries** present in the dataset:

- **Online Delivery is available only in India and UAE.**
- Even within these countries, many restaurants still do **not provide online delivery services**.

### Key Findings

- Online delivery adoption is highly concentrated.
- Most countries rely solely on restaurant listings and reviews.
- India has the largest number of restaurants offering online delivery.

---

## 🏙️ City-wise Analysis in India

The majority of Zomato usage in India is concentrated in the **National Capital Region (NCR)**.

Major contributing cities:

- New Delhi
- Gurgaon (Gurugram)
- Noida
- Faridabad
- Ghaziabad

### NCR City Distribution

<img width="549" height="463" alt="image" src="https://github.com/user-attachments/assets/8b7dd2e0-9e50-48a4-8264-cedbac82c693" />


### Insights

- **New Delhi** contributes the largest share of restaurants.
- **Gurgaon** is the second-largest contributor.
- **Noida**, **Faridabad**, and **Ghaziabad** collectively contribute a significant portion of the dataset.
- The NCR region dominates restaurant activity on Zomato in India.

---

## 🍜 Top 10 Most Popular Cuisines

The following cuisines appear most frequently in the dataset:

| Rank | Cuisine | Count |
|--------|---------|--------|
| 1 | North Indian | 936 |
| 2 | North Indian, Chinese | 511 |
| 3 | Chinese | 354 |
| 4 | Fast Food | 354 |
| 5 | North Indian, Mughlai | 334 |
| 6 | Cafe | 299 |
| 7 | Bakery | 218 |
| 8 | North Indian, Mughlai, Chinese | 197 |
| 9 | Bakery, Desserts | 170 |
| 10 | Street Food | 149 |

### Insights

- **North Indian cuisine** is the most popular cuisine on Zomato.
- Chinese cuisine frequently appears both independently and in combination with North Indian dishes.
- Fast Food and Cafe culture also have strong representation.
- Bakery and dessert-focused restaurants contribute significantly to the platform.

---

## 📈 Major Findings

### Country-Level Insights

- Restaurants are distributed across **14 countries**.
- India accounts for **94.39%** of all records.
- USA contributes **4.73%**.
- UK contributes **0.87%**.

### Rating Insights

- Ratings follow a near-normal distribution.
- Most restaurants receive ratings between **3.0 and 4.0**.
- Average-rated restaurants dominate the dataset.

### Delivery Insights

- Online delivery is available only in **India** and **UAE**.
- Many restaurants in these countries still do not provide delivery services.

### Location Insights

- The NCR region dominates restaurant listings in India.
- New Delhi contributes the highest number of restaurants.

### Cuisine Insights

- North Indian cuisine is the most popular cuisine.
- Chinese cuisine appears frequently both independently and in combination with North Indian food.
- Fast Food, Cafes, and Bakeries are among the most common restaurant categories.

## ❓ Business Questions Answered
1. Which countries dominate Zomato's restaurant listings?
2. How are restaurant ratings distributed across the platform?
3. Which cities in India have the highest restaurant density?
4. What cuisines are most popular on Zomato?
5. How widely is online delivery adopted across countries?

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📌 Conclusion

This analysis reveals that Zomato's restaurant ecosystem is heavily concentrated in India, particularly in the NCR region. Customer ratings generally follow a normal distribution, indicating that most restaurants receive average ratings. North Indian cuisine dominates the platform, while online delivery services remain limited to India and UAE. These findings provide valuable insights into restaurant trends, customer behavior, and service availability across the Zomato platform.
