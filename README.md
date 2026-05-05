# Boost-step-up-Converter
In this study, I present the design and test results of a boost converter circuit.A boost converter is a type of DC-DC power electronics topology that increases (steps up) an input voltage to a higher output voltage.

The main parameters used in the implemented circuit design are as follows:  
Input voltage (Vin): 12 V 
Output voltage (Vout): 28 V 
Output current (Iout): 4 A 
Switching frequency (Fsw): 150 kHz

The circuit schematic, design calculations, and measurement results are presented in the figures shared Above. By following these design notes, a boost converter with similar characteristics can be developed. The circuit has been built and tested on real hardware.
During the tests, it was observed that at low load current levels (for example, when the input current is approximately 0.30 A), the Vsw (switching node) voltage indicates that the converter operates in Discontinuous Conduction Mode (DCM). This is an expected result, as the inductor current ripple is greater than the load current under these conditions.
As the load current increases, the converter transitions into Continuous Conduction Mode (CCM), as intended in the design, and exhibits stable operation. This behavior confirms the accuracy of the design calculations and the proper selection of circuit components.

In conclusion, the experimental results demonstrate that the designed boost converter operates in agreement with theoretical calculations, maintains stable performance at a switching frequency of 150 kHz, and delivers the expected behavior in both DCM and CCM operating modes.
