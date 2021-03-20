# analog_digital_RPM_gauge
Arduino based RPM meter with analog and digital presentation with a ST7735 color display

An analogue meter on a 1.8" ST7735 TFT 128 x 160 color screen
The meter graphic function works best with slowly changing values without large rapid changes.

This program is created for the Arduino Nano. This is the demo version as seen on my Youtube channel https://youtu.be/2IAJjNZCXQ0 . In this version the random generator choses the "RPM". To connect this to your vehicle you need to wire it to the Arduino using a 5V zener diode on the input of the Arduino to protect the input. It is even better ( adviced) to use an opto device for counting the pulses. When there are no contact breakers present, it is possible to wrap a wire 6 turns around the ignitioncable of a sparkplug to count pulses ( RPM). Be sure you have a proper protection to avoid dammage of the Arduino inputs.

It is easy to adapt this program to be used as a coolant temperature, voltage or oil pressure meter.
