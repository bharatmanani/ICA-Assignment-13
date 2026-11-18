# 1. Attempt: calculations and referee's note

## A. Dataset and method

The file contains 96 rows: four items, two cities, and twelve weekly dates. Prices are in illustrative PKR per kg. For each item, mean and median were calculated across all 24 item-city observations. First-to-last percentage change was calculated using the average of the two cities on the first date and the average of the two cities on the last date:

`percentage change = ((last-date average - first-date average) / first-date average) × 100`

## B. Results

| Item | Observations | Mean (PKR/kg) | Median (PKR/kg) | First-date average | Last-date average | First-to-last change |
|---|---:|---:|---:|---:|---:|---:|
| Staple A | 24 | 111.17 | 111.75 | 104.00 | 117.50 | +12.98% |
| Oil B | 24 | 324.83 | 324.00 | 301.00 | 347.00 | +15.28% |
| Pulse C | 24 | 205.92 | 206.00 | 203.00 | 210.50 | +3.69% |
| Sweetener D | 24 | 166.75 | 166.75 | 152.00 | 181.50 | +19.41% |

## C. Referee's note (O/E/C labels)

**O — Observation:** In this illustrative twelve-week dataset, the average price of all four items was higher at the final date than at the first date.

**O — Observation:** Sweetener D had the largest first-to-last percentage increase, at approximately 19.41%.

**O — Observation:** Pulse C had the smallest first-to-last percentage increase, at approximately 3.69%.

**O — Observation:** Oil B had the highest overall mean price, approximately PKR 324.83 per kg, while Staple A had the lowest overall mean, approximately PKR 111.17 per kg.

**E — Possible explanation:** The differences in percentage change may reflect item-specific supply, demand, seasonal, or transport conditions, but this dataset does not contain evidence that identifies which explanation is correct.

**O — Observation:** For each item, the mean and median are close in this dataset. For example, Staple A's mean is PKR 111.17 and its median is PKR 111.75.

**E — Possible explanation:** The closeness of the mean and median suggests that extreme observations are not pulling the average far away from the middle in this particular sample. It does not prove that there are no unusual observations.

**C — Causal claim:** These data do not establish that inflation, fuel prices, weather, government policy, or any other cause produced the increases. The file contains prices only, not causal evidence.

**O — Observation:** The CSV explicitly identifies itself as illustrative teaching data and not actual PBS observations.

**C — Causal claim:** It would therefore be misleading to describe these results as official Pakistani market-price movements or as proof of what happened in real markets.

## D. What do the two averages tell us?

The mean uses every observation and is useful for describing the arithmetic average price across the recorded city-weeks. The median is the middle observation after sorting the prices and is less affected by unusually high or low values. Neither statistic alone describes the full distribution or proves what a “typical” household paid. The mean and median are close here, so they tell a similar central-value story, but the time trend and differences between items still matter.

## E. Flagged-value limitation 
