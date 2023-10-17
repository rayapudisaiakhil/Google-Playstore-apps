# Google Play Store App Analysis 

This project performs analysis on data from the Google Play Store to gain insights into app performance.

## Data

The dataset contains information on over 10,000 Android apps from the Google Play Store.

Key data fields include:

- App name
- Category
- Rating  
- Number of reviews
- Size
- Number of installs 
- Type (free vs paid)
- Price
- Content rating

The raw data has issues like missing values and inconsistent formats that need to be cleaned.  

## Analysis

The project focuses on exploring relationships between:

- Category and number of installs
- Category and app rating
- Category and installs for paid apps

## Results

Key findings from the analysis:

- Games have the highest number of installs
- Events apps have the highest user ratings
- Family apps have the most installs among paid apps
- App ratings are highest for Events category
- Paid apps in Events category have very few installs 

## Models

A CatBoost model is built to predict the market receptivity of an app based on:

- Location
- Category 

The model achieves 76.4% accuracy.

## Usage

The analysis is implemented in R. To run:

- Install required libraries
- Run the RMarkdown file

## Contributing

Contributions to improve the analysis are welcome! 
