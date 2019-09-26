README
=========

The Tesla shortcuts were created based on the excellent examples shared by u/jn1cks of reddit.com in this post: https://www.reddit.com/r/teslamotors/comments/ahe5be/i_created_a_siri_shortcut_that_wakes_up_my_tesla/. 

In order to import these shortcuts you will first need to allow the import of untrusted shortcuts. This can be done by completing the steps documented [here](https://9to5mac.com/2019/08/14/allow-untrusted-shortcuts-ios-13/). You can then click on each link below to import the appropriate shortcut. Once each shortcut has been imported into the shortcuts app on your device, you will then need to execute the "Generate Tesla Token" shortcut. This results in the creation of an authenticaiton token that is used to communicate with your car. Once that is complete you can then execute any of the other Tesla shortcuts.

Tesla iOS Shortcut Inventory:

* [Generate Tesla_Token](https://www.icloud.com/shortcuts/4851b9fd86444233b9dd91d92c6e1a58)
  * Generates an authorization token from the captured Tesla.com credentials
  * NOTE: This shortcut needs to be executed at least every 45 days since the tokens automatically expire
  * RECOMMENDATION: Set a reminder in your favorite calendaring or task app with the "workflow://run-workflow?name=Generate_Tesla_Token" link in the notes section

* [Open Frunk](https://www.icloud.com/shortcuts/009616fb076841aaa869819bac74e885)
  * Wakes the vehicle (if needed) and opens the frunk

* [Open Trunk](https://www.icloud.com/shortcuts/4c0d15f394624be9ab8fe291244c099c)
  * Wakes the vehicle (if needed) and opens the trunk

* [Turn On HVAC Normal](https://www.icloud.com/shortcuts/0da8c0e16545408cb6d4ab970c0b5f68)
  * Wakes the vehicle (if needed), turns on the HVAC system, and sets the temperature to 67 degrees Fahrenheit

* [Turn On HVAC Max](https://www.icloud.com/shortcuts/61f04a4485d043b9ad5c230acc348052)
  * Wakes the vehicle (if needed), turns on the HVAC system, sets the temperature to 82 degrees Fahrenheit, and turns on the driver's seat warmer

* [Turn Off HVAC](https://www.icloud.com/shortcuts/85a4db8b1b3d417cb5db5bef9d8bc331)
  * Wakes the vehicle (if needed) and turns off the HVAC system

* [Lock Doors](https://www.icloud.com/shortcuts/da6e4ae667514cb3b6a79acfc86e5826)
  * Wakes the vehicle (if needed) and locks the doors

* [Unlock Doors](https://www.icloud.com/shortcuts/360e7c9d93b747aa8918127388a15860)
  * Wakes the vehicle (if needed) and unlocks the doors

* [Turn On Sentry](https://www.icloud.com/shortcuts/a349d906e8ba420d96e72ef9c0584565)
  * Wakes the vehicle (if needed) and turns on Sentry Mode

* [Turn Off Sentry](https://www.icloud.com/shortcuts/32a1eebdf9504206ac07367a34ffd67c)
  * Wakes the vehicle (if needed) and turns off Sentry Mode

* [Set Charge Limit](https://www.icloud.com/shortcuts/c0f4bca934b748419d4703ef3be0c347)
  * Wakes the vehicle (if needed) and sets the charge limit to the user-selected percentage.

