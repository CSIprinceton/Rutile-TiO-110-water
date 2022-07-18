# DP training data for rutile TiO2 - water interface

This repository contains the training data and input files needed to train a DNN interatomic potential for TiO2 rutile (110)/ water interface. The DNN model was constructed using the Deep Potential (DP) method, as implemented in the DeepMD-kit code. Energy and forces in the data were computed with the SCAN functional implemented in the CP2K package. For more information of the methodology used to build the DNN training data, please see the reference cited at the end of this document.

Within this repository you will find:

1) raw_data: The raw data used to train the DP model;
2) train: The DeepMD-kit input files;
3) graphs: The frozen DNN graphs that can be used to run DP molecular dynamics. 


If you use this training data, please read and cite:

Bo Wen, Marcos F. Calegari Andrade, Li-Min Liu and Annabella Selloni (2022) To be submitted.
