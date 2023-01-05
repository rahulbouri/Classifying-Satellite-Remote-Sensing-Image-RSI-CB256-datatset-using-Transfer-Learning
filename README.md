# Classifying-Satellite-Remote-Sensing-Image-RSI-CB256-datatset-using-Transfer-Learning


## About the Dataset
For our classification task, we used the Satellite Remote Sensing Image-RSI-CB256 dataset. This is a readily available dataset that has RGB images (a total of 5631 images, with 3 channels) of varying sizes, from both sensor data and Google map snapshots, with each image classified into one of 4 classes: 
1. Cloudy
2. Water
3. Desert
4. Green Area


## Preprocessing
Since the dataset included only images already focused on the aspect that is the basis for classi cation, and does not as such involve spatial data or any other special formats, packages like EarthPy were not required for dataset loading and preprocessing. Only standard tensor ow image manipulation functions were used.
Since, as shown above, the images in the dataset are of di erent sizes, the images were rescaled to a standard size of (224, 224, 3). Apart from this, no other preprocessing was required for the application.
