# FLiT

Here we provide some basic MATLAB codes to implement FLiT stimulation. This simplified version of the script allows to control and syncronize the galvomirror and laser power attenuator, to implement basic calibrations, define stimulation parameters and pipelines and run  stumaltion events. 

Specifically, the two main scripts are: 
- FLiTcalibration.m : - to define basic setup parameter and hardware used, to implment and defien calbiration of diffraction effcicency, tiled holograms efficiency, and spot spatial calibrations. 
- FLiT_stimulation_MAIN: to define the stimulation patterns (nameley, the coordiantes of the spots and their distribution over the tiled holograms), set stimulation parameters, generate the proper waveform to drive galvos and power control and perform FLiT photostimulation.  The current version of the script implement a protocol of cyclic stimulation, but can be easy adapated to other photostimualtion modalities. 


 Additionally,  we provide a home-made GUI based application to control the Meadowlark SLM model used in the paper. The software is based on the SDK provided by the manufacturer  has an optimized graphic interface and some additional features that ease the SLM adressing for photostimulation pipelines. 

The provided material, although conceived and applicable under a specific hardware configuraton,  could be easily adapted and could provide a good starting point  to  help user to setup their own pipeline based on FLiT photostimulation. 
Do not hesitate to contact us for any questions. 

Dimitrii Tanese (dimitrii.tanese@inserm.fr)
Vincent de Sars  (vincent.de-sars@inserm.fr)



