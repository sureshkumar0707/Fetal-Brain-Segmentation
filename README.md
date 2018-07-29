# Fetal-Brain-Segmentation

## Introduction

This repository contains the implementation of 2D UNet architecture for fetal brain segmentation

## Network Architecture

![pipeline](./images/network.png)
(https://arxiv.org/pdf/1505.04597.pdf)

## Raw data

![data](./images/data.png)

<hr>

## Results

### Model predictions

![prediction](./images/model_predictions.png)


### Dice score with epochs

![dice](./images/dice_score.png)

<hr>

## How to use?

~~~~

git clone https://github.com/koriavinash1/Fetal-Brain-Segmentation.git
cd Fetal-Brain-Segmentation
pip install -r requirements.txt

~~~~

<hr>

## Pre-Processing data

Run Generate_Procesed_Data notebook for generating pre-processed data


## Folder structure

> ./src consists all source codes
> > config -> all initial configurations
> > data_loader -> multithread data loader
> > estimator -> model estimator class
> > network -> network architecture definition
> > runner -> main function


<hr>
If any comments or issues, pull requests/issues are Welcomed....

Thankyou
``` python runner.py``` for training or testing the model 
