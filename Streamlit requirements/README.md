

# Mask Detection

#### A Face Mask Detection System with Deep Learning and Computer Vision

Deep Learning Project

## Goal

The goal of this project is to build a face mask detection system using deep learning algorithsm and computer vision. The project uses the face mask detection images dataset from Kaggle that contains 11,800 images of face with mask and without mask, evenly distributed. The binary classification model was built with Keras/Tensorflow using CNN algorithm and had an accuracy score of 0.99. Using Haar Cascade Classifier as face detector, the face mask detection applies the binary CNN model as mask detector to the area of face and shows the prediction result. The application is built with Streamlit and deployed on Heroku


## Data

- Face Mask Detection Images Dataset from [Kaggle](https://www.kaggle.com/ashishjangra27/face-mask-12k-images-dataset) that contains 11,800 images of face with mask and without mask

**Added more datasets for 3-class model**

- [MaskedFace-Net](https://github.com/cabani/MaskedFace-Net) dataset that contains images of faces with a correctly or incorrectly worn mask (used 8,990 images of incorrectly worn mask and 3,900 images of correctly worn mask)
- cali9530/celeba-dataset) that contains images of celebrity faces (used 3,900 images for without mask)

## Workflow

-
  - Streamlit app on Heroku:
    - main python file
    - Procfile
      required library
    - Haar Cascade file
    - CNN model

## Results

**Application on Streamlit**

*Face mask detection on Images*


The app is deployed on Heroku without webcam feature. 

Try out the Heroku app for Mask Detection 

## Technologies

- Python (pandas, numpy)
- Google colab (Cloud computing)
- Keras/Tensorflow
- OpenCV
- Matplotlib, seaborn
- Streamlit
- Heroku
