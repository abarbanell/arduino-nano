# Arduino sketches for Arduino Nano

## i2cscanner

sketch code from arduino.cc (see comments in the code). 

Caveat: most Arduino Nano graphs have the pinout wrong, as I learned 
from [Big Dan the Blogging Man](https://bigdanzblog.wordpress.com/2015/01/30/cant-get-i2c-to-work-on-an-arduino-nano-pinout-diagrams/). 

These should be Analog pins, not digital: 

```
SDA              Pin A4
SCL              Pin A5
```

This is the [complete pinout](https://bigdanzblog.wordpress.com/2015/01/30/cant-get-i2c-to-work-on-an-arduino-nano-pinout-diagrams/#nano).

