# Analysis-of-Drug-situation-in-Thailand

This project aims to **analyze historical trends and forecast future trends in drug-related issues in Thailand**, focusing on the number of drug suspects and individuals receiving treatment. The analysis utilizes time series modeling (ARIMA), correlation analysis, linear regression, and simple growth models to understand the dynamics of the problem at both national and provincial levels. The ultimate goal is to provide insights that can inform strategies for prevention, suppression, and treatment of drug addiction in Thailand.

## Key Findings
* A continuous and rapid increase in the number of drug suspects across Thailand.
* The growth rate of drug suspects significantly outpaces the growth rate of individuals receiving treatment, suggesting a potential inadequacy in treatment capacity.
* Heatmap analysis reveals a concentration of drug-related issues in border regions, particularly the Northeast, Central, and South.
* Specific provinces, such as Nong Bua Lamphu and Saraburi, exhibit alarmingly high growth rates in drug suspects.
* While the number of treatment patients is projected to increase, the rate is considerably lower than the increase in suspects.
* There is a clear imbalance between the growing number of drug suspects and the capacity of the treatment system.

## Methodology
1. **Data Collection:** Gathered historical data on the number of drug suspects and treatment patients from 2017 to 2021.
2.  **Time Series Forecasting (ARIMA):** Utilized ARIMA models to forecast future trends in the number of drug suspects and treatment patients at the national level for the years 2022-2026.
3.  **Correlation Analysis:** Examined the correlation between the treatment and suspect datasets to understand their relationship.
4.  **Linear Regression:** Used the ARIMA forecast for treatment as a key variable to analyze the potential treatment capacity needed by 2026.
5.  **Simple Growth Model:** Applied a simple growth model to project treatment and suspect numbers at the provincial level.
6.  **Data Visualization:** Employed Looker Studio and Python libraries (Matplotlib, Seaborn) to visualize trends, growth rates, and geographical distribution of the drug problem. Heatmap analysis was used to identify high-risk areas.
7.  **Provincial Analysis:** Focused on identifying the top provinces with the highest growth rates for both suspects and treatment patients.
