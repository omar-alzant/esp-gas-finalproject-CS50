# esp-gas-finalproject-CS50
Send the level of gas sensor form esp  to G-sheet &amp; website (or IP) using IFTTT. 


***************************************
                                                  *Step of project*

* 1.Make the electronic circuit:
  * 1.1-Esp8266 NodeMCU. 
  * 1.2-MQ135- CO / CO2 gas sensor-.
  * 1.3-Source of WIFI - Like router || hotspot...
  
* 2.Create a verified Gmail.

* 3.SignUp to (( IFTTT )) from this Gmail.
  * 3.1.After SignUp, create a new applet;
  * 3.2.(If This ) is the esp-wifi- >>> connect to WebHooks.
    * 3.2.1.Set the name you need (event).
  * 3.3.(Then That) is the spreadSheet you want to receive on it.
    * 3.3.1.value1/value2/value3-Occ.. you need to use those JSON variable
          i.g.: value1 = ip of esp // value2 = CO level // value3 = CO2 level
  * 3.4.Check the applet, a new automaticly sheet and file maked?!! ... the code is valid.
  * 3.5.make notice  you want to copy the serial code of your applet (sheet >> setting >> 
         copy *bvOlufPzUDPs4J62Tb--nJ* >>    paste to MakerIFTTT_Key in arduino code ). 
         
* 4.programming a html/css/JS for webSite (i.g.: using VSCode)  
  * 4.1.This web site contain :
    *   4.1.1.Send data from esp to sheet-- IFTTT--. -using arcuino code-
    *   4.1.2.Get the uploaded data in sheet and make it in a table form-. -using XML ajax-
    *   4.1.3.Enter the esp Upload's delay.-using ESPWebServer library for arduino IDE-
    *   4.1.4.Enter the refresh page delay. -using jQuery-$- & window.refresh... -
    *   4.1.5.Change the row's color to red for the under-NormalLevel (Dangerouse) -using the condition #if-
  * 4.2.mini the html code, to put-it into the arduino code. 
  
     
*********************************************
                                                          *Some link*

 * ESP8266 : https://www.instructables.com/NodeMCU-ESP8266-Details-and-Pinout/
 * MQ135 : https://www.waveshare.com/wiki/MQ-135_Gas_Sensor
 * to minimize code :  http://www.tomeko.net/online_tools/cpp_text_escape.php?lang=en  
                      https://www.willpeavy.com/tools/minifier/
 * Program-Ard-IDE: https://www.arduino.cc/en/software
 * ESP library for arduino IDE :  https://randomnerdtutorials.com/how-to-install-esp8266-board-arduino-ide/

                    
********************************************************
                                            Electronic circuit
                                            
![esp](https://user-images.githubusercontent.com/70784310/143145099-bc54701d-df0b-4cc1-b7ac-f65d284a19e0.PNG)

                                            MQ135 kind of sensor
                                            
 ![mq-sensors](https://user-images.githubusercontent.com/70784310/143145389-b3dfe79a-ff11-4ff4-a491-b05dd2cd3234.jpg)
                                           
                                            
                                            Result
                                            
![excel](https://user-images.githubusercontent.com/70784310/143145292-5ed73d22-b584-4c3e-9fdc-5c55a63cee47.PNG)


***********************************

![data-page](https://user-images.githubusercontent.com/70784310/143145465-fd6d936c-11b8-4a5b-a533-010c1a0576e0.PNG)

