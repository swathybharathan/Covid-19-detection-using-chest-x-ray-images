# Covid-19-detection-using-chest-x-ray-images

I used a data set containing confirmed COVID-19 positive. The model used a pretrained VGG-16 model for the classification task. Transfer learning with fine-tuning was used in
this study to effectively train the network on a relatively small chest x-ray data set. 

Step 1: Creating a Dataset contains two folders, in which one has sampled X-Ray images of Normal Patients. Another folder in which the X-Ray images of corona virus patients.
Step 2: After creating two folders we will merge the images and set the labels
Step 3: Developing a quality assessment model. Then we will split that into training and testing set and creating a VGG model that will predict the data.
Step 4: Construct a fully connected layer and append it on the top of the VGG model.
Step 5: Training and experimentation on datasets


Tools: Python 3.8, Jupyter Notebook
