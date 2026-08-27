---
title: "Climate Hazards Center - UC Santa Barbara"
source: "https://www.chc.ucsb.edu/data/chirps-gefs"
author:
published:
created: 2026-08-26
description:
tags:
  - "clippings"
---
Data Update (July 2026): CHC now exclusively produces the CHIRPS3-GEFS forecast data product, which uses [CHIRPS version 3](https://chc.ucsb.edu/data/chirps3) for bias correction. CHIRPS2-GEFS data production ended on July 1, 2026. This change is in line with this being the final year of CHIRPS version 2 data production. December 2026 will be the final month of CHIRPS2 data.

![Latest CHIRPS3-GEFS 15-day global precipitation anomaly forecast](https://data.chc.ucsb.edu/products/CHIRPS-GEFS/v3/15_day/latest_pngs/c3g_anom_global.png)

CHIRPS-GEFS is a bias-corrected and downscaled version of NCEP Global Ensemble Forecast System (GEFS) version 12 precipitation forecasts. The GEFS data is adjusted to match the historical distribution of the CHIRPS dataset using quantile matching. The resulting 5-day to 15-day precipitation forecasts support users producing timely impact assessments of forecast rainfall amounts and anomalies, as well as potential changes to agro-climatological or hydrological situations that are being monitored with CHIRPS data.

### CHIRPS-GEFS Forecasts

### Daily 5-day, 10-day, 15-day Forecasts

> **5-day**
> 
> - Total [Image](https://data.chc.ucsb.edu/products/CHIRPS-GEFS/v3/05_day/latest_pngs/c3g_total_global.png) [Data](https://data.chc.ucsb.edu/products/CHIRPS-GEFS/v3/05_day/global/data/)
> - Anomaly [Image](https://data.chc.ucsb.edu/products/CHIRPS-GEFS/v3/05_day/latest_pngs/c3g_anom_global.png) [Data](https://data.chc.ucsb.edu/products/CHIRPS-GEFS/v3/05_day/global/anom/)

> **10-day**

> **15-day**

### Daily, Pentadal, and Dekadal Forecasts

> **Daily Forecasts**
> 
> - Total [Data](https://data.chc.ucsb.edu/products/CHIRPS-GEFS/v3/daily/global/)

> **Pentadal Forecasts**
> 
> - Lead 0 [Total](https://data.chc.ucsb.edu/products/CHIRPS-GEFS/v3/pentad_lead_0/global/data/) [Anomaly](https://data.chc.ucsb.edu/products/CHIRPS-GEFS/v3/pentad_lead_0/global/anom/)
> - Lead 1 [Total](https://data.chc.ucsb.edu/products/CHIRPS-GEFS/v3/pentad_lead_1/global/data/) [Anomaly](https://data.chc.ucsb.edu/products/CHIRPS-GEFS/v3/pentad_lead_1/global/anom/)
> - Lead 2 [Total](https://data.chc.ucsb.edu/products/CHIRPS-GEFS/v3/pentad_lead_2/global/data/) [Anomaly](https://data.chc.ucsb.edu/products/CHIRPS-GEFS/v3/pentad_lead_2/global/anom/)

> **Dekadal Forecasts**
> 
> - Lead 0 [Total](https://data.chc.ucsb.edu/products/CHIRPS-GEFS/v3/dekad_lead_0/global/data/) [Anomaly](https://data.chc.ucsb.edu/products/CHIRPS-GEFS/v3/dekad_lead_0/global/anom/)

### CHIRPS-compatible GEFS precipitation forecasts for anticipating flood and drought hazards

CHIRPS-GEFS unites key precipitation observation and forecast resources to support more streamlined situation assessments and hazards early warning. CHIRPS-GEFS forecasts are provided with compatible spatial characteristics and statistical distributions that facilitate their “inter-operation” with CHIRPS.

Operational CHIRPS-GEFS data are a bias-corrected 0.05-degree version of the GEFS real-time 00 UTC ensemble mean forecasts for total precipitation. The 16-day GEFS forecasts are bias-corrected to match the CHIRPS historical distribution using quantile matching. The procedure identifies how the forecast 16-day total ranks historically, compared to historical GEFS forecasts from 2001 to present for the same 16-day period. Using that rank-based percentile, an amount corresponding to the same percentile of the CHIRPS 16-day data distribution is identified. The new forecast thus retains important information from the GEFS, including the advanced weather forecasting ability of the GEFS version 12 system and the historical extremity of the current forecast, while also now aligning with the CHIRPS’ historical variance and high-quality 5-km resolution climatology.

The GEFSv12 FV3 Phase II “reforecast” data are produced by NCEP/EMC and are described in [Guan et al., (2022)](https://journals.ametsoc.org/view/journals/mwre/150/3/MWR-D-21-0245.1.xml) and [Hamill et al., (2022)](https://journals.ametsoc.org/view/journals/mwre/150/1/MWR-D-21-0023.1.xml). More information on the GEFS is available at [this link](https://www.emc.ncep.noaa.gov/emc/pages/numerical_forecast_systems/gefs.php).

### Accessing CHIRPS-GEFS

Forecast data are provided for several time periods to support users. The table above provides links to the latest forecasts and to a historical data archive for most time periods, in GeoTIFF format (0.05-degree, 60°N to 60°S, 180°W to 180°E). CHIRPS-GEFS data is available here for download and through the Early Warning Explorer.

CHIRPS version 3 data, released in 2025, is the primary operational CHIRPS dataset used by CHC. To support current and future users, CHC operationalized a CHIRPS-GEFS datastream calibrated to CHIRPS3. Historical and current forecasts using CHIRPS3 are identified with filenames of “c3g” and “CHIRPS3-GEFS”. The links above show CHIRPS3-GEFS data. The CHIRPS-GEFS based on CHIRPS version 2 can be accessed [here](https://data.chc.ucsb.edu/products/CHIRPS-GEFS_precip_v12/), although operational updates ended on July 1, 2026. Data users are encouraged to continue their applications using the CHIRPS3-GEFS historical archive and continuing daily CHIRPS3-GEFS data updates.

**Data Update Schedule:** 5-day, 10-day, and 15-day CHIRPS-GEFS are updated daily. Dekads and pentads periods are updated on the first day of each period (every ~5 to 10 days). Total precipitation values are available for all increments, and anomalies are available for all increments except daily.

**Data Notes:** The CHIRPS3-GEFS data archive begins January 2001, which is one year later than the original CHIRPS-GEFS data that was based on CHIRPS2. This is to align with the first complete year of the satellite-disaggregated version of CHIRPS3 daily data. CHIRPS3 provides two versions of daily data that differ with respect to which additional satellite (IMERG-Late v07) or reanalysis (ECMWF ERA5) data product is used for assigning the pentadal (~5-day) rainfall total to individual days. The rainfall total for a CHIRPS3 pentad is the same in both versions of CHIRPS3 daily data. To avoid partial years, 2020 is not included in the CHIRPS3-GEFS archive due to the nine month gap between the GEFS reforecast and the operational forecasts during that year.

### How to cite this data

This page is the registered CHIRPS-GEFS data repository. The assigned DataCite DOI doi:10.15780/G2PH2M.

Please cite CHIRPS-GEFS data as: CHIRPS-GEFS Precipitation Forecasts [https://doi.org/10.15780/G2PH2M](https://doi.org/10.15780/G2PH2M) (2021). Data was accessed on \[DATE\].

Harrison, L., Landsfeld, M., Husak, G. et al. Advancing early warning capabilities with CHIRPS-compatible NCEP GEFS precipitation forecasts. Sci Data 9, 375 (2022). [https://doi.org/10.1038/s41597-022-01468-2](https://doi.org/10.1038/s41597-022-01468-2)

### CHIRPS-GEFS in Action

- CHIRPS-GEFS is used in [CHC Early Estimates](https://chc.ucsb.edu/monitoring/early-estimates), a data and map resource for monitoring seasonal precipitation and agro-climatological hotspots. The CHC Early Estimates [Recent Rainfall Monitor](https://chc.ucsb.edu/monitoring/early-estimates) and [Seasonal Rainfall Monitor](https://chc.ucsb.edu/monitoring/early-estimates/seasonal) show rainfall accumulations for recent time periods based on the CHIRPS final and preliminary data. The “+ Forecast” version includes the CHIRPS-GEFS 15-day forecast.
- Monthly [GEOGLAM Crop Monitor](https://cropmonitor.org/) for Early Warning bulletins. CHIRPS-GEFS are used for evaluating rainfall conditions and for highlighting areas of concern in Regional Outlooks.
- A partnership with the [Ethiopian Meteorological Institute (EMI)](http://www.ethiomet.gov.et/) results in a [dekadally-updated bulletin](https://chc.ucsb.edu/monitoring/ethiopia) highlighting the current conditions by blending CHIRPS with data from the EMI's private station network. Outlooks in these reports use CHIRPS-GEFS forecasts and historical rainfall.
- CHIRPS-GEFS has potential for flood early warning, with an example shown here: [Blending CHIRPS Data and GEFS Forecasts for an Enhanced Rainfall Forecast Product](https://www.nasaharvest.org/news/a-hrefhttpsnasaharvestorgnewsblending-chirps-data-and-gefs-forecasts-enhanced-rainfall-forecast-productblending-chirps-data-and-gefs-forecasts-for-an-enhanced-rainfall-forecast-producta)
- Examples of CHIRPS-GEFS in early warning for the [March-to-May 2019 Eastern Horn drought](https://www.agrilinks.org/post/climate-hazards-center-early-estimates-and-east-africa-march-may-2019-drought), including generation of combined forecast seasonal rainfall scenarios.
- A video presentation of Dr. Chris Funk showcasing a number of products for southern Africa is available on the [CHC YouTube channel](https://www.youtube.com/watch?v=x5p1-NXifo4) here.
- Examples of CHIRPS-GEFS incorporated in operational monitoring of the [2018/19 growing season over Southern Africa](https://blog.chc.ucsb.edu/?p=525) can be found here.
- CHIRPS-GEFS, and other data available through the [Early Warning Explorer](https://chc.ucsb.edu/tools/ewx), have been featured in [Tanzania Ministry of Agriculture](https://www.kilimo.go.tz/index.php/en) National Food Security bulletins.
- SERVIR’s ClimateSERV portal has featured CHIRPS-GEFS data. [ClimateSERV](https://climateserv.servirglobal.net/map) tools include user-defined boundaries for spatial data extraction and historical time series.

*For comments or inquiries, please contact William Turner at [will.turner@geog.ucsb.edu](mailto:will.turner@geog.ucsb.edu)*

CHIRPS-GEFS is in the public domain, as registered with Creative Commons, and is under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/). To the extent possible under the law, the Climate Hazards Center has waived all copyright and related or neighboring rights to CHIRPS-GEFS. This work is published from: the United States.