

# R10.x pore chemistry

R10.4.1 is the most recent pore in the R10.x series. R10.4.1 is used with the sequencing kit 14 (_sqk-lsk114_), so this also known by terms such as kit 14. 

There have been previous versions in the R10.x series, for instance R10.4, R10.3 and R10. 
You can think of them like R10.4.0, R10.3.0 and R0.0.0 to avoid confusion. 


## basecalling models

In Guppy basecaller, _dna\_r10.4.1\_e8.2\_400bps\_\*_ and _dna\_r10.4.1\_e8.2\_200bps\_\*_ basecalling models are to be used with R10.4.1. 
For the default translocation speed of 400bps, the model to use is _dna\_r10.4.1\_e8.2\_400bps\_\*_. 
If the slower 200bps speed was selected during sequencing, _dna\_r10.4.1\_e8.2\_200bps\_\*_ model must be  used. e8.2 refers to the version of the motor protein.

There are models in Guppy for previous pores as well. 
Model _dna\_r10.4\_e8.1\_\*_ is for the older R10.4 pore with sequencing kit 12 (_sqk-lsk112_), _dna\_r10.3\_450bps\_\*_ is for R10.3 pores with sequencing kit 10. 
_dna\_r10\_450bps\_*_ is probably for the earliest R10.

Basecalling models have the prefixes *fast*, *hac* and *sup* which refers to fast basecalling, high accuracy basecalling and super accuracy basecalling. *fast*, *hac* and *sup* are in increasing order in terms of accuracy, as well as the computational burden.
Basecalling models also may have prefixes like *prom*. For instance consider the two models _dna\_r10.4.1\_e8.2\_400bps\_hac.cfg_ and _dna\_r10.4.1\_e8.2\_400bps\_hac_prom.cfg_. The only difference between those two models is the utilisation of GPUs.  Both will have same accuracy, so you can use either. 


# R9.x pores chemistry

R9.4.1 is the last in the R9.x pores series and was the work horse for many nanopore projects (which is now deprecated). For R9.4.1 there have been a few sequencing kits, namely, kit 9 (_sqk-lsk109_), kit 10 (_sqk-lsk110_) and kit 12 (_sqk-lsk112_).  

Note that there have been previous pores in the R9.x series, but I will not go into details here as they were not that popular. 

## basecalling models

In Guppy basecaller there are two types of models for R9.4.1: 
- _dna\_r9.4.1\_450bps\_\*_:  to be used for R9.4.1 pores sequenced with kit 9 or 10. 450bps refers to the translocation speed of the DNA through the pore.
- _dna\_r9.4.1\_e8.1\_\*_: to be used with R9.4.1 pores sequeced with kit 12. e8.1 refers to the new motor protein. The translocation speed is still 450bps though not mentioned.

Basecalling models have the prefixes *fast*, *hac* and *sup* and also optional prefixes like *prom*. See the explanations for R10.x. 



---

upto date as of 01/02/2023
