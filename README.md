The following sections are repeated in the colab notebook but with the code cells too

- Run sections 1, 2, 3, 4 - **more detailed descriptions are inside the collab file**

- Make sure you are changing section 5 as needed if you need to run extra models.

- Download the pkl files and upload them to your drive as specified in section 3. The pkl files are a part of this zip file.

- The data can also be downloaded yourself from section 2.1 and automatically saved to your drive, but this takes time and can be avoided if you just copy the pkl files into google drive.

- Our model results are in the excel file NLP Results from running the models ourselves.

# SECTION 1 - INSTALL/IMPORTS

**Install and import necessary packages; run all cells**

# SECTION 2 - OBTAINING DATA

**Run all cells except saving data to google drive**

You can obtain the data yourself from pybaseball, but the pkl files are already provided

# SECTION 2.1 - OPTIONAL*

**YOU DO NOT NEED TO RUN THIS CELL, ONLY IF YOU WANT TO SAVE THE DATA YOURSELF, BUT IT IS PROVIDED IN THE PKL FILES**

This process was already done by our team to save time in fetching data from pybaseball

# SECTION 3 - USING DATA FROM PKL

**How to load data from google drive; run this whole section**

1) put the downloaded pkl files from the zip into your google drive into the main MyDrive folder, and make sure the colab ipynb is in the main MyDrive google drive folder as well

2) connect drive to colab

3) run this cell to get the data into colab

NOTE: make sure this file and the pkl files are in your main drive, not in a folder; if you want to put it in the folder, change the path below but this is NOT RECOMMENDED

# SECTION 4 - DEFINING FUNCTIONS FOR MODELS

**Run all cells**

# SECTION 5 - RUNNING MODELS

**How to run the models: REQUIRES USER TO COPY AND PASTE**

1) run the initilization cell below which stores all the accuracies

2) run the unigram models to obtain a baseline

3) follow the commented out format and copy and paste to run the models

4) for *CONTEXT_SIZE*, choose between [2, 4, 6, 8, 10, 12, 16] because 0 is unigram model

5) for *TYPE_OF_SENTENCE*, choose between [convert_pitch_to_long_sentence, convert_pitch_to_short_sentence, just_ball_strike, just_pitch_type, features_only_no_other_words]

NOTE: only one example model was shown because model training time takes 20-30 mins, and 70+ models were trained

NOTE: you also need to make a wandb.ai account to use the api, it is free and you follow the directions when running the model with the above format

NOTE: all the data and statistics are saved in the google sheet

EX: there is an example below with *CONTEXT_SIZE* of 8 with *TYPE_OF SENTENCE* of convert_pitch_to_short_sentence
