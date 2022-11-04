# On-Demand-Traffic-Lights
Embedded Systems project based on ATmega32 Microcontroller in Embedded Systems Professional track provided by Udacity and egfwd. The project was developed using `Eclipse` IDE and simulated using `Proteus` Simulator.

## System Description
-Traffic lights normally consist of three signals, transmitting meaning to drivers and riders through colors and symbols including arrows and bicycles.

-The system consists of 6 LEDs which are red, yellow, and green for both pedestrians and cars, arranged vertically or horizontally in that order in addition to an on-demand crosswalk button.

-Crosswalk button lets the signal operations know that someone is planning to cross the street, so the light adjusts, giving the pedestrian enough time to get across.

![Screenshot 2022-11-04 155348](https://user-images.githubusercontent.com/70335125/200049190-bd06e929-0051-4f66-a88b-4166c355bd59.png)


## System Logic
- MCAL drivers which are DIO, TIMERS, and INTERRUPTS, and ECUAL drivers which are LED and BUTTON were implemented from scratch.

- The project is developed using the full static architecture and follows the SOLID principles.

- The system consists of 6 LEDs, a push button, and `AVR` `ATmega32` Microcontroller.

- Cars' traffic lights switches every 5 seconds. Same as for pedestrians' traffic lights but with inverted colors.

- The system is built so that to gurantee pedestrians' safety as they are allowed to cross the road if and only if the cars' traffic is red.

-

• The image below explains the file structure of the whole project.

![Project Explorer](https://user-images.githubusercontent.com/70335125/199995647-3e7b4231-2480-495f-af32-48a9d50f98d4.png)
