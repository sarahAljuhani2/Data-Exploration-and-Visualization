# 🏅 Olympic Games Data Analysis & Visualization Project

This project focuses on data exploration and visualization of Olympic Games data. It walks through each stage of the data analysis pipeline to uncover trends and insights from historical Olympic records.

---

## 📌 Project Steps

### 1.  Data Extraction

The dataset used in this project was sourced from **Kaggle** and includes over **70,000 rows** of rich historical data. It contains information about athletes, events, host cities, and countries participating in the Olympics.

**Key Columns in the Dataset:**
- `ID`: Unique identifier for each entry  
- `Name`: Athlete’s name  
- `Sex`: Gender of the athlete  
- `Age`: Athlete’s age during the event  
- `Height`: Athlete’s height  
- `Weight`: Athlete’s weight  
- `Team`: Team or country the athlete represents  
- `NOC`: National Olympic Committee code  
- `Games`: Edition of the Olympic Games (e.g., 2012 Summer)  
- `Year`: Year of the event  
- `Season`: Season (Summer or Winter)  
- `City`: Host city  
- `Sport`: Type of sport  
- `Event`: Specific competition  
- `Medal`: Type of medal won (Gold, Silver, Bronze, or None)  

---

### 2. 🧹 Data Preprocessing

To ensure data quality, the following preprocessing steps were taken:

- Removed the `ID` column (not useful for analysis)  
- Checked for and documented missing values:
  - `Age`: 2,732 missing values  
  - `Height`: 16,254 missing values  
  - `Weight`: 17,101 missing values  
  - `Medal`: 60,310 missing values  

---

### 3. 🔍 Data Exploration

After cleaning the data:

- Created a DataFrame with **14 columns** and **49,211 rows**  
- Generated **statistical summaries** for `Year`, `Age`, `Height`, and `Weight`  
- Plotted **histograms** for age, height, and weight distributions  
- Used **box plots** to show data spread by year  
- Created a **scatter plot** to show height vs. weight by gender  
- Built a **pair plot** to explore relationships between key features and medal types  

---

### 4. 📊 Data Visualization

Data visualization played a crucial role in:

- Understanding the distribution and trends of athlete features over time  
- Comparing athlete performance by sport, gender, and country  
- Gaining insights into the Olympic Games through intuitive visual tools  

---

