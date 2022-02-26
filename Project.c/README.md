# Prepaid Energy Meter using Arduino and GSM
# Description :
               
 In this project we are building a automated system by using Arduino and GSM module. we can recharge the electricity balance through this system,just by sending a SMS. It can also disconnect the home power supply connection, if there is low or zero balance in the system. And this system will reads the energy meter readings and automatically send some updates to user’s mobile phone like low balance alert, cut off alert, resume alert and recharge alert. and The word prepaid means"pay before use” one of the advantageous feature of this concept prepaid energy meter is used to prepaid the ongoing supply of electricity to homes, offices etc.

                   
# SWOT ANALYSIS :
 Strenghth:
 * Using this project we can reduce the readings from the energy meter which is cost effective solution
 * It is user friendly and we can enhance this project ,in which an electricity department can send meaasge to the customer about billing information.
 * it would reduce human efforts.
 * it provides better customer service.
 * Weakness : user will be responsibile for disconnections of the home power supply.
 * Opportunities : Prepaid Energy meter is a multipurpose project which can integrate all the functions like billing and automatic message responce to user.
 * Threats : user will be responsibile for disconnections of the home power supply.
 
 # 4 W'S and 1'H 
## WHO :
* Everyone can use the prepaid energy meter who want to have benefit of this sysyem.
## WHEN :
* when we need to recharge our system, we can recharge it simply by sending a SMS to the system, through our Cellphone.
## WHERE :
* User can can access this application using any embedded c compiler.
## WHAT : 
* Prepaid meters allow consumers to track their electricity usage in real time. This can incentivise customers to save money by reducing use of power-guzzling appliances if they feel that their power usage is spiralling out of their household budget.
## HOW : 
* These meters are opertaes based on the amount available at meters. 


## High level Requirements:
 |    HLR                        |              Description                  |  
 |-------------------------------|:------------------------------------------|
 |  HLR1                         | It shall disconnect the home power supply connection.  |
 | HLR2                          | system shall reads the energy meter readings and  automatically send some updates to user’s mobile phone.|
 | HLR3                          | user shall be responsibile for disconnections of the home power supply.|
 | HLR4                           | These meters are operates based on the amount available at meters.|
 
## Low level Requirements:
|    LLR       |              Description                  |
|-------------------------------|:------------------------------------------|
| LLR1 | it automatically send some updates to user’s mobile phone like low balance alert, cut off alert, resume alert and recharge alert. |
| LLR2 | say If available balance is greater then 15 rupes then, ARDUINO turn on the electricity of home or office by using relay.|
| LLR3 | If balance is less then 15 rupes, ARDUINO Sends SMS to the user phone regarding low balance alaret & requesting to recharge soon.  |
| LLR4 | If balance is low or zero ,then ARDUINO shall turn off and power cutoff due to low balance.|




## Block Diagram
![arduino_and_gsm_based_prepaid_energy_meter_w7C8Rqc1J8](https://user-images.githubusercontent.com/98826329/155730980-46400784-f4d2-431c-94a7-536595695d88.png)
## components Required :

## Arduino uno:
![Screenshot (42)](https://user-images.githubusercontent.com/98826329/155743782-a2c80015-f809-417d-80a3-76dfdb9bdebe.png)
* Here we have interfaced electricity energy meter with  Arduino using pulse LED (Calibration  or cal) of electricity Energy meter.
* We only need to connect tis CAL LED to Arduino through an optocoupler IC.

## Analogue Energy Meter:
![Screenshot (52)](https://user-images.githubusercontent.com/98826329/155767374-dd8dc8c1-1eb9-4b09-ab1b-08ad1c49c517.png)
* Energy or electrical meter is a device that measures the amount of electrical energy consumed by a residence business or any electrically- powered device .
* Electrical meteres are typically calibrated in billing units the most common one being the kilowatt hour.

## GSM Modern :
![Screenshot (53)](https://user-images.githubusercontent.com/98826329/155767574-7e036686-8e59-4b82-af24-976d30569837.png)
* GSM modern is a specialised type of modem which accepts sim card ,and operates over subscription to a mobile operator ,just like a mobile phone.
* From the mobile operator prospective, a GSM modem looks like just mobile phone .
* GSM module has been used to send & receive messages.

## LCD : 
![Screenshot (47)](https://user-images.githubusercontent.com/98826329/155748710-974898bc-56ef-49d1-bb33-3a436c36dd74.png)
 * Most common LCDs connected to the ardiuno are 16*2 display. 
 * This LCD gives the consumed power,balance amount which are essential to awareness about energy consumption. 

## Relay :
* A release is an electrically operated switch.
*  Many relays use an electromagnet to mechanically operated switch but other operating principles are used to such a solid state relays delays.
* Relays are used where it is necessary to control a circuit by low-power signal (with complete technique electrical isolation between control and controlled circuits). or where several circuit must be controlled by one signal

## EPROM :
![Screenshot (55)](https://user-images.githubusercontent.com/98826329/155767989-c14f6a47-041d-4738-9014-b34cd85c8da4.png)
* When we power up the system then it reads previous values of rupees stored in EEPROM.
* Restores them into the variables then checks the available balance with predefined value and it wil take action according to them.

 
## AUXILARY COMPONENTS :
* Led lights are used to know the circuit status,means power in the circuit is present or not.
* crystal oscillator is used to generate the proper voltage to relays in arduino.

# flow chart :
![Screenshot (59)](https://user-images.githubusercontent.com/98826329/155799154-f1f4796d-182d-4038-8814-8982202c5077.png)



TEST PLAN :

## Table no: High level test plan
|Test ID | Description |  Input   |   Exp O/P   |   
|:-------|:------------|:-----------|:------------|
| HLR1 | ex: If available balance is greater then 15 rupes | 15 | Arduino turn on the electricity of home or office by using relay.|
| HLR2 | ex: If balance is less then 15 rupes | 15 |  ARDUINO Sends SMS to user phone regarding low balance alaret & requesting to rechargesoon. |
| HLR3 | ex: if balance is less than 5 rupes | 5 | ARDUINO turn off,and power cut due to low balance.|

## Table no: Low level test plan

|Test ID|	Description|	 Input | Exp O/P |
|:-----|:------------|:---------|:--------|
| LLR1 | if balance is low | 0 |  ARDUINO turn off ,power cut due to low balance|
