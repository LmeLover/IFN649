# IFN649
A backup files. First git had COMMIT issues.
**About**
This project involved making an IoT Device that used 3 Tiers.
![Slide2](https://github.com/LmeLover/IFN649/assets/116260943/12e83beb-3805-486c-9d41-98d7e467cc4e)




The first tier has the sensors and actuators connected to a Teensy that uses Bluetooth to communicate with tier 2.

The second tier uses a Raspberri Pi as a gateway, that uses a internet connection to communicate with tier 3.

The 3rd tier uses AWS as a broker for MQTT.

For my project I used a waterproof temperature sensor (ds18b20) and a 3-Axis accelerometer (adxl335), as the main IoT Device.

The second IoT device has a rotary encoder and 4 different coloured LED. The device selects the modes for the main IoT Device.

The third IoT device is a physical dashboard using 2 8 Dot Matrix Displays, 3 different coloured LED lights and a buzzer.

**The Devices**

Device 1 :
![Slide3](https://github.com/LmeLover/IFN649/assets/116260943/fc0e02a6-cf20-4f4f-b79f-522ec00e7063)


Device 2 :
![Slide4](https://github.com/LmeLover/IFN649/assets/116260943/684d6692-c20b-4be0-a6bd-09f424ac47f3)


Device 3 :
![Slide5](https://github.com/LmeLover/IFN649/assets/116260943/5b297b04-bf1d-4c2b-a459-63d17b06ecf6)

**How do they work?**
![Slide6](https://github.com/LmeLover/IFN649/assets/116260943/8efe9546-036c-4c40-ba35-7d678cd9a7bc)


