# MADRIP
# Final Year Project
# FYP-S20-09-D-MADRIP

# MADRIP_v2.ipynb: 
This file contains the initial code for a system that identifies the stage of Diabetic Retinopathy and also provides a visuallization of the results of the multi-dimensional analysis performed by the system.

# Model_Training.ipynb
This python Notebook has all the code related to mounting the data loading trasnforming and training model with it. The notebook use the 'Base.7z' stored in the drive to extract data into colab environment and reads them using 'Annotationbase123.csv' also uploaded in the 'Training' folder of the drive associated with the MADRIP account. The model is trained and saved with file name dr3.pth with 'model.save' function of pytorch.

# DR Model.7z
This is the model that was trained and has been saved to 'dr3.pth' and renamed to 'DR Model.pth'. It has been split into two archive using 7z due to github size limitations.


# In order to run the code:
Download notebook and upload it on Google Collaboratory. After you run the first cell you would be required to mount a Google Drive; the credentials of the account are as follows:
email: fyp.madrip09@gmail.com
password: s2009d_madrip
After that you can run all the cells. When you run the Main cell; it would require you to log in or register in order to continue so if you just want to sign in below are the credentionals of an already created user.
username: wj12
password: wj123

# Training of data
Login with the MADRIP account and open the 'Model Training.ipynb' notebook located in the Colab Notebook run all the cells except last two and cell# 19 and 20 as they contain the model saving and loading code. The training will start and it will show the accuracy of the model.

# Web Module
The folder name is MADRIP_Web Module, this contaisn all the html and css files for the web design of MADRIP. To get an overview of the look and feel of web design, simply open file "index" which is basically our homepage, its an html file . To edit files you can simply open any editable file in an editor. the bannsers and all the images used are in 'img' folder.
There are also javascript files, the image uploading module is using that. Right now we are not retrieving file that functionality will be used in fyp-2.
