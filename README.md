# Physics-Informed Reservoir Model

![PINN_structure](https://github.com/Akmuhammet01/Physics-informed_Reservoir_Model/blob/main/images/10409_2021_1148_Fig1_HTML.png)

## Overview
This repository implements a Physics-Informed Neural Network (PINN) and Fourier Neural Operator (FNO) to model pressure dynamics in 2D oil reservoirs. The project predicts pressure fields for single-well and multi-well scenarios using the diffusivity equation, embedding physical laws into the loss function for accurate, mesh-free solutions. Built with PyTorch, the code compares three models: Basic MLP (Tanh activation), Sine MLP, and FNO. Results show effective pressure predictions with losses as low as 1.2e-5 for multi-well configurations.

## Features
- **PINN Framework**: Implements Basic MLP and Sine MLP with physics-informed loss functions (PDE, boundary, initial conditions).
- **Fourier Neural Operator (FNO)**: Models pressure dynamics using spectral convolutions for grid-based predictions.
- **Scenarios**: Supports single-well and multi-well configurations with customizable well positions and rates.
- **Visualizations**: The model predicts pressure fields for single-well and multi-well scenarios
![Visualizations](https://github.com/Akmuhammet01/Physics-informed_Reservoir_Model/blob/main/images/Screenshot%20from%202025-10-25%2019-03-55.png)![Visualizations](https://github.com/Akmuhammet01/Physics-informed_Reservoir_Model/blob/main/images/Screenshot%20from%202025-10-25%2019-03-43.png)
- **Comparison**: Evaluates model performance (loss, training time, pressure predictions) across Basic MLP, Sine MLP, and FNO.
![Visualizations](https://github.com/Akmuhammet01/Physics-informed_Reservoir_Model/blob/main/images/Screenshot%20from%202025-10-25%2020-46-22.png)
