# Lip-Syncing with AI using the wav2lip Model

## Project in "ai_lip.ipynb"

--------------------------------

## Introduction

The objective is to synchronize the lip movements of characters in a given video file with the corresponding audio file.


## Code Overview

The code provided showcases the implementation steps required to perform lip-syncing using the wav2lip model. Open the ai_lip.ipynb file in collab and let's go through the code step by step:

### - Setting Up the Environment :

Make sure you are using the same google account in Google Colab which you will be using to upload your desired image/video and audio files. Changing the hardware accelerator to GPU before


### - Cloning the Repository :

Next, this repository is cloned. My repository contains the implementation of the wav2lip model, which is the backbone of our lip-syncing application. We also install the required python packages to run the model contained in the "requirements.txt" file.

### - Mounting Google Drive :

I mounted Google Drive to access the required video and audio files for lip-syncing. This step allowed me to seamlessly access the files needed for the project.

### - Performing Lip-Syncing :

After setting up the environment and obtaining the necessary files, I copied the video file and audio file from Google Drive to the appropriate location for the lip-syncing process.




Finally, I ran the inference script (inference.py) provided in the Wav2Lip repository. This script takes the video file and audio file as input and generates a lip-synced video. The pre-trained model checkpoint path was specified using the --checkpoint_path flag.

<br>
<br>

> # Detailed explanation of the code is provided in the Google Colab Notebook.

<br>

--------------------

# Running the Code
--------------------------------

## To run the code and perform lip-syncing, follow these steps:

### 1.) Open the lipsync.ipynb file in Google Colab using the "Open in Colab" button.


![image](https://github.com/Yash-K1/AI-Lipsync/assets/114215353/0bd2d688-23c4-4351-b527-333a514b8466)


### 2.) Start executing the cells. The code cells from Prerequisites up to connecting this GitHub repository to Colab Notebook can be directly without any additional effort. I have managed all the dependencies by choosing all the suitable package versions that were inter-compatible.


### 3.) Create a new folder on your Google Drive. Upload the desired image/video and audio files in that folder.


### 4.) Run the model using the names of video and audio files and download the resultant video from the file manager of Wav2Lip on the left side of the colab notebook.








