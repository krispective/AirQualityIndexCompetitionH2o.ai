# AirQualityIndexCompetitionH2o.ai
Monitoring it and understanding its quality is of immense importance to our well-being. In this hackathon, participants will have the opportunity to use their data analysis and machine learning skills to forecast the AQI for major Indian AQI stations for the upcoming 28 days.

The dataset consists of the historical daily average of several air pollutants which directly affect the Air Quality Index.

Participants will be required to analyze this data and use it to build accurate models that can predict the AQI for each station.

Dataset Description
The dataset consists of historical daily average pollutants, including SO, CO, PM2.5, and other important factors that affect the air quality index. Keep in mind that different AQI stations have different lengths of historical data. Your challenge in this competition is to forecast average AQI levels across different stations in India for the next 28 days.

Files
train.csv - 2 years of historical data for 40 Indian AQI stations
ID_Date: Unique identifier of state, stationid and date
StateCode: State where the AQI station is located
StationId: AQI station ID
Date: Date when the observations where recorded
PM2.5: Average PM2.5 pollutant level
PM10: Average PM10 pollutant level
O3: Average O3 pollutant level
CO: Average CO pollutant level
SO2: Average SO2 pollutant level
AQI: Average Air Quality Index - target variable
sample_submission.csv - sample submission file to specify the submission format. This file will remain unchanged throughout the competition.
ID_Date: Unique identifier of state, stationid and date
AQI: Average Air Quality Index

Evaluation Metric for the Performance component
Submissions are evaluated on Modified Mean Absolute Error (MMAE) between forecasts and the actual values. The modification here is that it will penalize the under-predictions more heavily than over-predictions with a ratio of 1.5:1.

Note: Winners will be judged on the cumulative score from all the above 4 components. This competition only ranks the submissions on the performance component of the judging criteria.
