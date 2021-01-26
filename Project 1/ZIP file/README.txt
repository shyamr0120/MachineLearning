1) The project zip files contains "MLP_Project1 Program Files" folder and README.txt & Machine Learning Project 1 Report.docx
2) "MLP_Project1 Program Files" folder has MLP_Project1.ipynb jupyter notebook and data files, test.data & training.data
3) Copy MLP_Project1.ipynb jupyter notebook and data files, test.data & training.data into jupyter working directory. The data files (test.data & training.data) and jupyter notebook (MLP_Project1.ipynb) must be in the same folder.
4) Launch the jupyter notebook, navigate and find MLP_Project1.ipynb and click on it which would bring up the notebook in new browser tab.
5) Select all cells either by selecting "Run All" or any other method. All the cells must be run in order for the program to work.

Observation & Results:
1) Each model takes approximately about a minute to create. As there are 10 models to be created, the entire program takes approximately 15 to 20 minutes to run to its completion depending on computer resource availability and configuration.
2) The models for C4.5 are produced in the cell right after "cleaner" function. The CART models are produced in the following cell. An output of 01,2,....10 are printed to signify which model has been created.

For example, an output of 2 means, the second model has been completed. All the C4.5 models are completed before the models for CART are created.

3) The results of the validation of the 10 C4.5 models are produced in the fourth to last cell.
4) The results of the validation of the 10 CART models are produced in the third to last cell.
5) The results of the test data on the best C4.5 model are produced in the second to last cell.
6) The results of the test data on the best CART model are produced in the last cell.

The results have two columns for each model. The '+' and '-' values on the left columns are the predicted outputs of the given data cell. The '+' and '-' values on the right columns are the actual outputs of that particluar data entry.
Each model's F1 score is at the end of each column of that particular model.