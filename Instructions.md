# Instructions

### 1. Hardware Assembly (scroll down for code setup)

First, follow the wiring diagram to connect wires to the proper pins on the ESP32:

![IMG_3563](./images/IMG_3563.jpeg)![IMG_3562](./images/IMG_3562.jpeg)

Next, link 4 of the wires to the keycaps (wires are specified in wiring diagram). To connect the dupont wires to a keycap, you have to cut off the head of the wire and strip it down so that it can be wrapped around the keycap pin. Then snap your keycaps in place!

![IMG_3567](./images/IMG_3567.jpeg)

Then, link the wires to the display (follow the diagram)!

![IMG_3566](./images/IMG_3566.jpeg)

Finally, screw in the back cover and you're done with the build!

![IMG_3568](./images/IMG_3568.jpeg)

### 2. Software code setup

1. Install the Arduino IDE app [https://www.arduino.cc/en/software/](https://www.arduino.cc/en/software/)
2. Once software is installed, copy and paste the code from the [Weather display sketch](./weather_display_sketch.ino)
3. Replace this with your actual Wifi information  
![image](./images/pasted_20260729-201852.png)
4. Then add in your city  
![image](./images/pasted_20260729-201926.png)
5. Adjust this value to your time zone (calculate from the web)  
![image](./images/pasted_20260729-201940.png)
6. Install the libraries (files are in the libraries folder) by selecting Sketch > Include library > Add .Zip Library  
![image](./images/pasted_20260729-202103.png)
7. Confirm they are uploaded by going to library manager tab (books icon) and select installed libraries in the type section  
![image](./images/pasted_20260729-202214.png)
8. Connect your ESP32 by USB-C and make sure it is selected in the top bar of the app  
![image](./images/pasted_20260729-202245.png)
9. Click this icon to upload the code  
![image](./images/pasted_20260729-202304.png)
10. Finished! Enjoy your weather display!
