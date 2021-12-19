## Linear-Regression-VS-Kalman-Filter-on-UAV
In this repository, UAV pitch angle is fitted using linear regression and Kalman Filter. UAV performs loop-the-loop. The pitch angle change was measured with the gyro during 1 seconds.

**For linear regression task:**

Exclude from the consideration rare random deviation (outliers) and estimate the true value of the roll angle. Calculate the confidence interval of error for 95% confidence level. Consider that the gyro errors are normally distributed, except for the rare random deviations. Proper regression technique should be applied so as to fit the data while excluding rare random deviations.

**For Kalman Filter task:**

Estimate proper trajectory for the pitch angle while considering the gyro reading are normally distributed by using Kalman filter.
