## Competitor Selection for FMCG products
This project involves the process of selecting the top five closest competitors in the market. This selection is based on both the
fundamental attributes of weight/volume, price and category, as well as sales-related attributes, including market share, penetration rate, and distribution rate.

The initial step involves extracting volume/weight units from product names using regular expressions, requiring a few merges and concatenations to account for various cases (numeric/alphabetic).
Below is the result of this unit/value extraction from the product name:

<img width="193" alt="image" src="https://github.com/ZahraAfjehie/ZahraAfjehie/assets/13051084/1614d14a-ca71-4260-9a89-444e8c0b7ff0">




Subsequently, the units are standardized. In the following step, sales-related attributes are computed using multiple merge and group by techniques, and then normalized.The clustering process consists of two stages: first, clustering based on fundamental attributes, followed by clustering based on sales-related attributes. The final step encompasses the definition of two functions: the first function extracts the precise product name from the data frame, while the second function retrieves the top-five competitors cluster for that product.
Here is an example from the project's results, displaying the leading five competitors for a particular yogurt product:



<img width="335" alt="image" src="https://github.com/ZahraAfjehie/FMCG_Project/assets/13051084/96ef9c96-8bc4-46c2-968b-fafc73d5f7da">



Here are the scatter plots representing clustering metrics, with different clusters depicted using varying colors to represent products within the milk, yogurt, 
and cheese categories:



<img width="332" alt="image" src="https://github.com/ZahraAfjehie/FMCG_Project/assets/13051084/7316d510-f12d-4479-aff4-35c264fa880d">



