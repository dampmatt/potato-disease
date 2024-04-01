late blight->bacteria
early blight->virus

if these are identified early then it can save a lot of crops by being treated ealy. 

the project is a web based application where user can just take a picture of the plant and upload it to the website and the site will predict whether the plant is healthy or not.

process to be followed:
first we do data collection of plants of three types: healthy late blight or early blight

then we do data cleaning and preprocessing

after that we make the model using CNN and then export the trained model onto a disk 
once base model is created and the site works fine work on other models to increase accuracy and manage load

once all this is done we will use tf serving along with fast api to manage load on the models already developed to give a better response time to the users.

after this we will make a react js website this website will send request to the api's and will display the result it gets from them

TECH STACK
    MODEL BUILDING
        tf  
        CNN
        DATA AUGMENTATION
        TF DATASENT
    BACKEND SERVER
        tf serving 
        fast api
    frontend & deployment
        react js
        
