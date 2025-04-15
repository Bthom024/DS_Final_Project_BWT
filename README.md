# DS_Final_Project_BWT
This repository contains all necessary files, code, and documents related to the capstone project for DS-450-01.
The goal of this project is to develop a predictive model for breast cancer recurrence, leveraging advanced machine learning techniques to improve clinical decision-making and patient outcomes. Breast cancer recurrence, whether local or metastatic, remains a significant challenge in cancer care, and accurate prediction of recurrence risks is crucial for personalized treatment planning and long-term monitoring. The project will utilize a comprehensive dataset, which includes clinical and demographic features like tumor size, lymph node status, and age.

#### Final Project Proposal 
A comprehensive proposal for my semester-long predictive analytics project focused on predicting breast cancer recurrence by a number of demographic variables. This work will not only enhance understanding of risk factors associated with breast cancer recurrence but also demonstrate the practical application of predictive analytics in healthcare decision-making.

#### Exploratory Data Analysis
The exploratory data analysis phase provided critical insights into the structure, quality, and patterns within the dataset used to predict breast cancer recurrence. The dataset comprises a diverse array of clinical and demographic variables, including tumor size, lymph node status, patient age, and recurrence status.

Initial data inspection revealed a generally well-structured dataset with minimal missing values. Descriptive statistics and visualizations were used to summarize key features: tumor size and lymph node involvement showed right-skewed distributions, while age displayed a relatively normal distribution. Recurrence outcomes were imbalanced, with a smaller proportion of patients experiencing recurrence—a factor that will be important for model development and evaluation.

Correlation analysis indicated strong associations between certain clinical features and recurrence status, particularly tumor size and lymph node status, which are consistent with established clinical knowledge. Visual exploration using box plots and heatmaps further highlighted significant differences in these variables between recurrence and non-recurrence groups.

Additionally, stratifying the data by demographic features such as age groups revealed potential interaction effects worth exploring in later modeling stages. These insights will guide the feature selection process and help in engineering meaningful variables for predictive modeling.

Overall, the EDA phase laid a strong foundation for building robust machine learning models by identifying key predictive variables, detecting potential data quality issues, and informing decisions around class imbalance and feature preprocessing.

#### Predictive Analytics
The project employed multiple machine learning models to predict breast cancer recurrence using clinical and demographic data. After preprocessing and validating statistical assumptions, a linear regression model was used as a baseline to examine general trends and variable relationships.

Subsequently, classification models were implemented, including:

Logistic Regression: Provided interpretability and baseline classification performance.

Decision Tree Classifier: Captured nonlinear patterns and interactions.

Random Forest Classifier: Improved performance via ensemble learning and reduced overfitting.

XGBoost Classifier: Delivered high accuracy and robustness through gradient boosting.

Each model was evaluated using metrics such as accuracy, precision, recall, and ROC-AUC, with XGBoost and Random Forest outperforming others. Feature importance analyses highlighted tumor size, invasive nodes, and menopausal status as key predictors.

Overall, the analysis supported the feasibility of predicting recurrence with high confidence, providing a foundation for data-driven clinical decision support.

#### Research Poster
A poster summarizing the work of the capstone project, which will be presented at Bellarmine University's 2025 Celebration of Student Research and Creativity.

### Commit Update 1/16/25
Files committed in this update include everything related to the initial project proposal. All files are titled DS_Final_Project_Proposal_BWT.xxxx This includes a .pdf file of the initial proposal report and a .pptx file of the project proposal presentation. The data set for this project was also committed at this time (DS_FinalProject_Data_BWT.csv).

### Commit Update 2/5/25
Files committed in this update include everything related to the Exploratory Data Analysis. All files are titled DS_EDA_BWT.xxxx This includes an .ipynb file containing the code necessary to complete the exploratory data analysis, a .pdf file containing the report for the exploratory data analysis, and a .pptx file containing the powerpoint presentation for the exploratory data analysis.

### Commit Update 2/28/25
Updated Exploratory Data Analysis to include more markdown descriptions and organization to the script. Script also contains overall conclusion.

### Commit Update 3/10/25
Committed the script for the preliminary predictive analytics model along with the associated powerpoint presentation for the last portion of the final project. The predictive analytics script contains XGBoost, Random Forest, and SVM predictive models.

### Commit Update 3/19/25
Committed the research poster of the final project for the Spring 2025 Celebration of Student Research and Creativity presentation.

### Commit Update 4/15/25
Committed the final predictive analytics model for the capstone project.
