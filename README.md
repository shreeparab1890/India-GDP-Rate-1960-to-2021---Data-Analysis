# India GDP Rate 1960 to 2021 - Data Analysis
This ipython notebook is the Exploratory data analysis (EDA) of the India GDP Rate 1960 to 2021. The dataset used has been compiled from various sources by web scrapping. You can follow the analysis on <a href="https://www.kaggle.com/code/shrikrishnaparab/india-gdp-rate-1960-to-2021-data-analysis">kaggle</a>

![GDP-India](gdp-india.jpg)

## Packeges Used:
 ![Python][python] ![NumPy][numpy-image] ![Pandas][Pandas-image] ![Matplotlib][Matplotlib-image]  ![Jupyter Notebook][ipython-image]
 
[python]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[numpy-image]: https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white
[Pandas-image]: https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white
[Matplotlib-image]: https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black
[ipython-image]: https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white

# What is Exploratory Data Analysis?
Exploratory Data Analysis (EDA) is a technique used to gain insights and understanding from a given dataset. It is an approach for analyzing and summarizing data that allows analysts to identify patterns, trends, and relationships within the data. EDA is typically the first step in the data analysis process and also is an iterative process that involves visualizing and summarizing the data in various ways.

The main goal of EDA is to develop a deeper understanding of the data and identify any potential issue or limitation. This process allows analysts to clean and prepare the data for further analysis, and can also reveal insights that can guide the analysis to move in a proper direction.

One of the key tools used in EDA is visualization. Visualizing data in various ways can reveal patterns and relationships that may not be immediately apparent when looking at raw data.  
Common visualizations used in EDA include:
  1. Histograms
  2. Scatter plots
  3. Box Plots
  4. Bar Charts
  5. Line Charts
  6. Pie Chart or Donut Chart
  7. Bubble Charts  
These visualizations can be used to identify outliers, patterns, and trends in the data, and can also be used to compare different subsets of the data.

Another important aspect of EDA is summarizing the data using statistical measures such as mean, median, standard deviation nd plotting the Corelation Matrix. These measures can be used to understand the distribution of the data and identify any potential outliers.

EDA can also include data cleaning and preprocessing, which is the process of identifying and correcting errors or inconsistencies in the data. This can include handling missing data, removing outliers, or transforming variables to make the data more suitable for analysis.

Overall, EDA is a crucial step in the data analysis process, as it allows analysts to gain a deeper understanding of the data and identify any potential issues or limitations before proceeding with more advanced analysis. It also can also be a great way to find the insights that can guide the further analysis.

## Gross Domestic Product (GDP)
Gross Domestic Product (GDP) is a measure of the economic activity of a country. It is the total value of goods and services produced within a country in a given period of time, typically a year. It is used to gauge the health of a country's economy and as a comparison tool between countries. It is also used to calculate other economic indicators such as Gross National Product (GNP) and Gross National Income (GNI).  

## GDP per capita
GDP per capita, which is calculated by dividing the Gross Domestic Product (GDP) of a country by its population, is commonly used as an indicator of the standard of living in a country. However, it is important to note that it has certain limitations as a measure of overall well-being. The GDP per capita does not account for factors such as income inequality and environmental sustainability, which can have a significant impact on a country's overall well-being.  

## GDP Growth Rate
The GDP growth rate is a measure of the change in a country's economic output over a specific period. It is commonly expressed as a percentage and is used to indicate the rate at which the economy is expanding. This measure is considered important by economic policymakers as it is believed to have a strong correlation with key policy objectives such as inflation and unemployment levels. The GDP growth rate is used as an indicator of a country's overall economic health and to compare the performance of different economies.

## The Task:
The task was to analyze the GDP Data of India and get some key insights about the GDP in India.

## The Process:
![Process](process.jpg)

## About Data:
The technique used for data collection is web scrapping and data is compiled in a CSV file. The CSV file consist of 4 Columns and has data from 1960 to 2021. 
Data Columns are:
    - Year = its Showing year of Indian GDP
    - GDP ( Billions of US $) = its showing GDP ( Billions of US $) per year
    - Per Capita= in this column per capita in rupees
    - Growth= showing changes in every year in %

## EDA (Data Analysis Results):
Please Go thorugh the ipython file for more in detail analysis, below are some key Details.

![year-wise-graph](Year-wise.jpg)

### Which is the year with minimum GDP Growth:
    We can see that the 2020 was the year with lowest GDP growth i.e. -6.6%. This may be because of the COVID-19 pandamic.
### Which are the 3 years which has seen lowest GDP Growth:
    We can see that 2020, 1979 and 1965 are the 3 years with lowest growth. 
    - 1965 was India - Pakistan War, 
    - 1979 had severe drought gripping most of the country and crude oil prices almost doubling due to Iranian Revolution which caused a disruption of oil supply.    Also, India just came out of emergency(1975-1977), 
    - 2020 was hit by the COVID 19 pandamic.
### Which is the year with Highest GDP Growth:
    - 1988 was the year with highest growth of 9.33%
### Which are the top years with highest GDP Growth:
    - 1988, 1975, 2021, 1999, 2010 were the top five years with highest growth.
### Which is the year with Highest Per Capita Income:
    - The Year 2021 is the year with highest GDP Per Capita Income of $2277



