README

1) The project zip file, Rajendren_Project2.zip, contains a "Program Files" folder and README.txt & MLP_Project2_Report.docx
2) The "Program Files" folder has the MLP_Project2.ipynb jupyter notebook and data file, nba.csv.
3) Extract MLP_Project2.ipynb jupyter notebook and data file, nba.csv into jupyter working directory. The data file, nba.csv and MLP_Project2.ipynb must be in the same folder.
4) Launch the jupyter notebook, navigate and find MLP_Project2.ipynb and clicking on it will bring up the notebook in a new browser tab.
5) Select all cells either by pressing shift + enter or by clicking on the Menu "Cell" and selecting "Run All".

All cells of the MLP_Project2.ipynb program file must be selected at once and ran for the program to work properly.
After this an individual cell can be run to test a particular model.

Notes:
1) Testing the best parameters with grid search is the part of the program that takes a long time to complete, depending on the model it can take up to three minutes to run.
2) MLP_Project2.ipynb is tested with python 3.8.3 with jupyter version 6.0.3. The time taken to run the entire program (i.e. cells) and produce results can take anywhere between 10 to 20 minutes depending on resources and configuration of the computer.

This program will take the nba.csv dataset and remove the 'name' attribute as it is not relevant in predictiong an outcome. 
The data will then be split into a training set (80%) and test set (20%). This training set will be given to a dataframe.
We will then remove/add certain features to the training set which will then be given to another dataframe.
We will compare the F1 scores produced by each model for both dataframes and select the superior dataframe to run further tests on.
