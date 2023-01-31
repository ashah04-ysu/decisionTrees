# Signup Prediction Code
This code uses 'numpy' and 'pandas' to analyze signup data and predict the service chosen by users. The data is read from a csv file "PredictingSignupsTrain.csv" and analyzed based on the features 'Referrer', 'Location', 'Read_FAQ', and 'Pages_Viewed'.

The code calculates the frequency of each feature for each service chosen ('None', 'Basic', and 'Premium') and calculates entropy values based on the frequency data. The entropy values are used to calculate information gain for each feature and to determine the most informative feature for predicting the service chosen.

## Requirements
The following packages are required to run the code:

'numpy'
'pandas'
'math'
'scipy.stats'

## Usage
The code can be run as a standalone script. The output will show the frequency of each feature for each service chosen, followed by the calculated entropy values and information gain.
