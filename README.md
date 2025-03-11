# EV-Sales-Analysis-TSA
In this project I used SARIMA architecture to train a model which forecasts the number of registrations of EV in India in year 2023. The Data is collected from https://vahan.parivahan.gov.in/vahan4dashboard/vahan/view/reportview.xhtml. 

Used Seasonal-Trend Decomposition using LOESS (STL) method to break the original series into its trend, seasonal and residual components. 
It gives the seasonality and any anomaly in the original series. In this case anomaly is the time period of COVID-19 during which no or very few registration were made.

As the analysis goes by we can also see that the major sales growth in EV occured just after the COVID-19 period.
