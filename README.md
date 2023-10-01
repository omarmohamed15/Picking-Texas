# Picking-Texas
## Description
* Transfer Learning for Seismic Phase Picking in Texas.

## How to Run?
# 1- In this directory, we have the test file:
* test_EQ_Texas.npy  --- The IDs for testing.

# 2- Run the "EQCCT_P_Test.py" to evaluate the performance of the EQCCT using the test set.
* You need to change the path of the best model in Line 1123 "input_model".

# 3- Run the "EQCCT_S_Test.py" to evaluate the performance of the EQCCT using the test set.
* You need to change the path of the best model in Line 1131 "input_model". 

# 4- Run the "Read_Data_Evaluation_P.py" to obtain the different evaluation metrics for the EQCCT picks.
* This script will save the P picking error in Numpy file (only the picks with errors less than 0.5 s)

# 5- Run the "Read_Data_Evaluation_S.py" to obtain the different evaluation metrics for the EQCCT picks.
* This script will save the S picking error in Numpy file (only the picks with errors less than 0.5 s)


