📊 **Browsing History Analysis Report**

---

## 🎯 **Objective**
This analysis uncovers behavioral patterns from anonymized browsing history data. By leveraging data wrangling, visualization, and storytelling, the study reveals meaningful insights into user activity trends—providing a clear narrative of online behavior.  

---

## 📁 **Dataset Overview**
The dataset includes:
- 🧾 **Identifiers**: `OrgId`, `ParticipantId`, `DeviceId`  
- 🌐 **Browsing Data**: URLs, timestamps (`eventtimeutc`), referral info  
- 📈 **Behavioral Metrics**: Transition types (e.g., link, typed), domain frequencies, time-based patterns  

---

## 🛠️ **Methodology**

### 🔄 **1. Data Preprocessing**
- ✅ Standardized column names
- ⏰ Converted timestamps to datetime format
  - Extracted **hour**, **day of the week**, and **date**
- 🧼 Cleaned missing values and removed duplicates
- 🔍 Extracted domain names from URLs using `tldextract`

---

### 🔎 **2. Exploratory Data Analysis (EDA)**
Explored behavior across key dimensions:
- 🏆 **Top Domains**: Most frequently visited sites  
- 🕒 **Time-Based Trends**: Activity by hour, weekday, and date  
- 🔗 **User Navigation**: Referral and transition type patterns  

---

### 📊 **3. Visualizations Created**
Made interactive charts using **Plotly**:

- 📋 **Bar Charts**  
  - Top 10 most visited domains  
  - Hourly and weekday activity distribution  

- 📈 **Line Graph**  
  - Daily visit trends over time  

- 🥧 **Pie Chart**  
  - Transition types (link, typed, etc.)  

- 🔥 **Heatmap**  
  - Domain visit intensity by time of day  

---

## 💡 **Key Insights**

1. 🕐 **Peak Activity Hours**  
   - Browsing spikes during specific hours, showing structured routines  

2. 🌍 **Dominant Domains**  
   - Few domains (like YouTube, Google) account for most visits  

3. 📅 **Weekday Patterns**  
   - More activity on certain weekdays—possibly work/study-related behavior  

4. 🔗 **Link Navigation Dominance**  
   - Majority of visits stem from link-based transitions, suggesting referral-based browsing habits  

---

## 🧰 **Technologies Used**
- 🐍 **Python**: `Pandas`, `Plotly`, `tldextract`  
- ☁️ **Google Colab**: For coding & visualization   

---

## 📦 **Deliverables**
1. 🧠 **Python Notebook** – Modular and well-documented scripts  
2. 📉 **Interactive Visuals** – Charts that communicate insights clearly  
3. 📄 **Report** – This structured summary of findings  

