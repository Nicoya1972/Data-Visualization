# Data-Visualization

House Prices Data Visualization Project

This data set contains information about house prices. In this project we explore the price of houses based on (3) criterias. Neighborhood, style and price. I will fous on what impact does the size, neighborhhod and style have on the over all price of the house.

data_visualization_slides, conatins the slide show presenting the data.


 data_visualization.ipynb, containg the data visualization and explanation of each steps.
 
 # Sources
 Multivariate
https://www.kaggle.com/residentmario/multivariate-plotting

Bivaraite
https://regenerativetoday.com/understand-the-data-with-charts-and-plots-with-medical-data/

Univariate
https://www.kaggle.com/residentmario/univariate-plotting-with-pandas

nbconver to slides
https://medium.com/@mjspeck/presenting-code-using-jupyter-notebook-slides-a8a3c3b59d67

# Summary of Findings

Data analysis shows Victorian style houses account for 50% of the total homes in the data set. The highest priced home, an eight bedroom Victorian style, is worth $3.68 million. Victorian style houses offer the greatest square footage, the largest number of bedrooms and is the only style which offers 6,7 and 8 bedrooms. The Lodge style homes hold the lowest values, have the fewest bedrooms and smallest square footage. Data shows that home value increases with number of bedrooms. Neighborhood B contains the most houses, followed by A and lastly neighborhood C which has the fewest homes. Neighborhood B holds the most expensive homes, conversly, the most affordable home is also in Neighborhood B.  


### Key Insights for Presentation

For this presentation, I use various graph styles to visually depict the realtionships between five home variables (house style, neighborhoods, square footage, price, and number of bedrooms). I start the presentation with univariate data exploration. I use a histogram to show which neighborhoods contain the most homes, a pie graph to show relative percentages of the three home styles (Victorian, ranch, and lodge), and a histogram which shows the number of houses for each price. 

The aformentioned graphs show Neighborhood B contains the most houses, Victorian is the dominant style as it comprises nearly 50% of all home styles, and the number of houses less than 1 million dollars far exceed the number of more expensive homes.  I move on to bivariate exploration in which box plots show the trends in home price based on home style;  a violin plot graph depicts home price trends based on neighborhoods; a scatter plot shows how number of bedrooms affects home price. The bivariate graphs illustrates that the most expensive homes are Victorian, while the least expesive are Lodge. Comparing the box and violin plots, which shows Neighborhood B and Victorian houses are the most expensive homes, we can understand that the most expensive homes are infact Vicorian homes in Neighborhood B. This presentation is concluded with two multivariate box plots. 

The fist depicts the relationship of home area and neighborhood by style.  The second illustrates the relationship between number of bedrooms and price in each style home. A person looking for a home with 6 or more bedrooms will be confined to Victorian style with an expensive pricetag.  If a person is looking for a four bedroom home they will be able to find all three styles with a similar value. Homes with one or no bedrooms are only available in the Lodge style and are the least expensive.


### Data Shortcomings.

It would have been great if the data set containg age, sex and race breakdown.  Also isntead of the neighborhood being describe as a, b and c, if they were actual places.


