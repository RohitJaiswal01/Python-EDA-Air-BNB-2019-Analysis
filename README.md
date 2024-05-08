# Python-EDA-Air-BNB-2019-Analysis
EDA Analysis of the dataset Air BNB 2019, understanding of the data and discovering incredible insights with Pandas and NumPy and visualizing the findings and understanding with help of matplotlib and seaborn to solve and drive business decisions.

Air_BNB_2019 V1,V2,V3,V4,V5 are being used for commits only.

Air BNB 2019 FINAL EDA Submission Template.ipynb is the final completed analysis.


# AIR BNB BOOKIN ANALYSIS

Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present a more unique, personalized way of experiencing the world. Today, Airbnb became one of a kind service that is used and recognized by the whole world. Data analysis on millions of listings provided through Airbnb is a crucial factor for the company. These millions of listings generate a lot of data - data that can be analyzed and used for security, business decisions, understanding of customers' and providers' (hosts) behavior and performance on the platform, guiding marketing initiatives, implementation of innovative additional services and much more. This dataset has around 49,000 observations in it with 16 columns and it is a mix between categorical and numeric values.

# What is AIRBNB?

Airbnb, Inc., based in San Francisco, California, operates an online marketplace focused on short-term homestays and experiences. The company acts as a broker and charges a commission from each booking. The company was founded in 2008 by Brian Chesky, Nathan Blecharczyk, and Joe Gebbia.

![airbnb1-678x381](https://github.com/RohitJaiswal01/Python-EDA-Air-BNB-2019-Analysis/assets/152694882/0b7ae846-dae2-4aa1-bfc6-e8ea4505ec47)


# Project Summary
The Exploratory Data Analysis (EDA) of Airbnb booking analysis is a critical component of the overall project aimed at understanding the various factors that influence customer booking decisions on the Airbnb platform. The EDA will provide insights into the patterns and trends in the booking data and identify any underlying relationships between variables that may impact customer behavior.

The EDA will begin with data collection from the Airbnb platform, including information on the listings, their availability, prices, and customer reviews. The data will then be cleaned to remove any missing, inconsistent, or irrelevant information. The next phase of the EDA will involve data analysis to uncover patterns and trends in customer behavior, such as the most popular listing types, the most sought-after amenities, and the factors that impact booking rates.

Hypothesis formulation and analysis has been done and findings have been compared and described with the approach and the feature involved name variable and the price of that listing.

I have used Seaborn and Matplotlib for creating all the visualizations. This is just a glimpse of eda on the airbnb dataset and there’s no any predictions involved.

Data visualization will be used to effectively communicate the insights and findings of the data analysis. A combination of graphs, charts, and maps will be used to showcase the trends and patterns in the data. This will help to identify areas of opportunity and highlight areas that require improvement.

The final phase of the EDA will involve summarizing the findings and providing recommendations on how the insights can be leveraged to improve the customer experience and increase booking rates. This will include recommendations on optimizing pricing strategies, enhancing the listing descriptions, and improving the overall customer experience. The findings and recommendations will be presented in a comprehensive report, detailing the methodology, findings, and recommendations.

In conclusion, the EDA of Airbnb booking analysis will provide valuable insights into the patterns and relationships in the booking data . The EDA will play a crucial role in ensuring the success of the overall Airbnb booking analysis project by providing a foundation for further analysis and optimization. The insights and recommendations generated by the EDA will help to drive growth and success for the Airbnb platform and ensure its continued evolution and adaptation to changing customer needs and preferences.




# Business Objective
Exploration and Analysis to extract insights from the data, helping in understanding of customers' and providers' (hosts) behaviour and preference or choice on the platform, guiding marketing initiatives, implementation of secure and innovative additional services and much more.

To explore and understand the patterns and trends in the Airbnb booking data and to identify any underlying relationships between variables that may impact customer booking decisions.

Data oriented business decisions, helps in improving processes and services, translating the complex data and discover key understanding for future actionable plans.

# About the Data
48895 Row, 16 Column in a dataset

Categorical data : host name, neighbourhood_group, neighbourhood, room_type

Data Has int, float and object data type

Id : It is unique for each bookings, numeric values, data is not repeatable.

name : How is the room. Ex : Clean & quiet apt home by the park, this can be neglected.

host_id : ID of the host, Data is repeatable, Numerical data .

host_name : Name of the host. Categorical data .

neighbourhood_group : It is a location . Brooklyn,Manhattan, Queens, Bronx, Staten Island .

Neighbourhood: Area of the location inside neighborhood group.

Latitude : Numerical values , Position of the location.

Longitude :Numerical values , Position of the location.

room_type : Private, Shared or Entire/Home, Categorical value.

price : Cost of the room, Numerical value.

minimum_nights : How many days compulsory to stay.

number_of_reviews : Total number of review for this host

last_review : Give information regarding last reviews is given in date.

reviews_per_month : Total number of reviews / Days in months

calculated_host_listings_count : The total number of apartments and bedrooms referred to the same landlord/ host.

availability_365 : Days it is available in a year

The last_review and reviews_per_month column may have null values because of "0" number_of_reviews at that destination .

# Tools Used
1 . Google Collab is used as IDE.

2. Pandas and NumPy are used for Data Manipulation & Pre-processing and Mathematical functions respectively.
  
3. For visualization of the plots, Matplotlib and Seaborn are used

![image](https://github.com/RohitJaiswal01/Python-EDA-Air-BNB-2019-Analysis/assets/152694882/1391eec7-6439-44f3-a189-88e831aaad45)

# Data Visualisation some plots

![image](https://github.com/RohitJaiswal01/Python-EDA-Air-BNB-2019-Analysis/assets/152694882/dee82ac2-cafd-486f-b70a-81eb1d0f7af5)


![image](https://github.com/RohitJaiswal01/Python-EDA-Air-BNB-2019-Analysis/assets/152694882/d330f842-8c69-4d58-a300-f4c51d1c5b84)

![image](https://github.com/RohitJaiswal01/Python-EDA-Air-BNB-2019-Analysis/assets/152694882/c5037a66-9829-4cab-b268-15e5c932eae1)


![image](https://github.com/RohitJaiswal01/Python-EDA-Air-BNB-2019-Analysis/assets/152694882/aaf0c6df-7dcd-42fb-8722-3a486796d4d3)

![image](https://github.com/RohitJaiswal01/Python-EDA-Air-BNB-2019-Analysis/assets/152694882/74363d8c-be91-494c-a877-858edac23b17)


![image](https://github.com/RohitJaiswal01/Python-EDA-Air-BNB-2019-Analysis/assets/152694882/187b8150-25b3-4994-b71f-ea38fb187e02)

![image](https://github.com/RohitJaiswal01/Python-EDA-Air-BNB-2019-Analysis/assets/152694882/90149c98-aef4-46de-ad09-e2123d1c5a45)



# Conclusion 

In this analysis project, about 14 different cases were analyzed on the given dataset to make better business decisions and help analyze trends, which can lead to new and better products and services. It has been found that Most of the Bookings were takes place for the "Manhattan" of around “44.3%" followed by “Brooklyn", “Queens" which has “41.1%" & "11.6%" respectively.

Around 25 % listing having criteria for minumum nights of 1 night only, which is also the minimum night citeria.

Around 75 % listing having minimum nights criteria till 5 nights. Rest 25 % having minimum nights criteria from 5 nights to 1250 nights.

The dataset having availability_365 = 0 also shows that the 75% of listing in the dataset have Total Count = 1, means the host having single listing on Air BNB is having availability_365 = 0 means in demand.

We have also analyzed that, Manhattan has the highest price range for the listings with about dollar 140 as an average price, followed by Brooklyn with $90 per night, Queens and Staten Island seem to have a very similar distribution, the Bronx being the cheapest.

Additionally, we also find-out the Top (Host). Preference of Guests w.r.t. Property Type & Room Type.
Manhattan have the high price per listing followed by Brooklyn then Queens,Staten island and Bronx.

Entire home/apart have the highest prices as followed by private rooms and then shared room.

Furthermore, we have also been analyzed Customer Reviews/Comments, provided by the Airbnb’s and many more.

The most interesting variables regarding price prediction are:

1.   Location
2.   Room type
3.   calculated_host_listings_count
4.   Number of reviews

