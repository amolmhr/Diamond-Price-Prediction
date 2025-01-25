# Diamond Price Prediction

This project aims to predict the price of diamonds using various machine learning algorithms. The dataset used for this project contains features such as carat, cut, color, clarity, and more.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Models](#models)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/amolmhr/diamond-price-prediction.git
    ```
2. Navigate to the project directory:
    ```sh
    cd diamond-price-prediction
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage


1. Train the model:
    ```sh
    python training_pipeline.py
    ```
2. Make predictions:
    ```sh
    python prediction_pipeline.py
    ```

## Dataset

The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/shivam2503/diamonds). It contains the following features:
- Carat
- Cut
- Color
- Clarity
- Depth
- Table
- Price
- X (length)
- Y (width)
- Z (depth)

## Models

The following machine learning models are used in this project:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

## Results

The performance of each model is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²) score. The results are summarized in the `results` directory.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.