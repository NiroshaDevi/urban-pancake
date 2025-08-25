# ☕️ Dirty Cafe Sales Data Cleaning & Power BI Analytics 🚀

## Abstract

Transforming chaos into clarity!  
This project tackles a raw, messy transactional dataset from a bustling café (10,000+ rows, 8 columns), riddled with errors like `UNKNOWN`, `ERROR`, and blanks. The goal: turn unreliable data into powerful business insights for stakeholders.

---

## 🧹 Data Cleaning Highlights

| Column            | ERROR | UNKNOWN | BLANKS |
|-------------------|-------|---------|--------|
| Transaction ID    | 0     | 0       | 0      |
| Item              | 292   | 344     | 333    |
| Quantity          | 170   | 171     | 138    |
| Price per Unit    | 190   | 164     | 179    |
| Total Spent       | 164   | 165     | 173    |
| Payment Method    | 306   | 293     | 2,579  |
| Location          | 358   | 338     | 3,265  |
| Transaction Date  | 142   | 159     | 159    |

**Total Errors Fixed:**  
- ERROR: 1,622  
- UNKNOWN: 1,634  
- BLANKS: 6,826

---

## 🛠️ Step-by-Step Data Cleaning Process

1. **Basic Correction:**  
   - Removed duplicates  
   - Logical matching for missing items  
   - Estimated missing quantities, prices, & totals

2. **Formula Error Handling:**  
   - Cleared Excel errors (#N/A, #DIV/0!)  
   - Revalidated & refilled blank entries

3. **Edge Blanks:**  
   - Backfilled with item-quantity relationships  
   - Used “mode” substitution for common values

4. **Logical Gap Filling:**  
   - Imputed typical purchase quantities  
   - Recalculated totals

5. **Deep Missing Data:**  
   - Estimated prices from known data  
   - Mapped likely items & computed quantities

6. **Payment, Location & Date Fixes:**  
   - Proportional distribution for missing Payment & Location  
   - Refreshed transaction dates using yearly calendar & most frequent dates

---

## 🎯 Final Output

- **100% Clean Data:** No missing or invalid values in key fields
- **Logical Consistency:** All records make sense
- **Ready for Power BI:** Deep analytics & visual storytelling

---

## 📊 Dashboard Analysis Summary

### 1. **Time-Based Sales Analysis**
   - **Monthly Trend:** Line chart for peak & low seasons
   - **Daily Distribution:** Area chart for event spikes & staffing

### 2. **Item Performance**
   - **Top Sellers:** Funnel chart for revenue drivers
   - **Sales by Quantity:** Clustered columns for pricing strategy

### 3. **Payment Method Analysis**
   - **Donut Chart:** Cash vs Card vs Digital Wallet adoption

### 4. **Location & Order Type Breakdown**
   - **Stacked Columns:** In-store vs Take-away—profit insights

### 5. **Customer & Transaction Insights**
   - **AOV (Average Order Value):** Card display for spend tracking

### 🔍 Interactive Features
   - Slicers to filter by time, item, payment, location

---

## 🚦 Conclusion

The **Dirty Cafe Sales** Power BI dashboard transforms complex, inconsistent data into a clear, actionable decision-support tool  
— unlocking insights into sales trends, customer behavior, and operational performance.

---

> **Ready to brew up business insights from raw data!**
[dirty_cafe_sales_raw_data.xlsx](https://github.com/user-attachments/files/21960508/dirty_cafe_sales_raw_data.xlsx)
[Dirty_cafe_sales_Answer.xlsx](https://github.com/user-attachments/files/21960504/Dirty_cafe_sales_Answer.xlsx)
[Cafe Sales(cleaned).xlsx](https://github.com/user-attachments/files/21960487/Cafe.Sales.cleaned.xlsx)
[DIRTY CAFÉ PROJECT ABSTRACT.docx](https://github.com/user-attachments/files/21960527/DIRTY.CAFE.PROJECT.ABSTRACT.docx)
[Dirty Cafe Dashboard.pdf](https://github.com/user-attachments/files/21960521/Dirty.Cafe.Dashboard.pdf)



