### Predict Hotel Cancelation Rate

**Jonathan Heberer**
Notebook used in this analysis is located here:
https://github.com/jheberer/Berkeley-Profession-Certificate-in-ML---EDA-for-Capstone/blob/main/hotelcancellations_21.ipynb

#### Executive summary
Predicting hotel cancelations can be extremely beneficial for hotel businesses. In this analysis, we looked at the many characteristics of a reservation and the reserving party, to understand what features lead can be used to predict if a booking will get canceled. 
Our initial analysis found that factors like lead time, average daily rate, and type of deposit are some of the key features in determining if a hotel reservation may get cancelled. 

#### Rationale
Hotel cancellations, commensurate with travel boom, skyrocketed from 2019 to 2022. We experienced about 15% cancellations in 2019, which was up to 20% in 2022. An almost 33% increase. With the economic slowdown being what it is, this sort of prediction model can help hotel with revenue planning, staffing, and other operational planning.
Hotels can also use this pattern to inform their cancellation policies.

#### Research Question
What features of a reservation can predict hotel cancellation?

#### Data Sources
Importing hotel cancellation data sourced from Kaggle- https://www.kaggle.com/datasets/arezaei81/hotel-bookingcvs/data

High level data description: Data contains - Details of a reservation (lead time, dates, status, etc,) - Information on the booking party, such as number of kids, previous cancellation history - Information on the hotel, property type.

#### Methodology
Exploratory data analysis
Feature engineering/data cleanup
Machine learning models for classification such as random forest, decisions trees.

#### Results
1. Lead time i.e. time between making a reservation and reservation arrival time, features prominently in being to predict if a reservation will get cancelled.
2. Other features were average daily rate, non refundable deposit type of deposit, and online bookings - all contribute to a higher likelihood of cancellation. 

#### Next steps
1. Look further into the 2 models we used to identify which is a better choice for this type of data.
2. Extend the research into predicting when cancellation will take place such that hotels could deliberat a custom cancelation policy. 

#### Outline of project

https://github.com/jheberer/Berkeley-Profession-Certificate-in-ML---EDA-for-Capstone/blob/main/hotelcancellations_21.ipynb

##### Contact and Further Information
Jonathan Heberer
Michigan
517-614-0626
jrheberer@gmail.com