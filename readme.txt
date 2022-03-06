Copyright Ryan Stubbs 2022
05/03/22

Reads moisture level using python code and displays in a gauge.

How to interact with the user interface:
 - press the buttons with arrows on to move/turn in the direction shown.
 - press the water switch to activate the water pump; it will turn blue and all other functional buttons will
   disappear.
 - press the water switch again to deactivate the water pump; it will turn blank and all other functional buttons
   will reappear.
 - press the dig/insert moisture sensor button to dig a hole in the soil; all other functional buttons will
   disappear and the moisture sensor buttons and retract button will appear.
 - press the retract button to pull up the moisture sensor and linear actuator; the moisture sensor and retract
   buttons will disappear and other functional buttons will reappear.
 - press the read moisture level button to show the percentage of moisture of the soil.
 - press the seed dispenser button to dispense a seed in the hole you have just dug.
 - press the calibrate seed dispenser buttons to adjust the starting position of the seed dispenser so it is in a
   vertical position.
 - press the shut down button to shut down the raspberry pi; wait until the green light stops flashing then turn 
   off the power pack by pressing the standby button twice; the dashboard will no longer be functional.
 - when the raspberry pi turns off, take a battery out of the battery pack to turn the motor controller off.