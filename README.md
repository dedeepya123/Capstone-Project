Traffic Sign Detection
-----------------------------------------------------------
In the world of Artificial Intelligence and advancement in technologies, many researchers and big companies like Tesla, Uber, Google, Mercedes-Benz, Toyota, Ford, Audi, etc are working on autonomous vehicles and self-driving cars. So, for achieving accuracy in this technology, the vehicles should be able to interpret traffic signs and make decisions accordingly.
There are several different types of traffic signs like speed limits, no entry, traffic signals, turn left or right, children crossing, no passing of heavy vehicles, etc. Traffic signs classification is the process of identifying which class a traffic sign belongs to.

Dataset
---------------------------------------------------------
The GTSRB-german traffic sign detection benchmark dataset was utilized in this study. This  dataset is available for on platforms such as Kaggle. There are over 43 picture classes in this dataset, with over 5000 photos for testing and validation. My dataset was further separated into three sections: testing, training which allows me to assess how well our model is performing. 

The test and train dataset for project can be found here 
https://benchmark.ini.rub.de/gtsrb_news.html

Model
-----------------------------------------------------
In this project I will build a deep neural network model that can classify traffic signs present in the image into different categories. With this model, one can be able to read and understand traffic signs which are a very important task for all autonomous vehicles.

I'm using numpy for creation of array of images, pandas for reading the csv file, matplotlib for plots, pillow for image processing, tensorflow for backend, cv2, keras and sklearn libraries are also required.