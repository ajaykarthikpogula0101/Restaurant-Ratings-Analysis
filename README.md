# Restaurant Ratings Analysis

## Table of Content
* [Case Study](#case-study)
* [Dataset Description](#dataset-description)
* [ER Diagram](#er-diagram)
* [Data Cleaning](#data-cleaning)
* [Data Analysis](#data-analysis)
* [Dashboard](#dashboard)

## Case Study
Restaurant ratings in Mexico by real consumers from 2012, including additional information about each restaurant and their cuisines, and each consumer and their preferences.

## Dataset Description
Our dataset consists of the following observations:

### Consumers
| Column | Description |
|--------|-------------|
| Consumer_ID | Unique identifier for each consumer |
| City | City where the consumer lives |
| State | State where the consumer lives |
| Country | Country where the consumer lives |
| Latitude | Latitude where the consumer lives |
| Longitude | Longitude where the consumer lives |
| Smoker | Whether the consumer smokes or not |
| Drink_Level | Whether the consumer is an abstemious, casual, or social drinker |
| Transportation_Method | Whether the consumer transports on foot, by public transport, or by car |
| Marital_Status | The consumer's marital status (single or married) |
| Children | Whether the consumer has dependent/independent children or kids |
| Age | The consumer's age |
| Occupation | The consumer's occupation (student, employed, or unemployed) |
| Budget | The consumer's budget (low, medium, high) |

### Consumer Preferences
| Column | Description |
|--------|-------------|
| Consumer_ID | Unique identifier for each consumer |
| Preferred_Cuisine | Types of food the consumer prefers |

### Ratings
| Column | Description |
|--------|-------------|
| Consumer_ID | Unique identifier for each consumer |
| Restaurant_ID | Unique identifier for each restaurant |
| Overall_Rating | The overall rating (0=Unsatisfactory, 1=Satisfactory, 2=Highly Satisfactory) |
| Food_Rating | The food's rating (0=Unsatisfactory, 1=Satisfactory, 2=Highly Satisfactory) |
| Service_Rating | The service rating (0=Unsatisfactory, 1=Satisfactory, 2=Highly Satisfactory) |

### Restaurants
| Column | Description |
|--------|-------------|
| Restaurant_ID | Unique identifier for each restaurant |
| Name | The restaurant's name |
| City | The restaurant's city |
| State | The restaurant's state |
| Country | The restaurant's country |
| Zip_Code | The restaurant's zip code |
| Latitude | The restaurant's latitude |
| Longitude | The restaurant's longitude |
| Alcohol_Service | Whether the restaurant serves no alcohol, wine & beer, or a full bar |
| Smoking_Allowed | Whether any smoking is allowed |
| Price | The restaurant's price (low, medium, high) |
| Franchise | Whether the restaurant is a franchise |
| Area | Whether the restaurant is in an open or closed area |
| Parking | Whether the restaurant offers parking (none, yes, public, valet) |

### Restaurant Cuisines
| Column | Description |
|--------|-------------|
| Restaurant_ID | Unique identifier for each restaurant |
| Cuisine | Types of food the restaurant serves |

## ER Diagram
![ER Diagram](ER.png)

## Data Cleaning
_(Coming soon)_

## Data Analysis
_(Coming soon)_

## Dashboard
_(Coming soon)_
