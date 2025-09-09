# Quantium Retail Analytics – Task 1 (Chips Category)

## 📌 Project Overview
This project is based on Quantium’s retail analytics case study on an online internship from forage.  
The objective is to analyze transaction and customer data for the **Chips category** and provide commercial insights & recommendations to the Category Manager.

---

## 🛠️ Steps Taken
1. **Data Cleaning & Preparation**
   - Checked for missing values and outliers
   - Derived new fields (e.g., `PACK_SIZE`, `BRAND`)
   - Merged transaction and customer datasets

2. **Exploratory Data Analysis**
   - Total sales over time
   - Sales by customer segments (`LIFESTAGE`, `PREMIUM_CUSTOMER`)
   - Most popular brands and pack sizes
   - Transaction patterns by day of week and month

3. **Statistical Testing**
   - Independent t-tests between customer segments (e.g., Mainstream vs Premium)

4. **Key Metrics**
   - Total sales
   - Number of unique customers
   - Average units per transaction
   - Average spend per customer

---

## 📊 Key Insights
- **Seasonality**: Sales peak in December; no sales on Christmas Day.  
- **Top Segments**: Budget – Older Families and Mainstream – Young Singles/Couples are the biggest contributors.  
- **Pack Sizes**: 175g packs are most popular across all groups.  
- **Brands**: Top brands (e.g., Smiths, Doritos) dominate sales.  
- **Customer Behavior**:
  - Families purchase more units per transaction  
  - Young Singles/Couples pay more on average per unit  

---

## 💡 Recommendations
1. **Target Promotions**:
   - Multi-buy deals for Family segments (they purchase higher volumes).
   - Premium or “value-premium” product lines for Young Singles/Couples (higher willingness to pay).  

2. **Brand Partnerships**:
   - Focus marketing with top-selling brands to maximize reach.  

3. **Seasonal Planning**:
   - Stock more chips before December to meet peak demand.  

---

## 📂 Files in Repo
- `quantium_task1.ipynb` → Jupyter Notebook with full analysis  
- `task1_analysis.pdf` → Exported report with code, plots, and insights  
- `README.md` → This documentation  

---

## 🚀 Tools Used
- Python (pandas, matplotlib, seaborn, scipy)  
- Jupyter Notebook  
- Excel (for some quick validation)  
