# Plagiarism Project Deployment
The project is pursued as a part of Machine Learning Engineer Nanodegree by Udacity. A great deal of code (initial commit of this repository) was developed by the Udacity team and in not my original work.

This repository contains code and associated files for deploying a plagiarism detector using AWS SageMaker.

## Project Overview
In this project, I completed a plagiarism detector that examines a text file and performs binary classification; labeling that file as either plagiarized or not, depending on how similar that text file is to a provided source text. Detecting plagiarism is an active area of research; the task is non-trivial and the differences between paraphrased answers and original work are often not so obvious.

A strong simplification of the task is the requirement to detect plagiarism from a single source (a Wikipedia article for a respective topic).

This project is broken down into three main notebooks:

### Notebook 1: Data Exploration (entirely provided by Udacity)
Load in the corpus of plagiarism text data.
Explore the existing data features and the data distribution.

### Notebook 2: Feature Engineering (partially provided by Udacity)
Clean and pre-process the text data.
Define features for comparing the similarity of an answer text and a source text, and extract similarity features.

### Notebook 3: Train and Deploy Your Model in SageMaker (partially provided by Udacity)
Upload train/test feature data to S3.
Define a binary classification model and a training script.
Train your model and deploy it using SageMaker.
Evaluate your deployed classifier.

I used a NN classifier form sklearn. This approach achieved 96% accuracy on the test data.
