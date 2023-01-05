Install libraries:

pip install -U torch imutils

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Get-Data: File to resize all the images to (30,30), convert and store it in npy file. 

Badnets: File contains the main badnet code. We add trigger to the image and create poisoned dataset. 

Opencv-trigger-detection: Store each label image in a seperate folder. This file contains our model design. The triggered image is sent to both the models and trigger is identified. 

NormalNets: File contains code to develop secured neural network model and test accuracy on that

** we have included only npy files for our dataset. we you want original dataset download it from here and place all files in root directory and run get-data.ipynb file. this will generated npy files for project. link for that is this: [ https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign ] 