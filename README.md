# ✈️ Northern Lights Air — Airline Loyalty Program Analysis

## 📊 Project Overview
Interactive **Power BI dashboard** analyzing the impact of a 2018 loyalty promotion for Northern Lights Air (NLA). Highlights campaign effectiveness, demographic adoption, and summer flight booking trends. Dataset is **fictional**.

---

## Project Objective 🎯
- Evaluate the impact of the Feb–Apr 2018 promotion on loyalty program enrollments.  
- Identify demographic trends (education, gender, marital status, province).  
- Assess the effect on summer flight bookings (Jun–Aug 2018).  

---

## Tool Used 🛠️
- Power BI Desktop

---

## Star Schema Data Model 🗂️
- **Fact Table:** CustomerFlightActivity  
- **Dimensions:** CustomerLoyaltyHistory, Calendar

---

## Dashboard Features 📌
- **KPIs:** Enrollments, Cancelled, Net Enrolled, Churn Rate, Booked Flights, Average Distance, Points Accumulated, Points Redeemed, Redeemed in Dollars, % of Flights with Points Redeemed  
- **Trend Charts:** Enrollment Trend (MoM), Booked Flights Trend, Compare Season YoY  
- **Demographics:** Education, Gender, Marital Status, Province  
- **Tooltip Pages:** Contextual details for Province  
- **Smart Narrative:** Automatically generated insights  
<img width="1435" height="797" alt="image" src="https://github.com/user-attachments/assets/ba16d669-75af-4e89-91c5-f68f6f4d8f86" />
<img width="1438" height="807" alt="image" src="https://github.com/user-attachments/assets/2f22b8c4-527c-4961-aa30-fb2aa33d38d1" />
<img width="1437" height="792" alt="image" src="https://github.com/user-attachments/assets/6f6552fc-e262-4a88-bd90-b8354a36345d" />
<img width="1436" height="794" alt="image" src="https://github.com/user-attachments/assets/5c9b7931-4c39-4a5c-99e7-b24b09f1927d" />

---

## Key Findings 🔑
- **Campaign Effectiveness:** Enrollment increased **40–77% MoM** during the promotion; churn dropped from **12.43% → 2.05%** after the campaign.  
- **Demographics:**  
  - 🎓 Bachelor’s degree: highest enrollments (18% of 2018 promotion)  
  - 👥 Gender: no significant difference  
  - 💍 Marital Status: contributed ~6% of enrollments during the campaign  
  - 🏔️ Yukon: highest enrollment from the campaign (~7.55%)  
- **Summer Flights:** June–August 2018 peak likely influenced by the promotion.  
- **Recommendations:** Focus on high-value segments (Bachelor & Doctor education, Married/Divorced members) and top provinces (Ontario, BC, Quebec).  

---

## How to View Dashboard 👀
1. Clone this repository.  
2. Open `NLA Airline Loyalty Program Analysis.pbix` in **Power BI Desktop**.  
3. Download the CSV dataset from Maven Analytics: [Airline Loyalty Program Data](https://mavenanalytics.io/data-playground/airline-loyalty-program)  
4. Refresh data and explore KPIs, trends, and demographics.

---

## Source Material 📚
Guided project by **Maven Analytics**: [Airline Loyalty Program Dataset](https://mavenanalytics.io/data-playground/airline-loyalty-program)  

---

## Notes & Limitations ⚠️
- Data is **fictional** for demonstration purposes.  
- CLV = total invoice value of all flights ever booked.  
- Seasonal/campaign effects are **correlative**, not causal.  

---

## Future Improvements 🚀
- Integrate additional customer behavior data (e.g., web/app interactions, promo code usage) to improve CLV predictions.  
- Include more granular flight details (routes, cabin class, booking channel) to analyze travel patterns.  
- Implement predictive analytics for churn risk and campaign impact.  
- Add real-time dashboard updates using live data sources or incremental refresh.  
- Incorporate visualizations for loyalty tier transitions and multi-year trends.  
