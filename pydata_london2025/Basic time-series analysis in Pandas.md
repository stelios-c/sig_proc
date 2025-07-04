<!-- Slide number: 1 -->
# Basic timeseries analysis in Pandas
Stelios Christodoulou
PyData London
June 2025

### Notes:

<!-- Slide number: 2 -->

# Basic timeseries analysis in Pandas
autocorrelation_plot()
.diff()
.autocorr()

lag_plot()
Test for randomness and periodicity
Focus on a particular lag identified from the autocorrelation plot
Difference function: highlighting discontinuities, removing “dc components”
Calculate the numerical value for autocorrelation at the particular lag

### Notes:

<!-- Slide number: 3 -->

# Autocorrelation Plot

![](GoogleShape492p53.jpg)

![](GoogleShape491p53.jpg)
Not random
Trend dominates over periodicity

### Notes:

<!-- Slide number: 4 -->

# Lag 1 and autocorr

![](GoogleShape502p54.jpg)

![](GoogleShape503p54.jpg)
Not random confirmed

### Notes:

<!-- Slide number: 5 -->

# For the computationally minded

![](GoogleShape508p55.jpg)
Why aren’t the numbers identical?
Which one is correct?

### Notes:

<!-- Slide number: 6 -->

# Diff and Lag

![](GoogleShape523p56.jpg)

![](GoogleShape524p56.jpg)

![](GoogleShape522p56.jpg)

![](GoogleShape525p56.jpg)
Diff makes lag 1 random

### Notes:

<!-- Slide number: 7 -->

# Diff and Autocorrelation

![](GoogleShape535p57.jpg)
Periodicity comes to the fore

### Notes:

<!-- Slide number: 8 -->

![](GoogleShape547p58.jpg)
# Lag for periodicity

![](GoogleShape546p58.jpg)
Diff and lag 12  quite correlated
Diff and lag 6 weakly correlated

### Notes:

<!-- Slide number: 9 -->

# Thank you

Bibliography
Pandas documentation
NIST/SEMATECH e-Handbook of Statistical Methods
Random Processes chapter in Communication Systems (Haykin)
https://github.com/stelios-c/sig_proc/
Released under the GPL 3.0 Licence.
Inspired from a Linked In post by Kunpeng (KP) Liao.

### Notes: