pteropus keyboard
=================
![pteropus](https://i.imgur.com/5AACuSX.jpg)
![pteropus](https://i.imgur.com/3FJeGAH.jpg)
Another Miryoku inspired 36-key keyboard.

After seeing the Miryoku layout on the web, I really wanted to try with a 36-key keyboard.

I looked some keyboards, like Iris, Crowboard, Kyria, etc., and I feel that I need to create keyboard geometry that fits my hands.

So I printed those layout and modify them to fit my hands and hopefully it will work.

Features
--------
This keyboard is a non-split linear staggered keyboard, like Crowboard or absolem.

Using a non-split keyboard, I can just use one microcontroller, and it simplify the design.

STM32F072 microcontroller
---------
This microcontroller is a crystal-less USB 2.0 controller, and it is embeded with serial resistors for USB_DP/USB_DM 

and a pull-up resistor for USB_DP, so it reduced the part count and simplify the trace routing.

