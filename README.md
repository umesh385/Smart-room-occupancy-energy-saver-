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






  
 

    

    
  
    
    
    

   
   
