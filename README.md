# IC_MF_Topics-in-Derivative-Pricing_CW
This repository stores the Coursework for Topics in Derivative Pricing module for Imperial Math Finance Program.

## Abstract

This project investigates Micro Relative Value (Micro RV) opportunities by analyzing localized dislocations in dealer-constructed interest rate curves. Using historical swap data across multiple currencies, we construct daily yield curves via natural cubic spline interpolation and identify curvature-based anomalies through butterfly spreads. We evaluate each structure using rolling-window $z$-scores and carry metrics, and select the most statistically significant configurations for backtesting. The profitability of these trades is assessed through DV01-adjusted PnL simulations under dynamically evolving maturities. Our numerical analysis suggests that Micro RV signals have the potential to generate profitable trades, with meaningful dislocations observed across different maturities and currencies under certain conditions.


## Contributor:
Waner Chen (CID: 01854827)\
Zhenyi Chen (CID: 06011402)\
Chengdong Song (CID: 02030540)


## Structure

- **`Code_Earlier_Version/`**  
  This folder includes older versions of our implementation, before the final submission.

- **`micro_rv_final.ipynb`**  
  This notebook contains the complete implementation for coursework

- **`Data_Used`**  
  This folder contains all the data used for the coursework:
  - **`Bloomberg - Historical Data v2024-11-26 (1).xlsx`** is the original Bloomberg historical data spreadsheet provided for the coursework. The following files are all modified version of one of this sheets.
  - **`MicroRV_CW.xlsx`** This sheet provides historical swap rate data for GBP SONIA OIS curves.
  - **`micro_rv_euro.xlsx`** This sheet contains swap rate data for the EUR ESTR curve. 
  - **`micro_rv_usd.xlsx`** This sheet provides historical swap rates based on USD SOFR.

---

Feel free to reach out if you have questions about the implementation.
