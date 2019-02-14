# solar-system-planet-led-mgr-node-network

<b>Primary objective:</b>
Creation of an accurate scale model of the solar system that fits within a 1000 acer ranch in West Texas. All planets must be visable from the Sun.

This specific set of projects covers the Design/Build of Planet nodes that represent outer planets as an LED light source.

<b>Projects include, but are not limited to.</b>

<b>1.</b> Design/build of a weather resistant, durable and aesthitically appropriate container to house all components safely in the extreme West Texas climate.

<b>2.</b> Design/build of a multi-color, dimable, controllable, programable LED light source that can be tuned to represent each planet (visable at night).

<b>3.</b> Design/build (Hardware & Software) of an Arduino-style controller (MCU) to operate/manage all node functions</b>

<b>4.</b> Design/build of a remote/self-contained Power System capable of meeting 7x24 power requirements for all node functions. 
Includes:
   - Power source (battery) capabable of maintaining all node functions for a defined cycle (assumed 24 hours with enough  
     reserve capacity to handle cloudy days).
   - Solar recharging system capable to charge the power source to required levels
   - Power management controller to avoid over charging / over draining battery to maximize usable lifespan
   
<b>5.</b> Design/build of a robust, low-power RX/TX network to enable reliable 2-way serial communication between nodes and the mothership master controller.

<b>6.</b> Design/build of the mothership master control unit
   - Provides centralized, yet independent control of all planet nodes
   - Capable of wireless serial network connectivity with each planet node for the purpose of sending control commands and    
     receiving status reports from each node.
   - Hosts a basic web-based application for viewing status of each planet with the ability to turn the LED on/off, change 
     color, change brightness, put in "find me" mode, etc.
   - WIFI connectivity for web browser access on the local WIFI network
   - Appropriate user-based security if future public Internet access to the web-application is desired.
