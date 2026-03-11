# Automated Sales Performance Tracker — Activewear Business Intelligence Dashboard

> **A comprehensive Power BI dashboard delivering end-to-end financial, operational, and customer intelligence for a U.S. activewear brand across 4 fiscal years (2021–2024).**

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Business Context](#business-context)
- [Dataset Summary](#dataset-summary)
- [Tools & Technologies](#tools--technologies)
- [Dashboard Preview](#dashboard-preview)
- [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)
- [Analytical Insights](#analytical-insights)
  - [Revenue Performance](#1-revenue-performance)
  - [Profit Trajectory](#2-profit-trajectory)
  - [Customer Growth](#3-customer-growth)
  - [Product Performance & Profitability](#4-product-performance--profitability)
  - [Sales Channel Analysis](#5-sales-channel-analysis)
  - [Geographic Performance](#6-geographic-performance)
  - [Regional Profit Trends](#7-regional-profit-trends)
  - [Monthly & Seasonal Patterns](#8-monthly--seasonal-patterns)
- [Strategic Recommendations](#strategic-recommendations)
- [Live Dashboard](#live-dashboard)
- [Connect With Me](#connect-with-me)

---

## Project Overview

In the competitive activewear market, sustained profitability depends not on surface-level revenue tracking alone — but on understanding the *interplay* between product mix, geography, sales channel efficiency, and customer acquisition trends.

This project delivers a fully automated, multi-page Power BI dashboard that tracks financial and operational performance across **6,060 orders**, **5,000 unique customers**, **9 product categories**, **4 sales channels**, and **50 U.S. states** from 2021 through 2024. The dashboard is designed to serve as a live decision-support system — enabling leadership to identify growth levers, address performance gaps, and make data-backed strategic calls in real time.

---

## Business Context

The activewear brand analyzed operates across four distinct distribution channels — Marketplaces, Online Store, Retail Stores, and Pop-ups & Events — and sells 9 product lines ranging from high-margin Jackets to volume-driven Socks. The business competes across all four U.S. census regions, with meaningful variation in performance by state and channel.

The analytical challenge: **revenue and profit grew overall, yet the growth is uneven, channel-dependent, and threatened by specific product underperformance** — dynamics that would be invisible without granular, automated tracking.

---

## Dataset Summary

| Attribute | Detail |
|---|---|
| **Period Covered** | 2021 – 2024 |
| **Total Records** | 6,250 rows |
| **Total Orders** | 6,060 unique orders |
| **Total Customers** | 5,000 unique customers |
| **Geography** | 50 U.S. States + D.C., across 4 regions |
| **Products** | 9 categories (Jackets, Sneakers, Backpacks, Yoga Mats, Leggings, Sports Bras, Shirts, Tank Tops, Socks) |
| **Sales Channels** | Marketplaces, Online Store, Retail Stores, Pop-ups & Events |
| **Key Fields** | Order ID, Order Date, Customer ID, State, Product Name, Sales Channel, Quantity, Price, Revenue, Profit, Region |

---

## Tools & Technologies

- **Power BI Desktop** — Dashboard design, DAX measures, interactive visuals
- **Power Query (M Language)** — Data transformation and cleaning
- **DAX** — Custom KPI calculations, YoY % change measures, dynamic filters
- **Microsoft Excel / CSV** — Source data preparation

---

## Dashboard Preview

![Dashboard Page 1](https://github.com/TofunmiTech01/Automated-Sales-Performance-Tracker-PowerBI/blob/main/Sales1.PNG)

![Dashboard Page 2](https://github.com/TofunmiTech01/Automated-Sales-Performance-Tracker-PowerBI/blob/main/Sales2.PNG)

---

## Key Performance Indicators (KPIs)

| KPI | 2021 | 2022 | 2023 | 2024 |
|---|---|---|---|---|
| **Total Revenue** | $200,476 | $231,391 | $229,107 | $247,935 |
| **Revenue YoY Change** | — | +15.4% | -1.0% | +8.2% |
| **Total Profit** | $60,478 | $69,358 | $68,834 | $74,566 |
| **Profit YoY Change** | — | +14.7% | -0.8% | +8.3% |
| **Profit Margin** | ~30.2% | ~30.0% | ~30.1% | ~30.1% |
| **Unique Customers** | 1,164 | 1,603 | 1,634 | 1,688 |
| **Customer YoY Change** | — | +37.7% | +1.9% | +3.3% |
| **Total Orders** | 1,325 | 1,603 | 1,634 | 1,688 |

> **4-Year Cumulative Totals:** $908,910 Revenue · $273,235 Profit · 5,000 Customers

---

## Analytical Insights

### 1. Revenue Performance

Total revenue across the 4-year period reached **$908,910**, with a compounded recovery story:

- **2022** delivered the strongest year-on-year revenue growth at **+15.4%**, jumping from $200,476 to $231,391 — driven by the largest single-year customer acquisition event in the business's history.
- **2023** saw a **-1.0% dip** to $229,107, a notable inflection that aligns with subdued order volumes and customer growth stagnation post the 2022 acquisition surge.
- **2024** marks a **healthy rebound of +8.2%** to $247,935, the highest annual revenue on record — signaling that the 2023 softening was transitional rather than structural.

The revenue trend confirms a **W-shaped recovery arc**, demanding careful watch on whether 2024's momentum sustains into 2025.

---

### 2. Profit Trajectory

Profitability followed an almost identical pattern to revenue, revealing a structurally stable **~30% gross profit margin** that has held consistent across all four years — a sign of disciplined pricing rather than margin compression.

| Year | Profit | YoY Change |
|---|---|---|
| 2021 | $60,478 | — |
| 2022 | $69,358 | **+14.7%** |
| 2023 | $68,834 | -0.8% |
| 2024 | $74,566 | **+8.3%** |

**Critical Observation:** The near-perfect margin consistency (~30.1% each year) means *profit growth is almost entirely volume-driven* — not efficiency-driven. This is a strategic vulnerability: any volume decline (as seen in 2023) directly translates to profit decline with minimal cushion from operational leverage.

---

### 3. Customer Growth

The business grew from **1,164 unique customers in 2021** to **5,000 cumulative customers by end of 2024**.

- The defining moment was **2022's 37.7% customer surge** — the most significant acquisition event across all four years. However, the growth mechanism behind this spike has not been replicated: 2023 grew only +1.9% and 2024 just +3.3%.
- **Customer retention analysis** reveals that **3,895 customers (78%)** placed only one order, while **1,105 customers (22%)** placed two or more orders. This suggests a **low repeat purchase rate** — a critical gap for a product category (activewear) where replenishment and loyalty purchases should be higher.

> **Strategic implication:** The business is overly reliant on new customer acquisition. A loyalty and retention program targeting the 78% single-purchase segment could significantly amplify revenue without additional acquisition spend.

---

### 4. Product Performance & Profitability

#### Total Profit by Product (2021–2024):

| Product | Total Profit | Total Revenue | Profit Margin | Profit/Unit |
|---|---|---|---|---|
| **Jackets** | $65,327 | $218,577 | 29.9% | **$30.22** |
| **Sneakers** | $54,635 | $180,262 | 30.3% | $24.47 |
| **Backpacks** | $44,305 | $146,077 | 30.3% | $21.44 |
| **Yoga Mats** | $30,481 | $101,264 | 30.1% | $15.18 |
| **Leggings** | $23,945 | $80,574 | 29.7% | $11.99 |
| **Sports Bras** | $20,606 | $69,000 | 29.9% | $9.05 |
| **Shirts** | $15,588 | $52,487 | 29.7% | $7.50 |
| **Tank Tops** | $11,961 | $39,687 | 30.1% | $6.08 |
| **Socks** | $6,387 | $20,982 | **30.4%** | $3.08 |

**Key Findings:**

- **Jackets dominate profit contribution** at $65,327 (23.9% of total profit) and the highest profit-per-unit at $30.22 — making them the most strategically valuable product in the portfolio.
- **Socks carry the highest profit margin (30.4%)** despite the lowest absolute profit — their margin efficiency at a low price point is noteworthy for bundling strategies.
- **Sports Bras present a compounding concern.** Despite being the *highest-volume product* (2,278 units sold — more than any other category), they rank 6th in total profit. Worse, their annual profit has been declining since 2022: $5,767 → $5,470 → $5,049. High volume with declining profit signals either increasing costs, pricing pressure, or a shrinking willingness-to-pay — all of which warrant urgent investigation.

---

### 5. Sales Channel Analysis

#### Total Profit by Channel (2021–2024):

| Channel | Total Profit | Profit Share | Avg. Order Revenue |
|---|---|---|---|
| **Marketplaces** | $77,004 | **28.2%** | $152.06 |
| **Pop-ups & Events** | $65,933 | 24.1% | $143.59 |
| **Online Store** | $65,182 | 23.9% | $140.11 |
| **Retail Stores** | $65,116 | 23.8% | $145.38 |

**Key Findings:**

- **Marketplaces lead in both total profit and average order value ($152.06)** — the highest AOV of any channel. This suggests marketplace customers either buy higher-priced items or purchase in larger quantities.
- **The three non-Marketplace channels are remarkably competitive with one another**, each contributing ~24% of total profit. This near-parity is strategically valuable — the business is not over-reliant on any single channel.
- **Pop-ups & Events is the stealth standout.** Despite being episodic and resource-intensive, it generates $65,933 in profit — nearly matching Retail Stores ($65,116) with likely far fewer fixed costs. The profit-per-event efficiency could be exceptional if modeled correctly.
- **Channel profitability is shifting.** In 2021, Marketplaces and Retail were the top two. By 2024, Marketplaces and Online Store lead — reflecting a secular shift toward digital commerce that the business should actively lean into.

---

### 6. Geographic Performance

#### Top 10 States by Total Profit (2021–2024):

| Rank | State | Total Profit | Region |
|---|---|---|---|
| 1 | Florida | $6,623 | South |
| 2 | Arkansas | $6,505 | South |
| 3 | New Hampshire | $6,338 | Northeast |
| 4 | Wisconsin | $6,330 | Midwest |
| 5 | Minnesota | $6,313 | Midwest |
| 6 | Iowa | $6,208 | Midwest |
| 7 | Colorado | $6,186 | West |
| 8 | North Dakota | $6,164 | Midwest |
| 9 | Maine | $6,140 | Northeast |
| 10 | Utah | $6,025 | West |

#### Bottom 5 States by Total Profit:

| State | Total Profit |
|---|---|
| Oregon | $4,629 |
| South Dakota | $4,442 |
| Maryland | $4,323 |
| Kansas | $4,169 |
| Alabama | $4,082 |

**Key Findings:**

- **Florida leads all 50 states** with $6,623 in cumulative profit — a South region anchor that, combined with Arkansas in 2nd, confirms the South's dominance as the most profitable region.
- **The Midwest punches above its weight**, placing 4 states in the top 10 (Wisconsin, Minnesota, Iowa, North Dakota) — indicating underappreciated market depth in that region.
- **2024 State-Level Growth Leaders:** California (+111%), Tennessee (+99%), Connecticut (+80%), Kansas (+74%), Pennsylvania (+64%) — all showing explosive year-over-year profit growth, making them high-priority markets for 2025 investment.
- **States with declining 2024 profit** include Wyoming (-33%), North Carolina (-29%), Maine (-30%), and Alabama (-20%) — markets requiring diagnostic review to determine if the decline is product-mix, channel, or demand-driven.

---

### 7. Regional Profit Trends

#### Profit by Region (2021–2024):

| Region | 2021 | 2022 | 2023 | 2024 | 4-Year Total |
|---|---|---|---|---|---|
| **South** | $19,376 | $19,996 | $22,117 | $23,630 | **$85,119** |
| **West** | $15,139 | $18,585 | $17,722 | $19,168 | **$70,613** |
| **Midwest** | $15,380 | $17,506 | $16,187 | $17,869 | **$66,942** |
| **Northeast** | $10,583 | $13,271 | $12,808 | $13,899 | **$50,560** |

**Key Findings:**

- The **South is the undisputed profit engine**, contributing $85,119 (31.2% of total profit) and growing consistently every year — the only region with zero profit decline across the full 4-year period.
- The **Northeast lags all other regions** and has never exceeded $14K in annual profit — representing either a distribution gap, weaker brand resonance, or a product-market fit issue in that geography.
- The **West and Midwest show cyclical dips** (both declined in 2023) but have recovered in 2024, suggesting their 2023 weakness was macro-driven rather than structural.

---

### 8. Monthly & Seasonal Patterns

#### Peak Profit Month by Year:

| Year | Peak Month | Peak Profit |
|---|---|---|
| 2021 | November | $5,623 |
| 2022 | December | $6,805 |
| 2023 | November | $6,695 |
| 2024 | February | $7,595 |

**Key Finding:** There is no consistent seasonal peak — the business does not follow a predictable retail calendar. November and December peaks in 2021–2023 suggest some holiday-season influence, but **2024's February peak ($7,595 — the single highest monthly profit on record)** breaks this pattern entirely, possibly driven by a targeted campaign, product launch, or channel push.

The absence of seasonality — while seemingly a challenge — also reveals **upside potential**: if the business could identify and replicate the drivers behind the February 2024 spike, it could engineer demand spikes strategically rather than waiting for organic holiday-season lifts.

---

## Strategic Recommendations

### 1. Diagnose and Revive Sports Bras
The Sports Bras line sells the most units of any product yet delivers the second-lowest profit and a declining 3-year trend ($5,767 → $5,470 → $5,049). Conduct an immediate product audit: review pricing competitiveness, return rates, production costs, and customer sentiment. Consider a redesign, price repositioning, or bundle pairing with high-margin Jackets and Sneakers.

### 2. 📦 Scale the Marketplace Channel
Marketplaces generate the highest profit ($77,004) and the highest average order value ($152.06). Invest in marketplace-specific listings, sponsored product placements, and bundle offers to further grow this channel's share — particularly for the top three profit-driving products: Jackets, Sneakers, and Backpacks.

### 3. Formalize the Pop-ups & Events Strategy
Pop-ups & Events nearly matches Retail Stores in total profit despite operating episodically. Build a repeatable event playbook — prioritizing South and West region events given their higher regional profitability — and track event-level ROI to identify the highest-performing event formats.

### 4. Build a Customer Retention Engine
With 78% of customers making only a single purchase, the business is leaving significant lifetime value on the table. Implement a post-purchase loyalty program, personalized replenishment reminders, and a tiered rewards system. Even moving 10% of single-purchase customers to repeat buyers could add an estimated $20K+ in incremental annual profit.

### 5. Invest in 2024's High-Growth States
California (+111%), Tennessee (+99%), and Connecticut (+80%) showed explosive 2024 profit growth. These markets are signaling demand acceleration — allocate incremental marketing and channel investment here to consolidate and extend momentum before competitors respond.

### 6. Investigate Declining State Markets
States like Wyoming, North Carolina, Maine, and Alabama saw 20–33% profit declines in 2024 despite the overall business growing. Determine whether the decline is channel mix shift, product preference change, or external market factors — and implement targeted recovery plans.

### 7. Decode the February 2024 Spike
The highest single monthly profit in the dataset ($7,595 in February 2024) is an anomaly worth investigating. If this was driven by a specific campaign, product launch, influencer event, or channel activation — it should be codified and repeated. Understanding this spike could unlock a repeatable demand-generation playbook.

### 8. Leverage Jackets as the Anchor Product
Jackets deliver the highest profit-per-unit ($30.22), the largest total profit ($65,327), and strong YoY consistency. Use Jackets as the hero product in acquisition campaigns, bundle strategies, and Marketplace listings to maximize average order values across all channels.

---

## Live Dashboard

> 🔗 Interact with the full live Power BI dashboard [**HERE**](https://app.powerbi.com/Redirect?action=OpenApp&appId=0f5beb4b-bf1b-44e4-9c93-1afa486595f7&ctid=ba38b7d0-440d-4aa0-9181-65fa6c227366&experience=power-bi)

---

## Connect With Me

I'd love to connect, collaborate, or hear your feedback on this project!

- 💼 [LinkedIn](https://www.linkedin.com/in/oluwatofunmi-isholadaniel/)
- 💻 [GitHub](https://github.com/TofunmiTech01)

---

*Built with Power BI · Analyzed with precision · Designed for decisions.*





