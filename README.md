# Blinkit PowerBI Dashboard

## Project Overview

This repository contains a **PowerBI Dashboard** that provides real-time data analytics and insights for **Blinkit** (formerly known as Grofers). The dashboard enables users to visualize key business metrics, such as order volumes, delivery performance, customer satisfaction, and inventory levels, and derive insights to optimize business operations.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [Contributing](#contributing)
- [Contact](#Contact)

## Features

- **Order Metrics**: Track daily, weekly, and monthly order volumes.
- **Delivery KPIs**: Monitor on-time delivery rates, average delivery time, and performance by delivery region.
- **Inventory Monitoring**: Real-time visualization of stock levels, item availability, and stock movement.
- **Customer Analytics**: Insights into customer behavior, satisfaction ratings, and repeat orders.
- **Data Filters**: Dynamic filtering by region, time range, product category, and other parameters.
  
## Prerequisites

To run this project, you will need:
- **Power BI Desktop**: Version `2.96.x` or later. [Download Power BI Desktop](https://powerbi.microsoft.com/desktop)
- **Blinkit API Access** (Optional): For real-time data integration.
- **Sample Dataset**: Provided in the `data/` folder (optional).
- **Basic knowledge of Power BI**.

## Installation

1. **Clone this repository**:
    ```bash
    git clone https://github.com/yourusername/Blinkit-PowerBI-Dashboard.git
    cd Blinkit-PowerBI-Dashboard
    ```

2. **Open the PowerBI file**:
    - Download the `Blinkit_PowerBI_Dashboard.pbix` file from the repository.
    - Open it using **Power BI Desktop**.

3. **Connect to Data**:
    - The dashboard uses mock data by default. To connect to real Blinkit data, configure the data source settings in Power BI Desktop:
      - Go to `Transform Data` > `Data Source Settings`.
      - Update the data source credentials or API endpoint for real-time data.

4. **Set up the Blinkit API (Optional)**:
    - Obtain API keys from Blinkit to integrate live data. Configure API settings in Power BI by editing the data source and providing the appropriate credentials and API URL.

## Usage

Once the dashboard is opened and connected to the data, explore various tabs for detailed insights:
- **Orders Overview**: Visualizes order trends and patterns.
- **Delivery Performance**: Displays delivery KPIs, including delays and regional performance.
- **Inventory**: Tracks real-time stock levels, stockouts, and restocking trends.
- **Customer Satisfaction**: Analyzes customer ratings, feedback, and order history.

### Customization
Feel free to customize the PowerBI dashboard as per your specific business needs. You can add new measures, KPIs, and filters to suit your analysis.

## Data Sources

The dashboard can pull data from:
- **Blinkit Order API** (for real-time data).
- **CSV or Excel files** (as mock data for testing purposes).

To switch data sources, go to `Transform Data` > `Data Source Settings` in Power BI Desktop and update the source accordingly.

## Contributing

Contributions to enhance this dashboard are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a Pull Request.

## contact me 

[LINKEDIN](https://www.linkedin.com/in/nitish-kr-dash/)
