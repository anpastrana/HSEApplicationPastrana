# Machine Learning Project - June 2022
# Getting Ready: A Study of Socioeconomic and Cultural Factors affecting Climate Change Readiness of ASEAN and G7 Nations

### A. Project Description
The project’s title is “A Study of Socioeconomic and Cultural Factors affecting Climate Change Readiness of ASEAN and G7 Nations.” It was completed as part of the requirements for the course DATA103 (Introduction to Machine Learning). This was a data science project that utilized Hyperparameter Training: RFE Feature Selection, Model Training through Root Mean Square Error, Mean Absolute Error, and R2 with train-test splits in order to use the best-suited statistical model to explore the research objective. SHAP Global and Local Explainability was also used to explore the findings. The research objective was to determine the relationship of certain socioeconomic and cultural factors with the climate change readiness of ASEAN and G7 nations. The results for each group were compared against each other, to determine the similarities and differences in what affected climate change readiness for each nation group.

Country data from 1995 to 2020 was obtained from the University of Notre Dame’s Global Adaptation Index and the World Bank. This data ranges across a variety of variables, from climate change readiness, ecosystem resilience, democracy index, etc. This data was wrangled and cleaned into workable datasets via Python. 

Model training indicated that the OLS Regression model was best-suited for the ASEAN, and Random Forest Regression was best for the G7. Findings indicate that what influenced climate change readiness did indeed differ between each group. Climate change readiness in the ASEAN was positively correlated with higher levels of economic readiness for climate change, exposure to severe weather, and access to clean water. For the G7, climate change readiness was positively correlated with higher levels of green investments and social commitment, and lower levels of exposure to severe weather. 


### B. Running Requirements
To run the notebook found in the GitHub link, it is necessary that Python and the following Python packages are installed:
1. Numpy
2. Pandas
3. Matplotlib
4. Scipy
5. Seaborn
6. Shap
7. Collections
8. Linearmodels
9. Plotly
10. Sklearn
After installing Python and the above packages, please run the notebook in JupyterLab. 


### C. Contributors
The following are the students who contributed to the project:
1. Arianne N. Pastrana - arianne_pastrana@dlsu.edu.ph 
2. Amanda Limjoco - amanda_limjoco@dlsu.edu.ph 
3. Enrico Miguel Portugal - enrico_miguel_portugal@dlsu.edu.ph 
4. Isaiah Dela Cruz - isaiah_delacruz@dlsu.edu.ph 


### D.  Precise Contribution of Applicant Arianne N. Pastrana
I was personally responsible for the following aspects of the project:
1. Obtained the datasets from the given online databases;
2. Coded all statistical treatment methods, including initial OLS regression, train-test split, model training, Hyperparameter training, and SHAP explainability for both the G7 and ASEAN datasets;
3. Assisted Amanda Limjoco in reinforcing the data wrangling code;
4. Provided the statistical intuition behind the use of the selected methodologies (Random Forest Regression, OLS Regression, and SVM, along with RFE and SHAP) at all stages of the project.
 

