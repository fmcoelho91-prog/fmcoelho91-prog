# Francisco Morais Coelho

### Data Analyst | Analytics Engineering | Marketing Analytics

I am a Data Analyst with a background in Digital Marketing, operations management and KPI-driven decision-making.

I see the Data Analyst role as one that is evolving.

In my view, analysts are increasingly expected to do more than explore data and build dashboards. Understanding how data is transformed, modelled, tested and made reliable before it reaches the analytical layer is becoming an increasingly valuable part of the role.

That is the direction I want to follow.

I started with Digital Marketing, where data was already central to understanding customer behaviour, campaign performance and conversion. I then moved deeper into Data Analytics, developing practical skills in Python, SQL, Power BI, Excel and ETL processes.

Today, I am expanding that foundation toward Analytics Engineering, working with technologies and practices such as dbt, Snowflake, dimensional modelling, data quality testing, documentation, lineage and Git.

I do not see this as moving away from analytics. I see it as becoming a more complete analyst: someone who can understand the business question, work with the underlying data, build reliable analytical models and ultimately turn that data into useful decisions.

My goal is to keep developing at the intersection of analytics, engineering and business, while building a profile that is prepared for how I believe the data profession is evolving.
---

# Technical Skills

## Data & Analytics

- SQL
- Python
- Pandas
- NumPy
- Exploratory Data Analysis
- Data Cleaning and Transformation
- Data Modelling
- Dimensional Modelling
- ETL Processes
- Business Analysis

## Analytics Engineering

- dbt
- Snowflake
- Staging / Intermediate / Marts Architecture
- Fact and Dimension Modelling
- Data Quality Testing
- dbt Documentation and Lineage
- Source Definitions
- Business Rule Validation
- Git / GitHub
- Pull Request Workflow

## Business Intelligence

- Power BI
- DAX
- Power Query
- Interactive Dashboard Development
- KPI Modelling
- Data Storytelling

## Databases & Tools

- Snowflake
- SQL Server
- dbt Cloud
- Jupyter Notebook
- Git
- GitHub
- Advanced Excel
- Power Pivot
- PivotTables
- XLOOKUP

## Marketing Analytics

- Google Analytics 4
- Google Ads
- Meta Ads
- Google Tag Manager
- Mailchimp
- Funnel Analysis
- Conversion Rate Optimisation
- Campaign Performance Analysis

---

# Areas of Interest

- Analytics Engineering
- Data Analytics
- Marketing Analytics
- Customer Analytics
- Business Intelligence
- Dimensional Modelling
- Data Quality
- Churn Analysis
- Revenue Risk Analysis
- Data Storytelling
- Cloud Analytics

---

# Featured Projects

## 🛒 Modern E-Commerce Analytics Platform — Snowflake + dbt

[📂 View the full project](https://github.com/fmcoelho91-prog/Olist-analytics-engineering)

### Objective

Development of a modern Analytics Engineering project using the Brazilian Olist e-commerce dataset.

The objective was to transform raw relational data into a clean, tested, documented and analysis-ready dimensional model using Snowflake and dbt.

The project focuses on data modelling reliability, grain definition, fanout prevention, automated data quality testing, documentation, lineage and production deployment.

### Technologies

- Snowflake
- dbt Cloud
- SQL
- Git
- GitHub

### Architecture

`RAW → STAGING → INTERMEDIATE → MARTS → ANALYSES`

### What Was Developed

- Loaded 9 relational source tables into Snowflake
- Profiled source data to identify grain, keys, nulls and one-to-many relationships
- Created staging models with standardized naming and source definitions
- Built intermediate models to aggregate order items, payments and reviews
- Prevented fanout by aggregating one-to-many relationships before order-level joins
- Created order-level and item-level fact tables
- Created customer, product and seller dimensions
- Implemented generic and singular dbt tests
- Added delivery performance and customer experience metrics
- Generated dbt documentation and lineage
- Used Git branches and pull requests for version control
- Created a dbt Cloud production deployment job
- Built reusable analytical SQL queries using the final marts

### Key Engineering Decisions

- Defined the grain of every model explicitly
- Preserved order-level accuracy by preventing fanout
- Separated facts from descriptive dimensions
- Used LEFT JOINs where missing relationships should not remove valid orders
- Kept transformations modular and explainable
- Validated business rules through automated tests
- Used analytical marts instead of querying raw data directly

### Key Business Insights

Delayed orders achieved an average review score of **2.27**, compared with **4.29** for orders delivered on time or early.

Customer ratings declined strongly as delays increased:

- On time / early: 4.29
- 1–3 days late: 3.29
- 4–7 days late: 2.11
- 8–14 days late: 1.67
- 15+ days late: 1.73

The highest-revenue product categories included:

- health_beauty
- watches_gifts
- bed_bath_table
- sports_leisure
- computers_accessories

The Top 10 sellers represented only approximately **13.15% of total marketplace revenue**, suggesting that revenue was relatively distributed across a broad seller base.

Delivery reliability also varied by customer state, with some regions showing considerably higher delayed-order rates than others.

---

## 🎸 Ecos Progressivos — End-to-End Marketing Performance Analytics

[🌐 Visit the website](https://ecosprogressivos.carrd.co/) | [📂 View the full project](https://github.com/fmcoelho91-prog/Ecos-Progressivos-Marketing-Analytics)

### Objective

Development of a complete Marketing Analytics project using real data from a digital campaign created to promote subscriptions to a progressive rock newsletter.

The project covers the entire process, from the creation of the landing page and Meta Ads campaign to the integration, transformation, storage and visualisation of data.

### Technologies

- Meta Ads
- Google Analytics 4
- Mailchimp
- Python
- Pandas
- SQLAlchemy
- SQL Server
- Power BI
- DAX

### Architecture

`Meta Ads + GA4 + Mailchimp → Python ETL → SQL Server → Power BI`

### What Was Developed

- Created the brand identity and value proposition for Ecos Progressivos
- Developed a landing page to capture newsletter subscribers
- Planned and executed a conversion campaign using Meta Ads
- Implemented website measurement through Google Analytics 4
- Collected confirmed subscriptions through Mailchimp
- Built a Python ETL process to clean and integrate data from multiple platforms
- Loaded transformed data into SQL Server
- Created DAX measures and an interactive Power BI dashboard
- Analysed the full conversion funnel
- Developed strategic recommendations based on campaign performance

### Key Results

- Meta Ads investment: **€64.79**
- Impressions: **25,386**
- Reach: **16,338**
- Website sessions: **532**
- New users: **481**
- Form starts: **43**
- Confirmed subscriptions: **16**
- Form-start rate: **8.08%**
- Session conversion rate: **3.01%**
- Overall cost per subscription: **€4.05**

### Key Insight

The largest funnel loss occurred before users started completing the subscription form.

From **532 website sessions**, only **43** generated a form-start event, highlighting the importance of landing-page clarity, form visibility, mobile experience and measurement quality in addition to traffic acquisition.

---

## 📊 Telecommunications Customer Churn & Revenue Risk Analysis

[📂 View the full project](https://github.com/fmcoelho91-prog/Telecommunications-Customer-Churn)

### Objective

Customer churn analysis based on a dataset containing **7,043 customers** from a telecommunications company.

The objective was to identify the main factors associated with customer churn, quantify its financial impact and develop recommendations focused on customer retention and revenue protection.

### Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Power BI
- DAX

### What Was Developed

- Data auditing, cleaning and validation
- Exploratory Data Analysis
- Feature engineering
- Customer segmentation by value and tenure
- Financial impact analysis
- Interactive Power BI dashboard development
- Strategic customer retention recommendations

### Key Results

- Overall churn rate: **26.54%**
- Customers lost: **1,869**
- Monthly recurring revenue associated with churn: **€139,130.85**
- Estimated annualised impact: approximately **€1.67M**
- Month-to-month churn rate: **42.71%**
- Approximately **87% of monthly revenue associated with churn** concentrated among monthly contracts
- High-value customers responsible for approximately **61% of monthly revenue associated with churn**
- Month-to-month churn without Tech Support: **50.37%**
- Month-to-month churn with Tech Support: **30.70%**

### Key Insight

Customers with `Month-to-month` contracts presented the highest churn risk and represented the largest share of monthly revenue associated with churn.

High-value customers therefore represent a priority segment for retention strategies, particularly when combined with short-term contracts and low service adoption.


---

# 🏆 Certifications

- **dbt Fundamentals** — dbt Labs
- **[Diploma in Digital Marketing](https://crowdclass-storage.s3.eu-west-1.amazonaws.com/zhrfy3hbkxdrug10ei9piycpa8ws)** — EDIT – Disruptive Digital Education
- **[Google Analytics Certification](https://api.accredible.com/v1/frontend/credential_website_embed_image/certificate/188051417)** — Google Skillshop
- **[Google Ads Search Certification](https://api.accredible.com/v1/frontend/credential_website_embed_image/certificate/184611605)** — Google Skillshop
- **[Inbound Marketing Certification](https://app-eu1.hubspot.com/academy/achievements/4zbk12bs/en/1/francisco-coelho/inbound)** — HubSpot Academy
- **[Content Marketing Certification](https://app-eu1.hubspot.com/academy/achievements/b6483k25/en/1/francisco-coelho/content-marketing)** — HubSpot Academy

---

# Current Focus

- Strengthening my profile in Analytics Engineering
- Building modern analytics workflows with dbt, Snowflake and SQL
- Developing stronger data modelling and data quality practices
- Expanding cloud data platform knowledge
- Applying analytics to real business problems
- Building a coherent portfolio across Analytics Engineering, Marketing Analytics and Customer Analytics
- Pursuing Data Analyst, Analytics Engineer and analytics-focused roles where technical skills and business understanding can be combined


# Contact

If you would like to discuss my projects or professional opportunities, feel free to contact me through:

- **Email:** [fmcoelho91@gmail.com](mailto:fmcoelho91@gmail.com)
- **LinkedIn:** [linkedin.com/in/fmcoelho91](https://www.linkedin.com/in/fmcoelho91)
