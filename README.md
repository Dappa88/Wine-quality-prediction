# Wine Quality Prediction with TensorFlow and Python (OOP)

![TensorFlow Logo](https://www.tensorflow.org/images/tf_logo_social.png)

This repository contains an amazing machine learning model for predicting wine quality using TensorFlow and Python. The project is structured using Object-Oriented Programming (OOP) principles, making it highly organized, maintainable, and scalable.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Performance](#performance)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The aim of this project is to build a robust machine learning model that predicts the quality of wines based on various features such as acidity, pH, alcohol content, etc. TensorFlow, a popular deep learning framework, is utilized to construct and train the predictive model. The use of OOP in the project allows for clear separation of concerns, enhancing code readability and reusability.

## Dataset

The dataset used in this project consists of samples of various wines with corresponding quality ratings. It is stored in a CSV format and is located in the `data` directory. The dataset has been preprocessed and cleaned, ensuring that the model's training process is efficient and effective.

## Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/Dappa88/wine-quality-prediction.git
```



## Usage

The project follows a simple structure for easy understanding and usage. The main components are:

- `wine_model.py`: The class containing the TensorFlow model and its training functions.
- `data_preprocessing.py`: The class responsible for loading and preprocessing the dataset.
- `train.py`: The script to initiate model training and evaluation.

To train the model, follow these steps:

1. Ensure you have installed all dependencies (see [Installation](#installation)).
2. Customize the hyperparameters and configuration in `train.py` if needed.
3. Run the training script:

```bash
python wine_prediction
```

The model will be trained on the dataset, and evaluation metrics will be displayed on the console.

## Model Architecture

The machine learning model used in this project is built using TensorFlow's Keras API. It is a deep neural network with multiple hidden layers, designed to capture complex patterns and relationships within the input data. The architecture can be summarized as follows:

1. Input Layer: Accepts the features of the wine samples.
2. Hidden Layers: Consist of several dense layers with activation functions to introduce non-linearity.
3. Output Layer: Produces a single scalar value representing the predicted wine quality.

The model's architecture and hyperparameters can be modified and experimented with in the `wine_model.py` file.

## Performance

The performance of the trained model can be assessed using various evaluation metrics, including accuracy, mean squared error, and others. During training, the model's performance on the validation set is continuously monitored to prevent overfitting and ensure generalization.

## Contributing

Contributions to this project are more than welcome! If you have ideas for improvements or new features, feel free to submit a pull request. Please make sure to follow the established coding guidelines and best practices.

## License

This project is licensed under the [MIT License](LICENSE), allowing you to use and modify the code with proper attribution.

Enjoy predicting wine quality with TensorFlow and OOP! 🍷🍇
