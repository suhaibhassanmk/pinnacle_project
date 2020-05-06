Road crack detection for autonomous driving.

We are using Google colab platform for this project.

Libraries included are keras, MATPLOTLIB,CV2,NUMPY and PIL .

The data set is divided into training, validation and testing data.

The dataset is uploaded into the google drive.

We include the directories of the training, validation and testing data into different variables.

We use a sample image using different filters just for showing the visibility of the crack.

We define a function for processing the image and creating the data.

We label images with cracks as ‘positive’ and images without cracks as ‘negative’.

The training data has 3000 images (1500 with cracks and 1500 without cracks). All the images are taken and converted into a matrix which is then reshaped.

The validation data has 600 images (300 with cracks and 300 without cracks) . All the images are taken and converted into a matrix which is then reshaped.

The training data has 400 images (200 with cracks and 200 without cracks). All the images are taken and converted into a matrix which is then reshaped.

We import Sequential, Conv2D, MaxPooling2D, Activation, Dropout, Flatten, Dense and load_model from the keras package.

The CNN model is created using these packages.

The model uses relu and sigmoid activation function.

The epochs size is kept as 30 and batch size is kept as 250 for the training process.

After training, there is accuracy of 97%.

A function defined for the prediction of image.

This function gets the input as an image from the user and predicts if the image has a crack or not.

If the input is a video, then the input is taken and converted into frames and is stored as an image file with jpg extension. Then the images are given as input using a loop so that each image is evaluated.

Dataset is taken from : https://data.mendeley.com/datasets/5y9wdsg2zt/1/files/c0d86f9f-852e-4d00-bf45-9a0e24e3b932

Self Expalainaroty Video for the Project Review Panel : https://drive.google.com/file/d/1GJTZsBoIK-R-jXzHVSpAboD38ORnWjtc/view?usp=sharing
