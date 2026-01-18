# Irrigation-System

This is a simple irrigation system for small potted plants that can be controlled physically and remotely.

The ESP32 runs a server that displays data about the soil humidity and water tank levels and controls the watering of the plant remotely. Watering can also be triggered physically.

### Materials

- ESP32-WROOM-32 Dev board - the main development board and local server host
- Breadboard
- Soil moisture sensor with probe
- Water level sensor
- SRD-05VDC-SL-C Relay module
- 5V submersible water pump
- Consumables (resistors, jumper wires, diode, electrolytic capacitor)
- Physical (water reservoir, plant pot, water tube)

### Plan
- A local server will be ran on the development board that will display a HTML page that periodically accepts status updates from the sensors. The page will display data about the water level values in the water reservoir and soil humidity. 
- Watering can be triggered either by the user remotely or physically.
- The design will be deliberately kept simple for ease on use.
