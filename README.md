# Data_Scientist_Writing_A_Data_Scientist_Blog
Analysing Airbnb data to write a blog post. The blog post was published on [medium](https://medium.com/@ali5s.atif/you-can-become-an-airbnb-host-bac214da1124)

## Project Motivation
The purpose of this project is for you to practise my technical skills and follow the CRISP-DM framework.

Here is an overview of the main steps in this project, following the CRISP-DM process:
- Determine three questions I am interested in answering.
- Extract the necessary data to answer these questions.
- Perform necessary cleaning, analysis, and modeling.
- Evaluate results.
- Share insights in a blog post.

## Acknowledgements
Thank you to Kaggle for the data. You can find the Context, Content other descriptive information at the Kaggle link available [here](https://www.kaggle.com/datasets/airbnb/seattle). Otherwise, feel free to use the code here as you would like!

## Libraries
Python3 was used. Here are the Python libraries used in the project:
Numpy
Pandas
Seaborn
matplotlib.pyplot
Math

## File Used
'listings.csv', Original dataset in csv format
'Investigating Seattle airbnb data.ipnb', notebook used for analysis

## Findings
For Airbnb listings in Seattle, it can be seen from the analysis above that:
- When the distance from the city centre is higher, the review score rating tends to be higher. This could be attributed to better quality properties away from the city centre i.e. size, amenities, etc.
- The correlation matrix also shows price is not affected by the review score, suggesting the Airbnb market in Seattle could have inelastic demand. This could be due to customers correctly anticipating the quality of the listings to be in line with the expected price paid.
- The number of amenities does marginally impact the overall review score rating of the AirBnB listings. Similarly, listings with more amenities tended to have a slightly higher price.
- As expected increasing the number of beds has no relationship with the review score rating. This is good news for people who may want to join the market with only i.e. 1 bed as it won't affect the listings rating.
- Similarly, landlords no longer have to worry if hefty cleaning fees impact their listings rating as the data suggests there isn't much of a correlation between the two variables. Of course, landlords should be sensible when deciding a cleaning fee as the fee amount should reflect the number of beds there are in their listings.
- The analysis from the dataset showed the highest-rated neighbourhoods listed tended to be further away from the city centre. In contrast, the neighbourhoods with the most amenities were also some of the closest neighbourhoods to the city centre.
