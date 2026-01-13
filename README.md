# sauna-monitor
A horribly vibe-coded sauna monitor for a waveshare ESP32 module. My first project.
### Bill of Materials
| Item | Quantity | Description | Link/Source |
| :--- | :--- | :--- | :--- |
| ESP32 Development Board | 1 | Waveshare ESP32-C6-LCD-1.47 | 
| Temperature Sensor | 1 | DS18B20 | 
| Pull-up for DS18B20| 1 | 4.7kΩ pull-up resistor (2.2kΩ to 10kΩ)  | 

The black GND of the DS18B20 connects to the GND of your board, the red cable of the DS18B20 goes on the 3.3V pin of your board, and the yellow data wire goes on the pin you specify in the code, here pin 5. The pull-up resistor goes between the red and yellow wire. This is to keep the data line on high for data readout. 
The obj file is straigt from 3ds max, subdivided to avoid whining from the Bambu lab slicer. No clip-ins for the model, just friction fit.
