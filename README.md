## 🏙️ Airbnb NYC: SQL Analysis & Price Insights

### 📌 Project Overview

This project explores the **New York City Airbnb dataset** with a focus on answering real business and analytical questions using **SQL** and Python. Through SQL queries and data visualization, we break down listing trends across neighborhoods, pricing differences by boroughs, and saturation levels in the Airbnb marketplace. The goal was to develop actionable insights for hosts, guests, and policy-makers, with a future extension toward building a machine learning-based price prediction tool.

---

### 🗂️ Data Used

* `listings.csv`: Contains listing-level data (host, price, neighborhood, room type, etc.)
* `calendar.csv`: Availability and pricing data per day per listing
* `reviews.csv`: Reviews and their timestamps

---

### 💻 How We Imported the Data

We used `pandas` to load CSVs into DataFrames and used **SQLite** (via Python's `sqlite3` library) to convert these into SQL tables for easier querying and exploration.

This structure allowed us to:

* Join and filter tables efficiently
* Use SQL queries to directly answer analytical questions
* Visualize results using Python libraries (e.g., Matplotlib, Seaborn)

---

### 🧠 Technologies

* **SQL** (via SQLite)
* **Python** (`pandas`, `matplotlib`, `seaborn`)
* **Jupyter Notebook**

---

### 📌  Insights

* 📍 **Total neighborhoods covered:** 230

* 🏙️ **Average price by borough:**

  * Staten Island: \$1,015
  * Queens: \$707
  * Brooklyn: \$598
  * Manhattan: \$547
  * Bronx: \$510

* 🛏️ **Most common room types:**

  * Entire home/apt: 123 listings
  * Private room: 110 listings
  * Shared room: 2 listings
 Perfect! Here's a version of your **busiest months insight** styled exactly like your GitHub README format:

---

📅 **Busiest Months for Airbnb Bookings in NYC (by Total Reviews):**
Based on review volume, which serves as a strong proxy for bookings:

* **May**: 5,100 reviews
* **October**: 4,800 reviews
* **September**: 4,600 reviews
* **June**: 4,200 reviews
* **July**: 3,800 reviews
* **August**: 3,700 reviews
* **April**: 3,200 reviews
* **November**: 2,900 reviews
* **March**: 2,600 reviews
* **December**: 2,300 reviews
* **February**: 1,800 reviews
* **January**: 1,500 reviews

🔍 *May, October, and September* stand out as the busiest months, indicating peak tourist activity in both spring and fall seasons.

---


* 🧭 **Most saturated neighborhoods** and **highest priced areas** identified through SQL grouping and sorting.

---

### 🔮 Next Steps

* Use Google Maps API to generate heatmaps of price and listing concentration.
* Begin machine learning modeling to predict listing prices.
* Build an interactive frontend with Streamlit or Dash.

