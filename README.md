# **Business Funnel Analysis for Revenue Optimization**

**Industry:** E-Commerce / B2B Marketplace Analytics

---

## 🧠 **Executive summary**

This project analyzes the complete business funnel — from Marketing Qualified Leads (MQLs) to Closed Deals and finally Order Delivery performance — using a real-world, multi-table dataset modeled on company-grade data.

As a beginner Data Analyst, I approached this like a real analytics engagement:
- First, understand the data deeply (EDA)
- Then, answer clear business questions using Python
- Finally, translate insights into a Power BI dashboard for stakeholders

**🚀 Key Business Impact (at a glance)**
- 📉 Only ~10% of MQLs convert into closed deals → clear funnel leakage
- ⚡ Deals closed within 15 days account for the majority of conversions
- 📣 Paid Search & Organic Search outperform other channels in conversion efficiency
- 🧑‍💼 Conversion performance varies significantly across SDRs, SRs, and business segments
- 🚚 ~8% of delivered orders are delayed, with carrier handover showing the highest variability

These insights directly inform marketing spend optimization, sales prioritization, and operational improvements.

---

## ❗ **Business problem**

**The business lacked a single, connected view of:**
- How efficiently leads move through the funnel
- Which channels, segments, and teams drive conversions
- Where time delays and bottlenecks occur post-sale

**Stakeholders needed answers to questions like:**
- _Where are we losing leads?_
- _Which channels and sales reps perform best?_
- _How fast do deals close — and does speed matter?_
- _Are delivery delays impacting overall performance?_
- 
---

## 🖼️ **Dashboard Preview:**

> ```markdown
> ![Dashboard](./Images/Dashboard.gif)
> ```

![Dashboard](./Images/Dashboard.gif)

---

## 🛠️ **Methodology (What I Did & Why)**

**1️⃣ Exploratory Data Analysis (EDA)**
- Validated data quality across 5 cleaned datasets
- Checked nulls, date consistency, unique keys, and distributions
- Ensured datasets were **analysis-ready** before modeling

**2️⃣ Funnel & Conversion Analysis (Python)**
Used Pandas, NumPy, Matplotlib, Seaborn to:
- Calculate overall and segmented conversion rates
- Analyze conversion by:
    - Marketing channel (origin)
    - Business segment
    - Lead type & behavior profile
- Identify **high-leakage funnel stages**

**3️⃣ Time-Based & Velocity Analysis**
- Measured time-to-close from first contact → deal won
- Segmented deals into velocity buckets (0–7, 8–15, 30+ days)
- Proved that **faster closures strongly correlate with higher success**

**4️⃣ Sales Team Performance**
- Ranked top SDRs and SRs by closed deals
- Highlighted performance skew instead of assuming uniform productivity

**5️⃣ Order & Delivery Analytics**
- Measured:
    - Average delivery time (~12 days)
    - Delay rate (~8%)
    - Stage-wise time variability
- Identified **carrier handover** as the biggest operational bottleneck

**6️⃣ Dashboarding (Power BI)**
- Built a **2-page interactive dashboard**
- Single slicer: `business_segment`
- Designed visuals for executives, sales leaders, and ops teams
- Avoided circular relationships and unnecessary DAX complexity

---

## 🧩 **Skills & tools used**

- **Python:** Pandas, NumPy, Matplotlib, Seaborn
- **EDA & Statistical Thinking**
- **Business Funnel Analysis**
- **Time-Series & Velocity Metrics**
- **Power BI:** Data Modeling, Relationships, DAX, Visual Design
- **SQL-style joins & data preparation**
- **Storytelling with data**

---

## **📈 Results & Insights **

- 🔻 Low MQL → Closed conversion (~10%)
    → Indicates need for better lead qualification or channel optimization

- 🏎️ Fast deals win
    → Majority of successful deals close within 15 days

- 📊 Channel efficiency varies widely
    → Paid Search & Organic Search outperform Social & Email

- 👥 Sales performance is uneven
    → Top SDRs/SRs close significantly more deals than average

- 🚚 Operational delays exist but are controllable
    → Only ~8% delayed, but variability suggests process gaps

---

## **📌 Business Recommendations**

* Reallocate marketing spend toward **high-conversion channels**
- Introduce **lead scoring** to prioritize fast-moving prospects
- Use top SDRs/SRs as benchmark profiles
- Improve **carrier handover processes** to reduce delivery variance
- Track funnel KPIs continuously using the Power BI dashboard
- 

---

## **🔮 Next Steps**

If extended further, this project could include:
- Revenue & deal size impact analysis
- Predictive modeling for deal conversion
- Cohort-based customer lifetime value (CLV)
- A/B testing landing pages with low conversion

---

## ⚠️ Limitations

- No direct revenue field linked to deals
- Customer repeat purchases were not present in this dataset
- Seller → order linkage was limited, requiring careful interpretation

---

## 🎯 Why This Project Matters

This is not a simple Kaggle EDA.

It demonstrates:

- Structured thinking
- Business-driven analytics
- End-to-end ownership (EDA → Python → Dashboard)
- Clear communication of insights

It reflects how a junior data analyst would actually work in a real company.

---

## 👋 Contact

If you’d like to discuss the code, the dashboard, reach out on GitHub or email (kaifsdkpro@gmail.com).

⭐ **If you found this project insightful, don’t forget to star ⭐ this repository!**  
📬 *Let’s connect on [LinkedIn](https://www.linkedin.com/in/kaifsayed57/)
 — open to data analyst and Excel-based analytics roles.

*Made with ❤️ — Kaif Anis Sayed*
