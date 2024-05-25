This repository provides supplemental information to the analyses in the master's thesis "Household Carbon Footprints and  Consumers’ Carbon Beliefs in Germany:  Analysis using Multivariate Regression and K-Prototype Clustering" submitted to the TUM School of Life Sciences for obtaining the degree of the Master of Science in Sustainable Resource Management. 
\
\
\
The six folders in this repository contain the following contents: 

**1. Data cleaning urban-rural classification - Python** 

This folder includes the Python Jupyter Notebook for combining the three datasets into one dataset: 1) NUTS ID and region name, 2) urban-rural classification, and 3) postal code.
The first notebook named 'data_cleaning_urban_classification_oecd' merges the datasets with OECD classification. The second one named 'data_cleaning_urban_classification_RLK_KTU' merges the datasets with BBRS classification.

**2. Data cleaning for regression analysis - Python** 

This folder includes the Python Jupyter Notebook for combining the three batches of survey data and cleaning the dataset for R regression analysis. The folder 'data' includes the three batches of the original responses from the survey.
In detail, this notebook does the following data-cleaning tasks:
      - It cleans the education columns so that only the highest level of education remains.
      - It maps the urban-rural classification with the postal code from the responses.
      - It drops the rows containing null values.
      - It calculates the actual rank and returns the belief difference variables.
      - It cleans the political party variable. 
      - It removes the outliers in the income column. 


**3. Exploratory data analysis - Python** 

This folder includes the Python Jupyter Notebook for exploratory data analysis of the final clean dataset from the second folder. Extensive descriptive analytics on the distributions of the variables from the responses are available here. 

**4. One way ANOVA for mobility - Python** 

This folder contains the Python Jupyter one-way ANOVA test for the distributions of the mobility data from the three batches of responses that were collected inconsistently. 
Moreover, the information on the engines of the cars of the respondents is provided here.

**5. Regression analysis - R** 

This folder contains the R scripts for the regression modeling across the four consumption areas and the total CO2 emission.

**6. Clustering analysis - Python** 

This folder contains the Python Jupyter Notebook for clustering analysis with the detailed steps and code for UMAP, K-Prototype, LGBM, and SHAP values. 
\
\
\
Downloading the folder is sufficient for running the code. The folder contains the dataset and the code to load the dataset is written in a relative path. 
Each Jupyter notebook and R markdown accompany the PDF version as well. 

