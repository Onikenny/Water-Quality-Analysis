# Water-Quality-Analysis

This Project uses CEFAS’ 2021 data on biotoxins and phytoplantkon (see https://www.cefas.co.uk/data-and-publications/habs/england-and-wales-biotoxins-and-phytoplankton-results-2021/) to find patterns of higher or lower concentration of either (or both) according to features provided. 

The data in focus is the phytoplankton tab. The data is cleaned and a multi-layer feed-forward neural network is trained to predict from a set of input features whether the phytoplankton level detected is above the threshold specified. The project aims to assess various factors that affect the performance of Artificial neural networks using this dataset as a case study. 

Read the final report on this project here on pages 2-6 here: [Understanding Artificial Intelligence.pdf](https://github.com/Onikenny/Water-Quality-Analysis/files/7925211/Understanding.Artificial.Intelligence.pdf)


### Packages used:
          Python.3.10 
          Pandas Python Data Analysis Library. V.1.3.4 for data cleaning and pre-processing. Also, to generate Statistical profiling of data.
          Sklearn for predictive analysis
          Keras for Predictive modelling
          Seaborn 0.11.2, Matplotlib for data visualization

For code on data cleaning and model building, view notebook here: https://colab.research.google.com/drive/1UVYE1yTJ_sU2gShHShXGQ6zz0qZWKTNy?usp=sharing
