# Exploratory-Data-Analysis-of-Used-Cars-in-the-US
In this project analysis, we will analyze the US Used Cars Dataset from Kaggle website. This dataset has over 3 million rows data with 66 columns. We'll use 17 columns for our exercise.
# Overview Description of the Project
- Analyzed data for around 3 million rows with 66 columns. We have used 17 columns for our used car analysis.
- Created visualizations (scatter plots, bar charts, geo heatmaps, etc.) using Seaborn & Plotly.
- Toyota, Ford, and Chevrolet have the most number of listings in the market and the car with the most listings has SUV/Crossover body type.

# Introduction
Exploratory Data Analysis refers to the critical process of performing initial investigations on data so as to discover patterns,to spot anomalies,to test hypothesis and to check assumptions with the help of summary statistics and graphical representations. It is an approach of analyzing data sets to summarize their main characteristics, often using statistical graphics and other data visualization methods.

There are four primary types of EDA:
- Univariate non-graphical: This form of data analysis is where the data is being analyzed consists of just one variable. Since it’s a single variable, it doesn’t deal with causes or relationships. The main purpose of univariate analysis is to describe the data and find patterns that exist within it.

- Univariate graphical: Non-graphical methods don’t give us a full picture of the data. Graphical methods are necessary. Common types of univariate graphics include: Stem-and-leaf plots, which show all data values and the shape of the distribution.

- Multivariate nongraphical: Multivariate data arises from more than 1 variable. Multivariate non-graphical EDA techniques generally show the relationship between two or more variables of the data through cross-tabulation or statistics.

- Multivariate graphical: Multivariate data uses graphics to display relationships between 2 or more data sets. The most used graphic is a grouped bar plot or bar chart with each group representing one level of one of the variables and each bar within a group representing the levels of the other variable.

# Objectives: 
The goal of this project is to get a overview and also a better understanding of the US used car market by applying some data analysis & visualization skills to the real-world dataset. Here are the following steps that we need to follow:
## Downloading a dataset from an Kaggle source.
- Data preparation and cleaning
- Open-ended exploratory analysis and visualization.
- Asking and answering interesting questions.
- Summarizing inferences and conclusion.
## Let's look at the some of the columns we are going to analyze and look at:
- listing_color: Dominant color group from the exterior color.
- listing_id: Listing id from the website.
- longitude: Longitude from the geolocation of the dealership.
- make_name: Make of the car.
- maximum_seating: Seating capacity of the car.
- engine_type: The engine configuration. Eg: I4, V6, etc.
- price: price of the vehicle.
- seller_rating: Rating of the seller who advertised the vehicle.
- year: Car manufacturing year.
- fuel_type: Dominant type of fuel ingested by the vehicle.
- vin: Vehicle Identification Number is a unique encoded string for every vehicle.
- body_type: Body Type of the vehicle. Like Convertible, Hatchback, Sedan, etc.
- city: city where the car is listed. Eg: Houston, San Antonio, etc.
- daysonmarket: Days since the vehicle was first listed on the website.
- franchise_dealer: Whether the dealer is a franchise dealer.
- mileage: Mileage of the car when it was advertised.
- is_new: If True means the vehicle was launched less than 2 years ago.
- latitude: Latitude from the geolocation of the dealership.
- listeddate: The date the vehicle was listed on the website. Does not make daysonmarket obsolete. The prices is dayson_market days after the listed date.

# Summary
- Seasonality does not really affect the price of the car. So, it does not matter in which year/month buying or selling the used car happens.
- US East Coast is the most active when it comes to used car listings. If you're based out of the east coast, you are more likely to have more options to select a car as compared to West Coast.
- Houston has the highest number of listings in the US used car market. It was quite shocking to see only 1065 listings for New York. This requires further investigation.
- Toyota, Ford and Chevrolet has the most number of listings in the market and the car with most listing has SUV/Crossover body type.
- The majority of the cars are listed is either 'White' or 'Black' in color and are 5 seater.
- On average the car stays in the market for 75 days before getting sold. Pick up trucks are faster moving as it takes around 70 days and the van are the slow  moving vehicals which takes more than 100 days on average.
- Majority of the listed car owners are registered in the year 2020. Prices of the new cars are relatively higher. If some one is looking for a more affordable vehicle then used car older than 2 years is the way to go.

# Future work
- Asking more questions, specific to certain users or types of cars to go deep into my market analysis
- The Actual data set has 66 columns so analysing with more columns will give better insights and clarity.
- Price relation with respective to horsepower and transmission etc. could give better understaning on how it may affect the used car price.
- Analyzing the location/city and checking which days of the week has more listings?
- How will the Pick up truck sales affect if we also include the listing of top 10 cities by population?
- Visualising and deriving more relationships out of the given dataset which can help the customer to take better decisions on how/when to buy/sell a used car.
