# FaceID Verification

This project centers around the implementation of Siamese Neural Networks for one-shot image recognition tasks.
## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Illustration](#illustration)

## Introduction

This project involves training the model with three distinct datasets: positive, anchor, and negative. 
When a positive image is paired with an anchor image, it should yield a label of one, whereas pairing an anchor image with a negative image should result in a label of zero.
The primary objective of this project is to develop a model that can be integrated with a connected camera to your computer or laptop, enabling real-time verification on a live stream.

## Illustraion

We devised a custom model utilizing the Layer class and proceeded to instantiate the neural network outlined in the referenced paper. 
Our dataset was meticulously curated, with the positive and anchor data sets harvested directly from the camera feed linked to our laptop or computer, ensuring a robust foundation for our model development.
We utilized the negative dataset sourced from the link provided at http://vis-www.cs.umass.edu/lfw/#download, which comprises images of various individuals worldwide. 
Following this data collection, we proceeded to train a model, employing precision and recall as the key evaluation metrics. 
Subsequently, we rigorously tested the model, and the final outcomes were deemed satisfactory.

## Features

- Set GPU growth
- Jupyter notebook for the code
