# DHT11 with LCD Raspberry pi

On this project, DHT11 temperature and humidity sensor (boutgh on Aliexpress for 1$) is paired with Raspberry PI and LCD display.

## Logic of the appliction

There are three files:

- read_and_disp_temp.py -> Basically, main file where all logic is happaning. You should only start this file and run program
- dht11_temp_hum.py -> where is created class for reading of temperature and humidity from sensor
- lcd_writer.py -> class for writing on LCD display by sending strings(line1, line2 and time how much text should stay on display)
    
   
Sensor readings from DHT11 are achived thanks to Adafruit_DHT library.

For any questions, feel free to contact me.


## Equipment:
- Hardware: Raspberry PI 3
- OS: Minibian 2016-03-12
- Sensor: DHT11 (3 pins) temperature and humidity
- LCD display: 16x2 with I2C PCF8574AT communication module attached

## Image:
![20170827_dsc_0386_lr](https://user-images.githubusercontent.com/22866358/29762770-7c8f3ec0-8bd0-11e7-8ce4-cc79c01070fa.jpg)



Have fun,
Aleksa


