Download Link: https://assignmentchef.com/product/solved-ece302-project-5-estimation-of-a-random-process-with-an-fir-filter
<br>
Estimation of a random process with an FIR filter.

Part 1: Pencil and paper. Consider the following system:

d[n]          s[n]                                           r[n]                            s_hat[n]                                      c[n]                           h[n]

We wish to design a filter h[n] to estimate s[n] from r[n] such that s_hat[n] is an MMSE estimate.

Assume that s[n] is an i.i.d processes which takes value +/-1 with equal probability for each sample. d[n] is a white, Gaussian noise process with variance 2 . c[n] is an FIR filter with impulse response of [1 .2 .4].

Find an expression for Rsr[n] and Rrr[n]. Rsr[n] is the cross-correlation of the observations R[n] an Rrr[n] is the auto-correlation of the observations.

Set up and solve the normal equations (9.55 or 11.11 from the MIT notes) for N = 4. (Note that N is the length of the FIR filter h[n], not c[n]

Part 2: MATLAB

MMSE estimation: Simulate the system for filters of length N = 4, 6 and 10. Report the MSE of your results in a table.