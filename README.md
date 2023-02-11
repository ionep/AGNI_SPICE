# AGNI_SPICE

The purpose of this GitHub file is to showcase our demonstration of performing the SPICE simulation and modeling the proposed "**AGNI: In-Situ, Iso-Latency Stochastic-to-Binary Number Conversion for In-DRAM Deep Learning**," which was published in ISQUED'23. This demonstration was done using the LTSPICE simulator. To successfully simulate our proposed AGNI substrate for N=4, kindly follow the steps below in order.

**Step 1** : Git clone the file to your local machine

**Step 2** : Once the Step 1 is executed and unzipped the git folder, the following files collateral will be populated in your local machine. The description and list of files binded in this bundle are elaborated the following table. Also, we included the description and functionality is provided for ease of your understanding.


| **Filename**  | **Description** |
| ------------- | ------------- |
| 4-bit combination with ADC for encoded binary.cir  | AGNI schematic SPICE file for N=4  |
| 4-bit combination with ADC for encoded binary.asc  | AGNI SPICE file in netlist format helpful preprocessing in LTSPICE for N=4|
|4-bit combination with ADC for encoded binary.Net| Netlist format of the AGNI substrate |
|4-bit combination with ADC for encoded binary.log|SPICE simulation log of the AGNI substrate |
|sau4v3.raw|RAW format of AGNI substrate utilized during python ltspy3 simulation and graph representation 

Step 1:- To perform the SPICE simulation, 
** SPICE File Analysis and Simulation**


* We will be discussing the recommended methods for analyzing SPICE files and the resources available to assist you in the process. Our study utilized the LTSPICE simulator (https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html) for analyzing the SPICE file. However, any SPICE simulator of your choice can be used.

* To import the SPICE file into LTSPICE, please watch the following tutorial https://youtu.be/4pZ4Uf7VJMU. The files consist of (.asc) extension, which is used for the circuit schematic simulation of AGNI for N=4. This simulation mimics the BLgroup size as 4, and the demonstration of this is described in the video https://youtu.be/4pZ4Uf7VJMU.
* Below table also show the list of the files and their description





* For ease of understanding, we have provided two separate video demonstrations of the SPICE simulation for transient analysis and the usage of the file. The first video https://youtu.be/233tJurw-ZA shows the SPICE simulation for transient analysis, and the second video  https://youtu.be/4pZ4Uf7VJMU  shows the usage of the file.

* The automation of the SPICE generation is done using the python package from http://www2.ee.unsw.edu.au/~tlehmann/ltspy3.py. To assist you in using this package, we have included a video tutorial on its usage in the following video https://youtu.be/A-CiMvKVQ_o.

**In conclusion, we hope that this bulletin and the accompanying resources will aid you in your SPICE file analysis and simulation process. If you have any questions or concerns, please feel free to reach out to us at supreethms@uky.edu.**

