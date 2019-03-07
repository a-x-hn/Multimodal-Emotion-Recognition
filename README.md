# Multimodal Sentiment Analysis

In this project, we are exploring state of the art models in multimodal sentiment analysis. We have chosen to explore textual, sound and video inputs and develop an ensemble model that gathers the information from all these sources and displays it in a clear and interpretable way. 

## Definition
We are trying to provide definitions of affective computing and multimodal sentiment analysis in the context of our research. Those definitions may vary depending on the context.
Affective computing is a field of Machine Learning and Computer Science that studies the recognition and the processing of human affects. 
Multimodal Sentiment Analysis is a relatively new discipline that aims to include text inputs, as well as sound and video. This field has been rising with the development of social network that gave researchers access to a vast amount of data.

This research will explore state of the art multimodal sentiment analysis models for affective computing in the context of emotion classification.

This research will be applied in the field of personal development for unemployed people. 

## Data Sources
We have chosen to diversify the data sources we used depending on the type ofdata considered.For the text input, we are using an annotated essay text corps provided by ...For sound data sets, we are using the Ryerson Audio-Visual Database ofEmotional Speech and Song (RAVDESS).”The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)contains 7356 files (total size: 24.8 GB). The database contains 24 professionalactors (12 female, 12 male), vocalizing two lexically-matched statements in aneutral North American accent. Speech includes calm, happy, sad, angry, fearful,surprise, and disgust expressions, and song contains calm, happy, sad, angry, andfearful emotions. Each expression is produced at two levels of emotional intensity(normal, strong), with an additional neutral expression. All conditions are avail-able in three modality formats: Audio-only (16bit, 48kHz .wav), Audio-Video(720p H.264, AAC 48kHz, .mp4), and Video-only (no sound).”For the video data sets, we are using the popular FER2013 Kaggle Challengedata set. The data consists of 48x48 pixel grayscale images of faces. The faceshave been automatically registered so that the face is more or less centered andoccupies about the same amount of space in each image. The data set remainsquite challenging to use, since there are empty pictures, or wrongly classifiedimages.

## Methodology
Our aim is to develop a model able to provide a live sentiment analysis with avisual user interface.Therefore, we have decided to separate two types of inputs :
- Textual input, such as answers to questions that would be asked to a personfrom the platform
- Video input from a live webcam or stored from an MP4 or WAV file, fromwhich we split the audio and the images

## What datas did we use ?
The data set can be found here :
- Video : https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data
- Sound : https://zenodo.org/record/1188976#.XCx-tc9KhQI
- Text : ...

All data sets used are free of charge and can be directly downloaded.

## How to use it ?
The project currently is under the form of a set of notebooks for each domain. The combination of the video, sound and text analysis can be found in the "Common" section. We will soon be publishing .py files as well as detailed explanations on the requirements. 

If you are interested in the research paper we are working on currently, feel free to check out this link :
https://www.overleaf.com/read/xvtrrfpvzwhf