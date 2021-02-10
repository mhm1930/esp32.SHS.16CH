# esp32.SHS.16CH
******Under development******

16 channel controller using esp32 unsing android app.

This code is not yet for use.

it is for testing only.

source code andfull description will be posted once it is completed

the goal of this repository is:

building IOT device with 16 on/off channels with the following features:

1- with 16 inputs for local control.

2- local control over WiFi.

3- remote control over mqtt protocol.

4- resume after power recovery.

5- indication of output status (on android app).

6- simple sharing of control, just share the app & scan QR code.

7- online, offline, within same WiFi indication (on android app).

8- smartconfig for WiFi credential and cloud token.

9- upgrade firmware from github repository, or manually using in app builtin OTA
   firmware upgrade function (in this case it is possible to flash with
   incompatible firmware, be carefull.)
  
10- timers and schedules.

11-when controlling over internet, it is possible to command the device even if it is offline, the device should read the new status when itconnectivity is recovered.

12- when mpre than one android device is usin the app at same time, users should see switches changing position when other user operate them andd se output indicater goes on or off when commands executed by esp32.
there is there is delay in receiving output status from esp32 as the priority is for sending commands.

the current design of PCB will contain 8 5A relays, 4 10A relays and 4 relays 20A
there is possibility to add power monitoring on 20A lines or all 16 lines, the benefits are real monitoring of outputs, troubleshooting hints for load status as well as providing possibilityto switch off output under certain load condition.

I know it will take considerable time to implement all or most of above features, I am working hard to introduce this product ASAP.


I welcome any questions or enquiries 

you can contact me over email: hajooze@gmail.com
or facebook: https://fb.me/smarthomealeppo 


