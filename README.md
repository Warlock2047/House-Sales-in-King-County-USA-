# House Sales in King County USA
## Promotion Of the Project
**id:** house notation
**date:** the date the house was sold
**price:** house price
**bedrooms:** number of bedrooms in the house
**bathrooms:** number of bathrooms in the house
**sqft_living:** square feet of house (square foot) 
**sqft_lot:** square feet of land (square foot) 
**floors:** total number of floors of the house 
**waterfront:** sea view house (0-1) 
**view:** view of the house (0-4)
**condition:** how good is the general condition (1-5)
**grade:** The overall rating given to the residence according to the King County rating system 
sqft_above: square feet of house excluding basement (square foot) 
sqft_basement: basement square feet (square foot)
**yr_built:** year of construction of the house
**yr_renovated:** house renovation year
**zipcode:** post code
**lat:** latitude coordinate
**long:** longitude coordinate
**sqft_living15:** square feet of the house in 2015 (square foot)
**sqft_lot15:** land square feet of the house in 2015 (square foot)


#House Sales in King County USA Report
[^1]:This dataset includes house prices for King County, which includes Seattle. Includes homes sold between May 2014 and May 2015. A great dataset for compiling simple regression models.
[^2]:When we examine our dataset, the date the house was sold, the price, the number of bathrooms, the notation of the house, the price of the house, the number of bedrooms, the square feet of the house, the square feet of the land, the number of floors, whether it has a sea view, the degree of the view, the degree of its general condition, King County we can observe the grade according to the rating system, the square feet of the house outside the basement, the square feet of the basement floor, the year of construction of the house, the year of renovation of the house, the zip code, the latitude coordinate, the longitude coordinate, the square feet of the house for 2015 and the square feet of the house for the year 2015.
[^3]:First of all, we started the analysis after examining our data. We used many different charts for various visualization options while examining the relationships between the variables in our data. We used multiple graphs such as barplot, lineplot , box plot, scatter plot, countplot, violinplot, jointplot, regplot to better understand the data.
[^4]:In the scatter plots we created using latitude and longitude, a partial map of this region is formed from all the houses in this region. We colored different price bands under the type heading according to pricing, which is our most important criterion. And we were able to observe how intense the price ranges we colored on these maps were in which regions of the map.
[^5]:It is clearly seen in which types the distribution mentioned in the image is intense. However, making sense of the regions dotted on the map can sometimes be tiring, and in such cases, the types can be printed on their own; Checking the points in that way strengthens the analysis.
[^6]:To explain with a small example, in the first graphic we colored with type 5' pink, it is close to impossible to choose among other dominant colors. With this method we use, we see that type 5 has a small place on the map.
We continue the same step for other types with colors that we cannot easily choose from the graphic, and after our checks, we observe that the graphic is not misleading and that type 2-3-4 is much more intense than the others.
[^7]:In this graph, we want to observe how important the square meters of the houses are in pricing. According to our chart, we can see an accumulation in the range of 1000-3000. As the square meter increases, we can say that the prices increase with high jumps, and there are deviations that we call extreme value for houses with 1000-3000 square meters. We can infer that there is an increase in relation to other parameters, independent of square meters.
[^8]:We are looking at the same variables in this lineplot chart, but the regplot we used above allows us to interpret the results much more clearly. We can say that the prices, which we have detected deviations for this chart, do not give a very healthy result as problems may occur while observing the prices due to the color getting lighter.
[^9]:In our FacetGrid chart, we observe the prices of the types we have previously classified.
[^10]:In this graph, where we observe the relationship between the scores of the houses and their views, we can see that the score increases in direct proportion to the view.
[^11]:In another histogram graph, where we observe the relationship between the state of the house and the year it was built, we infer the newer the better the condition of the house.
[^12]:We observe that the square meters of the houses with sea view are higher than the houses without sea view.
[^13]:In our barplot and lineplot composite chart, where we look at the effect of the square meter of the house on the scores, we confirm that the score increases as the square meter increases.
[^14]:We examine mean squared error, root mean squared error and r-square values in our K neighbors regressor model. We continue our analysis by placing the value of 6, which we see in common, into the input in our knn regression model.
[^15]:After examining our data, we need to create some regression models and decide on the best one.
[^16]:In order to reach the healthiest regression models we have created, mean squared error and root mean squared error values are the lowest (since they are error values); We want to choose the one with the highest r-square value.
[^17]:Random forest regressor and artificial neutral networks options from the graphics we created to be able to choose, have the lowest mean squared error and root mean squared error values; We see that they are the regression models with the highest r-square value.
[^18]:After comparing the values we reached at the end of our analysis, we decide that the most healthy model is the random forest regressor.
