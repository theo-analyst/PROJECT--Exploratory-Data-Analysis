# SQL Exploratory Data Analysis: Global Layoffs Trends

## The Problem
After cleaning the layoffs data, stakeholders needed to understand: Which companies, industries, and regions were hit hardest? When did the wave peak? What patterns explain why some companies failed completely while others survived?

## Why It Mattered
In 2022's volatile job market, job seekers needed to target stable industries, investors wanted risk signals, and companies needed competitive intelligence. Raw numbers without context didn't answer the critical question: **Who was most at risk?**

## What I Analyzed
- **Complete failures:** 100% layoffs (startups that shut down entirely)
- **Scale of impact:** Total layoffs by company, location, industry, and funding stage
- **Timeline patterns:** Year-over-year trends and monthly rolling totals
- **Risk indicators:** Correlation between funding raised and survival rate

## Key Insights

| Finding | Impact |
|---------|--------|
| **Amazon, Google, Meta** led in total layoffs (big tech restructuring) | Massive scale ≠ failure; these companies survived |
| **Startups with 100% layoffs** raised $2B+ (e.g., Quibi) | Funding doesn't guarantee survival; business model matters |
| **Consumer and Retail** industries dominated top layoff lists | Post-pandemic correction in over-hired sectors |
| **2022 peak** came in specific months with rolling totals climbing steadily | Timing matters for job seekers and hiring plans |
| **Post-IPO and Acquired companies** had highest layoff totals | Late-stage companies most vulnerable to market shifts |

## The Decision
**Recommended strategic workforce planning based on stage and industry risk profiles** — not just company size. Job seekers should prioritize early-stage startups with solid runway, while investors should scrutinize late-stage companies with high burn rates.

## Technical Skills
- Complex CTEs and window functions (DENSE_RANK, rolling totals)
- Time-series analysis with date manipulation
- Multi-level aggregation and trend identification
- Translating raw queries into business narrative

## Tools Used
- MySQL
- Cleaned dataset from previous SQL project


