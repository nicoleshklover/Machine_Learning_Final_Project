# Is a File Malicious?

## Authors: Nicole Shklover and Inbar Rodan

**Date:** [spring 2023]

## Introduction

This project served as the final assignment for a machine learning course at Tel Aviv University. Our task was to develop a classifier capable of determining the likelihood of a given file being malicious or safe. We based this prediction on a dataset of 60,000 files that had already been categorized.

Portable Executable (PE) files are executable file formats used in various operating systems. These files are called "Portable" because they are not tied to a specific computer architecture, making them adaptable across different systems.

## Our Approach

Our project involved a series of steps, including data analysis, data preprocessing, training multiple machine learning models, and selecting the best-performing model based on the highest AUC score on the validation dataset.

## Results

Using an AdaBoost classifier, we achieved an impressive test AUC score of 0.8834, indicating the effectiveness of our model in identifying potentially malicious files. For our efforts, we received a grade of 91 on the project.

The project's code was implemented using Python in Jupyter Notebook.




# Machine Learning Final Project
**Is a file malicious?**<br>
**By: Nicole Shklover and Inbar Rodan**<br><br>
This was the final project for a machine learning course at Tel Aviv University.<br><br>
We were provided with information regarding various features of Portable Executable (PE) files and were asked to create a classifier capable of predicting the likelihood of a given file being malicious. This prediction is supposed to be based on a dataset of 60,000 files that had already been categorized.<br>
Portable Executable (PE) files are executable file formats used in various operating systems. The term "Portable Executable" signifies that the file format is not tied to a specific architecture, making it versatile across different systems.<br>
Our process involved data analysis, preprocessing, training multiple models, and ultimately selecting the best one, determined by the highest AUC score (on the validation dataset). <br><br>
Using an AdaBoost classifier, we achieved a test AUC score of 0.8834 and recieved a grade of 91 on the project.
The project's code is implemented using Python in Jupyter Notebook.<br><br>
