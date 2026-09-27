# Heat_Index_Assam_District-wise


This repository contains the Python-based analytical framework and implementation code for evaluating biometeorological human thermal stress across the 33 administrative districts of Assam. Utilizing 34 years of time-series data (1991–2025) from the NASA POWER database, this project quantifies climate vulnerability by analyzing the joint physiological impact of ambient temperature and atmospheric moisture rather than relying solely on raw environmental temperatures.   
# Key Methodologies Implemented:
* **Heat Index Computation:** Calculates physiological apparent ('feels-like') temperature utilizing the Steadman framework and Rothfusz polynomial regression.
* **Trend Detection:** Employs the non-parametric Mann-Kendall test and Theil-Sen robust slope estimator to quantify the magnitude and direction of monotonic climatic shifts.
* **Spatial Autocorrelation:** Uses Global Moran's I alongside Local Indicators of Spatial Association (LISA) to identify significant spatial dependencies and map localized thermal hotspots and coldspots.
* **Geographically Weighted Regression (GWR):** Examines spatial non-stationarity and local environmental relationships to account for Assam's complex topographical matrix.
* **Extreme Value Analysis (EVA):** Applies the Gumbel distribution to forecast recurrence probabilities and extreme thermal return periods for 10, 25, and 50-year thresholds (projecting up to 2075).
# Core Findings Highlighted in the Data:
* Apparent warming rates significantly outpace actual air temperature increases across 28 districts.
* The southwestern riverine corridor, specifically South Salmara Mancachar and Goalpara, forms an acute High-High thermal hotspot.
* Projections indicate 50-year extreme apparent temperatures will exceed 35°C in highly vulnerable southern and southwestern districts, whereas elevated terrains like Dima Hasao, Biswanath, and Sonitpur function as thermal refugia with thresholds remaining below 31.25°C.
  

This empirical framework provides data-driven benchmarks intended to guide the development of district-specific Heat Action Plans and localized climate resilience strategies. All experiments and code within this repository were designed for execution in Google Colab utilizing an NVIDIA T4 Tensor Core GPU. 
