# adaptive-mcs-ofdm-measurements

* Repository contains measured data for MCS2, MCS3 and MCS4 of OFDM option 4 that maps received RSSI values to packet reception rate (PRR).

* The different .csv files represent the measured data for 127 byte packets, containing the PRR (second column) for the average measured RSSI (third column) for each PHY config (first column). The file name contains the attuanation value.

* attplot.py is Python script to quickly showcase the data in a graph. You can run this by typing "python attplot.py".

* Modulation.py is a Python module that is part of the 6tisch simulator implementation for the adaptive modulations that can be found here https://github.com/imec-idlab/adaptive-mcs-ga-simulator. It is included to showcase the regression models used on the data.
