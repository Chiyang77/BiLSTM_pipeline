# Jumper Unity Prediction with LSTM

A PyTorch-based LSTM model for predicting unity values in jumper structures.

## Project Overview

This project uses a bidirectional LSTM neural network to predict unity values for stress (longutidinal and combined stress) for pipe and elbow elements in jumper structures based on global parameters.
The current procedure requires the data to be pre-processed for unity values after running the FEM analysis.

## Features

- Data loading and preprocessing pipeline for jumper structure data
- Bidirectional LSTM model with embedding for element types
- Training with early stopping and model checkpointing
- Inference capabilities for new jumper configurations

## Requirements

- Python 3.7+
- PyTorch
- NumPy
- Matplotlib (for visualization)

## Usage

See the Jupyter notebook `LSTM_v2.ipynb` for a complete example of training and using the model.