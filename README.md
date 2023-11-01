

# TF2MLP
Export and run TensorFlow models on Arduino microcontrollers!

### Why?
Currently, tflite-micro can only run on high memory boards like the Nano 33 BLE. I wanted to make it possible to run TensorFlow models on boards even with low amounts of memory and make the process as simple as possible while still making it useful and efficient.



## Compatibility

| Arduino          | Chip           | RAM   | 
| ---------------- | -------------- | ----- |
| Arduino Uno      | ATmega328P     | 2KB   | 
| Arduino Mega (Recommended)     | ATmega2560     | 8KB   | 
| Arduino Due      | SAM3X8E M3     | 96KB  |
| Adafruit PyGamer | ATSAMD51J19 M4 | 192KB | 
| ESP32            | ESP-WROOM-32   | 320KB |


Inspired From : https://github.com/Bobingstern/MicroFlow
Made some chnages to the orginal library , for more precise float representation



