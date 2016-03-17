# SmartSlider
ESP8266 Based Smart Slider Controller

https://github.com/esp8266/Arduino is needed to flash it via Arduino IDE.

With this project you can make ANY dumb slider smart.

https://www.youtube.com/watch?v=h9jXmKDSoqA

Features:

- timelapse control (Slider runtime in minutes)
- calibration for Sliders in any length (runs from end to end to count the number of steps the motor needs for the way)
- speed presets for video use (100,50,33,etc.)
- silent and shakeless operation (thanks to SilentStepStick)

To-Do-List:

- go-stop-shoot-go-stop-shoot feature for long exposures
- maybe additional camera connection for shutter
- nice and clean HTML5/JavaScript Webinterface (as long as the ESP can handle it)

Parts List:

- ESP8266 (07, 12, 201)
- SilentStepStick
- Stepper Motor
- timing belt and gear wheels
- breadboard, prototyping PCB, connectors and cables
- USB Serial Adapter (CH340)
