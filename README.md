<h1>Hotel Booking Analysis</h1>
The success factoring a profitable hotel industry has been changing over time, driven by global competition and increasingly high customer expectations. Hotels focus on customer satisfaction and to exceed customer expectations. We have a hotel booking dataset containing information for city and resort hotels. This dataset has 32 variables with around 1,19,000 entries. It is collected in order to predict hotel bookings and its probability of cancellation. Some attributes here are to understand what factors do bring in the revenue for the business. Some attributes show the customers preference for booking whereas some attributes show the factors leading to cancellations. We have a hotel booking dataset. We are using our Python skills to perform EDA and gain informative insights about factors in hotel bookings and how they affect hotel booking

In our data study we have 2 types of hotels- the resort type and city hotel type. There are factors in the study which affect the business of the hotels. Factors such as location, ADR, Deposits charged, wait time, etc. We also have channels like distribution channel, Market segment to focus on to get more revenue.

<h2>Project Goal</h2>
This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. Purpose of our study is to find the best time to book a hotel room. The optimal length of stay in order to get the best daily rate. Study on special requests.We explore and analyze the data to discover important factors that govern the bookings.

<h3>Exploratory Data Analysis:-</h3>
In this study we have sample data about the hotel industry that is not processed for use. Unprocessed data gives inaccurate results. To process this data is called data cleaning. We have cleaned the data by handling null values, outliers and dropping unwanted columns.

Data Cleaning
Handling Null Values
Company Id and Agent Id: - These columns have null values of 93% and 15% respectively. Hence, these columns are dropped.

Country: - This has null values less than 5% thus the null values are filled with the mode value.

Children and babies: - There are only 4 null values so the null value is filled with mean

Handling Outliers
An outlier is an extremely high or extremely low data point relative to the nearest data point and the rest of the neighboring co-existing values in a data graph or dataset we work with. We have used the Interquartile range method to handle outliers. To find the interquartile range (IQR), ​we first find the median (middle value) of the lower and upper half of the data. These values are quartile 1 (Q1) and quartile 3 (Q3). The IQR is the difference between Q3 and Q1.

Data study
i) UNIVARIATE ANALYSIS: Univariate analysis is the simplest form of analyzing data i.e study of one variable. Its major purpose is to describe; distribution of single data, and find patterns in the data.

ii) BIVARIATE ANALYSIS: Bivariate analysis between two variables. One of the variables will be dependent and the other is independent. The study is analyzed between the two variables to understand to what extent the change has occurred.

iii) MULTIVARIATE ANALYSIS Multivariate data analysis is the study of relationships among the attributes, classify the collected samples into homogeneous groups, and make inferences about the underlying populations from the sample.

Data Visualization :-
Data visualization is the practice of translating information into a visual context, such as a map or graph, to make it easier to understand and gain insights from them. The graphs used here for study are: -

Box Plot.

Histogram.

Pie Chart.

Bar Plot.

Line Plot.

Scatter Plot.

Geo Mapping.

Conclusion :-
Majority of people prefer A-room type so hotels should increase their numbers to get more revenue.

Chances of cancellation is high when there are no deposits taken by hotels, so hotels should take minimum deposits to minimise the rate of cancellation.

Transient customers cancels more often but when people book in groups it leads to lesser cancellations, hence hotels should provide some offers focusing transient customers to decrease cancellations.

Maximum number of bookings are in the month May to August, so hotels should provide exciting deal to customers to increase their booking in off season. As hotels are getting less repeated customers so management should take customer’s feedback and improve the hotel facilities to increase the count of their repeated guests.

Every year there is 25-30% cancellation for resort hotels and 40-45% cancellation for city hotels.
