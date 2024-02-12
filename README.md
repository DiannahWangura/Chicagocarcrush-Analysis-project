## 1. Problem Statement 
Vehicle Safety Board of Chicago working with the insurance stakeholder are launching a campaign to reduce car crashes in the city. They would like to determine which car crashes are preventable and which are not. Specifically: Preventable Crashes: These accidents could have easily been avoided. They typically result from not following traffic laws or negligent driving. 

## 2. Data Preprocessing:
a. Dropping Irrelevant Columns: 
Columns that are not relevant to the prediction task such as "", "", "", "", "", "", "", "", "", "", "" were removed to reduce the dimensionality of the datasets and focus the model on relevant features whilst improving computational efficiency.
b. Checking Missing Data: 
Rows containing missing values were dropped using "dropna()" method 
c. Checking and handling duplicate data
d. Merging datasets (Crashes, Vehicles & People) : 
We used three different datasets and merged them to create a comprehensive dataset for training and training the dataset
e. Label encoding of categorical values:
Categorical variables were converted into numerical representations using Label Encoding, numerical are suitable for training models
f. Train-Test Split:
The dataset was split into training and testing using the "train_test_split" function. This allows the model to train on one subset and evaluate on another, providing a reliable estimate of the model's performance on unseen data. 

## 3. Modelling and Analysis:

List the machine learning, time series, or deep learning models you evaluated.
Briefly explain the rationale for choosing these models.
Describe your model training and evaluation process, including metrics used.
Mention any hyperparameter tuning performed and the techniques used.

## 4. Results and Discussion:

Present the key findings of your analysis, including model performance metrics.
Discuss the strengths and limitations of each model.
Highlight any interesting patterns or insights discovered from the data.

## 5. Conclusions and Future Work:

Summarize the main conclusions drawn from your analysis.
Discuss the implications of your findings for stakeholders like city officials, insurance companies, etc.
Suggest potential avenues for future research or improvements to your work.

## 6. Additional Sections (Optional):
Data Exploration: Briefly describe any exploratory data analysis performed.
Visualization: Include visualizations if they enhance understanding.
Code and Resources: Provide links to code repositories or data sources.
References: List relevant citations used in your research.
