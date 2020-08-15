# Malaria-Detection
A GUI based application which uses a custom CNN model(Accuracy:98.22%) to predict if an uploaded cell image is parastized or uninfected. At first a Deep learning model was trained and tested in Google Colab on the dataset obtained from kaggle, then in order to give it as a user interface, tkinter module in python is used. 
System will read the image uploaded by user, augment it and will use the saved custom model to detect whether the disease is present or not in the patient and thus display the result in a user-friendly language.

Below are the steps;
1)Upload image: The user can upload the medical test image through a workstation running on Windows OS. The image should be in jpeg, ping or jpg format.
2)Read image: The image will be scanned before augmentation takes place.
3)Transform image: The scanned image is then transformed into a format that is needed by the saved custom model.
4)Evaluate image using saved model: The saved custom model creates a feature map of the uploaded medical test image and predicts the output.
5)Determine and Analyze the Output: The predicted output is then analyzed and converted to a user friendly language.
6)Display the Output: The analyzed result is then displayed to the user.
