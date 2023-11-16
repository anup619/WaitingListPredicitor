# Waiting List Predictor Project

## Overview

This project aims to analyze and predict the waiting list trend for train tickets during the Diwali week. The motivation for this project came from a personal experience of booking tickets from Pune to Nagpur during Diwali and observing regular updates about the waiting list status.

## Project Structure

- **irctc.csv**: CSV file containing historical data with columns 'Date' and 'Waiting-List-No'.
- **irctc.ipynb**: Jupyter Notebook containing the Python code for data analysis and prediction.

## Code Explanation

### 1. Data Preparation
- Reads the historical data from 'irctc.csv'.
- Converts the 'Date' column to datetime format.
- Creates a line plot to visualize the waiting list trend over time.

### 2. Polynomial Regression
- Applies Polynomial Regression to predict the waiting list trend.
- The degree of the polynomial is set to 3.

### 3. Visualization
- Plots the historical waiting list data along with the predicted trend.

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/anup619/WaitingListPredictor.git

   ```

Open and run the **irctc.ipynb** Jupyter Notebook to reproduce the analysis and predictions.

## Dependencies
- Make sure to install the following dependencies before running the notebook:

```bash
pip install pandas matplotlib scikit-learn
```

## Contributing
- Contributions are welcome! If you have ideas for improvement, open an issue or create a pull request.
