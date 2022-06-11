# This code was tested on Python 3.7.3, TensorFlow 1.14 , and Keras 2.3.1
# Every other library the code will need it will make an error. Example : Missing_Module numpy , just install the latest version of it using pip.

# The default parameter script has quicktest=false and it trains the data on the Microphone Development Mode (MIC-DEV) , so please update it as needed.

# To run the code :
-First Check the parameter script for the paths of the dataset and the output results , the default used for the dataset is a folder created in the same folder of the code named dataset , for the extracted features there will be a folder named seld_feat_label_mic in the same folder after running the batch feature extraction script, and a results folder after running the seld script, Also the default is a full training mode so make sure to put quicktest=true if you want to run a quicktest.

# NOTE: The results folder in the code is the results of the relu activation function as it outperformed the sigmoid and produced pretty similar results as the default. The seld script will create a new folder called results including the results for the chosen parameters and modes.

-After setting up the right parameters for the dataset and output folders , you can now run the batch feature extraction script.

-Check for the seld_feat_label_mic folder created after running the batch feature extraction.

# NOTE: There are three keras model scripts included (1 for the default and 2 for the modifications), please only use the one you need (Default, Sigmoid , or RELU) , to use one just remove the other two to a new folder and rename the script to keras_model , example : if u want to use the default then rename the keras_model (default) to keras_model and remove the other two keras model scripts to another folder

-Now you can Train the Data by running the SELD script.

-After successfully running the SELD script you can now visualize the data using the visualize seld output script.
