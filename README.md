# Olist Delivery Performance & Customer Experience

A Tableau project exploring delivery reliability and customer ratings
using the Olist Brazilian E-Commerce dataset.

## Business questions

- How frequently do orders arrive late?
- How does late delivery rate vary across states and months?
- How do customer ratings differ between late and on-time deliveries?

## Key findings

| Metric | Result |
|---|---:|
| Eligible delivered orders | 96,470 |
| Late orders | 6,534 |
| Late delivery rate | 6.77% |
| Median delay among late orders | 7 days |
| Average rating — late deliveries | 2.27 / 5 |
| Average rating — on-time deliveries | 4.29 / 5 |

Late deliveries were associated with customer ratings 2.02 points
lower than on-time deliveries. This comparison does not establish causation.

## Dashboard

The dashboard includes headline KPIs, late delivery rates by state
and purchase month, and customer ratings by delivery status.

[Download the Tableau packaged workbook](Olist_Delivery_Performance_Mayank_Barala.twbx)

Download the file and open it in Tableau to explore the dashboard.
The packaged workbook includes the prepared data.

## Methodology

- Analysis uses one row per order.
- Delivery metrics include delivered orders with both actual and
  estimated delivery dates.
- Orders are late when the actual delivery calendar date is after
  the estimated delivery calendar date.
- Late delivery rate = late orders / eligible delivered orders.
- Median late delay includes late orders only.
- The monthly chart groups orders by purchase month and includes
  months with at least 100 eligible deliveries.
- Rating averages exclude missing review scores.

## Business implications and limitations

Investigate states with high late delivery rates alongside their
order volumes to prioritize operational reviews.

The data describe historical performance. Small state samples and
incomplete delivery outcomes for recent purchase cohorts can affect
comparisons. These findings do not measure current Olist performance.

## Data source

[Olist Brazilian E-Commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

Historical data from 2016–2018, provided by Olist under
CC BY-NC-SA 4.0. The included data were prepared for this analysis.

## Author

Mayank Barala
