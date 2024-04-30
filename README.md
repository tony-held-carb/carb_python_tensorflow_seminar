# Repo to introduce key ML/AI/TensorFlow concepts to CARB Python user group.
Created by: Tony Held (tony.held@arb.ca.gov)

## Introduction:
1) Key ML/AI concepts using TensorFlow are introduced in this repo including data pre-processing, 
regression, image processing, time series analysis, and Natural language processing (NLP).
2) Codebase was created as a subset of Tony's Google TensorFlow Certification code and notes  
that has been modified to be useful for CARB data analysis.
3) Repo is initially populated with the following files:
   * tf_util.py:  python utility classes and functions useful for ML/TensorFlow
   * arb_data_regression_example.ipynb: example of how to perform ML with CARB sample data
   * tensorflow_video_analysis.ipynb: examples of how to perform video and image processing using TensorFlow
   * overview_of_tensorflow_and_ml.ipynb: examples of how to data pre-processing and ML for a variety of ML applications (regression, time series analysis, image processing, NLP, etc)

## Example images and video
1) Example images and video are located in the image_video folder
2) You can inspect the input and output to get a feel for the accuracy of ML in object detection/classification

## Local Machine Usage:
1) Clone this repo to the local directory of your choosing
   * https://github.com/tony-held-carb/carb_python_tensorflow_seminar
2) Change the number of epochs and run flags at the top of the notebook (if desired)
3) Get coffee and popcorn and settle in for a long training time if you are on a CARB laptop :)

## Running on Colab:
1) open colab in your browser at https://colab.research.google.com/
2) The open-notebook modal form will likely pop up, if not go to File -> Open Notebook
3) Select GitHub and enter tony-held-carb for the user and click the magnifying glass
4) Select the tony-held-carb/carb_python_tensorflow_seminar and the main branch
5) Open the files and re-run them if you like
6) You can run the model in Colab by selecting Runtime->Run All
7) Unless you have a GPU enabled in your Colab session, model training may be very slow
8) You must save a copy of the notebook to your local account (you can't directly modify the repo file clone)




