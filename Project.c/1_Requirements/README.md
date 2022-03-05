# Description :
         
         In this project we are going to design a circuit for measuring temperature. This circuit is developed using “Atmega328”, Temperature is usually measured in “Centigrade” or “Faraheite” .It is used to maintain the heat in the vehicles in cold weather and  Temperature modification can be done easily.
 
# Code Analysis :
|       Codiga     |          Codacy             |       Cpp check       |       Git inspector    |
|-------------------------------|:------------------------------------------|:------------------------------------------------|:-------------------------------|
|gjhgjh  |   jgkjgk |jkhkjhk|hvmhvjh|gjgjhgj|
 
 
 # Abstract :
 


                   
# SWOT ANALYSIS :

![swot](https://user-images.githubusercontent.com/98826329/156692082-ebe1ad15-f109-49b5-af80-bb01a1389404.jpg)

 ## Strength:
 
* Temperature modification can be done easily.
* Cost effective.
* Heat generation is fast.


 ##   Weakness:
 * Need dry bags to store the heater.
* Mostly applicable in countries with low temperature.
* Not water proof.
  
 ## Opportunities :
 * By implementing both heater and AC
  
 ## Threats :
 * Can't use in high temperature areas.
* High electrical resistance could cause the heater pad in the seat to overheat.
 
 # 4 W'S and 1'H 
## WHY :
To maintain the heat in the vehicles in cold weather.
 ## WHAT : 
* Temperature measurement system to measure,control and generate heat.
## WHEN :
* In vehicles at low temperature areas.
* User can  access this application using any embedded C compiler.

## HOW : 
* By installing the system in vehicles.

# Detail Requirements :

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


