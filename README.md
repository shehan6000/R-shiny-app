# Plant Species Prediction Model

## Overview
This R Shiny application uses a machine learning model to predict plant species based on morphological measurements of flowers. The model takes petal length, petal width, sepal length, and sepal width as input features to perform the prediction.

## Project Structure
- `init.R`: Initializes the application with required libraries and settings.
- `model.rds`: The serialized R model object used for predictions.
- `README.md`: Documentation for the application.
- `run.R`: Script to run the application.
- `server.R`: Contains the server logic of the Shiny application.
- `testing.csv`: CSV file with testing data.
- `training.csv`: CSV file with training data.
- `ui.R`: Defines the user interface of the Shiny application.

## Installation
To run this application, you'll need R and the following R packages: `shiny`, `dplyr`, `ggplot2`, and `caret`.

## Usage
Run the application by executing the `run.R` script in R:
```R
source('run.R')
