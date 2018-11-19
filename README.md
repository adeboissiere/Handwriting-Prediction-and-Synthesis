# Handwriting Prediction and Synthesis based on Alex Graves' paper "Generating Sequences With Recurrent Neural Networks"

This project is an implementation of Alex Graves' handwriting generation using LSTM with Mixture Density Network and an Attention Mechanisme using Pytorch. The goal is to code in a straightforward manner. Performance might be sacrificed for better an easier to read code. 
So far, only the handwriting generation is functional (section 4). The synthesis is currently a WIP.
This project uses the strokes and ascii transcriptions of the IAM On-Line Handwriting databse.

## Handwriting Prediction (section 4)
The network consits of 3 layers of 400 LSTMS. 20 gaussian mixtures are used. See Handwriting generation.ipynb 
![alt text](https://raw.githubusercontent.com/gnocchiflette/Handwriting-Prediction-and-Synthesis/master/sample_random_color.png)

## Handwriting Synthesis (section 5)
See Handwriting prediction.ipynb. The code does not work so far. There seems to be an issue with the attention mechanisme. 
