# About:
### This project is a time series analysis of interest in Mariah Carey over time. Weekly data is gathered from google trends. Each week, there is a relative score (0-100) that reflects the google searches of the keyword (Mariah Carey).
# Contents
## SRC 
### Installing Code: All code used is in the SRC folder. To load in the datasets, the paths will need to be changed to local one.
### Usage of Code: Once the repository is cloned: the source code should be ran in the following order after changing the data paths.
| File | Description |
| --- | --- |
| MariahCarey_EDA.ipynb | Shows some exploratory plots for our dataset
| Mariah Carey Time Series.ipynb | Includes the mathematical model developed for the time series
| MariahCarey_Forecasting.ipynb | Includes the ARIMA model developed for the time series
## Data
| Data file | Description |
| --- | --- |
| merged_data.csv | Dataset with all of our target searches |
| MC_math_model | Includes polynomial and sinusoidal features used for the math model |
| Mariah_Carey_Data.csv | Interest in Mariah Carey over time |
| Christmas_Data.csv | Interest in Christmas over time |
| AIWFC_Data.csv | Interest in "All I Want For Chrismas" over time | 
| memes.csv | Interest in memes over time |

## Figures
| Figure | Description |
| --- | --- |
| AIWFC vs. Mariah Carey.png | Interest in AIWFC and Mariah Carey |
| All Data.png | Interest in all target searches |
| MC_decomp.png | Interest in Mariah Carey decomposed into trend, seasonal and noise |
| MC_forecast_long.png | A short term forecast of interest in Mariah Carey |
| MC_forecast_short.png | A long term forecast of interest in Mariah Carey |
| MC_math_model.png | Our mathematical model for interest in Mariah Carey |

## References
### [1] https://towardsdatascience.com/an-end-to-end-project-on-time-series-analysis-and-forecasting-with-python-4835e6bf050b
### [2] https://trends.google.com/trends/
