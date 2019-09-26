README
=========

The Tesla shortcuts were created based on the excellent examples shared by u/jn1cks of reddit.com in this post: https://www.reddit.com/r/teslamotors/comments/ahe5be/i_created_a_siri_shortcut_that_wakes_up_my_tesla/. 

In order to import these shortcuts you will first need to allow the import of untrusted shortcuts. This can be done by completing the steps documented [here](https://9to5mac.com/2019/08/14/allow-untrusted-shortcuts-ios-13/). You can then click on each link below to import the appropriate shortcut. Once each shortcut has been imported into the shortcuts app on your device, you will then need to execute the "Generate Tesla Token" shortcut. This results in the creation of an authenticaiton token that is used to communicate with your car. Once that is complete you can then execute any of the other Tesla shortcuts.

Tesla iOS Shortcut Inventory:

* [Generate Tesla_Token](https://www.icloud.com/shortcuts/5ca9ed690bfd41c69852d899951e86f8)
  * Generates an authorization token from the captured Tesla.com credentials
  * NOTE: This shortcut needs to be executed at least every 45 days since the tokens automatically expire
  * RECOMMENDATION: Set a reminder in your favorite calendaring or task app with the "workflow://run-workflow?name=Generate_Tesla_Token" link in the notes section

* [Open Frunk](https://www.icloud.com/shortcuts/68ce891946494983b30b5ccc73c48923)
  * Wakes the vehicle (if needed) and opens the frunk

* [Open Trunk](https://www.icloud.com/shortcuts/7c0c67e9b90a4236af818db02cd52bc5)
  * Wakes the vehicle (if needed) and opens the trunk

* [Turn On HVAC Normal](https://www.icloud.com/shortcuts/410b810cb84f424f99516d684a1e0c72)
  * Wakes the vehicle (if needed), turns on the HVAC system, and sets the temperature to 67 degrees Fahrenheit

* [Turn On HVAC Max](https://www.icloud.com/shortcuts/17ad7145af9444b5956d0fb9201f7858)
  * Wakes the vehicle (if needed), turns on the HVAC system, sets the temperature to 82 degrees Fahrenheit, and turns on the driver's seat warmer

* [Turn Off HVAC](https://www.icloud.com/shortcuts/2ac891b7092a45c8a4398d336c30ff4b)
  * Wakes the vehicle (if needed) and turns off the HVAC system

* [Lock Doors](https://www.icloud.com/shortcuts/af49a0e013544cee93dd4b67c90f0a26)
  * Wakes the vehicle (if needed) and locks the doors

* [Unlock Doors](https://www.icloud.com/shortcuts/779e75ebadfd42dcb7067d34dc4c5ae2)
  * Wakes the vehicle (if needed) and unlocks the doors

* [Turn On Sentry](https://www.icloud.com/shortcuts/8417c2ef445e4bd289348f5c60b190b8)
  * Wakes the vehicle (if needed) and turns on Sentry Mode

* [Turn Off Sentry](https://www.icloud.com/shortcuts/0f4117588c4b45c6adbdb8050b63abe8)
  * Wakes the vehicle (if needed) and turns off Sentry Mode

* [Set Charge Limit](https://www.icloud.com/shortcuts/01bd25cb38414ba1bf0eccb95e98d6bc)
  * Wakes the vehicle (if needed) and sets the charge limit to the user-selected percentage.

