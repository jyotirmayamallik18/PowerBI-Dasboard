# PowerBI-Dasboard
HR &amp; SALES Dashboard
# Cafe Rewards & Customer Engagement Analytics Dashboard

An interactive Power BI project designed to analyze customer behaviour, cafe rewards offers, campaign performance, and customer engagement.

## Project Overview

This project uses customer, offer, and event data to generate actionable insights that support marketing decisions, customer targeting, and reward strategy optimization.

## Key Objectives

- Evaluate the effectiveness of different offers.
- Identify customer segments that respond positively to campaigns.
- Compare offer types and reward structures.
- Analyze customer engagement and offer-viewing behaviour.
- Develop data-driven recommendations for future campaigns.

## Dashboard Features

- **KPI Analysis:** Total customers, offers received, offers viewed, and offers completed.
- **Offer Performance:** Comparison of individual offers and offer types.
- **Customer Segmentation:** Analysis by age group, income group, and gender.
- **Engagement Analysis:** Identification of customer groups with lower engagement.
- **Reward Strategy:** Comparison of reward amounts, offer difficulty, and duration.
- **Interactive Filters:** Slicers for exploring customer segments and offer categories.

## Dataset

The project uses four datasets:

| Dataset | Description |
|---|---|
| `customers.csv` | Customer demographics and profile information |
| `offers.csv` | Offer types, rewards, difficulty, and duration |
| `events.csv` | Offer activity, customer interactions, and transactions |
| `data_dictionary.csv` | Dataset field definitions |

## Tools & Technologies

- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Data Modelling
- Interactive Data Visualization

## Data Model

The data model connects customer and offer information to customer activity.

- `Customers[customer_id]` → `Events[customer_id]`
- `Offers[offer_id]` → `Events[offer_id]`

These relationships enable interactive analysis across customer segments and offer performance.

## Key Performance Indicators

- Total Customers
- Total Offers
- Offers Received
- Offers Viewed
- Offers Completed
- Total Transactions
- Total Transaction Spend
- Offer View Rate
- Offer Completion Rate
- Average Transaction Value

## Business Insights

The dashboard supports decisions about:

- Which offers show stronger customer engagement.
- Which customer segments may be suitable for targeted campaigns.
- Which offer types deserve further testing.
- Where customer engagement needs improvement.
- How reward structures can be evaluated for future campaigns.

## How to Use

1. Download or clone this repository.
2. Open the `.pbix` file in Power BI Desktop.
3. Update the source file paths if necessary.
4. Refresh the dataset.
5. Use the dashboard visuals and slicers to explore the results.

## Limitations

The analysis identifies patterns in the supplied data and does not establish causation. Transaction amounts should not be attributed to individual offers without a reliable attribution method. Campaign profitability requires additional cost and revenue information.

## Conclusion

This project demonstrates the use of Power BI, Power Query, and DAX to transform customer and offer data into interactive business insights for campaign analysis, customer engagement, and reward strategy planning.

*Created for educational and analytical purposes.*
