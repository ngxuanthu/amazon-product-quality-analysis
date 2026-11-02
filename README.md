# Amazon Product Quality & Customer Trust Improvement Program

**Python | Pandas | Tableau | Customer Experience Analytics**

## Project Overview

This project analyzes Amazon customer reviews to identify potential product quality concerns, understand recurring complaints, and support data-driven improvement decisions.

Using **9,739 reviews across 100 Home & Kitchen products** from Amazon Reviews 2023, the project combines data analysis with an interactive Tableau dashboard.

## Project Objectives

- Monitor customer satisfaction through ratings and review volumes.
- Identify products with elevated low-rating rates (1–2 stars).
- Analyze recurring customer complaints and potential quality concerns.
- Support product prioritization and continuous improvement initiatives.

## Tableau Dashboard

The dashboard provides:

- **Product Quality Overview:** 100 products, 9,739 reviews, and an overall low-rating rate of 8.80%.
- **Product Comparison:** Review counts, average ratings, and star-rating distributions.
- **Review Volume vs. Low Rating Rate:** Identification of potential quality concerns.
- **Customer Complaint Analysis:** Detailed investigation of a selected product.

![Amazon Product Quality Dashboard](images/dashboard.png)

## Case Study: Beckham Hotel Collection Pillows

**Parent ASIN:** B08XYD548C

| Key Metric | Result |
|---|---:|
| Sampled Reviews | 123 |
| Average Rating | 4.04 / 5 |
| Low Rating Rate (1–2★) | 18.70% |
| 5-Star Rate | 60.98% |

### Why This Product?

Although some products have higher low-rating rates, **Beckham Hotel Collection Pillows was selected for its relatively high review volume and meaningful number of negative reviews**.

With 123 reviews, including 23 low-rated reviews, the product provides a useful sample for identifying recurring customer complaints.

This selection highlights the importance of considering **both review volume and low-rating rate**, rather than prioritizing products based on percentages alone.

### Key Findings

Despite an average rating of 4.04/5 and 60.98% five-star reviews, **18.70% of sampled reviews received 1–2 stars**.

The analysis of 23 low-rated reviews identified the following recurring complaint themes:

| Complaint Theme | Reviews | Percentage |
|---|---:|---:|
| Support / Flattening | 15 | 65.22% |
| Heat | 6 | 26.09% |
| Lumpiness | 4 | 17.39% |
| Size | 3 | 13.04% |
| Missing Item | 1 | 4.35% |

*Complaint themes may overlap, as a single review can mention multiple issues.*

The most frequently identified concern relates to pillow support and flattening, suggesting an area for further investigation.

## Proposed Improvement Framework

**Identify → Investigate → Monitor → Escalate**

1. **Identify:** Prioritize products using low-rating rates, review volumes, and recurring complaints.
2. **Investigate:** Share customer feedback with relevant stakeholders to explore potential issues.
3. **Monitor:** Track new reviews, customer satisfaction, and complaint trends.
4. **Escalate:** Recommend further investigation if concerns persist.

This is a proposed analytical framework, not an official Amazon process.

## Tools & Skills

- **Python & Pandas:** Data cleaning, transformation, and review analysis.
- **Tableau Public:** Interactive dashboards and KPI visualization.
- **GitHub:** Project documentation and version control.

**Key Skills:** Data Analytics, KPI Monitoring, Customer Experience Analysis, Business Reporting, and Continuous Improvement.

## Data Source

[Amazon Reviews 2023 — McAuley Lab, UC San Diego](https://amazon-reviews-2023.github.io/)

*Independent portfolio project. Findings are based on sampled customer reviews and do not confirm product defects. Not affiliated with Amazon.*
