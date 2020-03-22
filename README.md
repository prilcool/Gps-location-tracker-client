# Gps-location-tracker-client for Corona Path Tracking


This app is made for the purpouses of demonstration and development of the Contact Tracing concept for Corona Virus in Fiji.

It's core purpouse is to collect your  location based on your gps and store it into a database .
From which the data can be used for  numerous purpouses by numerous frontends .

This android app records your location every 60 seconds

Your GPS Location is updated into the backend ever 60 seconds .

Conncted clients are Viewable at the following test storage location

 https://webhook.site/#!/76119bcd-0837-4937-940a-04b0169c89d0/10a6335d-b8bc-41d2-875e-9507d2c2b265/1


Developed by PKSU  if you need any help contact :https://www.linkedin.com/in/prilvesh-k-4349ba54/

## Installation Instructions for testers:
* 1 - Download the gps_path_tracing_fj_v1.apk
   
   * https://github.com/prilcool/Gps-location-tracker-client/blob/master/gps_path_tracing_fj_v1.apk
   
* 2 - Install onto your android mobile or table
* 3 - Since its not hosted on google you will need to go to Settings  > Security >Install Unknown Apps.

## Concept location Tracking service
### Conditions of using Test client to Synchronize data to the Backend 

* Your Device must have GPS and conencted to the internet"
* The application must be open and in focus "
* In production this interface will not be visible its only visible since devs would like to test it.


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

<br>




## Data Return format example
From the data that is stored you can simply query the database and return information in numerous formats basically any way you like.

## For example :

`{\"uid\":\"177efaedx007x\",\"lat\":\"178.100256\",\"lon\":\"-19.096252\",\"time\":\"22-03-2019 13:16:49\"}`

### Note:
right now we are using a temporary database.


# Syncing the data to your own server :
If you would like to have the data sync to your own server
 
 * Provide your server url or ipaddress and a enpoint address that will accept the data using the above parameters to author . 


## Data Storage format

![db storage](https://raw.githubusercontent.com/prilcool/Gps-location-tracker-client/master/post_image.PNG)





## On google maps
You can view your individual  location just to see if gps works correct .

![actual client](https://raw.githubusercontent.com/prilcool/Gps-location-tracker-client/master/on_gmap.jpg)





## App View
Finally this is the GPS tracker client view , In case if you wish to preview prior to instal.

![actual client](https://raw.githubusercontent.com/prilcool/Gps-location-tracker-client/master/GPS_Client.jpg)














*** The End ***

![Image of Yaktocat](https://octodex.github.com/images/privateinvestocat.jpg)

