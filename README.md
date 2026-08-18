# Tourism in Poland 2025 - Power BI
Interactive Power BI analysis of tourism in Poland based on official Statistics Poland (GUS) data.
## Live report

[▶ View interactive Power BI report]([https://app.powerbi.com/view?r=eyJrIjoiYjVkZTg1NjgtNzkzZC00NGJlLTgxODMtZDdjMGE1MTc4NDM5IiwidCI6IjNkZmU5YWI2LTgxYmYtNDkxYy1iNjcwLTAxYzgyNGEwOWUxOSJ9&embedImagePlaceholder=true)

## Dashboard preview

![Tourism in Poland 2025 Power BI dashboard](images/overview.png)

## Project overview

This project analyses tourism in Poland in 2025 using official data from Statistics Poland (GUS).

The report focuses on tourism demand, domestic and international visitors, regional differences, accommodation capacity and seasonal patterns.

The goal was to transform multiple statistical datasets into a clear and interactive Power BI report that allows users to explore both national and regional tourism trends.

## Key questions

- How did tourism in Poland change compared with 2024?
- Which regions attract the most tourists?
- What is the share of domestic and international tourism?
- Which countries generate the most foreign visitors?
- How seasonal is tourism in Poland?
- How do accommodation capacity and utilization differ across regions?

## Key insights

- Poland recorded approximately 42.7 million tourists stayed in registered accommodation establishments in Poland in 2025, around **10% more than in 2024**.
- Domestic tourists accounted for approximately **79% of tourists using accommodation establishments**, compared with **21% international tourists**.
- The number of accommodation establishments increased by approximately **7.3%**, indicating faster growth in capacity than in tourism demand.
- July and August together generated around **30% of annual overnight stays**, confirming strong seasonality.
- Despite growing tourist volumes, the **average length of stay decreased**, suggesting a shift toward shorter trips.

## Data source

The analysis is based on official data from **Statistics Poland (GUS)**, primarily from the Local Data Bank (BDL).

The datasets cover tourism demand, domestic and international tourists, overnight stays, accommodation establishments, occupancy rates and regional population statistics.

Data for different time granularities and territorial levels were transformed and integrated in Power Query before being loaded into the Power BI data model.

## Data model

The Power BI model combines multiple fact tables with shared dimension tables, allowing analysis by time, region, country of origin and tourism indicators.

Main dimensions:
- `DimDate`
- `Dim_Terytorium`
- `Dim_Kraje`
- `Dim_Wskaźnik`

The model separates monthly and annual statistics where necessary to avoid incorrect aggregation and double counting.
