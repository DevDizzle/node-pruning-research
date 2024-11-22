# Node Pruning Optimization for CNNs

This project investigates the use of node pruning within a stratified k-fold cross-validation framework to improve the recall of CNNs in medical imaging tasks.

## Key Features
- Implements node pruning to optimize model complexity and recall.
- Uses ResNet50V2 as the base model for binary classification of skin lesions.
- Evaluates performance metrics across multiple pruning strategies.

## Repository Structure
- `notebook/`: Contains the Colab notebook for experiments.
- `data/`: Includes relevant datasets used for training and evaluation.
- `figures/`: Visualization assets like bar plots and scatter plots.
- `README.md`: Project overview and usage instructions.

## Results
Pruning significantly improved recall across multiple strategies while maintaining stable AUC.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Node-Pruning-Optimization.git
