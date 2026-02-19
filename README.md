R-Market Analytics: Real Estate & Automotive Insights
This repository contains advanced data manipulation and market analysis scripts using the R programming language. The project focuses on processing scraped web data to extract meaningful business insights from the real estate and automotive sectors.

Project Scope
The scripts perform deep-dives into two primary datasets (Bina.az and Turbo.az), applying statistical filtering and data engineering to understand market pricing, availability, and asset distribution.

Getty Images

Analysis Modules
1. Real Estate Market Analysis (casestudy2Rstudio.r)
This module focuses on the property market, specifically housing in Azerbaijan.

Asset Categorization: Distinguishing between "New" and "Old" buildings.

Pricing Strategy Analysis: Identifying price peaks and outliers in specific property types.

Spatial Distribution: Analyzing unique addresses to understand urban density.

Unit-Level Efficiency: Calculating the "NewCol" metric (Area per Room) to evaluate space utilization.

Legal/Document Analysis: Filtering assets based on legal status (e.g., "Kupça") to estimate market liquidity.

2. Automotive Sector Insights (rstudiohomework2.r)
This module analyzes the secondary car market to identify brand-specific trends.

Brand Valuation: Identifying high-value inventory (e.g., Lexus, Mercedes, BMW).

Inventory Segmentation: Analyzing frequency distribution of car colors and specifications (e.g., "Tam" drive systems).

Currency & Financial Analysis: Converting and filtering price data across different currencies (AZN, USD) to standardize valuation.

Supply Analysis: Quantitative analysis of specific model availability (e.g., Mercedes E220).

Technical Implementation
The project leverages the Tidyverse ecosystem for robust data pipelines:

dplyr: For complex data transformations, grouping, and aggregations.

readr: For high-performance flat-file ingestion.

Functional Programming: Using pipes (%>%) for clean, readable, and maintainable data workflows.

Core Competencies Demonstrated
Data Wrangling: Renaming, relocating, and mutating columns to prepare raw data for modeling.

Conditional Filtering: Multi-layered logic to extract niche market segments.

Summarization: Building aggregate reports (Mean, Max, Min, Count) for executive-level reporting.

Getting Started
Environment: Ensure R and RStudio are installed.

Packages: Run install.packages("tidyverse").

Data: Place the bina_az.csv and turbo_az.csv files in your working directory.

Execution: Run the scripts to generate the market report outputs in the R console.
