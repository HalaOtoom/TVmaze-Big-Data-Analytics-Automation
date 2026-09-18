# TVmaze Big Data Analytics & Automation

## Project Overview

This project applies Big Data Analytics, Machine Learning, and workflow automation to real-world TV show data collected from the TVmaze API.

The project focuses on collecting, cleaning, transforming, and analyzing large-scale TV show data to identify patterns and relationships associated with TV show ratings. The analysis generates data-driven insights and reports to support evidence-based decision-making.

## Technologies

- Python
- Polars
- PySpark
- Plotly
- n8n
- TVmaze API
- Machine Learning

## Key Features

- Real-world data collection using the TVmaze API
- Large-scale data processing and preparation
- Data cleaning and transformation
- Feature engineering
- Statistical analysis
- High vs. Low Rated classification
- Interactive data visualization
- Data-driven insights and reporting
- Automated API data collection and processing using n8n
- Automated CSV generation

## Data Analysis

The project analyzes relationships between:

- Ratings
- Genres
- Runtime
- Popularity weight
- Premiere year
- Networks
- Countries

The analysis was used to identify patterns and characteristics associated with higher-rated TV shows.

## Machine Learning

A classification approach was developed to classify TV shows into:

- High Rated
- Low Rated

The workflow included data preparation, feature engineering, training, and evaluation.

## Automation Workflow

The n8n workflow automates the data pipeline by:

1. Triggering the workflow on a schedule
2. Collecting TV show data from the TVmaze API
3. Handling API pagination
4. Cleaning and transforming the collected data
5. Creating machine learning features
6. Classifying shows as High Rated or Low Rated
7. Converting the processed data into CSV format
8. Saving the final dataset

## Insights & Reporting

The project transformed complex Big Data into meaningful analytical insights through statistical analysis, visualizations, and reporting.

The results provide an overview of TV show patterns and help identify characteristics associated with higher ratings, supporting data-driven content analysis and decision-making.

## Project Files

- `TVmazeABFinal.ipynb` – Data analysis and machine learning notebook
- `FinalSubmissionHalaAlatoomN8N.json` – n8n automation workflow
- `BigDataAnalyticsandVisualization1HalaAlatoom (1).pdf` – Full project report
