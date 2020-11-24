<h1 style="font-family: Georgia"> <p style="text-align:center;">Welcome to The Bronx!</p> </h1>
<p style="text-align:center;"> by Jessica Sparacio, Sowjanya Sritharasarma, Shayaan Mohammed, and Jason Wu </p>

> Though it may be the second-to-the-smallest borough of NYC's five, the Bronx is still home to some of NYC's most diverse communities and attractions. 


<h2 style="color: #0366d6; font-style: italic;">Our Project</h2>

The aim of our project was to explore Airbnb data in the Bronx to better understand the nature of short-term rentals in NYC. We planned to compare the Airbnb statistics in our Borough with the statistics in all Airbnb's across NYC, as well as explore four specific Bronx neighborhoods. 

We prepared three separate data-frames that we were going to compare throughout our project. Our first dataframe `airbnb` is the original dataset of all airbnb data for all four boroughs. Using `groupby`, we created two more sets, `bronx`, which contained the data just for all the neighborhoods in the Bronx, and `my_bronx`, which contained all of the data for our four specific neighborhoods. 

### Price Matters!

We decided as a group that the information about price was the most relevant when discussing airbnbs, so we wanted to approach our data analysis from this angle. When considering our neighborhoods and our borough, we wanted to primarily concentrate on correlations between price and other factors.

### Some statistics... 

To first approach our data, we wanted to get an idea of some of the basic price statistics in our three data sets. We printed out the following:

```
Number of listings in all boroughs: 48895
Number of listings in Bronx: 1091
Number of listings in our Bronx neighborhoods: 225

Price stats in all boroughs:
Mean: 152.7206871868289
Max: 10000
Min: 0

Price stats in all Bronx neighborhoods:
Mean: 87.4967919340055
Max: 2500
Min: 0

Price stats in our Bronx neighborhoods:
Mean: 79.19111111111111
Max: 450
Min: 21
```
### Visuals, Visuals, Visuals

Now that we had the preliminary price information, we wanted to visualize this data we had collected. We decided that it might be interesting to graph the mean price for each borough in NYC, each neighborhood in the Bronx, and finally each of our four neighborhoods.

**_1. Visualizing Mean Price_**

We first made bar graphs comparing the mean price of Airbnb's across New York City's five boroughs, in all the bronx neighborhoods, and in our four specific neighborhoods for our project. This data shows us that our four neighborhoods are quite similar in terms of mean price, but in comparison to the rest of the Bronx neighborhoods, our average prices fall on the shorter side.

![Mean Price of All Boroughs](meanPriceBoroughs.png){:height="45%" width="45%"} 
![Mean Price of Our Bronx Neighborhoods](meanPriceMyBronxNeighborhoods.png){:height="45%" width="45%"} 
![Mean Price of All Bronx Neighborhoods](meanPriceBronxNeighborhoods.png){:height="45%" width="45%"} 

**_2. Price Distribution Exploration_**

We then decided comparing mean prices was too simplistic. So, we used box plots in order to compare the prices in terms of medians and quartiles between Airbnb's in all New York City negihborhoods, all Bronx neighborhoods, and our four neighborhoods.

![Box Plots of Price Distribution](3PriceBoxplotsNOZEROS.png){:height="60%" width="60%"} 

**_3. Correlational Exploration_**

> After finding that there were some obvious distributional trends, we wanted to go a step
further and see if any other factors had astrong correlation with the price ofan Airbnb. We knew that
prices in the Bronx were generally lower, but _**why?**_

_Number of Host's Other listings_ vs. _Price_
  
We also graphed scatter plots to show the distribution of the data, as well as the minimum, maximum, and median values. This information is more useful because the median value is calculated in spite of the outlier prices.

These scatter plots show price distribution versus the host listings count for the Bronx as a whole, and for our four neighborhoods. The trend for both distributions seems to indicate that the fewer the  listings a host has, the more expensive the airbnb will be.
  
  ![Scatter Plot of Price Distribution](bronx_pricev.calculated_host_listings_count.png){:height="45%" width="45%"}
  ![Scatter Plot of My Bronx](PriceVscalculated_host_listingsMyBronxScatterplot.png){:height="45%" width="45%"}
    
_Minimum Nights_ vs. _Price_
  
Our other two scatter plots shows the distribution between price and minimum nights offered, for the Bronx neighborhoods and our four neighborhoods. Our data showed that most of the airbnb locations in both our four neighborhoods and in the Bronx in general tend to stay within $200 dollars in price and about a week for minimum nights.
  
  ![Scatter Plot of Minimum Nights Bronx](PriceVsMinNightsScatterplot.png){:height="45%" width="45%"}
  ![Scatter Plot of Minimum Nights My Bronx](PriceVsMinNightsMyBronxScatterplot.png){:height="45%" width="45%"}
  
_Room Type_ vs. _Price_

[sentence here]

```
price stats for each room_type in bronx:
                 count        mean         std   min   25%    50%    75%     max
room_type                                                                       
Entire home/apt  379.0  127.506596   95.027102  28.0  80.0  100.0  140.0  1000.0
Private room     652.0   66.788344  107.009071   0.0  40.0   53.5   70.0  2500.0
Shared room       60.0   59.800000  101.798871  20.0  28.0   40.0   55.5   800.0

price stats for each room_type in my_bronx:
                 count        mean        std   min   25%    50%    75%    max
room_type                                                                     
Entire home/apt   67.0  122.358209  69.508818  47.0  87.5  100.0  143.5  450.0
Private room     151.0   61.132450  29.571986  21.0  40.0   55.0   75.0  200.0
Shared room        7.0   55.571429  35.743797  22.0  33.5   55.0   57.5  130.0
```

Finally, we also decided to make pie charts to compare the number of room types available in all Bronx neighborhoods and our individual neighborhoods.

  ![Room Types Pie Chart Bronx](roomTypesB.png){:height="45%" width="45%"}
  ![Room Types Pie Chart My Bronx](roomTypesMB.png){:height="45%" width="45%"}


<h2 style="color: #0366d6; font-style: italic;">The Breakdown</h2>

The Bronx is an incredible borough on it's own, but a borough is really only as much as the sum of its parts! Each member of our team explored the statistics of Airbnb in four individual Bronx neighborhoods: **Kingsbridge, Fordham, Allerton, and Concourse.** Please click through to deep dive into each team member's project!


### FORDHAM 
by: Jessica Sparacio 

![A bustling intersection with views of storefronts, the elevated subway, and crowds. ](fordham-bronx-nyc-molly-flores_x9a0041__large.jpg)

[Click here to learn more about Fordham!](https://jessicalrsparacio.github.io/fordhamproj)

### KINGSBRIDGE
by: Sowjanya Sritharasarma

![A giant, castle-like building which takes up the entire block, next to a nearly-empty street, with parked cars.](KingsbridgeArmoryBetter.jpg)

[Click here to learn more about Kingsbridge!](https://sowjan95.github.io/kingsbridge/)

### CONCOURSE
by: Shayaan Mohammed

![A giant, Pantheon-like court bulding standing alone on a grassy lawn.](concourse.jpg)

[Click here to learn more about Concourse!](https://shayaan1234.github.io/Concourse/)

### ALLERTON
by: Jason Wu

![A housing development with views of residents, a group of apartment buildings, grassy lawns, and trees.](allertonforreal.jpg)

[Click here to learn more about Allerton!](https://jasonwu00.github.io/HC10-Allerton/)


<h2 style="font-family: Georgia"> <i> <p style="text-align:center;">
  Thanks for checking out the Bronx! Come back soon! </p> </i> </h2>

