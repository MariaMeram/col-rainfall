# col-rainfall

I am from Antioquia, and this year Colombia has experienced many climate disasters due to intense rainfall. This situation made me curious to analyze which places in Colombia, and specifically within Antioquia, have been the most affected over the last five years.

The dataset I am working with contains rainfall and precipitation anomaly information for different administrative regions across Colombia, identified by unique PCODE values, over a multi-year period. The RFQ values in the dataset are averages calculated from historical rainfall records collected since the start year of the reference climatology (1981-2018).

Each record represents a specific date and geographic area, providing detailed precipitation measurements alongside historical averages and derived anomaly indicators.

<h3>Key variables in the dataset include:</h3>

date – Observation date in day/month/year format, typically at 10-day intervals.

adm_level and adm_id – The administrative level and its unique identifier.

PCODE – Standardized location code, allowing grouping or filtering by region.

n_pixels – Number of spatial grid cells covering the area in the precipitation dataset, indicating spatial coverage and data density.

<h3>Rainfall metrics (in millimeters):</h3>

rfh, r1h, r3h – Observed rainfall amounts over different aggregation periods, likely half-month, 1-month, and 3-month windows.

rfh_avg, r1h_avg, r3h_avg – Historical averages for each period, based on long-term climatological data.

<h3>Anomaly indicators (percentages):</h3>

rfq – Rainfall anomaly for the half-month period. A value of 100% means rainfall equal to the historical mean, values above 100% indicate wetter-than-average conditions, and values below 100% indicate drier-than-average conditions.

r1q and r3q – Similar anomalies for 1-month and 3-month periods.

<h3>The page where i downloaded the data is: https://data.humdata.org/dataset/col-rainfall-subnational </h3>
