This repository provides supplemental information to the analyses in the master's thesis "Household Carbon Footprints and  Consumers’ Carbon Beliefs in Germany:  Analysis using Multivariate Regression and K-Prototype Clustering" submitted to the TUM School of Life Sciences for obtaining the degree of the Master of Science in Sustainable Resource Management. 

The six folders in this repository contain the following contents: 

1. This folder includes the python jupyter notebook for combining the three dataset, NUTS ID and region name, urban-rural classification and postal code into one table. The first one named .. merge the datasets with OECD classification. The second one named … merged the datasets with BBRS classification.
   
2. This folder includes python Jupyter notebook for combining the three batches of survey data and cleaning the dataset for R regression analysis. It cleans the political party variable, drops the rows containing null values  and excludes the outliers in income column. The folder in this folder, data contains the three batches of the original responses from the survey.
   
3. This folder includes exploratory data analysis of the final clean dataset from folder 2. More extensive descriptive analytics on the distributions of the variables from the responses are available in the Jupyter notebook …
   
4. This folder contains one way Anova test for the distributions of the mobility data from the three batches of responses that were collected inconsistently. Moreover, the information on the engines of the respondents are here.
   
5. This folder contains the R script for the regression Modeling across the four consumption areas as well as the total co2 emission. 
6. This folder contains the python Jupyter notebook for clustering analysis. It contains the code for UMAP, K-Prototype, LGBM, and SHAP values. 


Downloading the folder is sufficient for running the code. The folder contains the dataset and the code to load the dataset is written in a relative path. 
Each Jupyter notebook and R markdown accompany the pdf version as well. 

