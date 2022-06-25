# Unsupervised Learning
This project is my 6th semester term project from ML.
I used an external dataset i.e. [Wholesale customers Data Set](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers) dataset in my workspace, and trained the model in Jupyter Nodebook. 
In this project I used unsupervised machine learning techniques on product spending data collected for customers of a wholesale distributor in Lisbon, Portugal to identify customer segments hidden in the data. Here I firstly explore the data by selecting a small subset to sample and determine if any product categories highly correlate with one another. Afterwards, I preprocessed the data by scaling each product category and then identifying (and removing) unwanted outliers. With the good, clean customer spending data, I apply PCA transformations to the data and implement clustering algorithms to segment the transformed customer data. Finally, I compare the segmentation found with an additional labeling and consider ways this information could assist the wholesale distributor with future service changes.

# Software and Libraries:
This project uses the following software and Python libraries:

* Python 2.7<br>
* NumPy<br>
* pandas<br>
* scikit-learn<br>
* matplotlib<br>

# Starting the Project:
we need to have software installed to run and execute a Jupyter Notebook.

Note: If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer.Please make sure that you use the most recent version of project files when completing a project!

### This project contains three files:
* Creating Customer Segments(Unsupervised ML project).ipynb: This is the main file where I performed my work.<br>
* wholesale_customers_data.csv: The project dataset. We'll load this data in the notebook.<br>
* visuals.py: This Python script provides supplementary visualizations for the project. Do not modify.<br>

First we have to go to the folder containing the project files,then open the cmd(command Prompt) & use the command `jupyter notebook` or `ipython notebook` Follow the instructions in the notebook and answer each question presented to successfully complete the project. A README file has also been provided with the project files which may contain additional necessary information or instruction for the project. 
