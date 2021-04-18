# GDP_analysis
## GDP analysis using Pandas and Seaborn python on World bank GDP data (Europe)
The gross domestic product (GDP) data for 10 central and eastern European countries, the analysis was prepared based on the World Bank Data, particularly the dataset [World Development Indicatiors](http://databank.worldbank.org/data/reports.aspx?source=world-development-indicators)
was utilized. This set contains many different economic development indicators you can choose from. 
For simplicity, I focused on four of them: GDP per capita ( US$), GDP per capita growth (annual %), GDP growth (annual %),  GDP (current US$).
> With Pandas [Pandas](http://pandas.pydata.org/) -
Data cleaning, manipulation and data transformation was done.
easy-to-use data structures and data analysis tools for python. Additionally, there are many visualizations, where some of them were
prepared with matplotlib but [regression plots](http://seaborn.pydata.org/generated/seaborn.lmplot.html) and 
[bar plots](http://seaborn.pydata.org/generated/seaborn.barplot.html) were created with [seaborn](http://seaborn.pydata.org/) library. 
>Basic Pandas concepts implemented in the project: 
[data frames](http://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.html), 
[data transformations with apply function](http://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.apply.html), 
[reshaping and pivot tables](http://pandas.pydata.org/pandas-docs/stable/reshaping.html) etc. 


## Project description 

**analyzing four GDP factors:**

* GDP per capita ( US$)
* GDP per capita growth (annual %)
* GDP growth (annual %)
* GDP (current US$) 


## Project structure

The project contains two files, first contains raw CSV data taken from World Bank website. The second file
is python script with all the pandas and seaborn code:  

* Europe_GDP.csv - data file, generated from World Bank Development Indicators
* pandas_GDP.py - main file with analysis and plots

---

### References and data collected
* http://databank.worldbank.org/data/reports.aspx?source=world-development-indicators
* http://seaborn.pydata.org/generated/seaborn.lmplot.html
* http://pandas.pydata.org/
* http://seaborn.pydata.org/
* https://plon.io/files/58bab9581b12ce00012bd610
* https://plon.io/files/58babdee1b12ce00012bd63a
* http://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.html
* http://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.apply.html 
* http://pandas.pydata.org/pandas-docs/stable/reshaping.html
* https://www.youtube.com/watch?v=G1-HSWJmvEw *(check out this youtube video for what type of visualization is generated)*
* https://ksopyla.com/wizualizacja-danych/python-pandas-i-wizualizacja-danych-pkb-z-world-bank/  *(resource & implementation)*


