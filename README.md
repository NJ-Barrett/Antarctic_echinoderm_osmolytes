1.  "Normalized_. . " sheet is the master data matrix containing processed output of the spectral deconvolution, alignment and annotation algorithms. Samples are displayed in   columns, peak areas in rows. Data has been normalised following QC-based LOWESS algorithm and blank subtracted, then reformatted into tidydata compliant "Data" and "Peak" tables.

2.  "Data" sheet contain peak area information for each compound. Orange rows are for Odontaster valildus samples, yellow for Sterechinus neumayeri samples.

3.  "Peak" sheet contain annotation information, assigned by searching GC-MS mass spectral libraries. Each compound was assigned a "retention index", calculated from retention time and instrument method. This, along with spectral match scores, are used to assign a name to compounds. The "fill %" refers to the percentage of total samples the compound was found in e.g. a fill of 1 means the compound was found in every sample.

4.   MET numbers are used to identify features, rather than annotation names, to allow unknowns (which may be significant) to be included in the stats. This also allows unbiased analysis.

5.  "OV_filtered" sheet is the filtered 121 metabolite peak value data 

6.  "SN_filtered" sheet is the filtered 121 metabolite peak value data 
