
# Car Locator System

This system interfaces TM4C123G LaunchPad board with SIM808 GPS/GSM module to locate the car and upload its 
location to thingspeak server every specific time period. 


### TM4C123G LaunchPad
The TM4C123G LaunchPad Evaluation Kit is a low-cost evaluation platform for Arm Cortex-M4F based microcontrollers.

<img src="Images/tm4c_board.jpg">

### SIM808 GPS/GSM module
SIM808 module is a GSM,GPRS and GPS three-in-one function module. It is based on the latest GSM/GPS module SIM808 from SIMCOM, supports GSM/GPRS Quad-Band network and combines GPS technology for satellite navigation.

<img src="Images/sim808_gps_gsm_module.jpg">

### Connections

| TM4C | GPS/GSM |
|------|---------|
| Rx3  | Tx      |
| Tx3  | Rx      |
| GND  | GND     |

### System in real life 

<img src="Images/real_hardware.jpg">

### thingspeak data

<img src="Images/thingspeak_data1.jpg">

also thingspeak give the ability to download the data in .csv form 

<img src="Images/thingspeak_data2.jpg">






