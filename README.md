# This code was tested on Python 3.7.3, TensorFlow 1.14 , and Keras 2.3.1
# Every other library the code will need it will make an error. Example : Missing_Module numpy , just install the latest version of it using pip.


# To run the code :
-First Check the parameter script for the paths of the dataset and the output results , the default used for the dataset is a folder created in the same folder of the code named dataset , for the extracted features there will be a folder named seld_feat_label_mic in the same folder after running the batch feature extraction script, and a results folder after running the seld script, Also the default is a full training mode so make sure to put quicktest=true if you want to run a quicktest.

# NOTE: The results folder in the code is the results of the relu activation function as it outperformed the sigmoid and produced pretty similar results as the default. Please dont keep the results folder as it is as after running the seld script it might get overwrited or merged with the new results so put it in another folder, and the seld script will create the results folder again with the new results.

-After setting up the right parameters for the dataset and output folders , you can now run the batch feature extraction script.

-Check for the seld_feat_label_mic folder created after running the batch feature extraction.

# NOTE: There are three keras model scripts included (1 for the default and 2 for the modifications), please only use the one you need (Default, Sigmoid , or RELU) , to use one just remove the other two to a new folder and rename the script to keras_model , example : if u want to use the default then rename the keras_model (default) to keras_model and remove the other two keras model scripts to another folder

-Now you can Train the Data by running the SELD script.

-After successfully running the SELD script you can now visualize the data using the visualize seld output script.
