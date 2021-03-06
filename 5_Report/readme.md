# Abstract:
Windshield wiper control system is a small part of your car, but has a big impact on your driving and overall safety. The basic idealogy of a wiper system is to wipe the droplets of rain, snow, dirt, pollen, frost and other debris quickly and smoothly at the push of a button from the windsheild of the car, this helps you by letting you to concentrate more on driving by clearing out the droplets,snow, dirt and other scums and there by giving you a clear vision of the road from the windshield. The windshield wiper motor moves the windshield wiper arms across the windshield. The metal or hard plastic arms drag a thin rubber blade across the windshield to clear away water, giving you a better view of the road. In this project we consider 3 led's namely Blue, Green, Orange set at different On and Off time frequencies, in such a way that it replicates a Wiper control system. The Red Led indictes the On of Off state of the Push Button. For a given frequency the respective Led glows and goes off once the frequency changes, similar way the other 2 led's glow and turns off during their respective frequencies. The motive is when we press the push button once the Blue led glows for the first time and goes off when the button is pressed again and then Green led glows and turns off when the button is pressed again, this time the Orange led glows and turns off when the button is pressed. Similarly for every press of the push button the Blue, Green and Orange Led's glows and goes off replicating a wiper control system. If you long press and hold the push button for 2 seconds the Red led glows and the system goes to On state and in the sameway the system goes off when you long press the push button for 2 seconds, after the indication of Red led. By this way of using Led's, Push button and Reset Button from STM32F47XX Microcontroller the requied Wiper control system is implemented.

# Requirments: 
Ignition Key Position at ACC: The Red LED is ON, if the user button is pressed and held for 2 secs.
Wiper ON: Wiper is OFF: On press of the user input, Blue, Green and Orange LEDs come ON one at a time with the set frequency, The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz.
Wiper OFF: Wiper is ON: The LED glow pattern stops on the 4th press; the wiper action starts next press onwards as mentioned in step 2.
Ignition Key Position at Lock: The Red LED is OFF, if the user button is pressed and held for 2 secs.


# Design:

![Screenshot 2022-05-14 160100](https://user-images.githubusercontent.com/102800155/168483195-860683c9-49da-41e5-baf9-c10616cc6a81.png)

