# Final-Project
The focus of the project is to utilise advanced machine learning techniques, in particular XGBoost, to predict UK city temperatures, while exploring the complex interactions between city temperatures and a variety of climatic, geographical and temporal factors. Using data from the Community Earth System Model Large Ensemble (CESM-LE), the project assesses the effectiveness of urban temperature models in terms of different dimensions such as geographic location, seasonal variability, and temporal accuracy.
The workflow is streamlined using Jupyter notebooks, each serving a specific purpose in the analysis pipeline.

## Project Structure

- **environment.yml**: The environment file that includes all the necessary dependencies. Please install this first to set up your environment.

- **combine_data.ipynb**: After downloading the CESM-LE data, use this notebook to combine the data into a single dataset for analysis.

- **LinearRegression_compare.ipynb**: This notebook compares the performance of a linear regression model with the XGBoost model on the combined dataset.

- **xgboost_final.ipynb**: This notebook is used for hyperparameter tuning and building the final XGBoost model. The model is saved at the end of this notebook.

- **xgboost_final_ana.ipynb**: After the final model is built and saved, this notebook analyzes the model's performance in various scenarios and provides accuracy metrics.
