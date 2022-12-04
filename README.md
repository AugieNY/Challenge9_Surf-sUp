# Challenge9_Surf-sUp

## Overview of the Analysis
The objective of the analysis is to utilize SQL Alchemy in Jupyter notebook, and deep dive into a sqlite file's data. 
The dataset is retrieving temperatures in Oahu to provide a feasability to open an ice cream shop business. The main part is focusing on June and December's temperature, the two months that will determine if the new business can stay opened year round. 

## Results
Using pandas function, python, and SQL Alchemy, we were able to extract the summary statistics of both June and December.

###For June, 
![June temperatures](https://user-images.githubusercontent.com/75656368/205470085-1c54801a-0f57-4f8e-b33b-8099b9e38f35.png)
We observe that the average temperature between 2010 and 2017, is 75°F. The minimum being 64°F and the maximum 85°F.

###For December,
![December temperatures](https://user-images.githubusercontent.com/75656368/205470272-97b39107-dbc4-4570-8779-a33e876fbd07.png)
We observe that the average temperature between 2010 and 2017, is 71°F. The minimum being 56°F and the maximum 83°F.

### Deeper Analysis
We added an extra analysis for all the winter months, as December may not be the coldest winter month.
For October to April between 2010 and 2017, we get the following statistics:
![Winter temp_OcttoApr](https://user-images.githubusercontent.com/75656368/205470478-10a81f51-8254-44ae-a696-97b059954e1a.png)
The minimum goes down to 53°F within these 6 months.

Given the global warming concerns, we thought to look at the last 3 years minimum to see if there was an increase in winter temperature versus all years (2010 to 2017).
![L3Y_Winter](https://user-images.githubusercontent.com/75656368/205470768-225b3ecb-6c46-4dff-9b96-96b790122662.png)
The minimum is now 56°F and the maximum is 84°F. 
It is 3 degrees higher.


## Summary
We can now conclude that it can get chiller in the winter months but is there really a bad weather for ice cream? Knowing that the winter are getting warmer, the business of an ice cream shop may be open all year round with a projected increase in business exponential in winter in the next years.
Also, is there really a bad weather to eat ice cream?


