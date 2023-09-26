# Dedupe calculator for Storage & Network requirements
Calculations are theoretical and used to illustrate the dynamics of the impact deduplication.  They are not likely to match vendor calculations because there are many factors that influence deduplication capacity planning. Network throughput estimates and storage requirements are never exact because:

 • Some deduplication engines compress data in the individual dedupe chunks before its added to the dedupe repository. 
 
 • Deduplication overhead is ignored as it can be variable depending upon data type and deduplication implementation.  
 
 • Data that is encrypted, compressed or constantly unique could render deduplication rate less effective.  
 
 • Data that is made up very small chunks will reduce the effectiveness of deduplication. 
 
 • Transport layer technologies like WAN optimisation are ignored in calculations.

 Some deduplication engines ignore compressed data and/or data chunks that are too small. 
 
Author : Jim J. McDonald, Sydney

