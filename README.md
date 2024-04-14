# SimCLR_self_supervised_learning

# Self-Supervised Learning with SimCLR

This repository contains the implementation of the SimCLR framework tailored for self-supervised learning, particularly applied to medical imaging datasets, focusing on the PneumoniaMNIST dataset. The project demonstrates the construction of a dataset suitable for contrastive learning, the implementation of the SimCLR loss function, and the evaluation of model performance using linear probing and fine-tuning strategies.

## Project Setup

To run this project, you need to install several dependencies, primarily based around PyTorch and PyTorch Lightning.

## Data Preparation  

The project uses the MedMNIST dataset, specifically formatted for the PneumoniaMNIST variation. The data preparation involves setting up datasets that apply transformations and augmentations to create positive pairs for the contrastive learning model.

## Key Features
- SimCLR Framework: Implementation of the SimCLR architecture suitable for medical images.
- Data Augmentation: Utilizes various data augmentation techniques to generate positive and negative pairs for training the contrastive model.
- Loss Function: Custom SimCLR loss function for learning from positive and negative pairs.
- Evaluation Strategies: Includes linear probing and fine-tuning for evaluating the performance of pre-trained models.