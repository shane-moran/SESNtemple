This directory contains moving weighted average velocities of Fe II 5169 for SLSNe, SNe Ic-bl and SNe Ic, as computed in [Liu, Modjaz & Bianco (2017)](http://adsabs.harvard.edu/abs/2016arXiv161207321L) and shown in our Figure 1. The moving weighted average velocities are smoothed with a Gaussian kernel with a standard deviation of 5 days. The weights are taken to be the inverse of the square of the errors of individual measurements. The error bands on the mean values shown in the paper represent the weighted standard deviation of the data points (SIGMAD_ARR below).

#### Key Words/Outputs :
- PHASE_ARR: phase array in days [phase = time with respect to maximum light - for Ic and Ic-bl with respect to max light in V-band, for SLSNe in various bands, see paper]
- XMEAN_ARR: weighted average velocity array in km/s
- SIGMAM_ARR: weighted standard deviation on average velocity valuein km/s
- SIGMAD_ARR: weighted standard deviation of the data points in km/s
- NUM_SN: No. of SNe contributing to weighted average velocity at the corresponding phase
- STEP: moving step size in days

