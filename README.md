# A study of MANET routing protocol performance in a custom, pseudo-deterministic mobility model

In this repository you will find the full dataset of the 4320 simulations that were run as part of the Third Year Project research at The University of Manchester. The dataset is available as both in both text and Matlab format.

The software used to obtain these results is ns-3 (Network Simulator 3), available at: https://www.nsnam.org/ .
An example of how some of these results were analysed, including the explanation for what the parameters mean is available at: (link to published work to be added later).

The format of the file is as follows: each individual line represents a simulation, with both input parameters and performance metrics, in the following order:

**protocol, number of nodes, node speed, interwaypoint distance, hold distance, offset bound, throughput, normalised routing overhead, packet delivery ratio, average end to end delay, interarrival jitter, average hop count**

The value for the protocols is to be interpreted as follows: 1 = OLSR, 2 = AODV, 3 = DSDV, 4 = DSR. The simulations were run with hold distance = interwaypoint distance, so those two fields will always be equal on every line. This was done to allow for easy extension for future results, if more research is desired.
