# Comrade P1 - DIY pedal set controller for simracing

Firmware for microcontrollers based on STM32F103C8

The controller supports 3 12-bit axis (4096 steps)

Use for calibration Comrade Tool - https://github.com/ershov-konst/comrade-tool


Pinout:

                STM32F103C8T6
              -----------------
            - |3VB		 +3.3V| -
            - |C13		   GND| -
            - |C14		   +5V| - 
            - |C15		    B9| -
      AXIS1	- |A0		    B8| -
      AXIS2 - |A1		    B7| -
      AXIS3	- |A2		    B6| -
            - |A3		    B5| -
            - |A4		    B4| -
            - |A5		    B3| -
            - |A6		   A15| -
            - |A7		   A12| -
            - |B0		   A11| -
            - |B1		   A10| - 
            - |B10		    A9| - 
            - |B11		    A8| - 
            - |R		   B15| - 
            - |+3.3V	   B14| - 
            - |GND		   B13| - 
            - |GND		   B12| - 
              ----------------