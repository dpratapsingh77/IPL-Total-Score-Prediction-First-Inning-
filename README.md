# IPL-Total-Score-Prediction-
## Machine Learning Project that predicts the IPL match score (First Inning only).

![IPL](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.cnbctv18.com%2Fhealthcare%2Fipl-2020-suspended-till-further-notice-bcci-says-game-will-commence-when-its-safe-5706651.htm&psig=AOvVaw1GADIv7y-deWUba7e1InTk&ust=1596034951122000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCJC_mNmb8OoCFQAAAAAdAAAAABAD)

## Dataset
Data Source : Kaggle.com

The dataset 'IPL Data Set.csv' consists of ball-to-ball informations about every match of IPL from Season 1 to 10 ie: (2008 to 2017)

The data consists of 15 columns. We need to separate data into attributes and labels. Here our label is total score which is stored in variable y. Also, the data contains some columns which do not play any role in determining the total score so we can drop those columns. So, I have dropped first seven columns(mid, date, venue, bat_team, bowl_team, batsman, bowler) and stored the required attributes in variable named X.

## Dependencies
 • Python - 3.6
 • Scikit-Learn
 • Pandas
 • Numpy
 • Matplotlib
 • Seaborn

## Algorithms Used:
  • Linear Regression
  • Decision Tree Regression
  • Random Forest Regression
  • Gradient Boosting (XGBoost) 
