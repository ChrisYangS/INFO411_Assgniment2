# INFO411_Assignment2

This is for the assignment 2 project

Workbooks start with #.workbook name. You should open files in the order they
are listed in the README.md file:

1. assignment2_ECA
2. assignment2_model_training
3. Dashboard

## Note:

1. When you run the first document. This file contains the code to apply
   exploratory data analysis on the dataset. Then, it will apply data imputation
   to clean data by dropping ca columns which have more than 99% missing data,
   and apply knn method to fulflil the rest of missing data. The cleaned data
   will be saved in the `cleaned_data` folder. This dataset will be used in the
   next document.
2. the second Julia file will apply the model training on the cleaned data. We
   decided to use the following models:

    - Decision Tree
    - Random Forest
    - KNN In the end, we will compare the performance of these models and choose
      the best one to apply on the dashboard.

3. The third file will create a dashboard to demonstrate the output of
   exploratory data analysis and model training.

## Contributors:

-   Jason Lu (EDA, Dashboard)
-   Chris Yang (EDA, Training Model, Dashboard)
-   Gran Isaiah (EDA, Training Model, Report)
