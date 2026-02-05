# 📊 AfriTech Electronics – Social Sentiment, Crisis & Revenue Risk Analysis

## 🏢 Company Overview

**AfriTech Electronics** is a global consumer electronics company specializing in advanced **smartphones, tablets, and wearables** that combine innovation, design excellence, and high performance.
Headquartered in the United States, the company employs over **200 professionals** focused on redefining connectivity and productivity for modern consumers.

Founded on a user-centric vision, AfriTech has built a strong market presence. However, recent operational and customer-experience challenges have begun to impact brand perception and financial performance.

---

## 🚨 Business Challenges

Despite strong product innovation, AfriTech faced several interconnected challenges:

* Rising **product recalls**
* Increased **customer complaints**
* **Slow customer support response times**
* Declining **customer satisfaction**
* Falling **revenue and customer trust**
* Customers increasingly **switching to competitors**

Leadership required a **data-driven understanding** of how customer engagement, sentiment, and crisis handling were affecting revenue and brand health.

---

## 🗂️ Data Preparation & Engineering

### Data Source

* A **single denormalized table** containing:

  * Transactions
  * Customers
  * Social media activity
  * Crisis and complaint records

### Data Processing Workflow

**Database:** PostgreSQL
**BI Tool:** Power BI

Key steps:

1. **Normalization**

   * Split the raw dataset into **fact and dimension tables**
   * Designed a scalable **star-schema-style model**
2. **Data Cleaning**
<img width="758" height="641" alt="SQL query 1" src="https://github.com/user-attachments/assets/30d02a3b-04a1-4fd4-a12d-45bf18d27943" />
<img width="912" height="586" alt="SQL Query 2" src="https://github.com/user-attachments/assets/285fd2b6-40cc-4d19-9c3a-5e4bc9bfcb0a" />
<img width="704" height="240" alt="SQL Query 3" src="https://github.com/user-attachments/assets/c61bd6bf-8a3c-4c48-996d-1bd39b17ea90" />

   * Corrected data types (dates, numeric fields, text fields)
   * Identified and removed duplicates
3. **Exploratory Data Analysis (EDA)**
<img width="1070" height="994" alt="Crisis Analysis" src="https://github.com/user-attachments/assets/1ae53a19-43c4-4689-98bf-4d3de3154332" />
<img width="1171" height="665" alt="Transaction Analysis" src="https://github.com/user-attachments/assets/deeb7c7b-ac4e-4fd8-810a-04eac1c12cc6" />

   * Validated trends, anomalies, and data completeness
4. **Power BI Integration**

   * Connected PostgreSQL to Power BI
   * Applied final transformations in **Power Query**
   * Established proper **table relationships**
5. **Modeling**

   * Created a **custom date table**
   * Built key **DAX measures** for performance tracking

---

## 📈 Key Analytical Insights

### 1️⃣ Social Media & Engagement Insights

#### Early Engagement Trends (Nov–Dec 2022)

* Social media activity began in **November 2022**
* Engagement grew steadily to **over 1 million interactions**
* Engagement rate: **8%**
* Brand mention rate: **48.2%**
* Competitor mention rate: **52.6%**
* **Images** consistently generated the highest engagement
* **Returning customers** were the most engaged users
* **No strong correlation** between social engagement and sales

#### 2023 Engagement Performance
<img width="1327" height="140" alt="image" src="https://github.com/user-attachments/assets/d59269bb-e720-4af1-9497-3979741cf84a" />

* **Total engagements:** 10 million
* **Engagement rate:** 8%
* **Brand mention rate:** 50.2%
* **Net sentiment rate:** 21.59%

**Platform & Content Insights**

* Instagram: most posts, **lowest engagement rate**
* Images: highest engagement across platforms
* Content performance by platform:

  * **LinkedIn:** Images, videos, and links
  * **Twitter:** Text posts
  * **Instagram:** Stories
  * **Facebook:** Stories and text (highest volume)
  * **TikTok:** Videos and links

---

### 2️⃣ Customer Sentiment Analysis
<img width="1908" height="761" alt="image" src="https://github.com/user-attachments/assets/800bae4a-e74f-4a7c-95f4-bcd3bd9af4cd" />

* **Neutral sentiment:** 40.9%
* **Positive sentiment:** 40.35%
* **Negative sentiment:** 18.75%

This indicates:

* A **large undecided customer base**
* High potential to convert neutral users into brand advocates
* Negative sentiment remains significant and actionable

#### Engagement by Income Segment
<img width="1906" height="818" alt="image" src="https://github.com/user-attachments/assets/e3d5b3a7-bf4e-4154-958d-2f63ed928a0b" />

* Income **37,894 – 81,281:** 30% of total engagements
* Income **16,200 – 37,893:** 11.4% of engagements
* High-income customers (>81,281): lower engagement than expected

---

### 3️⃣ Crisis & Customer Support Performance

#### Complaint Resolution Trends

| Year | Resolution Rate |
| ---- | --------------- |
| 2021 | 58.96%          |
| 2022 | 44.51%          |
| 2023 | 49.24%          |

**Key Observations**

* Sharp decline in resolution effectiveness in 2022
* Partial recovery in 2023, but still below 2021 performance
* Slow response times correlate with:

  * Negative sentiment
  * Brand trust erosion
  * Customer churn risk

---

## 📌 Strategic Business Implications

* Social engagement **alone does not drive revenue**
* Content strategy is **misaligned across platforms**
* Customer support inefficiencies are **directly impacting brand trust**
* Neutral sentiment represents a **major growth opportunity**
* Crisis management performance is **below acceptable benchmarks**

---

## 💡 Market-Viable Recommendations

### 1️⃣ Customer Support & Crisis Management

* Introduce **SLA-based response targets** per complaint category
* Implement **real-time crisis dashboards** for unresolved cases
* Prioritize high-impact complaints affecting revenue and recalls
* Deploy **automated ticket triaging** using sentiment and urgency scores

### 2️⃣ Social Media Optimization

* Reduce Instagram posting volume; focus on **high-performing formats**
* Increase **image-led campaigns** across LinkedIn and Twitter
* Align content types strictly to **platform-specific performance**
* Shift from vanity metrics to **conversion-linked engagement KPIs**

### 3️⃣ Revenue & Customer Retention

* Target **neutral-sentiment customers** with education and trust-building campaigns
* Create loyalty initiatives for **high-engagement income segments**
* Use engagement data to inform **product recall communication strategies**

### 4️⃣ Advanced Analytics Enhancements

* Introduce **customer lifetime value (CLV)** modeling
* Build **churn prediction models** using sentiment + crisis data
* Track **post-crisis sentiment recovery** as a KPI
* Implement **cohort analysis** to link engagement to long-term revenue

---


