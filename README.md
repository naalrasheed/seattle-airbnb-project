# seattle-airbnb-project

# Project Motivation
Finding the right place to stay in Seattle might be a hustle for many people when visiting, and pricing plays a significant role in the booking process. Thus, in this analysis, which part of Udacity’s Data Science Nanodegree, I will try answering three main questions as shown below:
 
1- Can seasonality increase prices?

2- What are the main factors that affect prices?

3- Can you save money while looking for a place?

Before starting the analysis, let us understand how pricing works in Airbnb. According to their website, the final price can be broken into three types as listed below:

1-   Airbnb: "Guest service fee charged by Airbnb—this provides 24/7 community support and helps everything run to ensure the system runs smoothly."

2-   Host: Nightly rate, Cleaning fee, and Extra guest fee.

3-   Other: Currency exchange fee, VAT, and other local taxes required in certain countries/cities.

# File Description
Data Collection: 

The dataset is publicly accessible and was collected from Kaggle (https://www.kaggle.com/airbnb/seattle), it has three different CSV files originally generated from Airbnb, and each file has its unique information. Below are the descriptions for each file:
•	listings.csv: The file has the property's location, host info, guest fees, cleaning fees, amenities, and other features.
•	calender.csv: The file has the property's listing ID, price, and availability.
•	reviews.csv: This file reviews the properties listed, but it will not be used in this analysis.

# Summary
Certain features can affect the reservation price, such as the size of the property, # of bedrooms, # of beds, # of bathrooms, etc. In addition, prices start to increase during summer, and it peaks during July. Hopefully, this simple analysis helps you select the best time to visit Seattle and what features can save you some money.
