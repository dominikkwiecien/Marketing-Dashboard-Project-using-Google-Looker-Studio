
# Marketing Dashboard Project using Google Looker Studio

## Overview

Welcome to the Marketing Dashboard project, a powerful tool designed to visualize and analyze marketing data using Google Looker Studio. This project leverages PostgreSQL as the data source and employs advanced custom queries to create a comprehensive dashboard that provides insights into key marketing metrics. This repository contains the setup, configuration, and details required to recreate and explore the dashboard.

## Project Link

Explore the live dashboard: [Marketing Dashboard on Google Looker Studio](https://lookerstudio.google.com/reporting/baafd531-a1cd-4911-97f0-d4032bfaf5d3)

## Features

This dashboard is designed to offer a clear, insightful view of marketing performance, with the following features:

### 1. Data Source Configuration
- **Database**: PostgreSQL
- **Custom Query**: Used to retrieve and process data based on a specific marketing dataset, with queries optimized for performance and relevance.

### 2. Key Metrics Visualized
- **Ad Spend**: Total expenditure on advertisements.
- **CPC (Cost Per Click)**: Average cost incurred for each click on the advertisement.
- **CPM (Cost Per Thousand Impressions)**: Cost associated with 1,000 ad impressions.
- **CTR (Click-Through Rate)**: Ratio of users who click on the ad to the number of total users who view the ad.
- **ROMI (Return on Marketing Investment)**: A measure of the profitability of marketing campaigns.

### 3. Visual Components
- **Combined Chart**: Displays the sum of Ad Spend and ROMI across months, with dates on the horizontal axis and metrics on two vertical axes, sorted from oldest to newest.
- **Line Chart**: Illustrates the number of active campaigns each month.
- **Table with Heatmap**: Features campaign names as dimensions and key metrics (Ad Spend, CPC, CPM, CTR, ROMI) as metrics, with heatmap coloring to highlight performance.

### 4. Interactivity
- **Filters**: Easily filter the dashboard by campaign name and date of advertisement display to focus on specific data points of interest.

## How to Use

1. **Clone the Repository**: 
   ```
   git clone https://github.com/yourusername/marketing-dashboard.git
   ```
2. **Access the Dashboard**: 
   - Follow the [link](https://lookerstudio.google.com/reporting/baafd531-a1cd-4911-97f0-d4032bfaf5d3) to view the live dashboard.
   - Use the interactive filters and visualizations to explore the data.

3. **Recreate the Dashboard**:
   - Open Google Looker Studio and create a new report.
   - Connect to your PostgreSQL database using the provided custom query.
   - Configure the dashboard following the steps outlined in this repository.

## Requirements

- **Google Account**: Required to access Google Looker Studio.
- **PostgreSQL Database**: To recreate the dashboard, you need access to a PostgreSQL database with relevant data.
- **Basic SQL Knowledge**: Understanding of SQL to modify and use the custom query.

## Conclusion

This project showcases the power of data visualization in Google Looker Studio, enabling marketers to make data-driven decisions by analyzing key performance metrics. The dashboard is interactive, user-friendly, and customizable, making it a valuable tool for any marketing team.

## Contributions

Contributions are welcome! Feel free to submit a pull request or open an issue to discuss improvements or suggest new features.
