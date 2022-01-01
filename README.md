# Housing_Price_Analysis

This project is made by Ling Li👩🏻‍🏫 and Chao Wang👩🏻‍🌾(me).

The data were downloaded from Redfin (https://www.redfin.com/), with which we analyzed the housing price🏘 of five cities in Bay Area California:
1. Campbell
2. Cupertino
3. Santa Clara
4. Sunnyvale
5. West San Jose

Ps. Redfin does not have result of "West San Jose"(WSJ). This might because WSJ is not the name of an existing city, but a region. Thus, I searched 6 post codes that make up WSJ: 95117, 95118, 95124, 95128, 95129, 95130.

We did 5 steps for Data Cleaning:
1. Delete the unnecessary column of each data frame.
2. Delete the wrong data.(some error results returned by the Redfin search engine)
3. Repair the inconsistent letter case.
4. Delete the outlier data.
5. Delete the missing data.
In the end, 3257 house pricing cases remain and could be used for following research.

In this project, we answered questions below:

1. What is the relationship between House Pricing and its Self-Attributes?

Self-Attributes are: Property Type(Single Family House or Townhouse), City/ZIP, Beds, Baths, Price, Square Feet, $/Square Feet, HOA, Lot Size, Year Built.

2. What is the relationship between House Pricing and Covid-19?

2.1 During Covid-19, Does the house pricing grow faster than before?

2.2 During Covid-19, Does the houses with larger yards sell for higher prices?

2.3 During Covid-19, Does the price of houses with convenient transportation has not risen as fast as other places?
