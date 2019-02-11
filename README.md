Two codes to infer a weighted and directed network between a set of functional domains. 
Domains are computed using delta-MAPS and defined as semi-autonomous, spatially contiguous 
and possibly overlapping regions of the spatio-temporal field under investigation. 
Both network inferences codes take into account the strong autocorrelations of climate time series 
when testing for significance, however one of the two codes uses a simple t-test while the other 
code uses the False Discovery Rate. Using FDR allows to control (on average) the number of false positive.

Both codes are written in Mathematica.

You will also find a folder "domains". Here there is the set of domains identified by delta-MAPS for the HadISST dataset, using \alpha = 0.01 and K = 22. To run the code you should have in the same folder the following: (i) the code, (ii) a folder called "HadISST_sst _ 1980_ 2015" with inside the folder "domains", (iii) a file .mat with linearly detrended monthly anomalies in it (as computed from HadISST for the period 1980-2015) .
