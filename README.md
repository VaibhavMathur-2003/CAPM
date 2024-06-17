# CAPM Analysis

This project implements the Capital Asset Pricing Model (CAPM) using Python and various libraries such as pandas, statsmodels, and matplotlib. The CAPM is a widely used model in finance that describes the relationship between the expected return of an asset and its systematic risk.

## What is CAPM?

The Capital Asset Pricing Model (CAPM) is a theoretical model that describes the relationship between the expected return of an asset and its systematic risk, often represented by the asset's beta. According to the CAPM, the expected return of an asset is equal to the risk-free rate plus a risk premium, which is proportional to the asset's beta.

The CAPM formula is expressed as:

Expected Return = Risk-free Rate + Beta * (Market Return - Risk-free Rate)

Here's what each component represents:

- **Risk-free Rate**: The return on a risk-free investment, typically based on government bonds or Treasury bills.
- **Beta**: A measure of the asset's systematic risk, which represents the asset's sensitivity to market movements. A beta of 1 means the asset moves in lockstep with the market, a beta greater than 1 means the asset is more volatile than the market, and a beta less than 1 means the asset is less volatile than the market.
- **Market Return**: The expected return of the overall market portfolio, often represented by a broad market index like the S&P 500.

The CAPM provides a framework for understanding the risk-return relationship and is widely used in portfolio management, asset pricing, and cost of capital calculations.

## Usage

1. Install the required Python libraries: `pandas`, `numpy`, `statsmodels`, `matplotlib`, `sklearn`, and `yfinance`.

2. Run the script and provide the following inputs when prompted:
   - Stock ticker (e.g., "AAPL" for Apple Inc.)
   - Market proxy ticker (e.g., "^GSPC" for S&P 500 Index)
   - Risk-free rate (in decimal form, e.g., 0.03 for 3%)
   - Start date (in YYYY-MM-DD format)
   - End date (in YYYY-MM-DD format)

3. The script will download the historical data for the specified stock and market proxy, calculate the daily returns, and perform the CAPM analysis.

4. The script will generate two plots:
   - A plot showing the percentage changes of the stock and market proxy over time.
   - A plot showing the actual stock returns and the predicted returns based on the CAPM model.

5. The calculated beta value will be printed to the console.

## Files

- `CAPM-implementation.py`: The main Python script that implements the CAPM analysis.
- `README.md`: This file, providing an overview of the project and usage instructions.

## Dependencies

- pandas
- numpy
- statsmodels
- matplotlib
- sklearn
- yfinance

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.