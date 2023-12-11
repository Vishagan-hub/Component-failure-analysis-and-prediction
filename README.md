# Component failure analysis and prediction
Component Failure analysis is the process of analyzing the component data or the component itself to determine the reasons for degraded performance or catastrophic failure of a component either, during component manufacturing, performance testing, and during incoming inspection, or after delivery to the customer, at the final application. Collecting and analyzing data is vital to deciding on remedial action and preventing future occurrence. When stakes are high, we perform regular check and predictive analysis on our systems. For example, Lifts, cars are check once every few months and aircrafts are checked on daily basis to avoid any accident.

## Brief Description dataset

This dataset reflects real component failure prediction encountered in the
automobile and other industries with measurements from real equipment. 

**The features description:**

-_Type_: the quality of the product, consisting of a letter L, M, or H.
Meaning low, medium, and high, respectively.

-_Air temperature [K]_: generated using a random walk process .

-_Process temperature [K]_: generated using a random walk process .

-_Rotational speed [rpm]_: calculated from power of 2860 W, overlaid with a
normally distributed noise.

-_Torque [Nm]_: torque values are normally distributed around 40 Nm

-_Tool wear_: The quality variants H/M/L of tool wear
in the process.

**The targets are:**

-_Target_: failure or no failure (to perform binary classification).

-_Failure Type_: type of failure (to perform multiclass classification).
