# Machine Learning Final Project
**Is a file malicious?**<br>
**By: Nicole Shklover and Inbar Rodan**<br><br>
This was the final project for a machine learning course at Tel Aviv University.<br><br>

We were given information about several features of Portable Executable (PE) files and were asked to create a classifier that predicts the chance of a particular file to be malicious, based on 60,000 other files that were already classified.<br>

Portable Executable (PE) files are executable file formats used in various operating systems. The name "Portable Executable" refers to the fact that the file format is not architecture-specific, making it versatile across different systems.

We analyzed the data, pre-processed it, trained several models and selected the best one (with the highest AUC score). <br><br>
We achieved a test AUC score of 0.8834 using an "AdaBoost classifier".<br>
We were graded 91 on this project.<br><br>

The project is implemented with Python in Jupyter Notebook.<br><br>
