late blight->bacteria
early blight->virus

if these are identified early then it can save a lot of crops by being treated ealy. 

the project is an end-to-end mobile application where user can just take a picture of the plant and upload it on the app and the app will tell whether the plant is healthy or not.

process to be followed:
first we do data collection of plants of three types: healthy late blight or early blight

then we do data cleaning and preprocessing

after that we make the model using CNN and then export the trained model onto a disk 

once all this is done we will use tf serving along with fast api to enable our model to make predictions.

after this we will make a react js website

after this we make the mobile app development 

the models created are exporeted to tf lite models through quantization.


application working deals with gcf instead of tf lite model


TECH STACK
    MODEL BUILDING
        tf  
        CNN
        DATA AUGMENTATION
        TF DATASENT
    BACKEND SERVER
        tf serving 
        fast api
    model optimization
        quantization    
        tensorflow lite
    frontend & deployment
        react js
        react native
        deployment to gcp