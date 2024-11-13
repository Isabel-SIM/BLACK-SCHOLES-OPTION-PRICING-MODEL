# Discounted Cash Flow and Black-Scholes Option Pricing Model

This repository contains a Python implementation of a Discounted Cash Flow (DCF) analysis and Black-Scholes Option Pricing Model for evaluating nuclear power plant investments. The model incorporates realistic assumptions and provides scenario analysis for different nuclear adoption rates.

## Key Components

### Main Functions

1. `calculate_npv_and_option_value()`: Calculates the Net Present Value (NPV) and real option value for a nuclear power plant investment.
2. `run_scenario_analysis()`: Performs scenario analysis based on different nuclear adoption rates.

### Features

- Realistic cash flow projections including ramp-up period and maintenance costs
- Incorporation of decommissioning costs
- Black-Scholes option pricing calculation
- Scenario analysis for various utilization rates
- Error handling and input validation

## Requirements

- Python 3.x
- numpy
- scipy

## Model Parameters

- Initial Investment: AUD 8,500,000,000
- Base Annual Cash Flow: AUD 1,200,000,000
- Discount Rate: 7%
- Volatility: 25%
- Time to Maturity: 25 years
- Growth Rate: 2%
- Decommissioning Cost: AUD 900,000,000

## Scenarios

The model analyses four scenarios based on different nuclear adoption rates:

1. Low Nuclear Adoption (10% average utilisation)
2. Medium Nuclear Adoption (20% average utilisation)
3. High Nuclear Adoption (40% average utilisation)
4. Optimal Nuclear Adoption (90% average utilisation)

## Results

The model outputs include:

- Present Value of Expected Cash Flows
- Option Value of Delaying Investment
- Net Present Value (NPV)

Results are provided for the base case and each scenario.

## How to Use

1. Clone this repository
2. Ensure you have the required Python libraries installed
3. Run the script to see the analysis results
4. Modify parameters in the `calculate_npv_and_option_value()` function to adjust the model assumptions
