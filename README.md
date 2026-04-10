# SQL Data Cleaning: World Layoffs Analysis

## The Problem
Raw layoffs data contained duplicate records, inconsistent industry classifications, and formatting errors that made accurate trend analysis impossible. Analysts couldn't trust the numbers for strategic workforce planning.

## Why It Mattered
With tech layoffs surging in 2022, companies, investors, and job seekers needed reliable data to understand market patterns. Dirty data led to misleading conclusions about which industries and regions were most affected.

## What I Did
- Identified and removed 100+ duplicate records using ROW_NUMBER() and partitioning
- Standardized inconsistent industry names (e.g., "Crypto Currency" → "Crypto")
- Fixed malformed country entries ("United States." → "United States")
- Converted string dates to proper DATE format for time-series analysis
- Populated missing industry values by cross-referencing matching company records
- Removed 300+ rows with null layoff numbers that skewed aggregate calculations

## Key Insight
Data quality issues were hiding the true scale of layoffs — duplicates inflated counts by ~8%, while missing industry labels made sector analysis unreliable.

## The Decision
**Delivered a clean, analysis-ready dataset** that enables accurate trend analysis and trustworthy reporting on global workforce reductions.

## Technical Skills
- Advanced SQL: CTEs, window functions, JOINs
- Data validation and standardization
- Pattern recognition in messy real-world data

## Tools Used
- MySQL
- Kaggle dataset (World Layoffs 2022)

