

# TF2MLP
Export and run TensorFlow models on Arduino microcontrollers!

### Why?
Currently, tflite-micro can only run on high memory boards like the Nano 33 BLE. I wanted to make it possible to run TensorFlow models on boards even with low amounts of memory and make the process as simple as possible while still making it useful and efficient. If eventually they do manage to make it possible to run tflite on low memory boards like the Uno then this library will become obsolete 



## Compatibility

| Arduino          | Chip           | RAM   | 
| ---------------- | -------------- | ----- |
| Arduino Uno      | ATmega328P     | 2KB   | 
| Arduino Mega (Recommended)     | ATmega2560     | 8KB   | 
| Arduino Due      | SAM3X8E M3     | 96KB  |
| Adafruit PyGamer | ATSAMD51J19 M4 | 192KB | 
| ESP32            | ESP-WROOM-32   | 320KB |




