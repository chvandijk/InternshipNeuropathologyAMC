# InternshipNeuropathologyAMC
This repository contains scripts that I developed during my internship at the department of neuropathology (AMC).

## WGCNA_SmartSeq_V3
Contains the script to analyse the count matrix of the 'Allen Brain SMART-Seq Multiple Cortical Areas' database.
The cells from the Motor Cortex are isolated and cluster using a Seurat pipeline. 
Next, per cluster a co-expression network analysis is performed using a WGCNA pipeline to identify co-expression modules.
To identify the function of each of the identified modules we used the cluster profiler package.
