# upgraded-succotash
Market Share Data Analysis using Discrete Choice


We will estimate the effects of certain characteristics of 11 different carbonated soft drinks on consumers' choices of them. Instead of using individual consumer's choice data, we will use the market share data of these soft drinks only. The data file is “Soda_choice_data.csv”.

The market shares of the 11 soft drinks are measure weekly for 52 weeks. Because a consumer can choose not to buy soft drinks, there is also a weekly market share for the "outside goods". The choice set is denoted as {"1", "2", ..., "11", "0"}, where 1 through 11 are the ID's of the 11 soft drinks and 0 represents the outside goods (choosing not to have soft drinks). These 11 soft drinks belong to 3 different brands, which are labeled as brand 1, 2, and 3 in the data. We have the following columns in the data.

MarketShare:	The market share of the soft drink
ProductID:	 The ID of the product; 0 means the outside goods
Week:	The week indicator 
Brand:	The brand ID of the soft drink
Sugar:	The level (1 to 5) of sugar content; a greater number means higher sugar level
Caffeine:	The dummy for whether the drink contains caffeine {1=Yes, 0=No}
Promotion:	Level of promotion/discount; a greater percentage means deeper discount

