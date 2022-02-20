
# Density Based Traffic signal system using microcontroller

## Purpose:
The function of traffic lights is to provide sophisticated control and coordination to ensure that traffic moves  smoothly and safely as much as possible.
but traffic control is a major issue nowdays, because of the increment of automobile vechiles and because of long delay time between the traffic lights.
so,inorder to rectify this problem,we are intrested to bring up the traffic  signal system based on the density.
## Block Diagram :
![traffic light](https://user-images.githubusercontent.com/98826329/154789753-173bc634-9b45-438c-92b5-d5259628c818.png)                     ![Screenshot (15)](https://user-images.githubusercontent.com/98826329/154787734-9b36b464-f20a-4a65-b1d2-55fcededefbe.png)


* This system uses a LED light as an indicator and  IR sensors for receiving the signals from traffic.
* A microcontroller for  changing the signal after a specific time interval.
* The LEDs are automatically turned on and off by making the corresponding port pin of the microcontroller high and low.
 
## Components :
* Atmega32 Microcontroller
* IR sensor's
* LED's
* Power supply

## working of traffic signal:
* IR Sensors : The density based traffic light system use IR sensors to measure the traffic density. IR sensor has to be setup in each direction(road) ,so these sensors will always detect traffic on that route.
* Microcontroller: microcontroller is the prime part of this system, all the sensors are connected to microcontroller. The controller detects and regulates the traffic system based on the signals recevied by the  sensors.
* IR sensors are connected to the some port of the microcontroller and IR sensors and traffic lights are connected to the port of the microcontroller.
*  If there is traffic on road then that particular sensor output becomes logic 0 otherwise logic 1.
*  If microcontroller receives logic 0 from any of the IR sensors, then we have to give green light signal to that road and gives red traffic signal to  all other roads.so ,Here continuously we have to monitor the IR sensors to check for the traffic.
*  we have to place these IR pair in such a way that when we place an obstacle infront of this IR pairs,IR sensor should be able to receive the IR rays 
*  when we give the power,the transmitted IR rays hit the object and reflect back to the IR receiver.
* Instead of traffic lights you can use LEDs( red ,green ,yellow ).             
* In normal traffic system you have to glow the LED is on the time basis if the traffic density is high on any particular path 
then glow green LED of that particular path.
             

## High level Requirements:
 |    HLR                        |              Description                  |  
 |-------------------------------|:------------------------------------------|
 |  HLR1                         |  we can reduce the possibility of traffic jams caused by traffic lights   |
 | HLR2                          | system use IR sensors to measure the traffic density |
 | HLR3                          | by monitoring the IR sensors we can check the traffic. |
 | HLR4                          |   traffic lights is to provide sophisticated control and coordination to ensure that traffic moves as smoothly and safety as possible.|
 
## Low level Requirements:
|    LLR       |              Description                  |
|-------------------------------|:------------------------------------------|
| LLR1 | Instead of traffic lights we can use LEDs( red ,green ,yellow ) |
| LLR2 | By receving IR sensors output,we can write the program.|
| LLR3 | we can save a considerable amount of time |
| LLR4 | It keeps a track of the vechiles |

## V model :
![Screenshot (24)](https://user-images.githubusercontent.com/98826329/154850996-2530b592-9765-4459-a8a4-c02b9b615206.png)


## Application
* It is mainly used in the traffic signals in metropolitan cities to provide uniform distribution of traffic.
* This will help maintain efficient traffic control management system.
* It is used infirst order edge detection
* Emergency
* Edge detection
* Robert operator
