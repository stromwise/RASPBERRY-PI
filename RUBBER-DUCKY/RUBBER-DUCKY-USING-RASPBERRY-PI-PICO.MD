STEP 1:- open THID GITHUB REPO ( https://github.com/dbisu/pico-ducky )

STEP 2:- CircuitPython for the Raspberry Pi Pico ( https://circuitpython.org/board/raspberry_pi_pico/ )

STEP 3:- connect the raspberry pi pico to the computer while pressing the buttion on the rasberry pi pico.

STEP 4:- Now move the circuit python file in the raspberry pi pico

STEP 5:- now disconnect the raspberry pi pico and reconnect it

STEP 6:- now get back to github and downloawd ( adafruit-circuitpython-bundle-8.x-mpy-YYYYMMDD.zip )( https://github.com/adafruit/Adafruit_CircuitPython_Bundle/releases/tag/20230526 )

STEP 7:- extract the file adafruit**********.zip

STEP 8:- open it and open LIB FOLDER copy/paste the ( adafruit_hid )FOLDER to the raspberry pi pico LIB FOLDER.

STEP 9:- Copy adafruit_debouncer.mpy and adafruit_ticks.mpy to the lib folder on your Raspberry Pi Pico.

STEP 10:- Copy asyncio to the lib folder on your Pico.

STEP 11:- Copy adafruit_wsgi to the lib folder on your Pico.

STEP 12:- Copy boot.py from your clone to the root of your Pico.

STEP 13:- Copy duckyinpython.py, webapp.py, wsgiserver.py to the root folder of the Pico.

STEP 14:- delete the code.py from raspberry pi pico

STEP 15:- rename the duckyinpython.py to code.py

STEP 16:- Find a script here( ) or create your own one using Ducky Script( https://docs.hak5.org/hak5-usb-rubber-ducky/ducky-script-basics/hello-world ) and save it as payload.dd in the Pico. Currently, pico-ducky only supports DuckyScript 1.0, not 3.0.

STEP 17:- after modifieing the script for the ducky just save it as ( PAYLOAD.DD )

STEP 18:- now just copy paste the payload.dd in the raspberry pi pico but wait***********

STEP 19:- as soon as you paste it it will start the code in 5 seconds so for that as soon as you paste it just remove the usb.

STEP #:-########### How to reset the raspberry pi pico to add a new code in it. #####################

STEP 1:- justconnect it while pressing the (BOOTSEL)/BUTTON on the raspberry pi pico and then connect it to the computer it will reset the module.

STEP 2:- then copy/paste FLASH.NUKE ( https://datasheets.raspberrypi.com/soft/flash_nuke.uf2 ) in the raspberry pi pico to flash it

STEP 3:- now you can again do the procedure to run a new script on the module.

STEP #:- Setup mode

To edit the payload, enter setup mode by connecting the pin 1 (GP0) to pin 3 (GND), this will stop the pico-ducky from injecting the payload in your own machine. The easiest way to do so is by using a jumper wire between those pins as seen bellow.

STEP #:- Setup mode with a jumper

please check the images provided

If you need the pico-ducky to not show up as a USB mass storage device for stealth, follow these instructions.

Enter setup mode.

Copy your payload script to the pico-ducky.

Disconnect the pico from your host PC.

Connect a jumper wire between pin 18 (GND) and pin 20 (GPIO15).

This will prevent the pico-ducky from showing up as a USB drive when plugged into the target computer.

Remove the jumper and reconnect to your PC to reprogram.
Pico: The default mode is USB mass storage enabled.

STEP #:- Pico W: The default mode is USB mass storage disabled

PLease check the images provided.

STEP #:- Multiple payloads

Multiple payloads can be stored on the Pico and Pico W.

To select a payload, ground one of these pins:

GP4 - payload.dd

GP5 - payload2.dd

GP10 - payload3.dd

GP11 - payload4.dd

STEP #:- for reference : https://github.com/dbisu/pico-ducky
____________________________________________________________________________________________________________________________________________

▶ Name: StromWise

▶ Role: Creator

▶ Location: Unknown

▶ GitHub: https://github.com/stromwise 

▶ Instagram: https://www.instagram.com/stromwise/ 

▶ Facebook: 

▶ Youtube: https://www.youtube.com/channel/UC-tafc0TqgZNnQio8Gj-hjg 

▶ Twitter: https://twitter.com/StromWise 













____________________________________________________________________________________________________________________________________________
▶ Name: StromWise

▶ Role: Creator

▶ Location: Unknown

▶ GitHub: https://github.com/stromwise 

▶ Instagram: https://www.instagram.com/stromwise/ 

▶ Facebook: https://www.facebook.com/profile.php?id=100093706328777

▶ Youtube: https://www.youtube.com/channel/UC-tafc0TqgZNnQio8Gj-hjg 

▶ Twitter: https://twitter.com/StromWise 
____________________________________________________________________________________________________________________________________________

