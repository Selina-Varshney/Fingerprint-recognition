# Fingerprint-recognition
Fingerprint Recognition System:

The project is python based and uses OpenCV. 
For an authorised match it matches the datapoints using knn and flann based matcher, displaying that the user is authorised. 
For an unauthorised match, it prompts a message that the user 
is unauthorised.

Prerequisites:
Dataset downloaded from: https://www.kaggle.com/ruizgara/socofing
This would contain 2 folders:
Real- real fingerprints
Altered- blurred,faded,rotated versions of real dataset

Then run: main.py- the main python code
images- (authorised, no_entry) for displaying a prompt, have also been provided in this repository.

For authorized access:
![Verified_1](https://user-images.githubusercontent.com/99686864/236568506-c0f24953-89f2-467a-a2fe-5c1630c5f4e9.jpg)
