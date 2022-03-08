
# REPORT        
# LPG GAS LEAKAGE  DETECTOR using Arduino :
-BY LAKSHMI HULKOTI

# Table of Contents:            	
* Abstract
* Identifying Features
* State of Art                    	
* SWOT Analysis	
* 4 W's and 1H	

## Requirements	
* High Level Requirements	
* Low Level Requirements	

## Architecture	
* Block Diagram	
* Behaviour Diagram	
* Flow Chart	
* Structural Diagram	


## Applications	
* Test Case

## Output 



----------------------------------------------------------------------------------------------------------------------------------------------------



## Abstract:
 This project has a gas leakage detector implemented by using an LPG Gas sensor.LPG is an essential need of every household,To alert on LPG leakage and prevent any mishappening there are various products to detect the leakage. Here we have developed an Arduino based LPG gas detector alarm. If gas leakage occurs, this system detects it and makes an alert by buzing the buzzer attached with the circuit A Gas sensor is used to detect dangerous gas leaks in the kitchen or near the gas heater. Ideal to detect dangerous gas leaks in the kitchen. The sensor can also sense LPG and Coal Gas as well as Ideal sensor for use to detect the presence of a dangerous LPG leak in your car or in a service station, storage tank environment. 
 
 ## Identifying features :
 * This module contains a MQ3 sensor which actually detects LPG gas.
 * It gives a HIGH output when LPG gas  is sensed. 
 * A potentiometer is also used for controlling sensitivity of gas sensing.
 * Arduino controls the whole process of this system like reading LPG Gas sensor module output, sending message to LCD and activating buzzer.  

 # State of Art
 ![Screenshot (79)](https://user-images.githubusercontent.com/98826329/156982840-e6f8b586-d7c3-4756-bdf8-cd8f3c0cb3fb.png)
 
                 
# SWOT ANALYSIS :

![swot](https://user-images.githubusercontent.com/98826329/156692082-ebe1ad15-f109-49b5-af80-bb01a1389404.jpg)

 ## Strength:
* Detection and Prevention of any sort of gas leakage.
* No environmental effect or no effect of physical conditions.
* A Gas sensor is used to detect dangerous gas leaks in the kitchen or near the gas heater.
* The sensor has excellent sensitivity combined with a quick response time..
* This system provides quick response rate and diffusion if the critical situation can be made faster than the manual mathods

## Weakness: 
* It work only when at 5v power supply.
* It's sensitivity depends on Humidity and temperature.
* It may lead to fetal disaster and may cause human and material loss.

## Opportunities :
 * These sensors usually employ an audible alarm to alert people when a dangerous gas has been detected
 * The propsed system will help in giving better protection to life and propety.
 * They may be used in firefighting.
  
 ## Threats :
 * No prevention of fires possible with kit
 * That can, in turn, lead to severe headaches, fatigue, decreased vision, short breaths, and even loss of consciousness.


 # 4 W'S and 1'H 
 ![Screenshot (168)](https://user-images.githubusercontent.com/98826329/156935676-4ad15208-1a17-48cc-aae6-beca00498b06.png)


# Detail Requirements :

## High level Requirements:
 |    HLR                        |              Description                  |  
 |-------------------------------|:------------------------------------------|
 | HLR1                          | Sensor to detects the gas leakage.       |
 |  HLR2                        | User shall get notify when LPG Gas is sensed  |
 | HLR3                          | User shall not get notify when no LPG Gas is sensed |
 | HLR4                          | user shall get better protection to life and property | 

 
## Low level Requirements:
|    LLR       |              Description                  |
|-------------------------------|:------------------------------------------|
| LLR1 | This system triggers LED and buzzer to alert people when LPG leakage is detected LED get turn on when .|
| LLR2 | LPG leakage detection is essential to prevent accidents and to save human lives.  |
| LLR3 | It shall alert through Buzzer when system detects LPG GAS |



# BLOCK DIAGRAM :
![Screenshot (172)](https://user-images.githubusercontent.com/98826329/156936425-32d65a0c-5d59-4476-8683-f2002e53591a.png)

## Components Required :
1) Arduino uno
2) 16x2 LCD Display
3) MQ2 Gas sensor
4) 10k potentioometer
5) ADC
6) Buzzer
7) 5v charge
  
 ## software requirements
 * Simulide software
 * Arduino IDE

## Arduino uno:
![Screenshot (42)](https://user-images.githubusercontent.com/98826329/155743782-a2c80015-f809-417d-80a3-76dfdb9bdebe.png)
*	It  controls the whole process of this system like reading LPG Gas sensor module output, sending message to LCD and activating buzzer 
*	We can set sensitivity of this sensor module by inbuilt potentiometer placed on it.

## LCD : 
![Screenshot (47)](https://user-images.githubusercontent.com/98826329/155748710-974898bc-56ef-49d1-bb33-3a436c36dd74.png)

* The Term LCD stand ,for liquid crystal display and Most common LCDs connected to the ardiuno are 16*2 display
*	It is necessary requirement to put a display about system monitoring and controlling performance, which displays the various messages such as leakage of gas detection

## LPG Gas Sensor :

![sensor](https://user-images.githubusercontent.com/98826329/156936431-bd128bde-0e77-47b7-b7fb-90541b6b86f4.png)
*	A GAS SENSOR is an electronic device which Detects dangerous gas leaks in the industrial areas.
*	Good sensitivity to Combustible gas in wide range. 
*	High sensitivity to Propane, Butane and LPG.
*	Long life and low cost.

## BUZZER :

![Screenshot (175)](https://user-images.githubusercontent.com/98826329/156938473-ff9d91ec-2b8f-4930-a94c-d97590f8c18e.png)

*	A buzzer or beeper is a audio signaling device, usually electronic, typically used in automobiles, household appliances such as a microwave oven, or game shows .
*	A buzzer is turned on after LPG gas leakage so it acts as a gas leakage alarm

## Potentioometer : 
* A potentiometer is basically used for controlling the sensitivity of gas detecting .

## ADC :
* It convertes analog value to digital values and 	With the help of digital data from the ADC the data will be displayed on the LCD






# Behavioral Diagram :
 
 ## Flowchart

![flow chart](https://user-images.githubusercontent.com/98826329/156937044-90140fc4-c3ff-40bb-afa5-b7fff8e92452.png)

# Structural Diagram

## UML Diagram :

![Screenshot (85)](https://user-images.githubusercontent.com/98826329/157038359-e00291a0-2ca0-4874-bf91-71ed2d861f85.png)




![IMG-20220307-WA0053](https://user-images.githubusercontent.com/98826329/157043678-8f92a4b6-e800-4150-8f40-679e3ed8e2a6.jpg)


 ![image](https://user-images.githubusercontent.com/98826329/156998425-0338e108-0d07-49b3-b9de-80cab4ecffd4.png)


# TEST PLAN :


|Test ID | Description |  Input   |   Expepted  O/P   |  Actual Output | 
|:-------|:------------|:-----------|:------------|:--------------------|
| HLR1 |  When Arduino gets a High Pulse from LPG Gas | Sensor detects LPG Gas Leakage | LCD displays                                                                                                                                                                      " LPG GAS leakage Aleart "| LCD Displays      " LPG GAS leakage Aleart " |
| HLR2 | When Arduino gets a low Pulse from LPG Gas | sensor not detects no LPG Gas Leakage  | LCD displays "NO LPG Gas leakge Aleart " | LCD displays "NO LPG Gas leakge Aleart" |



# OUTPUT :

## Schematic Design
![first](https://user-images.githubusercontent.com/98826329/157050947-242d1720-e4e6-4d0a-9a73-edbeb2d9b19e.png)

##  Arduino turns ON & checks for Gas Leakage :
![whn we run](https://user-images.githubusercontent.com/98826329/157050925-62e28938-8f13-426f-9855-224dbe85fcad.png)

## When No LPG Gas is detected :
![No LPG Gas detector](https://user-images.githubusercontent.com/98826329/157051008-1e7c1d84-0678-4ebd-b870-19d263269408.png)

## When LPG Gas is Detected :
![LPG gas detector](https://user-images.githubusercontent.com/98826329/157050980-3a68a4c9-3aeb-4fc9-859d-2cf79c20845e.png) 

 ## LPG GAS LEAKAGE DETECTOR PRESENATAION VIDEO 
 https://user-images.githubusercontent.com/98826329/157309085-522354b3-4f60-4b09-8937-cad78b75dd06.mp4


 ## simulation working video :
https://user-images.githubusercontent.com/98826329/157070866-8c797327-cba7-4897-9a1a-fac5b02f3868.mp4

* Resources: 
* [Reference_1](https://technoreview85.com/lpg-gas-leakage-detector-using-arduino/)

