# Machine Learning Final Project
**Is a file malicious?**<br>
**By: Nicole Shklover and Inbar Rodan**<br><br>
This was the final project for a machine learning course at Tel Aviv University.<br><br>
We were provided with information regarding various features of Portable Executable (PE) files and were asked to create a classifier capable of predicting the likelihood of a given file being malicious. This prediction is supposed to be based on a dataset of 60,000 files that had already been categorized.<br>
Portable Executable (PE) files are executable file formats used in various operating systems. The term "Portable Executable" signifies that the file format is not tied to a specific architecture, making it versatile across different systems.<br>
Our process involved data analysis, preprocessing, training multiple models, and ultimately selecting the best one, determined by the highest AUC score (on the validation dataset). <br><br>
Using an "AdaBoost" classifier, we achieved a test AUC score of 0.8834 and recieved a grade of 91 on the project.
The project's code is implemented using Python in Jupyter Notebook.<br><br>
