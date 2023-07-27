# recordTimeMileRun
python code to estimate the best time a human can run a mile, units = minutes

time is in minutes: 3 min 49 seconds is coded as 3 + 49/60 = 3.82 minutes

Model;  dP/dt = r * P * (1 - P/K)  where P is the run time for a mile, r is the (constant) rate of decrease, K is the fastest time.  Code finds r and K, given data in the .csv file
