# TelloKeyboardMatlab
A function to control the tello ryze drone via keyborad from Matlab

The function requires the Ryze Tello Drone Support (https://www.mathworks.com/hardware-support/tello-drone-matlab.html).
First, connect the tello via wifi.
Then run the script TelloKeyboardControl and wait for the stream image. Then you can control the drone via keyboard (type the keys in the video stream) as follow:
Left arrow: fly left 20 cm
Right arrow: fly right 20 cm
Up arrow: fly forward 20 cm
Down arrow: fly backward 20 cm
q: turn counterclockwise 15°
e: turn clockwise 15°
w: fly up 20 cm
s: fly down 20 cm
l: land
You can change the linear and angular displacements by modifying the KeyDetectTello script.
Tips:
Give the instructions slowly, avoid multiple commands in a short period of time because it would crash.
If it crashes, disconnect the wifi to tello red, the drone will land automatically in 10 seconds.
