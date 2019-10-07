# GMC_CRASH_PREDICTIONS

Conducted Text Classification analysis of the data using POS, stop words and stemming for building the term/doc matrix.
Developed a regression model to predict the probability of the crash based on the attributes mentioned in the customer complaints.

A preview of the dataset:
The excel file contains 2,375 complaints about specific GMC vehicles submitted to the National Highway Safety and Traffic Administration (NHTSA).
The complants are in the column labeled 'description'.

The data dictionary is:

nthsa_id:    A unique number for each complaint 

Year:        The car year - 2003 through 2011 

make:        The make of the car - CHEVROLET, PONTIAC & SATURN 

model:       The car model - COBALT, G5, HHR, ION, SKY & SOLSTICE 

description: The actual complaints(text) 

crashed:     A binary attribute - "N" for no and "Y" for yes

abs:         Anti-lock Braking System - "N" for no and "Y" for yes 

mileage:     The miles on the car at the time of the accident_0-200,000 
