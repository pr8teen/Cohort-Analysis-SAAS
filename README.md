# SaaS Cohort Analysis: Customer Retention & LTV Modeling

---

## 💡 Project Goal

This project provides an **Excel-based cohort analysis model** for SaaS businesses. It tackles the critical challenge of understanding **customer retention**, **lifetime value (LTV)**, and **marketing ROI** by deeply tracking customer behavior from their very first purchase.

---

## 🎯 The Problem: Alex's Growth Mystery

Meet Alex, the founder of a promising SaaS startup with a **$50/month subscription product**. Despite spending **$115 to acquire each customer**, he struggles with fundamental unknowns:

* **Unpredictable customer retention:** Who stays, who leaves, and when?
* **Uncertain marketing ROI:** Is that $115 acquisition cost truly worth it in the long run?
* **Identifying high-value customers:** Which acquisition efforts bring in the most loyal and profitable customers?

Without these insights, making smart, data-driven growth decisions feels like a shot in the dark.

---

## ✅ The Solution: Deep Dive with Cohort Analysis

My Excel model leverages **cohort analysis** to cut through the uncertainty, transforming raw transactional data into clear, actionable insights. It helps businesses:

* **Track customer retention patterns:** Visualize how distinct customer groups (cohorts) behave over their lifecycle.
* **Calculate Customer Lifetime Value (LTV):** Uncover the true, long-term profitability each customer brings.
* **Validate marketing spend:** Directly assess the effectiveness of Customer Acquisition Cost (CAC) against LTV.
* **Identify revenue expansion opportunities:** Pinpoint moments when existing customers increase their spending.

---

## 📈 Validated Insights from Data

### Customer Retention Highlights:

* **Strongest Initial Retention:** The **June cohort** saw **95% of customers** remain active in Month 4, suggesting highly effective acquisition.
* **Mid-term Challenge:** The **January cohort** experienced a drop to **74% retention** by Month 3, flagging a key period for intervention.

### Revenue Trends & LTV Insights:

* **High Lifetime Value Driver:** The **January cohort** amassed **$14,200 in cumulative revenue** by Month 12, demonstrating long-term value despite earlier retention challenges.
* **Critical Revenue Drop:** An average **11.5% revenue decline** occurs across cohorts between Months 2-3 – a vital point to address with customer engagement strategies.

---

## 💡 Strategic Impact: Data-Driven Growth

This analysis provides Alex with the intelligence to fuel confident business growth to

* **Optimize Marketing:** Confidently **increase marketing spend by 30%** by prioritizing acquisition for high-performing groups like March (revenue expansion) and June (strong retention).
* **Boost Retention:** Develop targeted efforts to mitigate the **Month 2-3 churn**, improving overall customer stickiness.
* **Validate CAC Spend:** Confirms that the **$115 CAC is sustainable**; customers, on average, **break even by Month 4** ($123 LTV vs. $115 CAC), ultimately generating a **2.3x return ($264 LTV)** within their first year.

**Conclusion:** This cohort analysis proves that while Alex's initial CAC is manageable, retention significantly varies. By leveraging these insights, he can transform raw data into a powerful, **actionable growth strategy.**

---

## 🛠️ How to Use This Model
1.  **Input Data:** Populate your raw customer purchase data into the **"Customer Cohort"** tab of the Excel file.
2.  **Adjust Assumptions:** Easily modify **Gross Margin (default: 65%)** and **CAC (default: $115)** in the highlighted yellow cells.

### Key Formulas Used:

* **Retention Rate:** `Customers Active in Month N / Initial Cohort Size`
* **Net Dollar Retention (NDR):** `Month N Revenue / Month 0 Revenue`
* **Customer Lifetime Value (LTV):** `(Cumulative Revenue × Gross Margin) / Initial Customers`
