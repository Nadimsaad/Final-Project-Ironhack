# Final-Project-Ironhack
ROSSMANN STORES Sales Forecasting

# Rossmann Stores Sales Forecasting

Rossmann operates over 3,000 drug stores in 7 European countries. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With over a thousand individual managers predicting sales based on their unique intuitions, the accuracy of results can quite vary.

The source datasets were not able (to a certain extent) to provide necessary information such as the location of the stores. However, the information about the location was substracted from www.timeanddate.com based on holidays column which I placed in location.csv and then merged this dataset accordingly with my worked upon dataset (RossmannSales.csv).

Link to the datasets I was provided with: https://drive.google.com/drive/folders/1rV3E-miB8jvybdln8Em4z7RyNX2AUEyh?usp=sharing

This project is split into 3 phases:

### Phase 01

Phase 01 of the project dealt with Data Cleaning, EDA and feature Engineering.

Name of the python file: Final Project Rossmann Stores EDA available on my GitHub (https://github.com/Nadimsaad/Final-Project-Ironhack) 


### Phase 02

Phase 02 of the project dealt with using various Machine Learning models (Linear Regression, Lasso Regression, Decision Tree Regressor, and Prophet Regression) to predict Sales over a period up to 45 days for the Rossmann Stores.
I failed to implement the Auto ARIMA Time Series Model famously known for doing forecasts based on linear combinations of past values and forecasting errors because the dataset is too big for my laptop performance.

Among all the models used the XXX model showed best promise, with score of 94%.

Name of the python file: RossmannSales_ML_Models available on my GitHub (https://github.com/Nadimsaad/Final-Project-Ironhack) 


### Phase 03

Phase 03 dealt with using all the data inferred, from the previous phases, to create a simple business dashboard using tableau.



## Running the project

### Requirements

- Python 3.x 
- Jupyter
- Required ML libraries & visualisation libraries (scikit-learn, keras, tenserflow, numpy, pandas, seaborn, matplotlib) 
- Tableau Desktop

Note that the first python file (Final Project Rossmann Stores EDA) creates 2 .csv files location.csv and RossmannSales.csv
Alternatively, you can download these files from my GitHub link https://github.com/Nadimsaad/Final-Project-Ironhack.



## Run tableau playbook locally
- Download the tableau images of the dashboards from the above repo.
- Alternatively, you can check my tableau dashboards on the below Tableau Online links:


Executive Overview: https://public.tableau.com/shared/K7N79TQ6B?:display_count=n&:origin=viz_share_link

Analytic Overview: https://public.tableau.com/shared/98BF34FZB?:display_count=n&:origin=viz_share_link
