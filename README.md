# Food Delivery Sales Analytics

## 📌 Project Overview

An Excel-based business analytics project analyzing food delivery data to understand
**sales performance, market concentration, restaurant contribution, product mix,
customer experience, and temporal patterns**.

The project uses PivotTables, calculated fields, interactive slicers, and dashboard
visualizations to move from descriptive reporting toward **business-oriented insights
and recommendations**.

---

# 🎯 Business Problem

> **How can a food delivery platform identify its strongest markets, restaurant
> segments, and product categories while uncovering opportunities for growth and
> customer-experience improvement?**

The analysis focuses on three business decisions:

- **Market Prioritization** — Where should the business focus resources?
- **Restaurant & Product Strategy** — Which segments drive the most value?
- **Customer Experience** — Are strong-performing markets also delivering strong customer satisfaction?

---

# 🔎 Analytical Approach

The analysis was structured around five dimensions:

| Dimension | Key Questions |
|---|---|
| **Time** | When is sales performance strongest? |
| **Geography** | Which cities drive the most value? |
| **Restaurant** | Which restaurants contribute most? |
| **Product** | What food types/categories dominate? |
| **Customer Experience** | Where are high sales accompanied by weaker ratings? |

The dashboard enables these dimensions to be explored interactively through
Month, Category, Restaurant, Food Type and other slicers.

---

# 📊 Analysis & Business Insights

## 1. Sales are geographically concentrated

The five largest cities in the current analysis are:

1. Bengaluru
2. Lucknow
3. Mumbai
4. Hyderabad
5. New Delhi

Together, they contribute approximately **32.9% of observed sales value**.

### What does this tell us?

Sales performance is not evenly distributed across markets. A relatively small
number of cities generate a significant share of observed value.

### Business implication

The business should not treat all markets equally.

A market-tiering approach could be used:

| Market Profile | Strategic Direction |
|---|---|
| High sales | Defend & scale |
| High sales + low rating | Improve customer experience |
| Moderate sales + strong rating | Explore growth |
| Low sales | Evaluate market economics |

---

## 2. Bengaluru is the strongest market — but not the highest-rated

Bengaluru generated approximately **$2.71M** in observed sales value,
representing around **10.3%** of the current total.

It is the strongest-performing city, ahead of Lucknow, Mumbai, Hyderabad
and New Delhi. :contentReference[oaicite:2]{index=2}

However, Bengaluru's average rating is approximately **4.31**, slightly below
the overall average of **4.34**. :contentReference[oaicite:3]{index=3}

### Business insight

> **High commercial performance does not necessarily mean the strongest customer experience.**

### Business implication

Bengaluru should remain a core market, but growth should be accompanied by
customer-experience monitoring.

Potential actions:

- Strengthen relationships with high-performing restaurants
- Protect existing demand
- Investigate lower-rated restaurants
- Identify successful restaurant/category combinations that can be replicated elsewhere

---

## 3. Veg dominates value, while Non-Veg has a higher average price

In the current dashboard view:

| Food Type | Sales Value | Average Price |
|---|---:|---:|
| Veg | $16.92M | $245.17 |
| Non-Veg | $9.34M | $325.85 |

Veg contributes approximately **64.4% of observed sales value**, while
Non-Veg has an average recorded price approximately **33% higher**. :contentReference[oaicite:4]{index=4}

### Business insight

The two segments play different roles:

- **Veg → volume/value contributor**
- **Non-Veg → higher-price segment**

### Business implication

Non-Veg could be investigated as a potential premium segment for:

- Bundling
- Upselling
- Premium positioning
- Product recommendations

However, this is a **hypothesis for further analysis**, because the dataset
does not contain customer-level order information.

---

## 4. Restaurant sales are concentrated among major brands

The top restaurants by observed sales value include:

| Restaurant | Sales Value |
|---|---:|
| KFC | $2.09M |
| McDonald's | $1.65M |
| Pizza Hut | $1.04M |
| Burger King | $0.93M |
| Domino's Pizza | $0.89M |

The top five restaurants contribute approximately **25.2% of observed
sales value**. :contentReference[oaicite:5]{index=5}

### Business insight

A relatively small group of major brands contributes a substantial share
of observed value.

### Business implication

This creates a trade-off:

**Opportunity:**  
Major brands are powerful demand and value drivers.

**Risk:**  
High dependence on a small number of brands creates concentration risk.

### Recommended direction

> Maintain strong partnerships with major brands while developing
> high-potential local restaurants.

---

## 5. Sales are relatively stable across days of the week

Observed sales value by day:

| Day | Sales Value |
|---|---:|
| Saturday | $3.88M |
| Wednesday | $3.88M |
| Thursday | $3.75M |
| Friday | $3.72M |
| Sunday | $3.71M |
| Monday | $3.68M |
| Tuesday | $3.64M |

The difference between the highest and lowest days is relatively small. :contentReference[oaicite:6]{index=6}

### Business insight

There is no strong evidence of extreme weekend concentration.

### Business implication

A strategy based only on weekend promotions may not be optimal.

Instead, the business should investigate:

- City × Day patterns
- Category × Day patterns
- Restaurant × Day patterns

This could reveal more specific demand opportunities.

---

## 6. January leads the current period, followed by a February decline and recovery

Monthly observed sales value:

| Month | Sales Value |
|---|---:|
| January | $6.83M |
| February | $6.27M |
| March | $6.57M |
| April | $6.59M |

January is the strongest month in the current dashboard view.

February experienced an approximately **8.1% month-over-month decline**, followed
by a recovery in March. :contentReference[oaicite:7]{index=7}

### Business insight

The February decline is an **analytical signal**, but not an explanation.

Possible drivers to investigate include:

- Promotions and discounts
- Restaurant availability
- Customer demand
- Holidays/events
- Operational factors
- Data coverage

### Business implication

The next analytical step should be **root-cause analysis**, rather than
assuming the decline was caused by any one factor.

---

## 7. High-value markets should be evaluated together with customer ratings

Hyderabad generated approximately **₹1.48M** in observed sales value but had
an average rating of **4.27**, below the overall average of **4.34**. :contentReference[oaicite:8]{index=8}

### Business insight

Hyderabad represents a potential:

> **High-value / relatively lower-rating market**

### Business implication

Rather than immediately concluding that Hyderabad has a market-wide problem,
the next step should be to drill down into:

- Lowest-rated restaurants
- Categories associated with lower ratings
- Locations with weaker ratings
- High-sales restaurants with lower ratings

This distinguishes a **systemic market issue** from a problem concentrated
in a small number of restaurants.

---

# 💡 From Insights to Business Actions

The analysis leads to five main recommendations.

### 1. Defend core markets

Prioritize high-value markets such as Bengaluru while monitoring
customer experience.

### 2. Build a Sales × Rating framework

Identify markets that are:

- High sales / high rating
- High sales / low rating
- Low sales / high rating
- Low sales / low rating

This provides a more actionable basis for market prioritization.

### 3. Explore premium product opportunities

Investigate whether the higher recorded price of Non-Veg products can support
premium bundles, upselling or targeted recommendations.

### 4. Reduce restaurant concentration risk

Continue leveraging major brands while identifying local restaurants with:

- Strong ratings
- Strong observed sales
- Attractive price points
- Expansion potential

### 5. Investigate performance anomalies

Use additional variables to explain unusual monthly or market-level changes
rather than interpreting descriptive trends as causal relationships.

---

# 🧮 Data & Methodology

## Dataset

The dataset contains:

- **197,430 records**
- **14 variables**
- **28 states/cities**
- **993 restaurants**
- **59,064 unique dishes**
- **2 food types: Veg and Non-Veg** :contentReference[oaicite:9]{index=9}

Key fields:

`City` · `Order Date` · `Restaurant Name` · `Category` · `Dish Name`
· `Food Type` · `Price (INR)` · `Rating` · `Rating Count`

## Data Preparation

The analysis included:

- Data structure and completeness checks
- Time-based fields
- Month / Quarter / Week classification
- Food-type segmentation
- PivotTable preparation
- Interactive slicers
