# Privacy Analysis of Wearable Health Devices

In this project we are going to compare two wearable health devices, check their data collection process, analyse the data collected to answer some questions such as :
*) Have they followed data minimization techniques while collecting data?
*) Is the data which has been collected de identified/ anonymized?
 And finally try to apply differential privacy.

## Potential Datasets 

### FitBit Fitness Tracker Data 
https://www.kaggle.com/datasets/arashnic/fitbit/data?select=Fitabase+Data+4.12.16-5.12.16 
This dataset generated by respondents to a distributed survey via Amazon Mechanical Turk between 03.12.2016-05.12.2016. Thirty eligible Fitbit users consented to the submission of personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. Individual reports can be parsed by export session ID (column A) or timestamp (column B). Variation between output represents use of different types of Fitbit trackers and individual tracking behaviors / preferences.
### Apple Watch and Fitbit data 
https://www.kaggle.com/datasets/aleespinosa/apple-watch-and-fitbit-data 
Columns: Age, Gender, Height, Weight, Calories, steps, Heart Rate, Distance

If none of the above work, we are thinking to use personal data collected over a period of time

## Tools    
Diffprivlib is a general-purpose library for experimenting with, investigating and developing applications in, differential privacy.
https://github.com/IBM/differential-privacy-library 




