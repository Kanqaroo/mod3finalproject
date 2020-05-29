# mod3_final Project

## Synopsis

The goal of my project was to predict which variables of beer would determine the style of beer(Ale, Lager, Stout, etc..). I was lucky enough to find a open crowd-sourced database called brewerydb that provided information about all types of beers. I was able to pull data from the database with an API key, But they only provided a limited amount of access due to being a free account. Luckily i was able to get a gather enough data. I needed to drop out alot of empty variables that weren't filled in by the contributors. I would like to work with a KNN model first because i believe, beers that have similar styles would have similar variables and thought KNN would be perfect because its looking for clusters and nearby neighbors. I would also like to use a Random forest classifier. If the style of beer is not determined by similarly clustered attributes,then i dont know which attribute is contributing the most to determining the style. I need the model to determine which variable is contributing the most. Lastly i also went with xGBoosting model to optimize each variable that was being tested.

### What I Found out

So according to the data, the highest contributor to predicting what type of beer a beer is, is the SRM or standard reference method. It's a chart that determines the color of the beer. Originally i tested to see if brewery and category of beer would be the most extreme deciding factors and tested to see if that was correct, but only in the XGB model, was category had significance in variable importance. And even in XGB SRM was still high in the deciding factor.

### If i had more time

I would've liked to start predicting breweries based on image recognition. In the dataset there included beer pictures of their labeling, so i thought maybe if i could create a predictive model to see if i upload an image of a beer, the prediction model could predict a brewery.

## My Files

### MOD_3 Final Project Modeling.ipynb

mod_3 Final Project modeling has all my EDA, and Models

KNN Model
RFC Model
XGB Model

### MOD_3 Final Project DB Search.ipynb

Webscrapping data
creating dataframes
creating csvs of dataframes

### beer_final2.csv

final usable values

### beer1.csv

raw webscrapped data about beer

### brewery1.csv

webscrapped data about brewery
