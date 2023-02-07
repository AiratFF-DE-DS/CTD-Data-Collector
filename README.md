### Main Objective

* Collect the data for the historical runs, compute, and evaluate the Shocks and Vibration environment.
* Merge the output data with the failure reports in order to determine the root causes of the failures and to define the possible correlations.

### Description

The Coiled Tubing Data collector is a program that scans the pre-defined folders and searches the files with the "LAS" extension.
Also, the program can determine if the data is timebase or depth-based.
Once the files have been found, the code computes the vibration energy, nitrogen pumping volumes and temperature.

### Additional Info

The scrip also creates the log file with the scanned file names to avoid them scanning again, which saves some time.
