# dissect-BS
This project is implying numerical methods to investigate options pricing using the Black-Scholes equation. 
## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)

## General info
The Black Scholes equation: 

![equation](https://latex.codecogs.com/gif.latex?%5Cfrac%7B%5Cpartial%20V%7D%7B%5Cpartial%20t%7D%20&plus;%20%5Cfrac%7B1%7D%7B2%7D%20%5Csigma%5E%7B2%7DS%5E%7B2%7D%5Cfrac%7B%5Cpartial%5E2%20V%7D%7B%5Cpartial%20S%5E2%7D%20&plus;%20rS%5Cfrac%7B%5Cpartial%20V%7D%7B%5Cpartial%20S%7D%20-%20rV%20%3D%200)

![vequation](https://latex.codecogs.com/gif.latex?V%20%3A%20%5Cmbox%7Ba%20function%20of%20time%20%7D%20t)

![sequation](https://latex.codecogs.com/gif.latex?S%20%3A%20%5Cmbox%7Bthe%20spot%20price%20of%20the%20underlying%20security%20%7D)

![requation](https://latex.codecogs.com/gif.latex?r%20%3A%20%5Cmbox%7Bthe%20risk-free%20interest%20rate%20%7D)

![sigequation](https://latex.codecogs.com/gif.latex?%5Csigma%20%3A%20%5Cmbox%7Bthe%20volatility%20of%20the%20security%20price%20%7D)

In this project, we will assume fixed volatility, but a randomly changing interest rate.

Assume that the interest rate evolves by a Wiener process:

![dequation](https://latex.codecogs.com/gif.latex?dX_t%20%3D%20%5Cgamma%20dW_t)

## Technologies
The project is created with Mathematica
