SmartThings Door Chime
======================

Things needed:

  * Arduino Uno
  * SmarThings Shield
  * Peizo Buzzer

Setup
-----

  * Attach the shield to the Arduino. Then attach the red wire of the buzzer to pin 13 and the black to the ground.
  * Add the Shield to your Hub.
  * Change the Device Type to: `On/Off Shield`

Arduio Code
-----------

  * Download and install the SmartThings Arduino library
  * Compile my `doorchime.ino` file and flash your Arduino

SmartApp
--------

  * Publish my SmartApp `doorchime.groovy`for yourself.
  * Install that on your hub
  * Select the doors/windows (any open/close sensors)
  * Select the Arduino Device (should show up as an Outlet/Switch)

Now open a door/window and it should beep.


