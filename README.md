# Assignment Objective

Task A
    1.	Understand and implement the following windowing techniques
            o	Hann Window 
            o	Hamming Window 
            o	Rectangular Window 
    2.	Apply the above windowing techniques and Generate spectrograms using the Short-Time Fourier Transform (STFT) 
    3.	Train a simple classifier (e.g., SVM or neural network) using features extracted from the spectrograms and evaluate the performance results comparatively in different techniques. 

Task B
    1.	Select 4 songs from 4 different genres and compare their spectrograms. 
    2.	Analyse the spectrograms and provide a detailed comparative analysis based on your observations and speech understanding


# Requirements
This assignment requirs GPU to train the neural network and was executed in Colab. 
Software used is:
    Python 3.12.1
    
    External Package requirements:-
    numpy
    matplotlib
    scipy
    torch
    torchaudio
    pandas
    PIL
    torchvision
    pickle
    seaborn


IDE 
The IDE used is Visual Studio/Jupyter Colab for this project. 


# To Run this Project:-
Set following Path 
    audioPath = "/content/drive/MyDrive/assigments/UrbanSound8K/audio/"
    csvPath = "/content/drive/MyDrive/assigments/UrbanSound8K/metadata/UrbanSound8K.csv"
    modelPath = "/content/drive/MyDrive/models/"
    musicPath = "/content/drive/MyDrive/music/"

if using Colab - mount the drive with following command:-
from google.colab import drive
drive.mount('/content/drive', force_remount=True)

else set to the local path

# Author
Rohan Frederick
Roll No: M23CSA525


# References
https://www.geeksforgeeks.org/hide-axis-borders-and-white-spaces-in-matplotlib/
https://stackoverflow.com/questions/16120481/matplotlib-grayscale-heatmap-with-visually-• https://pytorch.org/tutorials/beginner/data_loading_tutorial.html
https://stackoverflow.com/questions/2148543/how-to-write-a-confusion-matrix
https://medium.com/data-science-in-your-pocket/calculating-precision-recall-for-multi-• https://www.youtube.com/watch?v=er3LoYljvsU

# Git Repository Link
https://github.com/rohanfred/SpeechUnderstanding 