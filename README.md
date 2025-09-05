# Investobuddy

InvestoBuddy is an investment analysis tool that blends value investing principles with machine learning to help investors make informed decisions. It calculates the intrinsic value of stocks using Discounted Cash Flow (DCF) + Monte Carlo simulations and predicts 6-month market trends using LSTM neural networks.


## Features
 - Fetches 5 years of historical financial & stock data via Alpha Vantage / Yahoo Finance APIs
 - Performs intrinsic valuation using DCF and Monte Carlo simulation
 - Builds LSTM neural network models to forecast 6-month price trends
 - Benchmarks against Random Forest for comparison
 - Provides buy/sell signals when intrinsic value diverges from market price
 - Interactive Flask + Angular webapp for end-users

## Tech Stack

 - Languages: Python, Angular (frontend)
 - Frameworks & Libraries: Flask, scikit-learn, NumPy, pandas, PyTorch
 - APIs: Alpha Vantage, Yahoo Finance
 - Models: Monte Carlo Simulation, LSTM, Random Forest
 - Visualization: Matplotlib

Note: This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.1.2.

## Contributors
 - [Tanay Mehendale](https://linkedin.com/in/tanay-mehendale/)
 - [Vishal Ramina](https://www.linkedin.com/in/vishal-ramina/)
 - [Shreyas Kailasanathan](https://www.linkedin.com/in/shreyas-k-731a24156/)

## Getting Started
### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
