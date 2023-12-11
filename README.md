# Component failure analysis and prediction
Component Failure analysis is the process of analyzing the component data or the component itself to determine the reasons for degraded performance or catastrophic failure of a component either, during component manufacturing, performance testing, and during incoming inspection, or after delivery to the customer, at the final application. Collecting and analyzing data is vital to deciding on remedial action and preventing future occurrence. When stakes are high, we perform regular check and predictive analysis on our systems. For example, Lifts, cars are check once every few months and aircrafts are checked on daily basis to avoid any accident.

## Brief Description dataset
"""
This dataset reflects real component failure prediction encountered in the
automobile and other industries with measurements from real equipment. 
The features description: -
Type: the quality of the product, consisting of a letter L, M, or H.
Meaning low, medium, and high, respectively.

Air temperature [K]: generated using a random walk process .

Process temperature [K]: generated using a random walk process .

Rotational speed [rpm]: calculated from power of 2860 W, overlaid with a
normally distributed noise.

Torque [Nm]: torque values are normally distributed around 40 Nm

Tool wear: The quality variants H/M/L of tool wear
in the process.

The targets are:
Target: failure or no failure (to perform binary classification).
Failure Type: type of failure (to perform multiclass classification).
