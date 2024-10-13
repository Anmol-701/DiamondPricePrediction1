# Diamond Price Prediction

This repository contains the **Diamond Price Prediction** project, which uses machine learning to predict diamond prices based on their characteristics. The project is made interactive using **Flask**, providing a web interface where users can input diamond attributes and get predicted prices.

## Overview

The aim of this project is to predict the price of diamonds using features such as carat, cut, clarity, color, etc. A machine learning model is trained to make predictions, and Flask is used to build an interactive web app where users can input data and get results in real time.

## Technologies Used

- **Python**
- **Flask**
- **Pandas**
- **Scikit-learn**
- **Jupyter Notebook**
- **HTML/CSS**

## Dataset

The dataset contains the following features:
- **Carat**: Weight of the diamond
- **Cut**: Quality of the diamond's cut
- **Color**: Diamond color grading
- **Clarity**: Measure of diamond's clarity
- **Depth**: Total depth percentage
- **Table**: Width of the diamond's top relative to its widest point
- **Price**: Price of the diamond (target variable)

The dataset is available on [Kaggle](https://www.kaggle.com/datasets/shivam2503/diamonds).

## Model

A **Linear Regression** model has been used to predict the diamond price. Additional models like **Random Forest** and **Decision Trees** were also tested.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Anmol-701/DiamondPricePrediction1.git

2. Navigate to the project directory:

   ```bash
   cd DiamondPricePrediction1
   
3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   
4. Run the Flask application:

   ```bash
   python app.py
5. Access the web interface at http://127.0.0.1:5000/ in your browser.

## Usage
1. Enter the features of the diamond (e.g., carat, cut, clarity, etc.) on the web interface.
2. Click on the "Predict" button.
3. The predicted diamond price will be displayed on the screen.
## Future Enhancements
1. Improve the prediction accuracy by experimenting with more advanced machine learning algorithms.
2. Add more features to the model, such as diamond certification and shape.
3. Enhance the user interface for better user experience.
4. Deploy the application on a cloud platform like Heroku or AWS.
