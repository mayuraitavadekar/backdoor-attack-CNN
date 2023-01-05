## datasets

all datasets are available on following onedrive: https://1drv.ms/u/s!AtAUKJym4Y77cPxhgg8iLVCa4A8?e=iUsmaa

<br/>

Note: we have included only npy files for our dataset. we you want original dataset download it from here and place all files in root directory and run get-data.ipynb file. this will generated npy files for project. link for that is this: [ https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign ]

## files in project

* get-data.ipy: File to resize all the images to (30,30), convert and store it in npy file. 
* badnets.ipynb: contains the main badnet code. We add trigger to the image and create poisoned dataset. 
* opencv-trigger-detection.ipynb: Store each label image in a seperate folder. This file contains our model design. The triggered image is sent to both the models and trigger is identified. 
* normal_net.ipynb: File contains code to develop secured neural network model and test accuracy on that


## other files:

* in-class presentation: final-project-report-group-2.pptx
* submitted report: final-project-report-group-2.docx, final-project-report-group-2.pdf

## Papers:

* badnets paper: https://arxiv.org/abs/1708.06733
* neural cleanse paper: https://people.cs.uchicago.edu/~ravenben/publications/pdf/backdoor-sp19.pdf
