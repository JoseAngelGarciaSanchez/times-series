# Exam Project README

This is an exam project based on the analysis of the "data_exam.xlsx" spreadsheet. The goal of this project is to improve variance and volatility measures, and study their joint relationships.

## Data Description
The "data_exam.xlsx" spreadsheet contains three columns:
- Column B: VIX level, which measures the volatility of the S&P 500 index.
- Column C: Parkinson estimates, which is a measure of volatility based on high, low, and closing prices.
- Column D: Squared returns, which is a measure of variance based on daily returns squared.

## Questions to Answer
The following questions will be answered in this project:
1. Explain the concept behind each column. What are these time series meant to represent? Transform these time series so that they are comparable in scale and order.
2. Estimate an AR model on each of these time series. Determine the order of the AR process and show the estimates. What can you conclude from these estimations?
3. Plot the fitted values for each model vs. the original time series. Why are these fitted values appealing for volatility measuring purposes?
4. Estimate an HAR model on each time series. Present the estimated coefficients of the model and compare the loglikelihood of each model to the one obtained from the AR estimations. Which model do you prefer? Retain the fitted values of the model you have selected for each of the three time series.
5. Test for the stationarity of the estimated time series. Comment on the results.
6. Estimate a VAR(p) model on your three stationary fitted values. Comment on the results.
7. Plot an impulse response function obtained from your VAR model and comment on the results.

## Usage
1. Clone the repository to your local machine.
2. Open the `Exam_Project.ipynb` file in Jupyter Notebook.
3. Run the code cells in order to perform the analysis and answer the questions.
