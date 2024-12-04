P: Petty Offense
F: Felony
M: Misdemeanor
S: Status
C: Civil

Train models using 2020 and 2021 arrests data sets and the mlt income dataset. Using the NH name to get the relevant income
info from income ds. Try to classify fel_misd.

One set of models (5 total) can be a grouping of logistic regression that each classifies one of the fel_misd values
Another regression model that predicts the probability of a higher offense (M or F)