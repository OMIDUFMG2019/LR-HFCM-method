# A Large Reservoir Computing Forecasting Method Based on Randomized Fuzzy Cognitive Maps
This repository contains the code a novel forecastings technique based on R-HFCM, called LR- HFCM (or large reservoir of randomized high-order FCM) for predicting univariate time series. LR-HFCM is a hybrid method combining fuzzy time series (FTS), FCMs, and reservoir comput- ing. It is a type of echo state network (ESN) consisting of the input layer, intermediate (or large reservoir) layer, and output layer, where  LASSO  regression  is  applied  to  train  the  output  layer. The novelty of this approach is that the internal layer includes a very large reservoir, considering different combinations from the sets of concepts and order using a certain number of sub- reservoirs  to  capture  different  dynamics  of  input  time  series. It is important to highlight that the weights within each sub- reservoir are chosen randomly and remain constant throughout the training process. The validity of the LR-HFCM approach is evaluated  across  15  different  time  series  datasets.  The  results highlight  the  outperformance  of  the  LR-HFCM  technique  in comparison to various baseline ML, DL and fuzyy forecasting models.

## Objectives and contributions
1) The code implements Developing a new R-HFCM forecasting method  termed  LR-HFCM.  LR-HFCM  is  a  form  of ESN that merges FTS, FCM, and RC where LASSO regression as  time-effective learning is applied to train the output layer.
2) The  first  introduction  of  FCM  as  a  large  reservoir computing model in the literature.
3) Implementing and evaluating a new forecasting model based on FCM, whereas k and Ω are chosen automatically. Thus, it improves the capacity of R-HFCM method generating differet dynamics of input time series to the output layer.
4) It is less complex and cheaper than existing deep learning models.
 
## References
Orang, O., Erazo-Costa, F. J., Silva, P. C. L., Barreto, G. A., & Guimarães, F. G. (2024). A Large Reservoir Computing Forecasting Method Based on Randomized Fuzzy Cognitive Maps. In 2024 IEEE International Conference on Evolving and Adaptive Intelligent Systems (EAIS). IEEE. DOI: 10.1109/EAIS58494.2024.10570027.

## Computational Experiments

To use the R-HFCM model, upload your cleaned and pre-processed dataset, then run the Jupyter Notebook to visualize the results. Before running the model, it is necessary to install the pyFTS library using the command !pip3 install -U git+https://github.com/PYFTS/pyFTS. All computational experiments in this study were implemented using Python 3.6.12 with open-source packages such as Scikit-learn, Pandas, Numpy,Pytorch, Tensorflow and pyFTS.# LR-HFCM-method
