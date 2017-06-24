# Default Mongoose OS firmware with the modified init.js (IoT Bell)


## Overview

This is the default Mongoose OS app + modified init.js.
It's for ringing an IoT bell over MQTT. 

For the bell, you can make one with a cheap reception bell and a 
5V solenoid. Make sure you use a relay and a relay drive circuit
and don't connect the solenoid directly to the GPIO pin.

Change relayPin, topic, or bellNumber if necessary.
