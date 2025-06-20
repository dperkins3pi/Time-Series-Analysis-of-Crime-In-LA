# Project Abstract
Crime is a complex societal issue that impacts communities and individuals, requiring thoughtful analysis to inform effective policymaking. In this project, we analyze crime data in Los Angeles to identify trends, seasonal patterns, and factors influencing crime volume. Using a dataset containing millions of crime records from 2020 onward, we clean and structure the data for time series modeling. We decompose the time series into trend, seasonal, and residual components to better understand long-term patterns. An Autoregressive Integrated Moving Average (ARIMA) model is used to predict future crime trends. Additionally, we explore demographic factors associated with crime volume and type, highlighting correlations without implying causation. Our analysis reveals significant seasonal patterns, demographic disparities, and age-related disparities, providing insights that could guide policymaking and resource allocation by law enforcement and public safety officials

For more information, refer to [our paper](CrimeSeriesPaper.pdf)

![Detrended Series](DeTrendedSeries.png)

![Weekly Seasonal Component](WeeklySeasonalComponent.png)

![Weekly Seasonal Component](ARIMAPredictions.png)

The dataset can be found at https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8/about_data
