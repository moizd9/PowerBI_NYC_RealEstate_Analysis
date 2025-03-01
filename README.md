# NYC Real Estate Analysis using Power BI

# 📋 Project Overview
This project presents an in-depth analysis of the residential real estate market in the Bayside neighborhood of Queens, NYC, using Power BI. The objective was to provide actionable insights for a real estate brokerage firm considering opening an office in Bayside. The analysis included importing data from a SQL database, data cleaning, creating a star schema, and performing revenue and forecast analyses to assess the market potential.

# 🏗️ Key Objectives
- Analyze historical real estate trends in Bayside.
- Evaluate key performance indicators (KPIs) for market performance.
- Conduct revenue analysis for potential earnings.
- Perform forecast analysis to predict future market trends.
- Provide data-driven recommendations for real estate investment.

# 📊 Analysis Breakdown

**Data Preparation and Cleaning**

- Imported NYC real estate data from metsql.database.windows.net.
- Cleaned data by removing illogical values (e.g., sale prices of $0, $10).
- Established a star schema by connecting Neighborhood ID, Borough ID, and Building Code ID.

**Key Performance Indicators (KPIs)**

- Analyzed residential sales volume for Bayside in 2021, totaling 850 transactions.
- Assessed market performance from 2017 to 2021, identifying a dip in 2019 due to the COVID-19 pandemic, followed by a sharp recovery in 2020 and 2021.
- Compared sales performance across boroughs, highlighting Queens as the 3rd highest in total sales with $185 billion.

**Revenue Analysis**

- Created a revenue column using DAX:
- Revenue = NYC_TRANSACTION_DATA[SALE_PRICE] * 0.05 * 0.125
- Estimated revenue for real estate firms in Bayside at $4.41 million in 2021.

**Forecast Analysis**

- Conducted forecast analysis using Power BI to predict future sale prices.
- The forecast indicated a continued upward trend, suggesting positive market growth for Bayside.
- Included a confidence interval to account for market fluctuations.

**Key Insights**

- Resilience During Economic Downturns: Bayside’s market remained stable during the 2020 pandemic, unlike other neighborhoods.
- Future Growth Potential: Positive forecast trends and stable historical performance make Bayside an attractive investment.
- High Revenue Potential: Significant revenue opportunities due to stable pricing and high sales volume.

**Recommendations and Conclusion**

- Recommended opening a real estate office in Bayside based on its stability and growth potential.
- Suggested focusing on "Two Stories - Detached SM or MID" property types due to their high revenue generation.
- Advised continued monitoring of market trends and potential economic uncertainties.

# 🛠️ Tools Used

- Power BI: For data cleaning, visualization, and forecasting.
- SQL: For data extraction from a remote server.
- DAX: For custom calculations and revenue estimation.

# 📈 Key Figures

- Total Sales in 2021: 850 transactions.
- Estimated Revenue: $4.41 million.
- Market Performance: Queens ranked 3rd with $185 billion in sales.
- Forecast Trend: Positive growth in sale prices for the coming years.
