## Project Description

For this project, we're looking into the kings county housing dataset, and deciding which houses are the most "valuable" to purchase in order to maximize our profitability of potentially reselling it, or getting the best "bang for our buck".

### The Data

The data used comes from one source:

Kings County Housing Data
This data is found in the Data folder

![image](https://user-images.githubusercontent.com/68972505/112782735-b62f4500-901b-11eb-86fb-380a6c9d81da.png)


### Key Findings

What makes a home valuable?

This question is the most important of all and helps us decide which houses we are going to purchase to obtain the most financial upside.  To do this we first looked to see which variables were most correlated with the house price.

![image](https://user-images.githubusercontent.com/68972505/112782683-97c94980-901b-11eb-86ca-ae91f7bceddf.png)

Here we can see that our data has a left skew, which makes sense because there are more homes available in a range of lower budgets that higher.

Our strongly correlated variables were sqftliving, bedrooms, bathrooms, sqftlot, grade, sqftliving15, sqftabove, and sqftlot15.  There was a slight left skew when looking at the initial pricing distribution however it turned out to be approximately normally distributed.  Below we can see via the heatmap.

![image](https://user-images.githubusercontent.com/68972505/112782850-fdb5d100-901b-11eb-84c3-1a67659dd264.png)





#### Recommendations
1. When looking to purchase a home, evaluating the upside of the location is paramount.
2. Ask the people that are familiar with the houses.  The kings county grading system was a great predictor and those that are familiar with the area are usually able to give better input on the value.

## Conclusion

The following made up the most important features that affect the price of a home in the dataset:

Zip Code- LOCATION, LOCATION, LOCATION.  The real estate mantra holds true, location is one of the biggest factors in how housing prices are determined.

Grade- Kings County seems to know their houses best, their grading system was one of the strongest features in our model.

Sqft-living- More money for more house.  Makes sense right?  Try not to add any more bedrooms though.

Bathrooms- The more bathrooms the merrier, as long as your wallet can oblige.  

Location, size, and number of bathrooms were the strongest features in our best model.  We recommend focuses on these when looking to maximize the potential value a home has/can have if you're looking to remodel/flip.

#### Future Work

Would like to investigate the price increase for incremental changes to number of bathrooms/bedrooms in the future to see where the breakpoint is in marginal utility.  Another interesting thing to look into would be to access how the Kings County system grades the houses in the dataset to see which of the features they're putting the most importance on, and, if that would carry over to other areas as well.

