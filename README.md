# 🏎️ F1 Race Strategy & Performance Analytics

This project focuses on analyzing Formula 1 race data to extract meaningful insights into **driver performance, race strategy, and tyre behavior**. Using Python for data processing and Power BI for visualization, the project simulates how real-world F1 strategists and analysts interpret race data to make performance-driven decisions.

The analysis goes beyond simple visualization and aims to provide **actionable insights** that can influence race strategy, including pit stop timing, tyre management, and race pace optimization.

---

# 📌 Project Objectives

The primary objectives of this project are:

* To analyze **driver pace and consistency** over race laps
* To study **gap evolution** between drivers and race leaders
* To evaluate **tyre degradation patterns** across different stints
* To develop a custom **Wear Score metric** to quantify tyre performance
* To simulate **strategy-level decision making** using data insights

---

# 📊 Dataset Description

The dataset consists of lap-by-lap race data including:

* Driver names
* Lap times
* Lap numbers
* Tyre compounds
* Tyre age (number of laps completed on a set)
* Pit stop information

This granular data allows for a detailed breakdown of race dynamics and performance trends.

---

# ⚙️ Methodology

The project follows a structured data analytics pipeline:

### 1. Data Cleaning and Preprocessing

* Removed missing or inconsistent lap time values
* Standardized driver names and race parameters
* Converted lap times into numerical formats for analysis

### 2. Feature Engineering

* Calculated **Gap to Leader** for each lap
* Computed **Tyre Age** progression
* Designed a custom **Wear Score** metric to quantify tyre degradation rate

### 3. Exploratory Data Analysis (EDA)

* Visualized lap time distributions
* Compared driver performance trends
* Analyzed stint-wise degradation patterns

### 4. Visualization and Dashboarding

* Built static visualizations using Python (Matplotlib, Seaborn)
* Developed interactive dashboards in Power BI

---

# 📊 Analysis & Insights

## 📊 Pace Distribution

### Description

This chart visualizes the distribution of lap times for each driver, helping assess both **speed and consistency**.

### Key Insights

* Drivers with a **tight distribution** demonstrate high consistency and stable performance
* Drivers with a **wider spread** indicate variability due to traffic, tyre wear, or race incidents
* Consistency is often more critical than outright speed in long race scenarios

---

## 📈 Gap to Leader

### Description

This visualization tracks how far each driver is behind the race leader over time.

### Key Insights

* **Sharp spikes** typically represent pit stops or unexpected events
* **Gradual gap increase** indicates pace disadvantage
* Helps identify potential **undercut or overcut strategy opportunities**

---

## 🟡 Tyre Degradation



### Description

This chart shows how lap times increase as tyre age increases, highlighting degradation patterns.

### Key Insights

* Lap times progressively increase as tyres age due to loss of grip
* Different drivers exhibit **different degradation curves**, indicating driving style impact
* Critical for identifying the **optimal pit stop window**

---

## 🔵 Wear Score (Custom Metric)



### Description

Wear Score is a custom-built metric that quantifies how quickly a driver's tyre performance declines.

### Key Insights

* Lower Wear Score indicates **efficient tyre management**
* Higher Wear Score suggests **aggressive driving or poor tyre conservation**
* Enables objective comparison between drivers beyond raw lap times

---

# 🧠 Business & Strategy Interpretation

This project translates raw race data into **strategic decision-making insights**:

* Identify drivers with the **best long-run pace**
* Determine the **optimal timing for pit stops**
* Evaluate benefits of **undercut vs overcut strategies**
* Compare **driver efficiency in tyre management**
* Understand how race position evolves dynamically

---

# 📊 Power BI Dashboard Design

The project includes a structured multi-page dashboard designed for storytelling:

### 🏁 Page 1 — Race Overview

* Pace Distribution
* Gap to Leader
* Race progression overview

### 🟡 Page 2 — Tyre Analysis

* Tyre Degradation curves
* Wear Score comparison
* Stint-wise performance

### 🧑‍🏎️ Page 3 — Driver Performance

* Consistency analysis
* Traffic impact evaluation
* Driver comparison metrics

### 🧠 Page 4 — Strategy Insights

* Pit stop timing analysis
* Stint comparison
* Strategy recommendations

---

# 🛠️ Tools & Technologies

* **Python** (Pandas, Matplotlib, Seaborn) for data analysis
* **Power BI** for dashboard creation and storytelling
* **Jupyter Notebook** for exploratory data analysis

---

# 📁 Project Structure

```
F1-Analytics-Project/
│
├── outputs/
│   ├── pace_distribution.png
│   ├── gap_to_leader.png
│   ├── degradation.png
│   ├── wear_score.png
│
├── notebooks/
│   └── analysis.ipynb
│
├── dashboard/
│   └── powerbi.pbix
│
├── README.md
```

---

# 🚀 Future Enhancements

* Integrate **machine learning models** for predictive strategy analysis
* Include **weather and track condition data**
* Add **real-time telemetry processing**
* Develop **driver vs teammate comparison module**

---

# 💡 Key Takeaway

This project demonstrates how raw motorsport data can be transformed into **high-impact analytical insights**, replicating the workflow of professional F1 data analysts and strategists.

It highlights the importance of combining **technical skills (Python, Power BI)** with **domain understanding (race strategy, tyre behavior)** to deliver meaningful, decision-driven analytics.

This project demonstrates how raw race data can be transformed into strategic insights similar to real F1 teams.
