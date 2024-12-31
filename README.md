# Hyperparameter Tuning in ANN using KerasTuner

This repository demonstrates the process of hyperparameter tuning for Artificial Neural Networks (ANN) using KerasTuner. By leveraging KerasTuner, we optimize key hyperparameters to achieve the best performance for a given dataset.

## Features

- Implementation of an ANN model with TensorFlow/Keras.
- Automated hyperparameter tuning using KerasTuner.
- Comparison of different hyperparameter configurations.
- Performance evaluation of the best-tuned model.

## Requirements

To run this project, install the following dependencies:

```bash
pip install tensorflow keras keras-tuner numpy pandas matplotlib
```

## Dataset

This project uses [Loan Approval Classification Dataset]. The dataset is preprocessed and split into training and testing sets before applying the ANN model.

## How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/prashant-shinde98/HyperparameterTuning-in-ANN-using-KerasTuner.git
   cd HyperparameterTuning-in-ANN-using-KerasTuner
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook or Python script to perform hyperparameter tuning:

   ```bash
   jupyter notebook Hyperparameter_Tuning.ipynb
   ```

4. View the results and use the best hyperparameters to train your final model.

## KerasTuner Workflow

1. **Define the Model:** Create a function to define your ANN model architecture, specifying hyperparameters to tune.
2. **Choose a Tuning Strategy:** Use one of the available KerasTuner strategies (e.g., RandomSearch, Hyperband, or BayesianOptimization).
3. **Run the Tuner:** Perform tuning to identify the best hyperparameter configuration.
4. **Evaluate the Model:** Test the optimized model on validation/test data to measure its performance.

## File Structure

- `Hyperparameter_Tuning.ipynb`: Main notebook for hyperparameter tuning and analysis.
- `README.md`: Project documentation.
- `requirements.txt`: List of Python dependencies.

## Key Results

- Best Hyperparameters:
  - 'num_layers': 2,
 'units0': 120,
 'activation': 'leaky_relu',
 'dropout0': 0.4,
 'optimizer': 'adam',
 'units1': 128,
 'dropout1': 0.9,
 'units2': 120,
 'dropout2': 0.1,
 'units3': 88,
 'dropout3': 0.7,
 'units4': 72,
 'dropout4': 0.3,
 'units5': 40,
 'dropout5': 0.8,
 'units6': 72,
 'dropout6': 0.5,
 'units7': 40,
 'dropout7': 0.9,
 'units8': 24,
 'dropout8': 0.6,
 'units9': 112,
 'dropout9': 0.3
- Model Accuracy: 0.9136

## References

- [KerasTuner Documentation](https://keras.io/keras_tuner/)
- [TensorFlow Documentation](https://www.tensorflow.org/)

## Contributing

Feel free to contribute to this repository by opening issues or submitting pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
