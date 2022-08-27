# Hotel Booking Analysis 

The hotel industry is one of the most important components of the wider service industry, catering for customers who require overnight accommodation. This project discusses the key success factors of the hospitality industry. We have studied the data to get some to run a successful business.

In this study we have sample data about the hotel industry that is not processed for use. Unprocessed data gives inaccurate results. To process this data is called data cleaning. We have cleaned the data by handling null values, outliers and dropping unwanted columns.

 We are then condensing the data for our study. This is Data Manipulation. We achieve this result by performing functions on the columns. We have come up with new columns such as total kids, guests, stays, revenue etc.

 In our data study we have 2 types of hotels- the resort type and city hotel type. There are factors in the study which affect the business of the hotels. Factors such as location, ADR, Deposits charged, wait time, etc. We also have channels like distribution channel, Market segment to focus on to get more revenue. 



## Exploratory Data Analysis:-

First step is to import libraries such as NumPy, pandas, matplotlib, seaborn.Then load the raw dataset. This data has many unprocessed values which cannot be considered for the study. Here is the workflow of correcting it for our analysis.

## Data Cleaning:-
a. Handling Null Values
Company Id and Agent Id: - These columns have null values of 93% and 15% respectively. Hence, these columns are dropped.
Country: - This has null values less than 5% thus the null values are filled with the mode value.
Children and babies: - There are only 4 null values so the null value is filled with mean
 
 b. Handling Outliers
An outlier is an extremely high or extremely low data point relative to the nearest data point and the rest of the neighboring co-existing values in a data graph or dataset we work with. 
We have used the Interquartile range method to handle outliers. To find the interquartile range (IQR), ​we first find the median (middle value) of the lower and upper half of the data. These values are quartile 1 (Q1) and quartile 3 (Q3). The IQR is the difference between Q3 and Q1.
     2. Data Manipulation: - Creating new columns
Kids= Children +babies
Total stay= stays_in_weekend_nights+ stays_in_week_nights
Guest= Adults+kids
Revenue= stay of non-cancelled guests * ADR





## Data study :-
i) UNIVARIATE ANALYSIS: 
Univariate analysis is the simplest form of analyzing data i.e study of one variable. Its major purpose is to describe; distribution of single data, and find patterns in the data.

ii) BIVARIATE ANALYSIS:
Bivariate analysis between two variables. One of the variables will be dependent and the other is independent. The study is analyzed between the two variables to understand to what extent the change has occurred.

iii) MULTIVARIATE ANALYSIS
Multivariate data analysis is the study of relationships among the attributes, classify the collected samples into homogeneous groups, and make inferences about the underlying populations from the sample.

## Data Visualization :-

Data visualization is the practice of translating information into a visual context, such as a map or graph, to make it easier to understand and gain insights from them. 
The graphs used here for study are: -

Box Plot.

Histogram.

Pie Chart.

Bar Plot.

Line Plot.

Scatter Plot.

Geo Mapping.

## Conclusion :-
                  
Majority of people prefer A-room type so hotels should increase their numbers to get more revenue.

Chances of cancellation is high when there are no deposits taken by hotels, so hotels should take minimum deposits to minimise the rate of cancellation.

Transient customers cancels more often but when people book in groups it leads to lesser cancellations, hence hotels should provide some offers focusing transient customers to decrease cancellations.

Maximum number of bookings are in the month May to August, so hotels should provide exciting deal to customers to increase their booking in off season. 
As hotels are getting less repeated customers so management should take customer’s feedback and improve the hotel facilities to increase the count of their repeated guests.
We have a huge number of visitors from  western Europe namely Portugal, France, UK and same countries generate highest revenue. So marketing teams should target these countries to get more customers.







