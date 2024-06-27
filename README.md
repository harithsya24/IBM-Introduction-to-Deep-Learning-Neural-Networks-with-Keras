# Concrete Strength Prediction Models

This repository contains Python scripts and models for predicting concrete strength using different configurations of neural networks. Each configuration represents a different experiment aimed at optimizing model performance.

## Files in the Repository

1. **baseline_model_non_normalized.py**: Implementation of a baseline neural network model trained on non-normalized data.
   
2. **model_with_normalized_data.py**: Neural network model trained on normalized data to evaluate the impact of data preprocessing on performance.
   
3. **model_with_more_epochs.py**: Neural network model with increased training epochs to assess convergence and potential overfitting.
   
4. **model_with_more_layers.py**: Neural network model with additional layers to explore the impact of network architecture on prediction accuracy.

## Setup and Requirements

To run these models, ensure you have Python installed along with the following libraries:

- TensorFlow
- NumPy
- Pandas
- Matplotlib (for visualization, if applicable)

You can install these dependencies using pip:


## Running the Models

Each script can be executed individually. For example, to run the baseline model with non-normalized data:



## Results

Results from each model configuration are stored within the respective scripts or can be analyzed by examining the output metrics and visualizations generated during training.

## Acknowledgments

- **Dataset:** The concrete strength dataset used in this project is sourced from [insert website name or link].

- **Machine Learning Library:** This project utilizes functionalities from [scikit-learn](https://scikit-learn.org/) for data preprocessing and model evaluation.

- **Educational Resources:** Portions of this project are inspired by the teachings and exercises from the [insert course name or platform] offered by IBM.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

