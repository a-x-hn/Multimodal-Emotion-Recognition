# Facial Emotion Recognition

This section is dedicated to Facial Emotion Recognition. The aim is to provide an emotion analysis based on a user's face. The video stream we typically be captured by a webcam in the final model. 

## Files

The different folders that can be found in this repo :
- `Notebook_Images` : A set of pictures saved from the notebooks for the final report
- `Test_Images` : A set of pictures used to test the pipeline of image treatment
- `Model_Images` : Models structures saved using `plot_model`
- `Resources` : Some resources that have to used to build the notebooks
- `Other_Notebooks` : Notebooks that have been created but were not used in the final version
- `Emoji` : A group of Emojis used to display the emotion in the live prediction version
- `emotionaldan` : A folder dedicated to Deep Alignment Network 

We'll now cover into more details what each notebook contains :
- `00-Fer2013.ipynb` : Gathers all the work
- `1-Pre-Processing.ipynb` : Transform the initial CSV file into train and test data sets
- `2-HOG_Features.ipynb` : A manual extraction of features such as Histograms of Oriented Gradients and Landmarks
- `3-Pre-Processing-EmotionalDAN.ipynb` : An implementation of Deep Alignment Networks to extract features
- `4-LGBM.ipynb` : Use of classical Boosting techniques on top on flatenned image or auto-encoded image
- `5-Simple_Arch.ipynb` : A simple Deep Learning Architecture
- `6-Inception.ipynb` : An implementation of the Inception Architecture
- `7-Xception.ipynb` : An implementation of the Xception Architecture
- `8-DeXpression.ipynb` : An implementation of the DeXpression Architecture
- `9-Prediction.ipynb` : Live Webcam prediction of the model

The Model weights can be found on this public drive :
*Link to Come*

## Performance

