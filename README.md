# US Airlines Flight Delays and Cancellations Analysis

This repository contains code and analysis for the US Airlines Flight Delays and Cancellations project. The project focuses on exploring flight delay and cancellation data for American airline Inc. in 2015, conducting exploratory data analysis (EDA), and building a logistic regression model to predict flight cancellations.

## Dataset

The dataset used in this project includes three main components: airlines, flights, and airports. These datasets provide information on flight details such as airline codes, flight numbers, origin and destination airports, scheduled departure and arrival times, actual departure and arrival times, delays, cancellations, and reasons for cancellations.

## Exploratory Data Analysis (EDA)

The exploratory data analysis involved examining the characteristics of the flight data, identifying patterns, and gaining insights into factors contributing to flight delays and cancellations. Key aspects explored in the EDA include:

- Distribution of flight delays and cancellations across different airlines, airports, and routes.
- Temporal patterns in flight delays and cancellations, such as variations by day of the week or time of day.
- Analysis of geographical patterns in flight delays, focusing on states and cities with the highest delay rates.
- Identification of the main reasons for flight delays and cancellations, including weather, air system issues, airline delays, and late aircraft arrivals.

## Logistic Regression for Flight Cancellation Prediction

A logistic regression model was built to predict flight cancellations for American airline Inc. The model utilized features such as scheduled departure and arrival times, actual departure and arrival times, delays, and other relevant factors. The model performance was evaluated using precision, recall, F1-score, and accuracy metrics. Key findings from the logistic regression model include:

- High precision and recall for predicting not cancelled flights, indicating accurate identification of non-cancelled flights.
- Low recall and F1-score for predicting cancelled flights, suggesting challenges in accurately identifying flight cancellations.
- Discussion on potential factors contributing to model performance, such as class imbalance and data quality issues.

## Repository Structure

- `data/`: Contains the datasets used in the analysis.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and logistic regression modeling.
- `README.md`: This README file providing an overview of the project, dataset, EDA, and logistic regression analysis.

## Usage

To replicate the analysis or explore the code:

1. Clone this repository to your local machine.
2. Navigate to the `notebooks/` directory.
3. Open the Jupyter notebooks using a Python environment with necessary dependencies installed.
4. Run the notebooks to execute the analysis and view the results.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) 


