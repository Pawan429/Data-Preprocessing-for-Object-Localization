# Data-Preprocessing-for-Object-Localization
This repository will contain the data Preprocessing script for Multi Class Object Localisation.


I have used Labelimg for labelling my data.

The Labelled data exists in xml format(as it is the output of LabelImg).

The preprocessing script works on a directory, where it searches for all files with .xml tags and extracts the Filename, Class_Label, Bounding_Box Coordinates of the labelled data into a pandas dataframe. 

You can use the 'flow_from_dataframe' method of the 'ImageDataGenerator' Class in 'keras' to load the data to your model. 
