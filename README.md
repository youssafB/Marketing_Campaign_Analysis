# 📊 Facebook vs Google Ads ROI Analysis  

## 📌 Business Problem  
Companies invest heavily in online advertising, but choosing between **Facebook Ads** and **Google Ads** can be challenging.  
This case study analyzes **365 days of campaign data (2019)** to answer:  
👉 *Which platform delivers better ROI?*  

---

## 📂 Dataset  
- **Period:** Jan–Dec 2019 (365 days)  
- **Platforms:** Facebook, Google  
- **Features:**  
  - Date  
  - Platform  
  - Impressions  
  - Clicks  
  - CTR (%)  
  - CPC ($)  
  - Cost ($)  
  - Conversions  

---

## 🔍 Methodology  

1. **Data Cleaning**  
   - Converted cost, CTR, CPC to numeric  
   - Extracted time-based features (month, weekday)  

2. **Exploratory Data Analysis (EDA)**  
   - Trends in conversions & CPC  
   - Weekly and monthly patterns  
   - Cost vs. conversions  

3. **Statistical Analysis**  
   - **A/B test (t-test):** Facebook vs Google conversions  
   - **Cointegration test:** Cost vs conversions (long-run relationship)  

4. **Predictive Modeling**  
   - Linear regression: *Clicks → Conversions*  

---

## 📈 Key Insights  

- ✅ **Facebook** drives ~2x more conversions than Google.  
- ✅ Strong **positive correlation** between Facebook clicks & conversions.  
- ✅ **Mondays & Tuesdays** show the highest conversions.  
- ✅ **May & November** have lowest CPC → best ROI months.  
- ✅ Cost & conversions are **cointegrated** → stable long-term relationship.  

---

## 💡 Business Recommendations  

- Allocate more budget to **Facebook Ads**.  
- Prioritize campaigns on **Mondays & Tuesdays**.  
- Increase spend during **low CPC months (May, Nov)**.  
- Use regression models for **budget planning**.  



