
# TAU Vehicle Type Recognition Competition

The data for the competition consists of training data together with the class labels and test data without the labels. Your task is to predict the secret labels for the test data.
Categories

The data contains vehicles from altogether 17 classes: Ambulance, Boat, Cart, Limousine, Snowmobile, Truck, Barge, Bus, Caterpillar, Motorcycle, Tank, Van, Bicycle, Car, Helicopter, Segway, Taxi
File descriptions

The dataset consists of three files listed below.

    train.zip - the training set: a set of images with true labels in the folder names. The zip file contains altogether 28045 files organized in folders. The folder name is the true class; i.e., "Boat" folder has all boat images, "Car" folder has all the car images and so on.
    test.zip - the test set: a set of images without labels. The zip file contains altogether 7958 files in a single folder. The file name is the id for the solution's first column; i.e., the predicted class for file "000000.jpg" should appear on the first row of your submission.
    sample_submission.csv - a sample submission file in the correct format (predicting all "cars" class)
    
Different architectures like VGG16, MobileNet, ResNet are applied on the model.
Results:
    ![image](https://user-images.githubusercontent.com/87253265/147847339-da5ac2d8-98cb-4b6f-9d79-cc51ac70c745.png)

