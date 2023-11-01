

# TF2MLP
Export and run TensorFlow models on Arduino microcontrollers!

### Why?
Currently, tflite-micro can only run on high memory boards like the Nano 33 BLE. I wanted to make it possible to run TensorFlow models on boards even with low amounts of memory and make the process as simple as possible while still making it useful and efficient. If eventually they do manage to make it possible to run tflite on low memory boards like the Uno then this library will become obsolete 



## Compatibility

| Arduino          | Chip           | RAM   | XOR     | Sin     |
| ---------------- | -------------- | ----- | ------- | ------- |
| Arduino Uno      | ATmega328P     | 2KB   | :white_check_mark:     | :x:     |
| Arduino Mega (Recommended)     | ATmega2560     | 8KB   | :white_check_mark: | :white_check_mark: |
| Arduino Due      | SAM3X8E M3     | 96KB  | :white_check_mark: | :white_check_mark: |
| Adafruit PyGamer | ATSAMD51J19 M4 | 192KB | :white_check_mark: | :white_check_mark: |
| ESP32            | ESP-WROOM-32   | 320KB | :white_check_mark: | :white_check_mark: |




