## Student information 
Group 137

* Name: Arya Araban | Student ID: 1439683
* Name: Aadesh Samdaria | Student ID: 1363757

## Project Abstract

This project involves identifying similar images from the Totally-Looks-Like dataset. The dataset consists of pairs of images that have been deemed as looking similar or related in some way. It is split into training and test sets. For each test image, the task is to identify the true matching image from a set of candidate images. The goal is to train a model that can effectively predict the correct match for new test images.


## Environment Setup

The code for this assignment was written in Python (>= 3.9) using Google Colab. 

To set up the environment to run the code, follow these steps:

**If you’re using Google Colab:**

1. Open Google Colab and upload the Python notebook file.
2. Change runtime type to GPU.
3. extract all the data encompassed within the data zip file and place it in a designated folder titled "COMP90086_2023" located at the root of your Google Drive account.
4. Run the cells in the notebook to perform the analysis.

**If you’re working locally:**

1. Install Python 3.9 or later.
2. Install the necessary libraries by running `pip install -r requirements.txt` in your terminal.
3.  Extract all the data from the data zip file and store it in a folder titled "COMP90086_2023" within the current working directory. Modify the file path in the code accordingly by removing the leading "/content/drive/MyDrive/".
4. Run the Python notebook file to perform the analysis.



## Notes
* The data doesn't necessarily need to be in the specified folders, and the file paths can easily be adjusted in the code.

* Produced output files for similarity scores on the test_candidates dataset are: predictions_canny.csv (For Approach 1), predictions_pretrained.csv (For Approach 2), predictions_siamese.csv (For Approach 3).

* In a Colab GPU enviornment, the overall expected runtime is around 90 minutes (30 minutes for the first two approaches, and at least 60 minutes for the final approach)
