# Lip-Syncing with AI using the wav2lip Model
--------------------------------

## Introduction

The objective is to synchronize the lip movements of characters in a given video file with the corresponding audio file.


## Code Overview

The code provided showcases the implementation steps required to perform lip-syncing using the wav2lip model. Open the ai_lip.ipynb file in collab and let's go through the code step by step:

### - Setting Up the Environment :

To begin, it is ensured that all the necessary dependencies are installed.

### - Cloning the Repository :

Next, the Wav2Lip repository is cloned from the provided GitHub URL. This repository contains the implementation of the wav2lip model, which is the backbone of our lip-syncing application. We also install the required python packages to run the model.

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

## To run the code and perform lip-syncing using the wav2lip model, follow these steps:

### 1.) Open the lipsync.ipynb file in Google Colab using the "Open in Colab" button.


![image](https://github.com/Yash-K1/AI-Lipsync/assets/114215353/0bd2d688-23c4-4351-b527-333a514b8466)


### 2.) Start executing the cells. The code present in the cells under Prerequisite can be run as it is. I have managed all the dependencies by choosing all the suitable package versions that were inter-compatible.



### 3.) Follow the instructions in the Google Colab Notebook to Connect Wav2Lip GitHub repository to Colab Notebook. 



### 4.) Install the required packages from the "requirements.txt" file present in my repository and replace these package names in the identical file present in the GitHub Repository of Wav2Lip.



### 5.) Upload both the pretrained model and desired video and audio files on google drive. Model goes in "Wav2lip" folder and video/audio goes in "Wav2Lip" folder.


### 6.) Run the model using the names of video and audio files and download the resultant video from the file manager of Wav2Lip on the left side of the colab notebook.








