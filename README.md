# Team CLI03_Wisely

This repository contains the code for the CLI03_Wisely team. The focuse of the code is a proof-of-concept for
the main functionality of our app **Wisely**.

All code was written in Jupyter Notebooks which allow to easily explore the code and the results directory here in GitHub, without 
the need to install anything. If you would like to play around with the notebooks and execute them yourself, the following dependencies are required (versions used by us in brackets):

* python (3.6)
* pandas (0.24.0)
* numpy (1.18.5)
* matplotlib (3.2.2)
* scikit-learn (0.23.1)
* seaborn (0.10.1)
* nb_conda (2.2.2)


# Notebooks
The following notebooks should be regarded as our project demo.

### Wisely_demo.ipynb
This notebook contains code for processing of weather and energy data and and implementation
of our machine learning prediction model for the year 2016. We show in plots how Wisely can accurately predict
energy production. We made a simple function that allows to input a date and see the predicted and actual energy production
for that date.

### Wisel_household_data_analysis.ipynb
This notebook contains our analysis of residential household appliance usage. Here we show how dishwashers and washinc machines
are mainly run during sub-optimal times with regards to renewable energy generation.