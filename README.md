## 🏙️ Airbnb NYC: SQL Analysis & Price Insights

### 📌 Project Overview

This project explores the **New York City Airbnb dataset** with a focus on answering real business and analytical questions using **SQL** and Python. Through SQL queries and data visualization, we break down listing trends across neighborhoods, pricing differences by boroughs, and saturation levels in the Airbnb marketplace. The goal was to develop actionable insights for hosts, guests, and policy-makers, with a future extension toward building a machine learning-based price prediction tool.

---

### ❓ Key Business Questions Answered

* **Neighborhoods & Boroughs**

  * How many neighborhoods are in each borough?
  * How many total neighborhoods does Airbnb cover in NYC?
  * Which boroughs have the most neighborhoods?

* **Listing Insights**

  * Where are the most listings?
  * What are the most common room types?
  * What’s the average price per borough?
  * Which neighborhoods are most saturated?
  * Which neighborhoods have the highest average price per night?

* **Reviews**

  * Which listings have received the most reviews?
  * What are the most common review dates?

* **Availability & Bookings**

  * What are the busiest months for Airbnb bookings in NYC?
  * What percentage of listings offer availability for the next 30 days? *(partially explored)*

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

### 📌 Sample Insights

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

* 🧭 **Most saturated neighborhoods** and **highest priced areas** identified through SQL grouping and sorting.

---

### 🔮 Next Steps

* Use Google Maps API to generate heatmaps of price and listing concentration.
* Begin machine learning modeling to predict listing prices.
* Build an interactive frontend with Streamlit or Dash.

