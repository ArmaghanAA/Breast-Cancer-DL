
In this project, the aim is to detect breast cancer with the help of a deep neural network.
The dataset was related to the features extracted from the cancerous masses in the breast of several patients. Some features have been obtained from digital images that describe the characteristics of cell nuclei in the said images. The goal is to build a deep learning model to diagnose whether a person's cancer is benign or malignant based on the above features.

# DataSet

In the data set provided to you, the type of cancer is written in the diagnosis column for each recorded data. Malignant (M) and benign (B)

# Step 1- Exploratory data analysis
*   More detailed and statistical analysis
*   Visualization ( histogram and heat map)
*   Corrolation map

# Step2- Data Preprocess
Data preparation for modeling:
*   Spliting Data into train, test and validation sets.
*   Encoding categorical features
*   Standardization Data

# Step3- Modeling Data
*   Sequential
*   Functional

## Sequential modeling
*   Initialize Dense_2, Dense_4 and Output layers with GlorotNormal method.
*   Initialize Dense_3 and Dense_3 layers with HeNormal method.
*   Set the Dropout probability in Dropout_1 and Dropout_2 to 0.2.
*   Set the Dropout probability on Dropout_3, Dropout_4 and Dropout_5 to 0.3.
*   For layers Dense_2 to Dense_5 as well as the Output layer, use L2 regularization and set its coefficient value to 0.02.

epochs and batch values are equal to 200 and 32, respectively.

## Functional modeling
Modeling in this way leaves your hand open for more free and complex designs.

# Step4 - Evaluating models along with drawing diagrams
*   Confusion matrix
*   Accuracy-epoch diagram
*   Loss-epoch diagram
"""
