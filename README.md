# Code and data for generating synthetic data

Aim: improving machine learning model for a small data set by generating synthetic data and learning a model on bigger data set

For generating data we are using [SDV](https://sdv.dev/) library

Files:
- Project_date_v3.xlsx - original data
- gen_data.csv - original data prepared for generating synthetic data
- test_data.csv - hold-out data set
- df_synth_X.csv - synthetic data, where X - used model
- synth_data.ipynb - processing original data, generating synthetic data
- test_synth.ipynb - testing synthetic data
