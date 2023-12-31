# Picking-Texas
## Description
* Transfer Learning for Seismic Phase Picking in Texas.
* Data Link: https://drive.google.com/drive/folders/1WXVB8ytNB4bOaZ97oq6OmMRyAEg95trp?usp=sharing
* Test IDs Link: https://drive.google.com/file/d/1rg8CEPgAq4QClCPHfnEJ-RJkS4Mrnxbo/view?usp=sharing

## Reference
    Omar, et al., 2024, Transfer Learning for Seismic Phase Picking in Texas, TBD.
    
BibTeX:

	@article{TFTEXAS,
	  title={Transfer Learning for Seismic Phase Picking in Texas},
	  author={Omar et al.},
	  journal={TBD},
	  volume={TBD},
	  number={TBD},
	  issue={TBD},
	  pages={TBD},
	  year={2024},
	  publisher={TBD}
	}
 
-----------

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


