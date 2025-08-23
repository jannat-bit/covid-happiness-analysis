🌍 COVID-19 & World Happiness Report Analysis
This project analyzes the relationship between COVID-19 confirmed cases, deaths, and happiness indicators such as GDP per capita, social support, and life expectancy.
We merge the Johns Hopkins COVID-19 dataset with the World Happiness Report (2020) and explore patterns using Python (pandas, seaborn, matplotlib).
📂 Dataset Sources
COVID-19 Data: Johns Hopkins University CSSE (time series confirmed cases & deaths)
World Happiness Report 2020: happiness data
🛠️ Technologies Used
Python 3.x
pandas (data cleaning & transformation)
matplotlib & seaborn (visualization)
Jupyter Notebook
🔍 Analysis Steps
Load COVID-19 confirmed cases and deaths datasets
Melt (reshape) the wide-format data into time-series format
Aggregate daily values → yearly totals per country
Merge with 2020 World Happiness Report
Create visualizations, e.g.:
Scatterplots: GDP per capita vs COVID deaths (color = Happiness score)
Correlations between happiness metrics and pandemic impact
