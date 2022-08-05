# Moving-robot-arm-using-S2T

This repository is about using web serial Api to move a robot arm using esp32.
It works as Follow:

first in the HTML website we have added the WebSerial Api and attached it to the button "connect". when its clicked , it prompts the user to select a serial device (such as our ESP32).

Then when it is connected, it opens a serial port to read and write data from and to the device. When the user speechs a certain word such as "right" the api will store it in a variable named "Right" otherwise will ignore it.

After that in our Arduino Ide we will open the same port and add the required codes to which will take our variable such as "Right" and then move the arm accordingly.

This is how a popup window shows up asking the user to select a serial device

![‪H-Voice To Text Convert! - Google Chrome‬ 1444-01-07 03-16-43_Moment](https://user-images.githubusercontent.com/107868812/182976379-adb30e21-fb0f-4d08-aa0f-fead90513cd8.jpg)

![‪H-Voice To Text Convert! - Google Chrome‬ 07_01_44 03_16_52 ص](https://user-images.githubusercontent.com/107868812/182976385-4e2f8116-6717-460f-8477-253c81c3f60a.png)


![photo_2022-08-05_03-14-06](https://user-images.githubusercontent.com/107868812/182975997-32eeb72d-1c3e-453a-b730-76ddb50c83d3.jpg)
