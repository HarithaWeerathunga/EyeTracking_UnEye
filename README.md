# Eye Movement Analysis with Saccade and Fixation Detection

This repository contains code to analyze eye movement data, particularly focusing on the detection of saccades and fixations. The main script processes eye-tracking data for specific subjects and uses a deep neural network model to classify events as saccades or fixations. It utilizes the `uneye` library for the deep neural network model to predict these events. The main tasks include reading the data, filtering it for specific subjects, and predicting the eye movement events.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- uneye

You can install the required libraries using:

`pip install pandas numpy matplotlib uneye`
