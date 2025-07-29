# Smart-room-occupancy-energy-saver-
An Arduino-based smart sysytem that detects room occupancy using sensors and automatically turns OFF lights,fans and devices to save electricity.Built for rural and urban applications to reduce energy waste.Includes AI-generated diagrams and real hardware-tested logic .

##. Project purpose.

• To reduce the wastage of electricity in
  local rural farms.

• To make farming budget friendly for poor
  farmers.

• To provide a low cost,efficient and
  sacalble solutions for smart energy
  usage specially in ruaral areas where
  energy resource is precious and awareness
  is still growing.

##. Features.

 • Automatic power control: 
   Turns appliances ON/OFF based on room 
   occupancy.

 • Motion sensor and camera detection:
   Uses PIR sensor and optional camera to 
   detect presence.

 • Relay-based switching:
   Control AC or DC devices via Arduino and     relay module.

 • Energy Efficient:
   Reduces power wastage in empty rooms.

 • Real world tested:
   verified performance in actual room          conditions.

 • Expandable design:
   can add light,temperature sensors and app
   contol in future.

##. How it works.

  • Motion detection using PIR sensor:
    A PIR sensor is placed on the entry/exit 
    of a room to detect a motion. When
    someone enters or exit the room, the 
    sensor sends a signal to the Arduino.

  • Arduino decision making:
    The Arduino reads the signal. If motion
    is detected, it triggers the relay to
    turn ON the connected electrical devices.

  • Auto-OFF logic:
    If no motion is detected for a set time
    the Arduino turns the devices OFF by 
    cutting the relay connection- saving 
    electricity when the room is empty.

  • Camera Usage:
    A camera is also added to monitor room 
    occupancy and send footage to the system.

  • Real-world tested:
    The system has already been tested           succesfully in a real setup, confirming
    that the realy switches devices 
    accurately based on room occupancy.


##. Components used/work/cost

  • Arduino Uno/Nano:
    Microcontroller to control logic and 
    relay switching.
  COST - ₹400
  
  • PIR Motion sensor:
    Detects Human motion in the room.
  COST- ₹120

  • Relay Module:
    Acts as an electronic switch to turn 
    appliances ON/OFF.
  COST- ₹90

  • Bulb:
    Electrical appliances.
  COST- ₹130

  • CCTV Camera:
    Monitors room visually.
  COST- ₹700

  • Jumper Wires:
    Connect components on Breadboard or
    directly.
  COST- ₹30

  • Breadboard:
    Testing setup for components.
  COST- ₹100

  • Power Supply(5v):
    Power the Arduino and sensors.
  COST- ₹125

  TOTAL COST = ₹1795

##. Field Testing Note.

This system has been fully built and tested in real-world conditions. After assembling the circuit with actual components — including the PIR motion sensor, relay module, and Arduino — I deployed it in a working room environment.

During testing:

The motion sensor accurately detected room entry and exit.

The relay successfully switched appliances like a bulb based on motion.

I also simulated a CCTV camera position near the ceiling to monitor potential AI-based upgrades for occupancy detection.


Although the setup worked perfectly, the physical wiring and sensor placement were not camera-ready (due to open wires and ceiling placements). Hence, I’ve used AI-generated visual illustrations that faithfully replicate the real setup to make the explanation clearer.


##. Images for Educational clarity.

[Flow chart]
(AI-Illustrated flow chart.png.png):
• Ai illustrated flow chart for better clarity.

[Circuit Daigram]
(AI-Illustrated circuit daigram.png.png):
• Ai illustrated circuit daigram for clarity.

##.Code Overview
# Arduino code working.

1)Sensor Input (Motion or IR Sensor)
• The Arduino constantly reads input from a 
  PIR(Passive Infrared)sensor or IR sensor.
• When the sensor detects motion or presence
  it sends a high signal to the Arduino pin.

2)Relay module.
• Based on sensor Input,the Arduino  
  activates or deactivates a relay module
  connected to electrical devices.
• If someone is detected in the room.
-->Arduino turns the relay ON-devices get 
   power.
  If no one in the room for a set time.
-->Arduino turns the relay OFF-devices are 
   powered down.

3)Delay Handling.
• A small dealy or timeout features is used 
  to prevent rapid switching.

4)Power control logic.
• The Relay works like a switch for AC
  devices .Arduino send low or High signals
  to control the power line safely.

# python code working.

1)Camera Initialization.
• The python script uses OpenCV to access a 
  camera feed.

2)Occupancy Decision.
• If a person is detected
  -->A flag is set to occupied=True
  If no person is detected for a set time
  -->The room is marked as empty.

3)Relay switching.
• when using with an Arduino the python code
  can communicate over serial(USB)
--> Sends'1' when room is occupied- 
    Arduino turns ON relay
--> Sends'0' when room is empty-
    Arduino turns OFF relay

4)Energy saving.
• This whope system helps automate room 
  power usage,saving energy intelligently
  with real time human presence detection.


(camera-> python detects person->sendssignal
->Arduino->Relay->devices(ON/OFF))

## Future Improvements.
I am thinking about to have some more modifications in it but currently i dont get the proper way of it but once i get the proper way i will definitely add in it.
       Or 
If anyone wants to suggest and improvements can suggest freely.

## Use of AI-Illustration.
  (I found this approach best for the better
   communication professionally and for
  better understanding rather than raw and
  many clutterd images.)

In the Smart Room Occupancy Energy Saver project, I used AI-generated illustrations to clearly show how the system detects human presence using sensors and controls electrical appliances like fans or lights accordingly.

While I built and tested the circuit using real components (PIR sensor, Arduino, relay, etc.), the physical setup involved loose wires, breadboards, and components taped around a room during early testing. The actual photos I captured didn’t clearly show how the system works or how components connect — especially for someone unfamiliar with electronics.

So, I created AI-generated diagrams that accurately represent my real working model. These visuals show how the sensor detects motion, how the signal is processed by the microcontroller, and how the relay switches the appliances. Every part shown matches the actual hardware I used.

I chose this approach only for clarity and communication. The AI illustrations helped me present the logic of the system in a clean, easy-to-understand way — which is especially useful for documentation and educational purposes.





  
 

    

    
  
    
    
    

   
   
