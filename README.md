# Proj4 Binary Classification

## How to run this code

1) Install Jupyter Notebook: http://jupyter.org/

2) Open a console in this project's directory

3) Run `jupyter notebook`

4) Open a browser to http://localhost:8888

5) Each model is located in a file with the following naming convention: <ML approach> - <dataset> (eg. NN - PTO).
  
6) Run each model file by clicking Cell -> Run All

7) In order to run the model using the with held data:
    - add the withheld to the respective dataset/category files (dataset_PTO.csv, Category_PTO.csv, dataset_DC.csv, and Category_DC.csv) 
    - In the 3rd cell of each model code, change the value of the `test_size` argument passed to `train_test_split` to "#data pairs in withheld data / total number of data pairs"

