# This code was tested on Python 3.7.3, TensorFlow 1.14 , and Keras 2.3.1. The dataset mode used during the project is the MIC-DEV.

# For Every other library the code needs it will make an error. Example : Missing_Module numpy , just install the latest version of it using pip, there is a requirments.txt file that includes all the libraries that were installed on the platform used to run the code.

# The default parameter script has quicktest=false and it trains the data on the Microphone Development Mode (MIC-DEV) , so please update it as needed.

# NOTE: The results folder contains the results of the relu activation function as it outperformed the sigmoid and produced pretty similar results as the default.

# To run the code :
-First Check the parameter script for the paths of the dataset and the output results , the default used for the dataset is a folder created in the same folder of the code named dataset , for the extracted features there will be a folder named seld_feat_label_mic in the same folder after running the batch feature extraction script, and a results folder after running the seld script, Also the default is a full training mode so make sure to put quicktest=true if you want to run a quicktest.



-After setting up the right parameters for the dataset and output folders , you can now run the batch feature extraction script.

-Check for the seld_feat_label_mic folder created after running the batch feature extraction.

# NOTE: There are three keras model scripts included (1 for the default and 2 for the modifications), please only use the one you need (Default, Sigmoid , or RELU) , to use one just copy the script needed and paste it with the other scripts , for example if you need the default then navigate to keras model scripts-Default code of the author and copy the keras model and paste it with the other scripts.

-Now you can Train the Data by running the SELD script.

-After successfully running the SELD script you can now visualize the data using the visualize seld output script.
