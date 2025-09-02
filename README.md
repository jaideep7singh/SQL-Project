# Data Analytics Pipeline using SQL
-Bronze Layer (Raw Data)

Stores raw, unprocessed data as ingested from the source systems (CSV, database exports, APIs, etc.).

Data is kept in its original format with minimal changes.

Purpose: Acts as a single source of truth and backup of raw datasets.

 -Silver Layer (Cleaned & Transformed Data)

Data from Bronze is cleaned, standardized, and transformed.

Handles tasks such as:

Removing duplicates / missing values

Standardizing formats (date, currency, etc.)

Applying business rules and joins

Purpose: Provides a reliable and analytics-ready dataset.

- Gold Layer (Business/Analytics Ready Data)

Curated, aggregated, and optimized datasets for reporting and analytics.

Contains KPI calculations, summary tables, and pre-aggregated metrics.

Purpose: Directly used for dashboards, visualizations, and decision-making.
