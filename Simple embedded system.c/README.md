
# Density Based Traffic signal system using microcontroller

The function of traffic lights is to provide sophisticated control and coordination to ensure that traffic moves as smoothly and safety as possible.
but traffic control becomes a major issue nowdays, because of the increment of automobile vechiles and because of large delay time between the traffic lights.
so,inorder to rectify this problem.we will go for density Based Traffic signal system using microcontroller
![traffic light](https://user-images.githubusercontent.com/98826329/154789753-173bc634-9b45-438c-92b5-d5259628c818.png)  ![Screenshot (15)](https://user-images.githubusercontent.com/98826329/154787734-9b36b464-f20a-4a65-b1d2-55fcededefbe.png)



* This system uses a LED light as an indicator and  IR sensors for receiving the signal from traffic.
* A microcontroller for auto change signal after a specifictime interval.
* The LEDs are automatically on and off by making the corresponding port pin of the microcontroller high

## working of traffic signal:
* IR Sensors : The density based traffic light system use IR sensors to measure the traffic density.We must set up one IR sensor for each road,so these sensors will always detect traffic on that route
* Microcontroller: The main and important part of this traffic system is the microcontroller.The microcontroller is connected to all of these sensors. The controller detects and regulates the traffic system using these sensors.
* the main heart of this traffic system is microcontroller .
* IR sensors are connected to the port of the microcontroller and traffic lights are connected to port of the microcontroller.
*  If there is traffic on road then that particular sensor output becomes logic 0 otherwise logic 1
*  If microcontroller receives logic 0 from any of the IR sensors, then we have to give green light signal to that road and gives red traffic signal to  all other roads.
* so ,Here continuously we have to monitor the IR sensors to check for the traffic.
*  we have to place these IR pair in such a way that when we place an obstacle infront of this IR pairs,IR sensor should be able to receive the IR rays 
*   when we give the power,the transmitted IR rays hit the object and reflect back to the IR receiver.
* Instead of traffic lights you can use LEDs( red ,green ,yellow ).             
*  In normal traffic system you have to glow the LED is on the time basis if the traffic density is high on any particular path 
then glow green LED of that particular path.
             

## High level Requirements:
 |    HLR                        |              Description                  |  
 |-------------------------------|:------------------------------------------|
 |  HLR1                         |   we can reduce the possibility of traffic jams caused by traffic lights   |
 | HLR2                          ||system use IR sensors to measure the traffic density |
 | HLR3                          | by monitoring the IR sensors we can check the traffic. |
 | HLR4                          |   traffic lights is to provide sophisticated control and coordination to ensure that traffic moves as smoothly and safety as possi  |
 
## Low level Requirements:
|    LLR       |              Description                  |
|-------------------------------|:------------------------------------------|
| LLR1 | Instead of traffic lights we can use LEDs( red ,green ,yellow ) |
| LLR2 | By receving IR sensors output,we can write the program.|
