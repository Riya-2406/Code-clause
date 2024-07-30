# House Price Prediction

## Aim
Build a simple linear regression model to predict house prices based on features like the number of bedrooms and square footage.

## Description
This project uses a dataset of house prices to build a regression model that predicts house prices based on features such as the number of bedrooms and square footage. The dataset is split into training and testing sets to evaluate the model's performance. The model is built using Scikit-learn, a machine learning library in Python.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Installation
To run this project, you will need Python installed on your machine. Additionally, you need to install the following Python libraries:

```bash
pip install pandas scikit-learn
```

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/house-price-prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd house-price-prediction
    ```
3. Ensure you have a dataset named `house_price.csv` in the project directory.
4. Run the script to train and evaluate the model:
    ```bash
    python house_price.py
    ```
## Features
- Load and preprocess the dataset.
- Split the dataset into training and testing sets.
- Build and train a linear regression model using Scikit-learn.
- Evaluate the model's performance on the testing set.

## Configuration
Ensure that the dataset file is in the correct path as specified in the script. You can modify the script to change the dataset path or any model parameters.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes.

## Acknowledgements
- [Scikit-learn](https://scikit-learn.org/)
- [Pandas](https://pandas.pydata.org/)
