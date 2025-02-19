# **DIY 3D Space Mouse** <sub>*for OnShape, Fusion 360 and more*</sub>
<img src="Images/Render Cut 2.PNG">
This Input device is made for OneSape.com and Fusion360 but can be adapted to other CAD applications. Current features: Orbit, Pan, Home view and normal/fit view.

[<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/09/YouTube_full-color_icon_%282017%29.svg/159px-YouTube_full-color_icon_%282017%29.svg.png">](https://youtu.be/iHBgNGnTiK4)
⇦Build video from sb-ocr

[<img src="https://yt3.googleusercontent.com/ytc/AOPolaSwBoXviLeQhikQwFOVSZCFjgkQLT0q5EiE85LS4u4=s176-c-k-c0x00ffffff-no-rj">]([https://youtu.be/iHBgNGnTiK4](https://www.instructables.com/DIY-Space-Mouse-for-Fusion-360-Using-Magnets))
⇦Build instructions


## **Fork update:**

I changed the code, so it works in OnShape and similar CAD applications. I used AI to help me, since I do not code usually.

All the Stl and Step files are replaced. I optimized it for 3D printing. 
The mouse can be assembled directly after printing, no support material needed. See Print_All.stl for optimal orientation.
The Base_bottom can be filled after printing no pausing needed. I used plaster to weighten the Base. Steel would be better, lead would be best.


<img src="Images/Polish_20230709_175925855.jpg">

## How to use
Ones connected the knob can be used to pan (aka moveing the object/camera in all directions on the view plane) by tilting the it in the appropriate direction.
By punshing the knob down (lightly), the orbiting mode gets activated (aka rotating the object/camera around the central point).
The buttons are corrently just set to tip a "**n**" or "**f**", but can be changed to every chaine of keyboard or mouse input. [Reference](https://www.arduino.cc/reference/en/language/functions/usb/keyboard/keyboardmodifiers/)

## Libraries needed:
```
TinyUSB_Mouse_and_Keyboard.h
BLE52 Mouse and Keyboard.h
OneButton.h
Tlv493d.h
SimpleKalmanFilter.h
```

