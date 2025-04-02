# IC_MF_Topics-in-Derivative-Pricing_CW
This repository stores the Coursework for Topics in Derivative Pricing module for Imperial Math Finance Program.

`Bloomberg - Historical Data v2024-11-26 (1).xlsx` is the original dataset

`MicroRV_CW.xlsx` is the modified dataset (first just pick the sheet (`Sonia`) we need, then delete duplicate time column)

`curvefit` is fit curve using cubic spline interpolation. The fitted curve and df is stored in two `.pkl` file respectively.

Future work is to implement the following functions:

`first_K_months_curve` this is trivial.

`choose_N_best_trades` I think this function need huge things to do. We probably need to implement `butterfly` positions which is covered in lectures but I haven't covered yet, also Piterbarg said review `z-scores` so we need to implement at least two `choose_N_best_trades` functions.

Then write a function to calculate the present value of swap and use it to backtest pnl.

Try different `K` and `N` to compare pnl.
