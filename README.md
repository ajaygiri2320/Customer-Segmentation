This project was aimed at understanding the customer purchase patterns for modifying the marketing strategy for each customer type. 
This is achieved by performing three key steps: Segmentation, Targeting and positioning the products. 

•	Segmentation - It is process of grouping the customer into a comparable group using different customer characteristics such as Demographic, Geographic, Psychographic and Behavioural patterns. Here, we segment our customer data into 4 different segments using K-means clustering technique on top of Principal component analysis (PCA). 

•	The four customers segments segmented using their Demographics, Income, Education, Occupation, etc are as follows.
	
 o	Segment 1 - This is highly standard since it has the customers with avg age of ~29 who have moderate income and occupation and lives in small & mid-sized cities (from settlement size)

 o	Segment 2 - This is fewer-opportunities since it has the customers with avg age of ~35 who have low income & occupation from the other segments and lives in small cities (from settlement size)
	
 o	Segment 3 - This is career-focussed since it has the customers with avg age of ~35 who have high income & occupation and lives in big cities (from settlement size)
	
 o	Segment 4 - This is Well-off since it has the customers with avg age of ~55 who have high income & occupation and lives in mid-sized & big cities (from settlement size)

•	Targeting - Evaluating the potential profits from each Segment and deciding which segments to focus on taking into factors like Segment size, Expected Growth, and Competitor's offerings. This is out of scope for this project as it is part of advertising. 	

•	Positioning - Evaluates what products can be offered to the customers that would have the closest characteristics to the customer needs which is also known as Marketing Mix. 
    o	Marketing Mix Modelling - This model answers the key questions like whether customer will buy the product? (Calculate purchase probability using Logistic Regression), which brand of products will they choose? (Calculate brand choice probability using Logistic Regression), and How much Qty of products will they purchase? (Calculate purchase quantity using Linear Regression).

•	Elasticity - Elasticity is broadly defined as % change in outcome of Interest (Demand for product in our case) to % change in price of the product. We combine the elasticity model with Logistic Regression model to calculate the own price elasticity and cross price elasticity with respect to other brand products.  

o	Own Price Elasticity – This is the measure of price threshold at which customers tends to remain non elastic i.e. elasticity < 1 meaning that even with slight change in the price, our customers remain loyal to our products. Once the elasticity = 1, our customers tend to become elastic that is with further increase in the price of our product, the customer tends to be swayed away for the competitor’s product. 

o	Cross Price Elasticity – This is the measure of price threshold at which customers tends to remain non elastic meaning that even if other brands reduce the price of their products still our customers will remain loyal to our products. Do note that the purchase probability of our products still decrease unless we also try to reduce our price to cope with other brand’s prices. 

•	Next we try to understand the impact of price on individual segments and each segment will be sensitive to different price point and products. 

•	Next we also try to understand the impact of promotions and brand choice for each segment. 




