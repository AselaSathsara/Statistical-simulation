# Supermarket Checkout System Simulation

This project presents a Discrete Event Simulation (DES) of a supermarket checkout system developed as part of the STA3113 Statistical Simulation course at the University of Peradeniya.

## The simulation models a supermarket operating with four checkout counters where:

Customer arrivals follow a Poisson process.
Shopping times follow a Log-Normal distribution.
Customers join the shortest available queue.
Cashier service times follow Exponential distributions with varying service rates.

## Objectives
Estimate average customer waiting times at each checkout counter.
Evaluate cashier utilization levels.
Calculate the average time customers spend in the supermarket.
Determine the total number of customers served per day.
Analyze system bottlenecks and identify potential operational improvements.

## Tools & Technologies
R Programming
Discrete Event Simulation
Queueing Theory
Statistical Modeling
dplyr
ggplot2
R Markdown

## Key Findings

The simulation revealed significant queue congestion and excessive customer waiting times under the given operating conditions, highlighting the need for improvements in cashier capacity and service efficiency.
