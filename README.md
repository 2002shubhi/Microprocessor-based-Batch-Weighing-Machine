# Microprocessor-based-Batch-Weighing-Machine

A microprocessor based based Batch Weighing Machine which checks whether the weight under consideration is greater than or less than 99Kg. It also tells us the weight of the object (in kgs) up to two decimal places.

Our design has a 2 decimal accuracy in display of weight and a weight 
constraint of 500 kg. Also, the process starts only when a switch is pressed till 
when the microprocessor is waiting for the interrupt given by the switch
(polling state).

This repository contains the ALP that is linked with the simulated hardware design made using Proteus and a report containing all the necessary information.

# Problem Statement
A microprocessor system is to be designed as a batch weighing machine. The system is interfaced to three load cells by means of a 10-bit A/D converter.

The conditioned output of the load cells is given by the equation: Vout = K x weight (Kgs.) Where K is dependent on the property of the sensor.

The system monitors the output of the load cells and finds out the total weight by taking the average of the three values that are sensed by each load cell. This value is displayed on a seven -segment di splay. When this value exceeds 99 kgs, an output port, which is connected to a relay, is switched on to sound an alarm.

# Assumptions & Justifications
Justification 
• As we are using this to measure everyday objects the maximum weight 
our load cell can measure is 500kg.
Assumptions
• It is assumed that the weights will be lesser than 500 kg
• It is assumed that after the display is shown/buzzer is stopped the 
machine is reset again by the user (by switching off the whole device).
• It is assumed that there is no time delay in switching the object between 
load cells

# Flowchart
![image](https://user-images.githubusercontent.com/84243901/178093997-db82976c-d7c6-4112-a3fa-cf6f8d04e525.png)

# Data Sheets used for components
1. Load cell
https://docs.rs-online.com/0252/A700000007176385.pdf
2. Relay
https://docs.rs-online.com/8ec1/0900766b80db86c6.pdf
3. Buzzer
https://www.e-radionica.com/productdata/1956696.pdf
4. 8255
https://www.datasheet-pdf.info/attach/1/5514326703.pdf
5. 8254
https://www.scs.stanford.edu/10wi-cs140/pintos/specs/8254.pdf
6. ADC 0808
http://www.da.isy.liu.se/vanheden/pdf/adc0808.pdf
7. 8284
https://www.datasheets360.com/pdf/-5916563377562544203
