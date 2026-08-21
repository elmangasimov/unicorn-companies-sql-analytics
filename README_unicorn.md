# Venture Capital & Unicorn Growth Analytics (SQL)

## Overview
A SQL-based analysis of venture capital investments and unicorn company data, identifying industry trends, funding patterns, and business insights from 2019 to 2021.

## What This Project Does
- Identifies the top 3 industries by number of unicorn companies (2019-2021)
- Ranks those industries year by year by number of unicorns and average valuation
- Uses Common Table Expressions (CTEs) to break a complex analysis into readable, reusable steps

## Tech Stack
- SQL (PostgreSQL-style syntax)
- CTEs (`WITH` clauses)
- JOINs across multiple tables (industries, dates, funding)
- Window/aggregate functions, `EXTRACT()` for date handling

## Key Query Logic
1. **`top_industries`** — finds the 3 industries with the most unicorn companies joining between 2019-2021
2. **`yearly_rankings`** — calculates the number of unicorns and average valuation per industry, per year
3. **Final query** — filters to the top industries only, ordered by year and unicorn count, with valuations rounded and converted to billions

## Files
- `unicorn_analytics.sql` — full SQL script

## Background
Built as part of a hands-on SQL portfolio, applying joins, CTEs, window functions, and aggregate queries to real-world business analytics — complementing my master data management and cloud data engineering projects.
