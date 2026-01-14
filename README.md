Bioreactor-Dashboard
====================

### About

A dashboard created with Node-RED for a bioreactor control system. Its separated into a monitor page to observe readings and a control page to adjust setpoints and toggle kill switches. It sends and receives messages under topics over MQTT to communicate, in this case, to an ESP32 which leads to adjustments in actuator outputs and readings displayed from sensors. 

### How to Use

Node.js and Node-RED must be installed on the users system.  
An MQTT connection must be setup to send and receive messages
1. Start Node-RED from cmd prompt using the command "node-red"
3. Open the Node-RED editor (usually at http://localhost:1880).
4. Go to Menu (three lines) -> Manage Palette and install the @flowfuse/node-red-dashboard module
5. Go to Menu -> Import and paste or upload the flows.json code from this repository
6. The dashboard itself can be viewed at http://localhost:1880/dashboard
