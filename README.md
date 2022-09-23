# WADE-NOESY

NMR pulse sequences and RF shapes for the experiments reported in JBNMR (2022)

Cite Reference articles @  JBNMR (2022)

The script and algorithms are patented @ https://patentcenter.uspto.gov/#!/applications/16861506

"wadenoesygpph_ndec.mpp" is the WADE-NOESY pulse sequence in Bruker format. The shape files are listed below. 
|Short Name | Full Shape Name| Operation Type  |  Pulse Length factor | Pulse Length |   Amplitude  |    reference  JBNMR (2022)|
| ----------| ------------   | -------------   | -------------        | ------------ | ----------- | ---------  
|W1F90|wadepi2x_rf0.00_25.700p1_bw1.85B1.mrf|WADE-π/2|25.7|25.7*40us=1028 us|6.25kHz|  Figure 5|
|WR4|wadepix_NP_2_rf0.00_34.595p1_bw0.82B1.mrf|WADE-π/2|34.595|34.595*40us= 1383.8 us|6.25kHz| Figure 5| 
 
 
 

Bandwidth can be tuned by changing the RF power, the correponding pulse length is calculated by multiplying the 90 degree pulse length with the pulse length factor for each pulse. 

consider the 'wadepi2x_rf0.00_25.700p1_bw1.85p1.mrf' shape,

for RF amplitude 25kHz (=> 90 pulse length = 10us), pulse length = 25.7*10us = 257 us 

for RF amplitude 12.5kHz (=> 90 pulse length = 20us), pulse length = 25.7*20us = 514 us 
 

------------------------------------------------------------------------------
 

Copyright & License Statement

RF pulse shapes are copyrighted by Regents of the University of Minnesota and the software for generating RF shapes covered by US patent 11,221,384. Regents of the University of Minnesota will license the use of RF shapes solely for educational and research purposes by non-profit institutions and US government agencies only. For other proposed uses, contact umotc@umn.edu. The software may not be sold or redistributed without prior approval. One may make copies of the software for their use provided that the copies, are not sold or distributed, are used under the same terms and conditions. As unestablished research software, this code is provided on an "as is'' basis without warranty of any kind, either expressed or implied. The downloading, or executing any part of this software constitutes an implicit agreement to these terms. These terms and conditions are subject to change at any time without prior notice.
