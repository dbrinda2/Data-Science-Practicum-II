# Data-Science-Practicum-II
An Analysis of Bike Shared Systems by Drew Brinda at Regis. 

Full Video Presentation link on youtube is at: 

## Goal
The problem I am trying to assess is by helping bike shared companies know how many bicycles should be available at each specific location in a particular city depending on time, season, weather, temperature and other factors.
## Datasets
The datasets I will be using are from Kaggle. There are these 2 different datasets:

There is both a train and test csv dataset.The datasets are historical hourly rental data spanning two years of worldwide bike rental systems. The training set is comprised of 19 days of each month while the testing set is the 20th day until the end of the month. Each dataset contains the fields datetime, season, holiday, working day, weather, temp, humidity, wind speed, registered users, unregister users, and count of total renters. All these factors will be considered when predicting the number of bike renters at a specific time.

## Data Cleaning
Used Python for the data cleaning aspect of this project. Went through each of my 2 datasets to clean the fields and values.

Example: Combining similar values for a specific weather type for a game. Changing Outdoors to Outdoor value as well as other misspellings in the dataset. 


## Exploratory Data Analysis

Below is some of the R code that I did orginally to analyze my datasets before starting to model. 

![Snip20211014_5](https://user-images.githubusercontent.com/92532095/137372798-4e3ccd2d-97f3-45e6-ac14-bb9ff6cdc7f2.png)

![Snip20211014_6](https://user-images.githubusercontent.com/92532095/137372828-8a9cdee2-5bd4-4fd0-ac7d-df3153e24053.png)

## Data Vizualizations

Below are some of the main graphs that I produced comparing all the variables to see the major trends. The rest of them will be found and discussed in my final video link.

<img width="763" alt="Screen Shot 2022-12-10 at 8 29 16 AM" src="https://user-images.githubusercontent.com/92532095/206863290-a68907b9-c627-4710-8b87-eb2056d0e549.png">

<img width="699" alt="Screen Shot 2022-12-10 at 8 33 28 AM" src="https://user-images.githubusercontent.com/92532095/206863297-53bf3241-aaa4-45d1-8410-451cf186a95d.png">

## File Structure in Repository

PythonCleaning.ipynb : Python source code of full cleaning file of 3 datasets that I worked with.

EDA and Modeling.R : R source code of exploratory data analysis and modeling/plots of variable relationships.

Drew Final Video .pptx: Powerpoint Presentation of final video slides.

InjuryRecordSample.csv: Sample of Injury Record Dataset 

PlayListSample.csv: Sample of Play List Dataset

PlayTrackSample.csv: Sample of Player Track Dataset
