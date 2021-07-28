# Sales Analysis using Pandas
This project entails the analysing 12 months worth of sales data.
## Aim of this project
The ultimate goal of this project is to explore 5 high level business questions related to our data:
* What was the best month for sales? How much was earned that month?
* What city sold the most product?
* Which hour range should we display advertisemens to maximize the likelihood of customer’s buying product?
* What products are most often sold together?
* What product sold the most? Why do you think it sold the most?
## Notebook Walkthrough
1. In the first step, I started with concatenating multiple csvs together to create a new DataFrame (pd.concat). 
2. The second step is cleaning the data. The cleaning tasks include:
* Drop NaN values from DataFrame
* Removing rows based on a condition
* Change the type of columns (to_numeric, to_datetime, astype)
3. In order to answer the questions of best month, city and hour range (which are not included in the table):
* Adding columns
Parsing cells as strings to make new columns (.str)
Using the .apply() method
Using groupby to perform aggregate analysis
4. Data visualisation
In each question, I used Seaborn and Matplotlib to plot bar charts, line graphs and kdeplot to visual graphs.
Reference:
I couldn't have finished the project without the help from tutorial from Keith Galli in this video: https://www.youtube.com/watch?v=eMOA1pPVUc4&list=PLFCB5Dp81iNVmuoGIqcT5oF4K-7kTI5vp&index=8

### 
