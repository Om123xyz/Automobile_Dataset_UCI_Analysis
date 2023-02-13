# UCI_Automobile_Dataset_Exploratory_dataAnalysis

In this project, I have done exploratory data analysis on the UCI Automobile dataset available at https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data

This dataset consists of data From the 1985 Ward's Automotive Yearbook. Here are the sources

1) 1985 Model Import Car and Truck Specifications, 1985 Ward's Automotive Yearbook.
2) Personal Auto Manuals, Insurance Services Office, 160 Water Street, New York, NY 10038
3) Insurance Collision Report, Insurance Institute for Highway Safety, Watergate 600, Washington, DC 20037

Number of Instances: 398
Number of Attributes: 9 including the class attribute

Attribute Information:

mpg: continuous
cylinders: multi-valued discrete
displacement: continuous
horsepower: continuous
weight: continuous
acceleration: continuous
model year: multi-valued discrete
origin: multi-valued discrete
car name: string (unique for each instance)

This data set consists of three types of entities:

I - The specification of an auto in terms of various characteristics

II - Tts assigned an insurance risk rating. This corresponds to the degree to which the auto is riskier than its price indicates. Cars are initially assigned a risk factor symbol associated with its price. Then, if it is riskier (or less), this symbol is adjusted by moving it up (or down) the scale. Actuaries call this process "symboling".

III - Its normalized losses in use as compared to other cars. This is the relative average loss payment per insured vehicle year. This value is normalized for all autos within a particular size classification (two-door small, station wagons, sports/specialty, etc…), and represents the average loss per car per year.

The analysis is divided into two parts:

Data Wrangling

Pre-processing data in python
Dealing with missing values
Data formatting
Data normalization
Binning
Exploratory Data Analysis
Descriptive statistics
Groupby
Analysis of variance
Correlation
Correlation stats
Acknowledgment
Dataset: UCI Machine Learning Repository
Data link: https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data
