# TED-Talks-View-Prediction
# Problem Objective

TED is devoted to spreading powerful ideas on just about any topic. These datasets contain over 4,000 TED talks including transcripts in many languages.The main objective is to build a predictive model, which could help in predicting the views of the videos uploaded on the TEDx website.

# Project Work Flow

Importing Libraries

Loading the Dataset

Data Cleaning

EDA & Feature Engineering

Feature selection

Fitting the regression models and HyperParameter Tuning

Final selection of the model

# Feature Information
talk_id: A unique identifier for each TED Talk video.

title: The title of the talk.

speaker_1: The primary speaker for the talk.

all_speakers: A list of all the speakers for the talk.

occupations: The occupations of the speakers.

about_speakers: Information about the speakers, such as their backgrounds and expertise.

views: The number of views the video has received.

recorded_date: The date the talk was recorded.

published_date: The date the talk was published on the TED Talks YouTube channel.

event: The name of the TED event where the talk was given.

native_lang: The language the talk was given in.

available_lang: The languages the talk is available in.

duration: The length of the video.(in sec.)

topics: The topics covered in the talk.

related talks: Other TED Talks that are related to this talk.

url: The URL of the video.

description: A brief description of the talk.

transcript: A transcript of the talk.

Target Variable: Views(The number of views the video has received.

# Model Implementation

Making models through linear regression, ridge regression, lasso regression, decision tree, random forest, gradient boosting, and XGBoost.

# Conclusion

Random Forest is the best regression model used for the task. However, in future we can try some other techniques to obtain more better results.


