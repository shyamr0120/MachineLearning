All cells of the MLP_Project1.ipynb program file must be selected at once and ran for the program to work properly.

training.data and test.data must be in the same folder as the MLP_Project1.ipynb program file.

Each model takes approixmately a minute to be created. As 10 models are produced for both the C4.5 and CART algorithms, the program takes approximately 20 minutes to run to its completion.

The models for C4.5 are produced in the cell right after the cell that contains the "cleaner function". The models for CART are produced in the cell right after. An ouput ot 01,2,....10 is printed to signify which model has been created.
For example, an output of 2 means that the second model has been completed. All the C4.5 models are completed before the models for CART are created.

The results of the validation of the 10 C4.5 models are produced in the fourth to last cell.
The results of the validation of the 10 CART models are produced in the third to last cell.

The results of the test data on the best C4.5 model are produced in the second to last cell.
The results of the test data on the best CART model are produced in the last cell.

The results have two columns for each model. The '+' and '-' values on the left column are the predicted ouputs of the given data cell. The '+' and '-' values on the right column are the actual ouputs of the given data cell.
At the end of each column is that particular model's F1 score.