# Solar-Cycle-Analysis
This project analyses 277 years of monthly sunspot data from 1749 to 2026. It is done using Python to characterize the solar period through three independent methods. 

Data source: SILSO World Data Center, Royal Observatory of Belgium.
Monthly mean sunspot number (csv file)
URL: https://www.sidc.be/SILSO/datafiles

Methods- 
I have performed a time series visualization, 72 month rolling average for trend extraction, automatic peak detection (using scipy.signal.find_peaks) and  FFT analysis using numpy.

Key Findings- 
1. Average solar cycle from peak detection: 10.98 years
2. Dominant period from FFT analysis: 11.10 years
- Both these values are consistent with the accepted Schwabe cycle of ~11 years.
3. SC25 current smoothed maximum (93.6) already exceeds SC24's confirmed peak (80.6).

Tools used- 
Python, numpy, pandas, matplotlib, scipy 
