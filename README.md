# AGNI_SPICE
** SPICE File Analysis and Simulation**

* We will be discussing the recommended methods for analyzing SPICE files and the resources available to assist you in the process. Our study utilized the LTSPICE simulator (https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html) for analyzing the SPICE file. However, any SPICE simulator of your choice can be used.

* To import the SPICE file into LTSPICE, please watch the following tutorial https://youtu.be/4pZ4Uf7VJMU. The files consist of (.asc) extension, which is used for the circuit schematic simulation of AGNI for N=4. This simulation mimics the BLgroup size as 4, and the demonstration of this is described in the video https://youtu.be/4pZ4Uf7VJMU.
* Below table also show the list of the files and their description

| **Filename**  | **Description** |
| ------------- | ------------- |
| 4-bit combination with ADC for encoded binary.cir  | AGNI schematic SPICE file for N=4  |
| 4-bit combination with ADC for encoded binary.asc  | AGNI SPICE file in netlist format helpful preprocessing in LTSPICE |
|4-bit combination with ADC for encoded binary.Net| Netlist format of the AGNI substrate |
|4-bit combination with ADC for encoded binary.log|SPICE simulation log of the AGNI substrate |
|sau4v3.raw|RAW format of AGNI substrate utilized during python ltspy3 simulation and graphical interface|



* For ease of understanding, we have provided two separate video demonstrations of the SPICE simulation for transient analysis and the usage of the file. The first video https://youtu.be/233tJurw-ZA shows the SPICE simulation for transient analysis, and the second video  https://youtu.be/4pZ4Uf7VJMU  shows the usage of the file.

* The automation of the SPICE generation is done using the python package from http://www2.ee.unsw.edu.au/~tlehmann/ltspy3.py. To assist you in using this package, we have included a video tutorial on its usage in the following video https://youtu.be/A-CiMvKVQ_o.

**In conclusion, we hope that this bulletin and the accompanying resources will aid you in your SPICE file analysis and simulation process. If you have any questions or concerns, please feel free to reach out to us at supreethms@uky.edu.**

