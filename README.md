# Machine Learning Final Project
**Is a file malicious?**<br>
**By: Nicole Shklover and Inbar Rodan**<br><br>
This was the final project for a machine learning course at Tel Aviv University.<br><br>
We were given information about several features of executable files (.exe) and were asked to build a model that predicts the chance of a particular file to be malicious through static analysis of the files.<br>
This project is a binary classification problem in which we classified files into two categories - is the file malicious (1) or not (0), based on the features in the data set. Some of the features we received are known and some are anonymous.<br>
we received 60,000 observations that were classified as a malicious/non-malicious file. We analyze the given data, processed it and selected the best model to predict the patterns in the unseen test data.<br><br>
We achieved a test AUC score of 0.9579 using "XGBoost classifier".<br>
We recieved a score of 95 on this project.<br><br>
The project is in Jupyter Notebook in Python and Markdown.<br><br>


In our project, we focused on analyzing Portable Executable (PE) files, which are executable file formats used in various operating systems. The name "Portable Executable" refers to the fact that the file format is not architecture-specific, making it versatile across different systems. Our primary goal was to develop a binary classifier capable of accurately identifying whether a given file is malicious. To achieve this, we used advanced techniques to examine the relationships between the file's features and identify patterns indicative of malicious behavior.
