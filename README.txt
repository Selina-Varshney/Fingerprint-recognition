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
