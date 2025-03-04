# Cross-Border-Transactions-Insights-

## Overview
This project provides an in-depth analysis of wire transactions across the US, Canada, and Mexico using Power BI. The aim is to uncover insights into transaction patterns, trends, and key factors influencing transaction amounts. The data spans over the last two years and includes inbound and outbound transactions, sender and receiver countries, transaction amounts, and message types.

## Objectives
- To analyze transaction volumes and amounts over time.
- To compare inbound and outbound transactions for each country.
- To identify key factors influencing transaction amounts.
- To provide geospatial insights into transaction flows.
- To optimize performance using dataflows and incremental refresh.

## Key Insights
- Monthly and yearly trends in transaction volumes and amounts.
- Breakdown of transactions by sender and receiver countries.
- Identification of most common message types.
- Comparison of inbound vs. outbound transactions.
- Top transactions and their corresponding countries.
- Geospatial distribution of transactions and flows between countries.

## Tools & Skills
- **Power BI**: For creating visualizations and dashboards.
- **SQL**: To query and pull data from the enterprise data lake (EDL).
- **Power BI Dataflows**: To aggregate data and set up incremental refresh.
- **Data Transformation**: Converting transaction amounts to CAD using monthly exchange rates from the Canadian bank.
- **Performance Optimization**: Using dataflows and incremental refresh to handle large datasets efficiently.

## Instructions to Access
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Wire-Transaction-Analysis.git
   ```

2. **Open the Power BI Desktop File**:
   - Open `Wire-Transaction-Analysis.pbix` in Power BI Desktop.

3. **Data Source Connection**:
   - Ensure you have access to the enterprise data lake (EDL) and have set up the necessary gateway.
   - Update the connection settings in Power BI to connect to the SQL data source using your credentials.

4. **Incremental Refresh Setup**:
   - Incremental refresh is already set up in the dataflow to pull two years of aggregated data.
   - Ensure your Power BI service account has the necessary permissions to perform incremental refresh.

5. **Currency Conversion**:
   - The transaction amounts are converted to CAD using the monthly exchange rate from the Canadian bank.
   - Review the transformation steps in the Power Query Editor if needed.

6. **Publishing the Dashboard**:
   - After reviewing the dashboard, you can publish it to your Power BI service workspace.
   - Share the dashboard with relevant stakeholders for insights and decision-making.

## Dataflow Setup and Performance Optimization
- **SQL Query**: We used a SQL query to pull the data from the enterprise data lake (EDL) using a gateway.
- **Dataflow**: A dataflow was created to aggregate the data and set up incremental refresh to pull two years of aggregated data.
- **Incremental Refresh**: Incremental refresh was configured to optimize performance by only updating the new or changed data rather than refreshing the entire dataset.
- **Data Transformation**: The transaction amounts were converted to CAD using the monthly exchange rates from the Canadian bank to ensure consistency in reporting.

## Contact
For any questions or issues, please reach out to [your contact email].
