# Physics-Informed Reservoir Model

![PINN_structure](https://github.com/Akmuhammet01/Physics-informed_Reservoir_Model/blob/main/images/10409_2021_1148_Fig1_HTML.png)

## Overview
This repository contains a Physics-Informed Neural Network (PINN) implementation for modeling pressure dynamics in 2D oil reservoirs. The model predicts pressure fields for single-well and multi-well scenarios using the diffusivity equation, embedding physical laws into the loss function for mesh-free solutions. Built with PyTorch, it achieves accurate predictions with losses as low as 1.2e-5 for two wells.

## Features
- **PINN Framework**: Multilayer perceptron (MLP) with tanh/sine activations.
- **Physics Integration**: Incorporates the diffusivity equation, boundary, and initial conditions.
- **Scenarios**: Single-well and multi-well (2, 3, 4 wells) pressure predictions.
- **Visualizations**: The model predicts pressure fields for single-well and multi-well scenarios
![Visualizations](https://github.com/Akmuhammet01/Physics-informed_Reservoir_Model/blob/main/images/Screenshot%20from%202025-10-25%2019-03-55.png)
![Visualizations](https://github.com/Akmuhammet01/Physics-informed_Reservoir_Model/blob/main/images/Screenshot%20from%202025-10-25%2019-03-43.png)
