## Rental Price Estimation
The goal of this project is to analyse and develop a machine learning model to predict the rental price of a house. Advanced regression techniques (random forest and gradient boosting) are deployed to predict the rental price.

### Data Overview
This data set consists of 8,111 records with 9 features and the original data set is available on DataCamp website. 

#### Features

* id: ID of the property
* latitude: location (latitude) of the house
* logitude: location (logitude) of the house
* property_type: Type of property such as Apartment, Condominium, etc. 26 different types of property is listed. 
* room_type : type of rooms to be rented out. 4 different room types are listed. 
* bathrooms : number of bathrooms in the house/room range from 0 to 14 rooms. 
* bedrooms : number of bedrooms in the house/room range from 0 to 14 rooms.. 
* minimum_nights : mimum number of nights to be stayed. 
* price : rental price ranged from zero to 10,000. 

#### Background
Inn the Neighborhood is an online platform that allows people to rent out their properties for short stays. At the moment, only 2% of people who come to the site interested in renting out their homes start to use it.

The product manager would like to increase this. They want to develop an application to help people estimate how much they could earn renting out their living space. They hope that this would make people more likely to sign up.

### Business Requirements
The product manager wants to develop a way to predict how much someone could earn from renting their property and the prediction price not to exceed more than 25 dollars off of the actual price. 
