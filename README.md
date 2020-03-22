# Gps-location-tracker-client for Corona Path Tracking

This android app records your locations every 60 seconds


Your GPS Location is updated ever 60 seconds

Conncted clients Viewable at test storage location

 https://webhook.site/#!/76119bcd-0837-4937-940a-04b0169c89d0/10a6335d-b8bc-41d2-875e-9507d2c2b265/1
 
## Concept location Tracking service
Conditions of using Test client to Synchronize data to the Backend 
Your Device must have GPS and conencted to the internet"
The application must be open and in focus "
In production this interface will not be visible


## Test Device 
* Tested on Galaxy Tab A 8.0 (2019)
* SM-T295
* Running Android version 9


## The Application will store onto the Backend

- $_Get['lat'] - The Latitude (double)
- $_Get['lon'] - The Longitude (double)
- $_Get['time'] -The date and time (date time) 
- $_Get['uid']-The Unique device id (varchar)
- $_Get['map_url']-The URL to show show the location on google maps (varchar)



![db storage](https://raw.githubusercontent.com/prilcool/Gps-location-tracker-client/master/post_image.PNG)




## Data Return format example
From the data that is stored you can simply query the database and return it in any way you like example :
Note:right now we are using a temporary db coz we dont actually have a server but heres the expected return format

`{\"uid\":\"177efaedx007x\",\"lat\":\"178.100256\",\"lon\":\"-19.096252\",\"time\":\"22-03-2019 13:16:49\"}`




This app is made for the purpouses of demonstration and development of the Contact Tracing concept for Corona Virus in Fiji

Developed by PKSU  if you need any help contact :https://www.linkedin.com/in/prilvesh-k-4349ba54/





Finally this is what the demo app looks like not this is just th synchronization client for the backend  :

![actual client](https://raw.githubusercontent.com/prilcool/Gps-location-tracker-client/master/GPS_Client.jpg)






You can view your individual  location just to see if gps works correct .

![actual client](https://raw.githubusercontent.com/prilcool/Gps-location-tracker-client/master/on_gmap.jpg)







*** The End ***

![Image of Yaktocat](https://octodex.github.com/images/privateinvestocat.jpg)

