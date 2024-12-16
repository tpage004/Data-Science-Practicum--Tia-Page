# MSDS692 Practicum I Summary
This project titled "Recipe for Success: Data-Driven Strategies for New Restaurant Owners in San Diego," aims to provide data-driven insights to help new and prospective restaurant owners succeed in San Diego's competitive market. The three main goals of this project are to identify key success factors for restaurants in San Diego, recommend optimal locations in the city to establish one's restaurant, and find strategies to enhance customer experience. All of these factors are essential in navigating the competitive nature of San Diego's food industry.

This project utilizes Python to analyze data from various sources, including restaurant reviews, demographic data, and geographic information. The code is organized into sections for data collection, cleaning, exploratory analysis, machine learning, and visualization to achieve these goals. By leveraging these techniques, this project empowers aspiring restaurant owners with the knowledge to thrive in San Diego's culinary landscape.

The results of the machine learning models and data visualization techniques were able to provide useful insights that aspiring restaurant owners can use to make business decisions with the data that was available. The three main goals of this project were achieved, as data visualization plots, along with machine learning models such as the Random Forest Classifier and TextBlob sentiment analysis model, were able to reveal the key factors of a restaurant being successful in San Diego, optimal locations to establish business, and ways to maintain customer satisfaction. 

From the Random Forest Classifier model, it was revealed that review count and food category were the two most important features linked with a restaurants success. Restaurants in the data set with an overall rating of 4 or more stars were classified as "successful." It was found that most restaurants with a rating of 4 stars or higher had the highest review counts. This not only speaks to the popularity of the restaurants, but their high visibility as well. This model also showed that the category of the food served contributed to a restaurant's ratings. Through this model, it was shown that in the city of San Diego, certain types of cuisine are more preferred than others and that restaurants that serve them tend to be rated more favorability. The outputted results of the Random Forest Classifier showed that restaurants that serve Asian and Italian food tend to be ranked higher by reviewers than restaurants that serve other types of cuisine. 

In addition, the TextBlob Sentiment Analysis model also revealed factors that contribute to certain review ratings. This model produced a Word Cloud for each star rating (1-5 stars) by extracting the key words from the "review" column of the data set. The Word Cloud for 1-star reviews had many words associated with fast food, such as "drive thru" and "fast food." The words "customer service" and "drive thru" lead me to believe that not only are most of the 1-star reviews originate from fast food restaurants, but they are created by customers due to poor customer service. As for the 5-star reviews, the Word Cloud shows that customer service, location, and the food itself largely contributed to the high ratings. 

As for determining the optimal location to establish a new restaurant, several data visualization guides helped to recognize the appropriate areas for business. Three bar plots in the "Data Visualization" section of the project's code display the densities of restaurants by specific neighborhoods and food categories. One of the codes allows new and prospective users to insert a food category (ex. American, Asian, Italian, etc) in order to see which areas of San Diego are less competitive when it comes to that specific category. These data visualization guides revealed that Downtown San Diego has the highest density of restaurants overall. They also revealed that Downtown San Diego has the highest density of Italian restaurants. If a new and prospective restaurant owner wanted to open a new Italian restaurant in San Diego, it would be advised to view the bar plot and focus on neighborhoods with the lowest density of Italian restaurant in order to avoid competition, while also looking at the bar plot showing neighborhoods with the highest restaurant number of review counts in order to avoid areas with the least amount of business.

In summary, this project provides valuable insights for individuals who are just getting started with establishing a new restaurant or those who aspire to own a restaurant in San Diego. Although there is not much financial data for these restaurants (ex. budgets, profits, revenues, etc), the available data set from this project and its findings nevertheless provide a good starting point for achieving success in San Diego's competitive food industry. 

# Instructions for Downloading Data Sets
1. Go to the "Data" folder and view the listed files.
2. Click on a file, then click "download raw file." This will prompt the data set to download.