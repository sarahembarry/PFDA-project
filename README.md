# PFDA-project

## Table of Contents:
- [About Me](#about-me)
- [About This Project](#about-this-project)
- [How to Get Started](#how-to-get-started)
- [References](#references)

## About Me
My name is Sarah Barry, and I am currently pursuing a Higher Diploma in Computing in Data Analytics at Atlantic Technological University (ATU). This repository is part of my coursework for the module: Programming for Data Analytics.

## About This Project
This repository analyses weather data from five Irish locations to assess wind farm feasibility. It demonstrates skills in data cleaning, visualisation, and forecasting, including:

- **Data Cleaning:** Addressed missing values and managed data using SQLite.  
- **Visualisation:** Created interactive and static plots with Plotly and Matplotlib.  
- **Machine Learning:** Used Linear Regression to evaluate trends and model accuracy.  
- **Forecasting:** Developed SARIMAX models to predict 10-year wind speeds for Dublin and Malin Head.   

### Goals:
- Identify top wind energy locations using historical and forecasted data. 

## How to Get Started

1. **Clone the Repository:**
```bash
git clone https://github.com/sarahembarry/PFDA-project.git
cd PFDA-project
```
2. **Set Up Dependencies:**
Install required Python libraries using the provided `requirements.txt` file:

```bash
pip install -r requirements.txt
```

3. **Run the Analysis and Explore Results:**
Open the Jupyter Notebook to access the full analysis, execute the cells, and review visualisations, outputs, and insights.

## References
This project applies concepts from statistical analysis, machine learning, and visualization, with references included in the notebook where used. See also below for a complete list of references used:

### General References

- **[Met Eireann Historical Data](https://www.met.ie/climate/available-data/historical-data)**\
  Source: met.ie, 2024

- **[Beaufort scale for land](https://www.met.ie/cms/assets/uploads/2022/09/Beaufort-scale-for-land.png)**\
  Source: met.ie, 2024

- **[Wind Energy Technology](http://www.iwea.ie/technicalfaqs#:~:text=Turbines%20reach%20maximum%20power%20output,prevent%20excessive%20wear%20and%20tear.)**\
  Source: iwea.ie, 2024

### Pandas DataFrame References

- **[Pandas DataFrames as interactive HTML DataTables](https://marc-wouts.medium.com/pandas-dataframes-as-interactive-html-datatables-9737c7266abf)**\
  Source: medium.com, 2022

- **[Add column with constant value to pandas dataframe](https://www.geeksforgeeks.org/add-column-with-constant-value-to-pandas-dataframe/)**\
  Source: geeksforgeeks.org, 2020

- **[pandas.concat() function in Python](https://www.geeksforgeeks.org/pandas-concat-function-in-python/)**\
  Source: geeksforgeeks.org, 2023

- **[How to reset index after Groupby pandas?](https://www.geeksforgeeks.org/how-to-reset-index-after-groupby-pandas/)**\
  Source: geeksforgeeks.org, 2024

- **[How to Specify Format in pandas.to\_datetime](https://www.statology.org/pandas-to-datetime-format/)**\
  Source: statology.org, 2023

- **[Pandas DataFrame assign() Method | Create new Columns in DataFrame](https://www.geeksforgeeks.org/pandas-dataframe-assign/)**\
  Source: geeksforgeeks.org, 2024  

- [**Pandas quantile()**](https://www.programiz.com/python-programming/pandas/methods/quantile)\
  Source: programiz.com, 2024

- **[The Basics of the Python Enumerate() Function](https://blog.hubspot.com/website/python-enumerate)**\
  Source: blog.hubspot.com, 2023  

- **[BUG: Un-actionable FutureWarning in DataFrame.value_counts with categorical column(s)](https://github.com/pandas-dev/pandas/issues/54775)**\
  Source: github.com, 2023   

### Data Cleaning References

- **[Pandas DataFrame copy() Method](https://realpython.com/python-raw-strings/)**\
  Source: w3schools.com, 2024

- **[Pandas: How to replace zero with 'NaN'](https://www.statology.org/pandas-replace-0-with-nan/)**\
  Source: statology.org, 2022

- **[Replace values in Pandas dataframe using regex](https://www.geeksforgeeks.org/replace-values-in-pandas-dataframe-using-regex/)**\
  Source: geeksforgeeks.org, 2023

- **[A Guide to R Regular Expressions](https://www.datacamp.com/tutorial/regex-r-regular-expressions-guide)**\
  Source: datacamp.com, 2022

- **[Using isnull() and groupby() on a pandas dataframe](https://stackoverflow.com/questions/46106954/using-isnull-and-groupby-on-a-pandas-dataframe)**\
  Source: stackoverflow\.com, 2018

- **[pd.NA vs np.nan for pandas](https://stackoverflow.com/questions/60115806/pd-na-vs-np-nan-for-pandas)**\
  Source: stackoverflow\.com, 2017

- **[Pandas: How to Use dropna() with Specific Columns](https://www.statology.org/pandas-dropna-specific-column/)**\
  Source: statology.org, 2023

### Visualisation References

- **[Plotly: Subplots in Python](https://plotly.com/python/subplots/)**\
  Source: plotly.com, 2024

- **[Plotly: Scatter Plots in Python](https://plotly.com/python/line-and-scatter/)**\
  Source: plotly.com, 2024

- **[Plotly: Python Figure Reference: layout](https://plotly.com/python/reference/layout/)**\
  Source: plotly.com, 2024

- **[Plotly: Python Figure Reference: layout.xaxis](https://plotly.com/python/reference/layout/xaxis/)**\
  Source: plotly.com, 2024

- **[Plotly: Python Figure Reference: layout.yaxis](https://plotly.com/python/reference/layout/yaxis/#:~\:text=Python%20Figure%20Reference%3A%20layout.,yaxis\&text=Type%3A%20dict%20containing%20one%20or%20more%20of%20the%20keys%20listed%20below.\&text=If%20set%20to%20an%20opposite,the%20corresponding%20opposite%2Dletter%20axis.)**\
  Source: plotly.com, 2024

- **[Plotly: Scatterplot Matrix in Python](https://plotly.com/python/splom/)**\
  Source: plotly.com, 2024

- **[Plotly: Hover Text and Formatting in Python](https://plotly.com/python/hover-text-and-formatting/#:~:text=Customizing%20Hover%20text%20with%20Plotly%20Express,-Plotly%20Express%20functions&text=The%20hover_data%20argument%20accepts%20a,bold%20as%20the%20tooltip%20title.)**\
  Source: plotly.com, 2024

- **[Plotly: Sunburst Charts in Python](https://plotly.com/python/sunburst-charts/)**\
  Source: plotly.com, 2024  

- **[Plotly: plotly.express.sunburst](https://plotly.com/python-api-reference/generated/plotly.express.sunburst.html)**\
  Source: plotly.com, 2024    

- **[Plotly: Excessive margins in graphs (how to remove?)](https://community.plotly.com/t/excessive-margins-in-graphs-how-to-remove/49094)**\
  Source: plotly.com, 2024      


- **[Grouped Barplot using Seaborn](https://python-graph-gallery.com/grouped-barplot/)**\
  Source: python-graph-gallery.com, 2024

- **[Annotate bars with values on Pandas bar plots](https://stackoverflow.com/questions/25447700/annotate-bars-with-values-on-pandas-bar-plots)**\
  Source: stackoverflow\.com, 2014

- **[How To Annotate Bars in Barplot with Matplotlib in Python?](https://www.geeksforgeeks.org/how-to-annotate-bars-in-barplot-with-matplotlib-in-python/)**\
  Source: geeksforgeeks.org, 2024

### Machine Learning and Forecasting References

- **[Python: Linear regression from Pandas df - ordinal dates conversion](https://stackoverflow.com/questions/66720622/python-linear-regression-from-pandas-df-ordinal-dates-conversion)**\
  Source: stackoverflow\.com, 2021

- **[Python: python linear regression predict by date](https://stackoverflow.com/questions/40217369/python-linear-regression-predict-by-date)**\
  Source: stackoverflow\.com, 2016

- **[Pandas date\_range to generate monthly data at beginning of the month](https://stackoverflow.com/questions/34915828/pandas-date-range-to-generate-monthly-data-at-beginning-of-the-month)**\
  Source: stackoverflow\.com, 2016

- **[Linear Regression in Python](https://realpython.com/linear-regression-in-python/)**\
  Source: realpython.com, 2024

- **[How to split data into training and testing in Python without sklearn](https://www.geeksforgeeks.org/how-to-split-data-into-training-and-testing-in-python-without-sklearn/)**\
  Source: geeksforgeeks.org, 2023




- **[Split dataframe into two on the basis of date](https://stackoverflow.com/questions/37532098/split-dataframe-into-two-on-the-basis-of-date)**\
  Source: stackoverflow\.com, 2016

- **[Regression Metrics for Machine Learning](https://machinelearningmastery.com/regression-metrics-for-machine-learning/)**\
  Source: machinelearningmastery.com, 2021

- **[Split Your Dataset With scikit-learn's train\_test\_split()](https://realpython.com/train-test-split-python-data/e)**\
  Source: realpython.com, 2016

- **[Mastering Mean Absolute Error: A Beginner's Guide to Evaluating Regression Models](https://machinelearningmastery.com/regression-metrics-for-machine-learning/)**\
  Source: the-pi-guy.com, 2024

- **[How to Create an Index for Python Pandas DataFrame: A Guide](https://saturncloud.io/blog/how-to-create-an-index-for-python-pandas-dataframe-a-comprehensive-guide/)**\
  Source: saturncloud.io, 2023

- **[Complete Guide To SARIMAX in Python](https://www.geeksforgeeks.org/complete-guide-to-sarimax-in-python/)**\
  Source: geeksforgeeks.org, 2023

- **[Forecasting Time Series Data with SARIMAX: A Step-by-Step Guide](https://medium.com/pythonforall/forecasting-time-series-data-with-sarimax-a-step-by-step-guide-701bffc990dd)**\
  Source: medium.com, 2024

- **[Splitting data using time-based splitting in test and train datasets](https://stackoverflow.com/questions/50879915/splitting-data-using-time-based-splitting-in-test-and-train-datasets)**\
  Source: stackoverflow\.com, 2018

- **[Seasonality and SARIMAX](https://www.kaggle.com/code/nholloway/seasonality-and-sarimax)**\
  Source: kaggle.com, 2018

- **[Three techniques to improve SARIMAX model for time series forecasting](https://medium.com/@poudel.birat25/three-techniques-to-improve-sarimax-model-for-time-series-forecasting-5d48db984fbe)**\
  Source: medium.com, 2024

- **[Forecasting in statsmodels](https://www.statsmodels.org/dev/examples/notebooks/generated/statespace_forecasting.html)**\
  Source: statsmodels.org, 2024

- **[How to Use Seasonal ARIMA (SARIMA) for Time Series Forecasting in Python](https://www.statology.org/how-to-use-seasonal-arima-sarima-for-time-series-forecasting-in-python/)**\
  Source: statology.org, 2024

- **[Time Series Forecasting with Python](https://www.blog.trainindata.com/time-series-forecasting-python/)**\
  Source: blog.trainindata.com, 2024

- **[How to Calculate Mean Absolute Error in Python](https://www.statology.org/mean-absolute-error-python)**\
  Source: statsmodels.org, 2024

### SQL References

- **[How to write Pandas dataframe to sqlite with Index](https://stackoverflow.com/questions/14431646/how-to-write-pandas-dataframe-to-sqlite-with-index)**\
  Source: stackoverflow\.com, 2013

- **[Accessing SQLite Databases Using Python and Pandas](https://datacarpentry.github.io/python-ecology-lesson/instructor/09-working-with-sql.html)**\
  Source: datacarpentry.github.io, 2023

- **[MySQL LIMIT Clause](https://www.w3schools.com/mysql/mysql_limit.asp)**\
  Source: w3schools.com, 2024

- **[Pandas Read SQL Query or Table with Examples](https://sparkbyexamples.com/pandas/pandas-read-sql-query-or-table/)**\
  Source: sparkbyexamples.com, 2024

- **[The SQL WHERE Clause](https://www.w3schools.com/sql/sql_where.asp)**\
  Source: w3schools.com, 2024

- **[MySQL AND, OR and NOT Operators](https://www.w3schools.com/mysql/mysql_and_or.asp)**\
  Source: w3schools.com, 2024

