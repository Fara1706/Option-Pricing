# Monte Carlo Option-Pricing
This program calculates the price of European call and put options using the Monte Carlo simulation method. It models stock price behavior via Geometric Brownian Motion and estimates option prices by simulating multiple stock price paths at maturity.
## Features
- Simulates stock prices using Gaussian noise.
- Calculates option payoffs (call and put).
- Discounts expected payoffs to obtain option prices.
# European Option Pricing using Black-Scholes Model
This repository contains an implementation of the Black-Scholes Option Pricing Model, which calculates the price of European call and put options. The code also calculates the Greeks (Delta, Gamma, Theta, Vega, Rho), intrinsic value, and implied volatility for the options. These parameters are vital in understanding the sensitivity of option prices to market factors.
## Black-Scholes Model
The Black-Scholes Model is a mathematical framework for pricing European-style options. It assumes:
- The stock price follows a Geometric Brownian Motion with constant volatility and drift.
- Markets are frictionless (no transaction costs or taxes).
- No dividends are paid during the option's life.
- The risk-free interest rate is constant.
This implementation calculates:
1. Premium: The option's fair value.
2. Days Till Expiry (DTE): The time left until the option expires (in days).
3. Greeks:
   - Delta: Sensitivity of the option price to changes in the underlying asset's price.
   - Gamma: Sensitivity of Delta to changes in the underlying asset's price.
   - Theta: Sensitivity of the option price to the passage of time (time decay).
   - Vega: Sensitivity of the option price to changes in volatility.
   - Rho: Sensitivity of the option price to changes in the risk-free interest rate.
4. Implied Volatility: The volatility implied by the market price of the option.
5. Intrinsic Value: The option's value if exercised immediately.
