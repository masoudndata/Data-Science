**Context**<br/>
**Data description**

The FAOSTAT Temperature Change domain disseminates statistics of mean surface temperature change by country, with annual updates. The current dissemination covers the period 1961–2019. Statistics are available for monthly, seasonal and annual mean temperature anomalies, i.e., temperature change with respect to a baseline climatology, corresponding to the period 1951–1980. The standard deviation of the temperature change of the baseline methodology is also available. Data are based on the publicly available GISTEMP data, the Global Surface Temperature Change data distributed by the National Aeronautics and Space Administration Goddard Institute for Space Studies (NASA-GISS). Here we try to predict the change in average global temperature for the next 15 years with a Facebook's Prophet model.

![2019-Temp](https://user-images.githubusercontent.com/50455870/132024754-181f892c-7708-4948-bb70-7cba4e53e56f.jpg)

**Prophet**<br/>
Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. <br/>
· Seasonal effects caused by human behavior: weekly, monthly and yearly cycles, dips and peaks on public holidays.<br/>
· Changes in trend due to new products and market events.<br/>
· Outliers.

In its essence, Prophet library utilizes the additive regression model y(t) comprising the following components:<br/>
y(t)=g(t)+s(t)+h(t)+ϵt,<br/>
where:<br/>
· Trend g(t): models non-periodic changes.<br/>
· Seasonality s(t): represents periodic changes.<br/>
· Holidays component h(t): contributes information about holidays and events.<br/>
 
 Because there are some missing values in almost all of these time series columns. 
