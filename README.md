# Data-Analytics-Project
Course project for the subject Data Analytics(UE18CS312)

'''Since Github renders .ipynb files at times, while viewing the .ipynb file PLEASE click on 'external with nbviewer' on the top right of file (looks like 'theta' symbol) so that all the plots, graphs and other visualizations are completely visible'''

Election Result Prediction using Random Forest

PG_28_DATA SPHERE

AKASH YADAV         - PES2201800415

NAVEEN SURESH       - PES2201800508

SAIPRAKASH L SHETTY - PES2201800730

With a basic glance on the proposed problem, we find out that the solution to the problem should belong to the classification category since the candidate contesting the election can wether win the election or lose it, it's a case of binary classification. The classifier we'll be using is the Random forest classifier. By using an ensemble classifier we can aim for a higher accuracy and better prediction.

The dataset used here has a total of 2263 rows and 19 columns. The number of candidates who contested the election is 2018.
In order to predict the target variable "WINNER", first we need to select the columns necessary for prediction and exclude all the redundant columns. Also we nedd to categorize the columns into categorical & numerical columns.

We will be using Random Forest Classifier to predict the winners of the election. In order to know the optimum number of trees required to predict the result with highest accuracy, we will be plotting the accuracy score for various values of k and will be selecting k value that gives highest accuracy.
We found the accuracy to be 96.2478 %. 

To Run the code:

Download the file "DATA SPHERE ELECTION DATASET.csv"

Download the "Data_sphere_Final.ipynb" file and place it in the same folder as the dataset, then install the required libraries.

Run the Notebook to obtain the result.
