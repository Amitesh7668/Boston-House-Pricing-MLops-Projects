# Boston House Price Prediction

This project is a web application for predicting house prices in Boston using a linear regression model. The app is built with Flask and utilizes a pre-trained machine learning model.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Model Information](#model-information)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Amitesh7668/Boston-House-Pricing-MLops-Projects
   ```
2. Navigate to the project directory:
   ```bash
   cd boston-house-pricing-MLops-Projects
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Flask application:
   ```bash
   python app.py
   ```
2. Open your web browser and go to https://boston-house-pricing-mlops-projects.onrender.com

3. Enter the required input values for house features and click on the "Predict" button to get the house price prediction.

## Project Structure

- `app.py`: The main Flask application file.
- `templates/home.html`: The HTML file for the web interface.
- `regModel.pkl`: The pre-trained linear regression model.
- `scaling.pkl`: The scaler used to preprocess input data.
- `requirements.txt`: A file containing the list of dependencies.

## Model Information

The linear regression model used in this project is trained on the Boston Housing dataset. It predicts the house price based on the following features:
- CRIM: Per capita crime rate by town
- ZN: Proportion of residential land zoned for lots over 25,000 sq. ft.
- INDUS: Proportion of non-retail business acres per town
- CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- NOX: Nitric oxides concentration (parts per 10 million)
- RM: Average number of rooms per dwelling
- Age: Proportion of owner-occupied units built prior to 1940
- DIS: Weighted distances to five Boston employment centers
- RAD: Index of accessibility to radial highways
- TAX: Full-value property tax rate per $10,000
- PTRATIO: Pupil-teacher ratio by town
- B: 1000(Bk - 0.63)^2 where Bk is the proportion of black people by town
- LSTAT: Percentage of lower status of the population

## Dependencies

The project requires the following Python libraries:
- Flask
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn
- gunicorn

You can install these dependencies using the command:
```bash
pip install -r requirements.txt
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
