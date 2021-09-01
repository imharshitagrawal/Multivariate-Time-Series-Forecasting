# Architecture for Multi-variate Time-Series Forecasting




### Abstract
> Time-Series Forecasting problems contain a complex mixture of inputs including static covariates, observed inputs only in the past, and known inputs into future. Given the diversity of time-series problems across various domains, numerous neural network design choices have emerged. Over the years, literature has been enriched with numerous models for Time-Series Forecasting such as 1D Convolutional Neural Networks to Long-Short-Term Memory Networks and sequence-to-sequence architectures. In recent years, research has proposed several deep learning (DL) approaches to provide reliable remaining useful life (RUL) predictions in Prognostics and Health Management (PHM) applications. However, the available approaches do not consider the heterogeneity of the prognostics
data and are often not very efficient in utilizing the temporal correlation in sensor data. In this work, we propose an Encoder-Decoder architecture followed by the use of Multi-Head Self Attention mechanism, while taking into consideration the variety of inputs, to learn both the short-term temporal features and long-term dependencies respectively in sensor data to accurately predict the RUL of aircraft engines. Since the sensor data can be complex and relatively simple in different datasets, we also employ Gated Linear Units (GLUs) to make our architecture self-adjusting to variety of complexities in datasets. Our work shows significant improvements in RUL estimation over the already available approaches for Commercial Modular Aero-Propulsion System Simulation (CMAPPS) and New Commercial Modular Aero-Propulsion System Simulation (NCMAPPS) datasets.
.


##  Jupyter Notebooks Description

> CMAPPS Hyperparameter_optimization.ipynb  : Contains our model, runs on CMAPPS datasetand also includes hyperparameter optimization. Simply run the notebook cell by cell following the     
                                              instructions written.
> CMAPPS Most optimal parameters.ipynb  : Contains our model, runs on CMAPPS datasetand using the hyperparameters obtained by hyperparameter optimization. Simply run the notebook cell by cell
                                          following the instructions written.
> NCMAPPS Best.ipynb : Contains our model and runs NCMAPPS dataset.
