# Critical-Temperature-Prediction
This repository contains the dataset for different Chemical Compounds. The dataset has 2 files. One contains the physical and chemical properties including the Boiling point, Melting point, Standard Enthalpies, etc. The other file contains the chemical decomposition of the material.
This predictor utilizes these features to predict the Critical Temperature of the Superconductivity material. 
This repo contains the jupyter notebook for the implementation and the testing of the results. The dimensions of the input space is 167. 
The methods used for the regression were-
1) The Support Vector Regressor, with the "rbf" kernel and the penalty factor(or regularization factor-C) was 30.
2) The Neural Network Method with 3 Hidden layers and Early Stopping as a regulariser, both adaptive and invscaling methods to modify the learning rates were used. 
Support Vector Machine Regressor with high penalty factor means hard decision boundaries but at the same time increased computation cost. T
