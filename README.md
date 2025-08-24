# 🏅 Olympic Data Analysis Dashboard (Power BI)

### 📌 Project Overview
This project analyzes **120 years of Olympic history** to uncover insights about medal distribution, participation trends, and top-performing athletes/countries.  
It was created as part of a **Power BI training workshop**, focusing on data cleaning, transformation, and visualization best practices.

---

### 📊 Data Sources
- **Athlete Events Table** – historical athlete participation and medal data  
- **Country Definitions Table** – country/NOC mapping  

---

### 🛠 Data Preparation
1. **Cleaning & Formatting**
   - Fixed column headers
   - Removed irrelevant fields (ID, height, weight, team, city, event)
   - Renamed columns for clarity  

2. **Merging Tables**
   - Joined `athlete_event` and `country_definitions` on **NOC** (full outer join)  

3. **Standardization**
   - Replaced values (`M → Male`, `F → Female`)  
   - Filtered out missing/blank entries (`N/A`)  

---

### 📈 Visualizations
- **Medal Distribution**
  - By Gender (Pie Chart)  
  - By Age (Ribbon Chart)  
  - By Season (Stacked Bar Chart)  
  - By Year (Line Chart)  

- **Country & Athlete Insights**
  - Country-wise Medal Matrix (Top 10)  
  - Distribution Among Top 10 Athletes (Column Chart)  

- **Sports-wise Analysis**
  - Medal Tree Map by Sport  
  - Conditional formatting to highlight trends  

- **Interactivity**
  - Slicers for Gender, Sport, and Season  
  - Buttons for filter reset and navigation  

---

### 🎨 Design & Formatting
- Consistent **Gold–Silver–Bronze** color scheme  
- Uniform title styles (bold, aligned, sized)  
- Transparent Olympic logo as dashboard background  
- Rounded borders, clean layout, and interactive tooltips  

---

### 💡 Key Insights
- **208 countries**, **67 sports**, and **134K+ players** participated historically  
- USA, Russia, and Germany dominate total medal counts  
- Male athletes won ~72% of all medals  
- Most medals come from the **Summer Olympics**  
- Peak performance age: **24–30 years**  

---

### 📂 Repository Structure
