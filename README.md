# AGNI_SPICE

The purpose of this GitHub file is to showcase our demonstration of performing the SPICE simulation and model the proposed "**AGNI: In-Situ, Iso-Latency Stochastic-to-Binary Number Conversion for In-DRAM Deep Learning**," which was published in [**ISQUED'23**](). This demonstration was done using the LTSPICE simulator. To successfully simulate our proposed AGNI substrate for N=4, kindly follow the steps below in order.

**Step 1** : Git clone the file to your local machine

**Step 2** : Once the Step 1 is executed and unzipped the git folder, the following files collateral will be populated in your local machine. The description and list of files binded in this bundle are elaborated the following table. 
NoteHere in the below files list .cir is the schematic file from which you can dump out the .asc, .Net , .RAW files.


| **Filename**  | **Description** |
| ------------- | ------------- |
| 4-bit combination with ADC for encoded binary.cir  | AGNI schematic SPICE file for N=4  |
| 4-bit combination with ADC for encoded binary.asc  | AGNI SPICE file for N=4 in netlist format |
|4-bit combination with ADC for encoded binary.Net| Netlist format of the AGNI substrate |
|4-bit combination with ADC for encoded binary.log|SPICE simulation log of the AGNI substrate |
|sau4v3.raw|RAW format of AGNI substrate utilized during python ltspy3 simulation and graph representation|

**Step 3** :- Importing of AGNI SPICE simulation

**SPICE File Analysis and Simulation**

* Once the step 2 is complete, you will need a compatible SPICE simulator. Our study utilized the [LTSPICE](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html) (https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html) for analyzing the SPICE file. However, any SPICE simulator of your choice can be used.

**Note:-** Video tutorial on how to use the [LTSPICE Tutorial](https://www.analog.com/en/education/education-library/videos/video-series/ltspice-getting-started-tutorial.html)

* To import the SPICE file into LTSPICE, please watch the following tutorial [AGNI LTSPICE FILE IMPORTING](https://youtu.be/4pZ4Uf7VJMU). Here in this video we illustrated on how to view the 4-bit combination with ADC for encoded binary.asc (i.e., extension), which is used for the circuit schematic simulation. This simulation mimics the BLgroup size as 4.

**Step 4 :-** Tranisient analysis in LTSPICE

* once the Step 3 is completed, please watch [AGNI Transient analysis](https://youtu.be/233tJurw-ZA), which shows the video demonstration on how to configure the SPICE file for the simulation. Along with this in this video we have shown how the circuit are modelled w.r.t the paper.

* The automation of the SPICE generation is done using the python package from [LTSPICE Python package](http://www2.ee.unsw.edu.au/~tlehmann/ltspy3.py). To assist you in using this package,please watch this [AGNI Python automation](https://youtu.be/A-CiMvKVQ_o).

**In conclusion, we hope that this bulletin and the accompanying resources will aid you in your SPICE file analysis and simulation process. If you have any questions or concerns, please feel free to reach out to us at supreethms@uky.edu.**

