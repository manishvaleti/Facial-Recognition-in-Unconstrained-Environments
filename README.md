# Facial-Recognition-in-Unconstrained-Environments
## Description
The core goal of this project is not to build a single facial recognition system, but to compare and benchmark various well-known CNN models. By implementing and testing architectures like VGG19, ResNet-50, and EfficientNetB0 on a standardized dataset, this work provides insights into their relative strengths and weaknesses for facial recognition tasks in unconstrained environments.

## Features
Model Implementation: Provides working implementations for multiple CNNs for facial recognition.

Performance Benchmarking: Analyzes and compares the models based on key metrics like accuracy.

Standardized Testing: All models are evaluated on the public LFW dataset to ensure a fair and consistent comparison.

## Dataset
This analysis exclusively uses the Labeled Faces in the Wild (LFW) dataset. LFW is a standard benchmark for evaluating facial recognition algorithms in unconstrained settings, containing more than 13,000 images of faces collected from the web. This choice ensures that the performance analysis is comparable to other published results.

## Models & Analysis
This project is centered around the evaluation of the following pre-trained CNN architectures:

VGG19: A classic deep CNN architecture known for its simplicity and depth.

ResNet-50: A residual network designed to overcome the vanishing gradient problem in very deep networks.

EfficientNetB0: A modern architecture that scales model depth, width, and resolution in a balanced way for optimal efficiency and accuracy.

The analysis involves fine-tuning each of these models on the LFW dataset and then rigorously evaluating their performance to determine which architecture is best suited for this particular task.
