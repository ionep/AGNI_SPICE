# LTSPICE Simulations for AGNI Substrate

This repository cosists of simulation files and tutorial videos for LTSPICE-based simulations of the AGNI substrate [1], which is an in-DRAM computing sustrate for stochastic to binary number conversion.

[1] Supreeth Mysore Shivanandamurthy, Sairam Sri Vatsavai, Ishan Thakkar, Sayed Ahmad Salehi, “AGNI: In-Situ, Iso-Latency Stochastic-to-Binary Number Conversion for In-DRAM Deep Learning,” IEEE International Symposium on Quality Electronic Design (ISQED'23), April 2023.

To successfully simulate our proposed AGNI substrate for N=4, kindly follow the steps below in order.

**Step 1** : Git clone the files to your local machine.

**Step 2** : If needed, unzip the files. The following files should be populated in your local machine. The description and list of files are given in the following table. 


| **Filename**  | **Description** |
| ------------- | ------------- |
| 4-bit combination with ADC for encoded binary.cir  | AGNI schematic SPICE file for N=4  |
| 4-bit combination with ADC for encoded binary.asc  | AGNI SPICE file for N=4 in netlist format |
|4-bit combination with ADC for encoded binary.Net| Netlist format of the AGNI substrate |
|4-bit combination with ADC for encoded binary.log|SPICE simulation log of the AGNI substrate |
|sau4v3.raw|RAW format of AGNI substrate utilized during python ltspy3 simulation and graph representation|

In the above table, the .cir file is the schematic file from which you can derive the .asc, .Net, and .RAW files.

**Step 3** : Import the files into a SPICE simulator

* For this, a compatible SPICE simulator will be needed. We have utilized [LTSPICE](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html) (https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html) for this work. However, any other SPICE simulator of your choice can also be used.

**Note:-** Video tutorial on how to use the [LTSPICE Tutorial](https://www.analog.com/en/education/education-library/videos/video-series/ltspice-getting-started-tutorial.html)

* To import the SPICE file into LTSPICE, please watch the following tutorial [AGNI LTSPICE FILE IMPORTING](https://youtu.be/4pZ4Uf7VJMU). Here in this video we illustrated on how to view the 4-bit combination with ADC for encoded binary.asc (i.e., extension), which is used for the circuit schematic simulation. This simulation mimics the BLgroup size as 4.

**Step 4 :-** Tranisient analysis in LTSPICE

* once the Step 3 is completed, please watch [AGNI Transient analysis](https://youtu.be/233tJurw-ZA), which shows the video demonstration on how to configure the SPICE file for the simulation. Along with this in this video we have shown how the circuit are modelled w.r.t the paper.

* The automation of the SPICE generation is done using the python package from [LTSPICE Python package](http://www2.ee.unsw.edu.au/~tlehmann/ltspy3.py). To assist you in using this package,please watch this [AGNI Python automation](https://youtu.be/A-CiMvKVQ_o).

**In conclusion, we hope that this bulletin and the accompanying resources will aid you in your SPICE file analysis and simulation process. If you have any questions or concerns, please feel free to reach out to us at supreethms@uky.edu.**

