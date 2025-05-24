# [Exploratory Data Analysis VS Confirmatory Data Analysis](https://www.coursera.org/projects/exploratory-vs-confirmatory-data-analysis-using-python)

Imagine you're a data scientist working for a retail company that sells a wide range of products online and offline in the US. Your manager has asked you to analyze the company's sales data from the past four years to uncover hidden patterns and better understand customer behavior. What will you do? To begin, you conduct Exploratory Data Analysis (EDA) to get familiar with the dataset, and after that, you can perform Confirmatory Data Analysis (CDA) to test your hypotheses. 

## **What is EDA?**
* EDA is one of the data analysis methods where we use different statistical summaries and graphical representations to perform initial investigations on the data to discover interesting patterns, spot anomalies, and overall, for a better understanding of our data. 
* To put a long story short, EDA is used to see how our data can be useful. 

## **Where to start?** 
* The first step of Data Exploration is to check what kinds of data types we are working with.  
* Create a road map for your data exploration based on the different data types you have in 
your dataset. 
* Having a list of different information types (Time, Place, Product, Sales, etc.) that are in your dataset always helps.

## **Time and Customer Information Aspect** 
* If you have a datetime column in your data frame, make sure it has the datetime64 data type. 
* To start your data exploration, always check the time span of your data.  
* If you have a datetime column in your data frame, you can explore your data based on different granularity levels (Year, Month, Day, Hour, Minute, and Second). For example, you can aggregate the profit gained based on different Years, Months, and Days.  
* Data aggregation is one of the required skills of data exploration.  
* Line charts are the most common visualization techniques used while working with time series data.

**Line chart of monthly profit**

![line chart](https://github.com/harishmuh/EDA-VS-CDA/blob/main/images/Monthly%20profit.PNG?raw=true)

## **Data Exploration - Geo Information** 
* Choropleth maps are a common visualization technique used for exploring Geo Data.

**Choropleth map of profit across the US**

 ![Choropleth map](https://github.com/harishmuh/EDA-VS-CDA/blob/main/images/profit%20in%20USA%20choropleth%20map.PNG?raw=true) 

## **Exploratory Data Analysis - Hierarchical Information about the products** 
* Sunburst Diagram and Treemap Diagram are two of the most common data visualization techniques 
that are used to explore hierarchical data. 
* Exploring hierarchical data can always be very insightful. Try to find hierarchical information 
in your data. 
* Time information is also a piece of hierarchical information. You can use Treemap and sunburst diagrams to explore your data based on different hierarchical levels (granularity levels) such as year, month, day, hour, minute, and even second.

**Sunburst diagram**

![sunburst](https://github.com/harishmuh/EDA-VS-CDA/blob/main/images/sunburst%20diagram.PNG?raw=true) 

**Tree map**

![tree map](https://github.com/harishmuh/EDA-VS-CDA/blob/main/images/tree%20map.PNG?raw=true) 

## **Data Exploration - Distributional analysis of sales information columns** 
* You can apply distribution analysis to any numerical value column in your data.  
* You can use statistical summaries to see if there are any outliers in your column. 
* Histograms and Box plots are two visualization techniques used for distributional analysis.  
* Always pay attention to the skewness of your histogram.  
* Right-skewed histogram tells you there are outliers on the right side of your data range. 
You can see the tail on the right side of your histogram 
* Left-skewed histogram tells you there are outliers on the left side of your data range. You 
can see the tail on the left side of your histogram

**Histogram of product quantity**

![histogram](https://github.com/harishmuh/EDA-VS-CDA/blob/main/images/Histogram.PNG?raw=true)

**Boxplot of product quantity**

![boxplot](https://github.com/harishmuh/EDA-VS-CDA/blob/main/images/Boxplot%20category.PNG?raw=true)

## **Confirmatory Data Analysis (CDA)** 
* Once you've gathered these insights from time dimension, geographical data, product hierarchies, and distributional analysis, you can move on to Confirmatory Data Analysis (CDA) to test hypotheses
* CDA is the process of using statistical summaries and graphical representations to evaluate the validity of an assumption about the data at hand. 
* This is one of the popular data analysis methods. Where you make some assumptions about your data, and you start to validate it. For instance, you want to test your assumption:  "Every summer, technology products have the highest sales quantity compared to other product categories". You need to validate by collecting and filtering data on product quantity in the summer. The result can be seen below

**Product quantity based on category in the last 4 years**

![CDA](https://github.com/harishmuh/EDA-VS-CDA/blob/main/images/CDA%20testing%20hypotheses.PNG?raw=true)

Based on the chart above, we can see that your assumption is invalid. The highest quantity of products sold came from the office supplies category.

## **Assets**
* You can check the detailed analysis on this [jupyter notebook](https://github.com/harishmuh/EDA-VS-CDA/blob/main/notebook/The%20Notebook.ipynb).

