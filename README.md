# Water Softener Smart Lid with ESPHome and M5Stack

This is my take on a water softener smart lid to report salt levels to my Home Assistant setup. In hindsight I should have gone for the VL53L0X sensor which is supported natively by ESPHome.

### In operation

The magnetic USB C cable is convenient for when you need to remove the lid for filling up with salt.

<img src="images/smart-lid.jpg" alt="Water Softener Smart Lid" width="300">

### Gauge in Home Assistant dashboard

<img src="images/ha-gauge.png" alt="HA Gauge" width="150">

### Top view

Note how I used the nylon nuts to level the sensor.

<img src="images/top.jpg" alt="Top View" width="300">

### Bottom view
<img src="images/bottom.jpg" alt="Bottom View" width="300">


## Components

All the components were sourced from [The PiHut](https://thepihut.com/).

| Image | Component | Price|
|---|---|---:|
| <img alt="AtomS3 Lite" src="images/atom-s3.png" width="100">     | AtomS3 Lite ESP32-S3 Dev Kit | £9.00 |
| <img alt="ToF Sensor" src="images/tof-sensor.png" width="100">   | Time-of-Flight Distance Unit (VL53L1X) | £8.70 |
| <img alt="Brick" src="images/sandwich-c-brick.png" width="100">  | M5Stack SandwichC Brick| £1.00 |
| <img alt="Head Screws" src="images/head-screws.png" width="100"> | Nylon Slotted Cheese Head Screws - M2.5 x 20mm (10 Pack) | £0.70 |
| <img alt="Nylon Nuts" src="images/nylon-nut.png" width="100">    | Nylon Nut - M2.5 (10 Pack) | £0.70 |
| <img alt="Magnetic Type C Cable" src="images/magnetic-c-cable.png" width="100"> | M5Stack Magnetic Type-C Cable with Connector - 1m | £4.40 |
||Total|£24.50|

