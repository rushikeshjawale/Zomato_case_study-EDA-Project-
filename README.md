# Zomato Case Study(Bengaluru)
## Project Description:

Zomato is a restaurant search and discovery service that provides information on over 1.5 million restaurants across 24 countries.
Users can search for restaurants by location, cuisine, and other parameters, and can view menus, user reviews, and ratings.
The company also offers online ordering, table reservations, and food delivery services.
It was founded in 2008 in India and has since expanded to other countries.

A case study of Zomato would likely focus on the company's growth and expansion strategy, as well as its business model and revenue streams.
important aspect of Zomato's business model is its focus on generating revenue through multiple streams.
In addition to traditional online advertising and sponsored listings, the company also generates revenue through online ordering, table reservations, and food delivery services.
By providing a wide range of services, Zomato has been able to create a loyal user base and generate a steady stream of revenue
#### Audience:
The case study will be aimed at a business audience, such as company executives, investors, and industry analysts,
as well as students and researchers studying the food delivery market.

Zomato is a restaurant search and discovery service that provides information on over 1.5 million restaurants across 24 countries.
Users can search for restaurants by location, cuisine, and other parameters, and can view menus, user reviews, and ratings.
The company also offers online ordering, table reservations, and food delivery services.
It was founded in 2008 in India and has since expanded to other countries.

Our project is a case study on zomato. In this we are going to discuss these above mention parameters of zomato that will help us to understand about
this platform and give us some over all information about how the Zomato's impact on restaurants focus on how the platform has affected the way restaurants operate and interact with customers in Bengaluru.

## Outline:

| SL. NO |       Outline       |
|:------:|:-------------------:|
|   1    |  Executive Summery  |
|   2    |    Introduction     |
|   4    |      Objective      |
|   3    | Question & solution |
|   4    |      Appendix       |
|   5    |     Conclusion      |

## Executive Summary:

This Project will give you an overview of :

1. Average rating of restaurants in Bengaluru.

2. Top restaurant chains.

3. Different types of restaurants.

4. Highest voted restaurants.

5. Restaurants which are present in different location.

6. Variety of restaurants present in Bengaluru.

7. Affordable and luxurious  restaurants.

8. votes feature of zomato.

9. price feature of zomato.

## Introduction:

* ### Audience:
- A case study of Zomato can be used by various stakeholders including:

  1. Business students and academics: Case studies are a popular teaching tool in business schools, and a case study of Zomato can be used to teach students about topics such as growth and expansion strategies, business models, and revenue streams.

  2. Investors and venture capitalists: A case study of Zomato can provide insight into the company's financial performance and growth potential, which can be useful for investors and venture capitalists who are considering investing in the company.

  3. Entrepreneurs and start-up founders: A case study of Zomato can provide valuable lessons for entrepreneurs and start-up founders who are looking to launch and grow their own businesses in the food and restaurant industry.

  4. Competitors: A case study of Zomato can be used by competitors in the food and restaurant industry to gain insight into the company's strategies and business model, which can inform their own competitive strategies.

  5. Researchers: A case study of Zomato can be used by researchers in fields such as marketing, management, and business strategy to gain insights into the company's operations and performance.

  6. Zomato management: Zomato management can use case study information as a reference point to evaluate their own performance and measure their progress in comparison to the industry standard.

### Project Objectives:
The main objectives of the case study are to understand Zomato's business model, growth, and performance in the Indian food delivery market in Bangalore,
and to identify key trends and challenges facing the company.

## Question and Solutions of Analysis:

### 1) Get the Distribution of Rating column and try to find out what distribution this feature supports ?

To solve this problem statement we install and import seaborn library.
then by performing some operations we find out average rating of each restaurant,
we use that information to plot using displot function from seaborn library

![1 Distribution of Rating column.jpeg](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/images/1%20Distribution%20of%20Rating%20column.jpeg)

**Conclusion:**
- From this plot you can say that the rating count in range of 3 to 4 is
above 400 that means maximum number of customers gives ranting between 3 to 4.

[click here](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/2%20Analysing%20of%20Restraurant.ipynb)
to get entire code.

### 2) Top restaurant chains in Bangalore.

Restaurant chains are a group of restaurants that are owned or franchised by the same company. These restaurants typically offer the same menu, branding, and overall customer experience across all locations. They can be found in multiple locations, cities, or even countries
 
To plot this result we use barplot function from seaborn library

![2 Top restaurant chains in Bengalore.jpeg](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/images/2%20Top%20restaurant%20chains%20in%20Bengalore.jpeg)

**Conclusion:**
- As you can see x-axis contains Number of outlets and y-axis contains name of restaurants.
- According to this graph you can see cafe coffee day has more than 80 outlets in bangalore.

[click here](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/2%20Analysing%20of%20Restraurant.ipynb)
to get entire code.

### 3) How many of the restaurant accept or do not accept online order.

Here we plot the percentage of restaurants who accepts and do not accepts online order in pie-chart

![3 restaurant accept or do not accept online order.jpeg](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/images/3%20restaurant%20accept%20or%20do%20not%20accept%20online%20order.jpeg)

**Conclusion:**
- From this pie-chart you can say that 64.42 % of restaurants accepts online order and 35.58 % do not accept online order.
- So maximum percentage of restaurant in Bangalore accepts online order.

[click here](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/2%20Analysing%20of%20Restraurant.ipynb)
to get entire code.



### 4) How many restaurants provide booking table and do not provide booking table

We plot pie chart same as above problem statement

![4 restaurant that provide booking table.jpeg](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/images/4%20restaurant%20that%20provide%20booking%20table.jpeg)

**Conclusion:**
- From this pie-chart we can conclude that 85.36 % of total restaurants do not provide
booking table feature in Bangalore, and only 14.64 % from total restaurants provide booking table 
feature.
- Hence maximum restaurants in Bangalore do not provide booking table feature.

[click here](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/2%20Analysing%20of%20Restraurant.ipynb)
to get entire code.

### 5) Analysis of Types of restaurant count in Bangalore.
Here type of restaurants means what types of restaurant.

It can be Cafe, Sweet Shop, Food Court, Pub, Lounge etc.

Here we count total number of each type and plot that on barchart using plotly library.

![2 Analysing of Restaurant.jpeg](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/images/2%20Analysing%20of%20Restaurant.jpeg)

**Conclusion:**
- Here you can see what type of restaurant or shop has maximum count, or you can say what type of restaurant or shop is more
in Bangalore.
s
- As you can see Quick Bites restaurants or shop has total count of 15073. 
where Bakery hold the lowest count of 234.

- So you can say maximum number of shops are of Quick Bites type where number of Bakeries are lowest in Bangalore.

[click here](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/2%20Analysing%20of%20Restraurant.ipynb)
to get entire code.

### 6) Find the highest voted restaurant in Bangalore

Voting on restaurants in Zomato is an important feature as it allows users to provide feedback on their dining experiences, helps Zomato to gather data on the quality of restaurants, creates a sense of community among users, helps Zomato to maintain its reputation as a reliable source of information and also helps the restaurants to improve their service, food and ambiance.

To solve this problem statement we use groupby operation of pandas library
and group all the restaurant 'name' feature with respect to their 'votes' feature and plot them as a bar graph using plotly.

![highest voted restaurant in bangelore.jpeg](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/images/highest%20voted%20restaurant%20in%20bangelore.jpeg)

**Conclusion:**
- Here you can see according to graph these are some highest voted restaurant in Bangalore.
"Onesta" is the highest voted or most liked restaurant in Bangalore which have more than 350k
likes or to be precised 347520 likes.

[click here](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/2%20Analysing%20of%20Restraurant.ipynb)
to get entire code.


- Where  "koramangala Social" hold lowest votes which is 75021 in Bangalore

### 7) Total restaurant on different location in Bengalore.
Here we have to find total count of restaurants at different location in Bangalore.

Means we have to find how many restaurants is located in different areas of Bangalore.

To solve this problem statement, first we use groupby function to group the data of location feature or column,
then we iterate through that groupby function using for loop and stored both the data into separate list, where one list 
contains the location of restaurant and other list contains total length of unique location.
Finally we use zip function to zip those separate lists into one and save that zip data in newly created dataframe.

Then we plot data of that data frame by using matplotlib

![total rest at diff location.jpeg](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/images/total%20rest%20at%20diff%20location.jpeg)

**Conclusion:**
- From this data you can see that "whitefield" area in Bangalore has maximum number of restaurants
which is more than 600. which means "whitefield" can be the market area or city center.
- Wheres "Bellandur" area or location in Bangalore has less than or equal to 300 restaurants approx
which means it is not a main area or location of bangalore neither it can be close to city center.

[click here](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/2%20Analysing%20of%20Restraurant.ipynb)
to get entire code.


### 8) Total number of variety of restaurants in Bangalore ?

In this problem statement we are going to count the total number of varity of restaurants
in Bangalore, for example North Indian, North Indian chinese, South Indian etc.

To solve this problem we are going to use bar chart from plotly express library
so first install and import plotly.express library.
Then consider "cuisines" feature from dataframe, use value count function to count the total number
of cuisines.After you get some results plot that results into bar graph 
using px.bar() function.

![variety of rest in bangelore.jpeg](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/images/variety%20of%20rest%20in%20bangelore.jpeg)

**Conclusion:**
- From this graph you can see the number of "North Indian" restaurants is 2284
Wheres "South Indian" restaurants holds 3rd place with the count of 1320.
- Hence you can conclude that though Bengaluru is located at south part of India
but North Indian restaurants are more in Bengaluru than South Indian restaurants.

[click here](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/2%20Analysing%20of%20Restraurant.ipynb)
to get entire code.

### 9) Analysing Approx cost of 2 people Feature

we are usind distplot from seaborn library to plot "approx_cost(for two people)" feature.

![Approx cost for 2 people.jpeg](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/images/Approx%20cost%20for%202%20people.jpeg)

**Conclusion:**

From above graph you can conclude that 70% of restaurants offers food for two people under cost of approx 700 rupee

[click here](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/2%20Analysing%20of%20Restraurant.ipynb)
to get entire code.


### 10) Analysing Approx cost of 2 people with respect to rating

To solve this problem statement we use scatter plot from seaborn library

![scatter plot Approx cost of two people .jpeg](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/images/scatter%20plot%20Approx%20cost%20of%20two%20people%20.jpeg)

**Conclusion:**

- As you can see the majority of restaurants which do not provides online order feature
has "approx_cost(for two people)" less than 1000 rupees fall under rating of 3 to 4.
and restaurant which do provides online order feature and has "approx_cost(for two people)" less than 1000 rupees is
fall under rating of 4 to 5. So you can conclude that online order feature affects on rating of restaurants.
- Hence the restaurant that provides online order feature has gained more rating
as compare to restaurants that do not have online order feature.


- Another thing you can see that as "approx_cost(for two people)" is increasing
the restaurants lies in that category do not have online order feature but they still manage to get rating 4 to 5.
- what this mean is expensive restaurants in Bangalore do not provide online order feature but they are able to achieve rating of 4 to 5.

[click here](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/2%20Analysing%20of%20Restraurant.ipynb)
to get entire code.


### 11) Is there any affect on votes of restaurants who accepts Online orders and not accept Online orders respectively.
We use boxplot function from seaborn library to check whether online orders affects on votes or not.

![affect on votes of restaurants who accepts Online orders.jp](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/images/affect%20on%20votes%20of%20restaurants%20who%20accepts%20Online%20orders.jpeg)

from this box plot you can conclude that the restaurant that provides online order 
gets higher number of votes then the restaurants that do not provide online order.

[click here](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/2%20Analysing%20of%20Restraurant.ipynb)
to get entire code.


### 12) Is there any affect on price of restaurants who accepts Online orders and not accept Online orders respectively

![affect on price of restaurants who accepts Online orders.jpe](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/images/affect%20on%20price%20of%20restaurants%20who%20accepts%20Online%20orders.jpeg)

**Conclusion:**

From this plot you can say that the restaurants who accept online order are more affordable as compare to 
restaurants who do not accept online order.
we find same result in scatter plot in previous problem statement

[click here](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/2%20Analysing%20of%20Restraurant.ipynb)
to get entire code.


### 13) Top 10 Most Expensive restaurant with approx cost for 2 people

![Top10 most expensive restaurants.jpeg](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/images/Top10%20most%20expensive%20restaurants.jpeg)

**Conclusion:**

These are most expensive and luxurious restaurants in bangalore.
The most expensive restaurant has "approx_cost(for two people" 6000 rupees

[click here](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/2%20Analysing%20of%20Restraurant.ipynb)
to get entire code.

### 14) Top 10 Most Affordable Restaurant in Bangalore

![Top10 most affordable restaurants.jpeg](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/2%20Analysing%20of%20Restraurant.ipynb)

**Conclusion:**
These are most affordable restaurants in Bangalore.

[click here](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/2%20Analysing%20of%20Restraurant.ipynb)
to get entire code.

## Geographical Analysis questions:
- Geographical analysis is the study of spatial relationships, patterns, and processes that exist within geographical or physical space.
It involves using various techniques such as mapping, spatial statistics, and geographic information systems (GIS) to analyze data in relation to location. 
The goal of geographical analysis is to better understand and make decisions about the distribution of people, resources, and environmental factors on the earth's surface. 
It is widely used in fields such as urban planning, environmental science, public health, and marketing.

- In upcoming problem statements we have to plot data on map of Bengaluru
to visualise the saturation of the restaurants on the particular location of Bangalore
we will visualize the data using heatmap.
A heat map is a graphical representation of data where individual values are represented as colors. It is used to visualize data in a matrix-like format, where the color intensity represents the magnitude of a particular value.
Heat maps are commonly used in fields such as finance, biology, and marketing to identify patterns and trends in large datasets.

**{ Note : These maps cannot be visualise in github because its a live map
like google map. So you have to download and run project in your system to able to access this Geographical map }**

### 15) Generate Heat map of Restaurants in Bangalore
To solve this problem statement we have to find latitude and longitude of 
different location in Bangalore and then plot the heat map on those coordinates

After performing these operations this is the result.

![heatmap_rest_bangalore.jpg](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/images/heatmap_rest_bangalore.jpg)

**Conclusion:**
From this Heat map you can see the bright green color at "Kormangala" location
which means majority of restaurants in Bangalore are located at Kormangala.

Blue color is also represent the location of restaurants but that color represent 
only few number of restaurants.

[click here](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/3%20Spatial%20Analysis.ipynb)
to get entire code.

### 16) Heatmap of North Indian Restaurant
The process is similar to above question 15. We have to plot the heat map on the map of bangalore

![heatmap_northindres_bangalore.jpg](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/images/heatmap_northindres_bangalore.jpg)

**Conclusion:**
As you can see the map is similar to the above map and the reason is
the majority of restaurants in Bangalore are North Indian restaurants
and we have prove this in the question number Q8 where we have to find total number of variety of 
restaurant in Bangalore.

[click here](https://github.com/rushikeshjawale/Zomato_case_study-EDA-Project-/blob/master/2%20Analysing%20of%20Restraurant.ipynb)
to get entire code.

## Appendix

### • Software used in this project:

In case of local machine We are going to use the following softwares in this project :

Programming Language : [Python](https://www.python.org/)

IDE : [Jupyter Notebook](https://jupyter.org/)

Packages : [Pandas](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html), [Numpy](https://numpy.org/), [Seaborn](https://seaborn.pydata.org/), [Matplotlib](https://matplotlib.org/), [Plotly](https://plotly.com/), [Folium](https://python-visualization.github.io/folium/, [Geopy](https://pypi.org/project/geopy/)).

### • The Data Sets:
Download dataset zip file and extract it into your system to use

[Zomato_data](https://drive.google.com/drive/folders/1rDH8c1MA3sEb9Yd6sbXXprU9VUL-ErJZ) zip file

# Ovearall Conclusion:

Zomato has been able to establish a strong foothold in the Indian food delivery market, thanks to its innovative business model and strong market positioning.
However, the company faces several challenges, including intense competition and changing consumer preferences.
To continue its growth and maintain its market position, Zomato must stay aware of these challenges and opportunities, and adapt its strategies accordingly.
The company can also focus on expanding its offerings and services to attract more customers and increase its revenue.
Overall, Zomato has a good potential to continue to grow in the Indian food delivery market with the right strategies in place.

# Author

- [@Rishikesh Jawale](https://github.com/rushikeshjawale?tab=repositories)

# 🔗 Connect with me:
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rishikesh-jawale-433551252/)









