
# Density Based Traffic signal system using microcontroller

The function of traffic lights is to provide sophisticated control and coordination to ensure that traffic moves as smoothly and safety as possible.
Nowdays,controlling the traffic becomes major issue because of rapid increase in automobiles and also because of large time delays between traffic lights.so,inorder to rectify this problem.we will go for large time delays between traffic lights system.
                    z![traffic](https://user-images.githubusercontent.com/98826329/154784826-b23555f4-103c-4fb1-a419-8ae654290a4c.png)

* this system uses a LED light as an indicator and  IR sensors for receiving the signal from traffic.
* A microcontroller for auto change signalaftera specifictime interval.
* The LEDs are automatically on and off by making the corresponding port pin of the microcontroller high.

## working of traffic signal:
* In this system we will use a IR sensor to measure the traffic density 
* we have to arrange one IR sensor for each road the sensors always send the traffic on that particular road.
* All the sensors are interfaced to the microcontroller based on these sensors controller detects the traffic and control the traffic system .
* the main heart of this traffic system is microcontroller .
* IR sensors are connected to the port of the microcontroller and traffic lights are connected to port of the microcontroller.
*  if there is a traffic on then that particular sensor output become logic 0 otherwise logic 1 by receiving these IR sensor outputs .
*   if you receive logic 0 from any of these sensors,  we have to give the green signals to that particular path and give read signals to all other parts continuously we have to monitor the IR sensor to check for the traffic.
*   we have to place this I have a in such a way that when we placed an obstacle in front of this IR pair IR sensor should be able to receive the IRS when we give the power the transmitted IR is heat the object and reflect back to the IR receiver.
* Instead of traffic lights you can use LEDs( red ,green ,yellow ). In normal traffic system you have to glow the LED is on the time basis if the traffic density is high on any particular path then glow green LED of that particular path. 


## High level Requirements:
 |    HLR                        |              Description                  |  
 |-------------------------------|:------------------------------------------|
 |  HLR1                         |   we can reduce the possibility of traffic jams caused by traffic lights   |
 | HLR2                          |   traffic lights is to provide sophisticated control and coordination to ensure that traffic moves as smoothly and safety as possible.|
 | HLR3                          |  If there is traffic on road then that particular sensor output becomes logic 0 otherwise logic 1 |
 | HLR4                          |  By receiving these IR sensors outputs,we can write the program  |
 
## Low level Requirements:
| LLR1 | Instead of traffic lights you can use LEDs( red ,green ,yellow ) |
| LLR2 | 
