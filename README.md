# Data-Science-Practicum-II
An Analysis of Bike Shared Systems by Drew Brinda at Regis. 

Full Video Presentation link on youtube is at: https://youtu.be/jhqWOmsE6VM

## Goal
The problem I am trying to assess is by helping bike shared companies know how many bicycles should be available at each specific location in a particular city depending on time, season, weather, temperature and other factors.
## Datasets
The datasets I will be using are from Kaggle. There are these 2 different datasets:

There is both a train and test csv dataset.The datasets are historical hourly rental data spanning two years of worldwide bike rental systems. The training set is comprised of 19 days of each month while the testing set is the 20th day until the end of the month. Each dataset contains the fields datetime, season, holiday, working day, weather, temp, humidity, wind speed, registered users, unregister users, and count of total renters. All these factors will be considered when predicting the number of bike renters at a specific time.

## Data Cleaning
Used Python for the data cleaning aspect of this project. Went through each of my 2 datasets to clean the fields and values.

## Data Vizualizations

Below are some of the main graphs that I produced comparing all the variables to see the major trends. The rest of them will be found and discussed in my final video link.

<img width="763" alt="Screen Shot 2022-12-10 at 8 29 16 AM" src="https://user-images.githubusercontent.com/92532095/206863290-a68907b9-c627-4710-8b87-eb2056d0e549.png">

<img width="699" alt="Screen Shot 2022-12-10 at 8 33 28 AM" src="https://user-images.githubusercontent.com/92532095/206863297-53bf3241-aaa4-45d1-8410-451cf186a95d.png">

<img width="618" alt="Screen Shot 2022-12-10 at 8 40 08 AM" src="https://user-images.githubusercontent.com/92532095/206863334-a296a188-5618-40f0-8118-b5dd662ab115.png">

<img width="431" alt="Screen Shot 2022-12-10 at 8 43 52 AM" src="https://user-images.githubusercontent.com/92532095/206863340-0b300f28-b577-4b85-843c-9ec81608d679.png">

<img width="443" alt="Screen Shot 2022-12-10 at 8 44 51 AM" src="https://user-images.githubusercontent.com/92532095/206863348-752c9f08-ff68-48be-a7c7-d00cf0303291.png">

<img width="415" alt="Screen Shot 2022-12-10 at 8 44 56 AM" src="https://user-images.githubusercontent.com/92532095/206863353-55bfe411-68d6-4e35-a2af-4722e65fc4d9.png">

<img width="430" alt="Screen Shot 2022-12-10 at 8 48 12 AM" src="https://user-images.githubusercontent.com/92532095/206863363-feaa2d4a-0713-4701-9a27-8c06b31cc3c9.png">

## Machine Learning Models

<img width="621" alt="Screen Shot 2022-12-10 at 9 07 10 AM" src="https://user-images.githubusercontent.com/92532095/206863374-28c852ee-fd85-4047-8a72-afaef4210644.png">

## File Structure in Repository

BikeSharedSystemCode.ipynb : Python source code of full project file of 2 datasets that I worked with.

Drew Final Video .pptx: Powerpoint Presentation of final video slides.

train.csv: Training Bike Shared System Dataset 

test.csv: Testing Bike Shared System Dataset 

