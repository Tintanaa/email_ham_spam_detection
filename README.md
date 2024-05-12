### UNDER CONSTRUCTION (as .ipynb too)
Project Overview

This repository contains a pet project focused on email ham/spam detection. It utilizes both baseline machine learning models and large language models (LLMs) to achieve this goal. 

This project explores various approaches to classify emails and provides insights into the effectiveness of different methods.

Features

* Baseline Models: Implementations of traditional machine learning models for spam detection, such as:
    * Naive Bayes
    * Support Vector Machines (SVM)
    * Random Forest and etc.
* LLM Integration: Exploration of utilizing LLMs for enhanced spam detection, including:
    * Fine-tuning pre-trained LLMs on email data
    * Utilizing LLMs for feature extraction or augmentation

* Comparative Analysis: Evaluation and comparison of the performance of different models on a benchmark email dataset. 
* Data Preprocessing: Implementation of techniques for cleaning and preparing email data for model training.
* Visualization (under construction): Visualization of results and analysis to understand model performance and behavior.

Getting Started

1. Clone the repository:
git clone https://github.com/Tintanaa/email_ham_spam_detection.git

2. Install dependencies (in .venv/ .conda) (made with pip freeze, dont be scared of file size):
pip install -r requirements.txt

3. Add ham/spam folders in same directory with related data from file by link:
https://omsk-community.notion.site/Python-ML-NLP-da425a7699b04a76ab0d71d50d17cef1

4. Add results/csv folder. There will be stored preprocessed dataset for further work (for now, because i am too lazy to write mkdir=/)

4. Enjoy!

Project Structure

* `results/csv/{nameofpreprocessedcsv}.csv`: Contains folder for storing preprocessed .csv file
* `ham/`:  Ham email info
* `spam/`: Spam email info
* `spamdetect.ipynb`: Main ipynb for everything

### UNDER CONSTRUCTION (as .ipynb too)
Further Exploration

* Experiment with different hyperparameters for the baseline models.
* Explore various pre-trained LLMs and fine-tuning strategies.
* Analyze the impact of different data preprocessing techniques.
* Implement ensemble methods that combine baseline models and LLMs. 
* Develop a web application or API to demonstrate the spam detection functionality.
* Airflow integration
* .ipynb only for preprocessing, for other stuff .py files

Contact email: miiagkov123456@gmail.com

Appropriate folder structure after running .ipynb:

![изображение](https://github.com/Tintanaa/petproj_email_ham_spam_detection/assets/99679370/e8249794-8ae3-4184-acf0-a2c9b2b8d924)
