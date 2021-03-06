# Straphanger 

## IoT-Kit

Circuit Connection:

1.V-in of NEO 6M to 3.3V of NODE MCU

2.Gnd of NEO 6M to Gnd of NODE MCU

3.RX of Neo 6M to pin D7 of NODE MCU

4.TX of NEO 6M to pin D6 of NODE MCU.

## How to use
Microcontorller code for functioning of NEO 6M GPS module with NODE MCU (ESP 8266) and uploading the gps co-ordinates to the online cloud platform Thingspeak.

1.Create a Thingspeak account for yourself and create a channel in it for your own IoT data.

2.Get the channel number and API credentials for your channel and paste in the code.

3.Also paste your hotspot's name and password for internet connectivity.

4.Upload the code in the board by choosing Node MCU 1.0 12-E ESP 8266 board from Boards Manager of Arduino IDE.

5.Also download the necessary library files for ESP 8266.


## Android Application

The front-end application is to be accessed by the end user in this case the commuters of MTC buses who can track the location of their desired bus routes via this application and also check for the availability of seats in the same.The application is written from scratch in Java and it uses Google Maps API to plot the GPS co-ordinates of the live location which is fetched from the server end.


## Screenshots
<p float="left">
<img src="https://github.com/barath83/Smart-Transportation-System/blob/master/images/kit.jpg" width="250" height="350" >
<img src="https://github.com/barath83/Smart-Transportation-System/blob/master/images/ss-app.png" width="250" height="350">
</p>

## Co-Creators

<p>Barath Gopinath - <span><a href="https://github.com/barath83"/>barath83</span></a></p>
<p>Janani VI - <span><a href="https://github.com/Janani216"/>Janani216</span></a></p>


