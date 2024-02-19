<b>Time Series Final Project<br>
Authors: Shubhangi Sharma, Akanksha Arun, Juhil Ahir, Tanvi Vijay<br>
Date: 2023-12-01<br>

This project focuses on analyzing and forecasting avocado sales data, specifically conventional and organic avocados in California.<br>

Initial Data Exploration<br>
We began by exploring the dataset using various visualization techniques and statistical analysis methods. Some key observations include:<br>

Initial plot analysis revealed no apparent trend, seasonality, level, or noise.<br>
Seasonal decomposition plots indicated a yearly seasonality component for both conventional and organic avocados.<br>
Boxplots and seasonplots provided insights into sales patterns and outliers.<br>
Modeling<br>
We utilized several modeling techniques, including linear models, naive forecasting, moving average models, ARIMA models, and incorporating price effects into the model. For each technique, we performed modeling and validation on both conventional and organic avocado sales data.<br>

Linear Models<br>
We fitted linear models with both additive and multiplicative trends and seasonality for both conventional and organic avocados. These models provided insights into the linear relationships between time and avocado sales.<br>

Naive and Seasonal Naive Forecasting<br>
We used naive and seasonal naive forecasting methods to generate forecasts based on historical observations. These methods served as simple benchmarks for comparison with more sophisticated models.<br>

Moving Average Models<br>
We explored moving average models, including centered and trailing moving averages, to smooth out noise and identify underlying trends in the data.<br>

ARIMA Models<br>
ARIMA models were employed to capture the autocorrelation and seasonality present in the data. We experimented with different orders and seasonalities to find the best-fitting models.<br>

Incorporating Price Effects<br>
Incorporating the effect of price on avocado sales, we integrated average price data into our models to improve forecasting accuracy.<br>

Forecasting<br>
Finally, we used the best-performing models to forecast avocado sales for the remainder of 2018. Both conventional and organic avocado sales were forecasted, considering the effects of seasonality and price.<br>

Conclusion<br>
Correlation between Demand and Price: The analysis reveals a robust correlation between avocado demand and price, indicating an inverse relationship. Fluctuations in price significantly impact demand, highlighting the importance of understanding and forecasting market dynamics for strategic pricing decisions.<br>

Peak Sales Period: The analysis identifies a consistent market trend where the same week in February witnesses peak sales for both conventional and organic avocados. This pattern suggests a strategic opportunity for pricing decisions to capitalize on historical surge in demand during this period.<br>

Avocado Harvest Season Impact: The avocado harvest season contributes to fluctuations in price and demand. Increased production leads to lower prices and subsequently higher demand. Conversely, external factors such as droughts and worker strikes can lead to price hikes and decreased demand.<br>

Impact of External Events: External events such as the Super Bowl have a noticeable impact on avocado demand, leading to increased sales. Conversely, factors like reduced production due to drought conditions can result in elevated prices and decreased demand.<br>

Implications for Strategic Planning: Understanding demand influencers like the Super Bowl and harvest cycles enables strategic planning for production and pricing. Forecasted values offer a roadmap for anticipating market trends and optimizing yield, providing actionable intelligence for informed decision-making.<br>
