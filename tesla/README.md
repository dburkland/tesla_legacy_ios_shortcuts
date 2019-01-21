README
=========

The Tesla shortcuts were created based on the excellent examples shared by u/jn1cks of reddit.com in this post: https://www.reddit.com/r/teslamotors/comments/ahe5be/i_created_a_siri_shortcut_that_wakes_up_my_tesla/. 

In order to utilize these shortcuts you will need to first import and execute the "Tesla_Generate_Token.shortcut" shortcut in order to generate the authorization token. Once that is complete you can import and execute any of the other Tesla shortcuts.

Tesla iOS Shortcut Inventory:

* Tesla_Generate_Token.shortcut
  * Generates an authorization token from the captured Tesla.com credentials
  * NOTE: This shortcut needs to be executed at least every 45 days since the tokens automatically expire
  * RECOMMENDATION: Set a reminder in your favorite calendaring or task app with "workflow://run-workflow?name=Tesla_Generate_Token" in the notes which is a direct link to the Tesla generate token shortcut
* Tesla_Turn_On_HVAC_Normal.shortcut
  * Wakes the vehicle, turns on the HVAC system, and sets the temperature to 67 degrees Fahrenheit
* Tesla_Turn_On_HVAC_Max.shortcut
  * Wakes the vehicle, turns on the HVAC system, sets the temperature to 82 degrees Fahrenheit, and turns on the driver's seat warmer
* Tesla_Turn_Off_HVAC.shortcut
  * Wakes the vehicle and turns off the HVAC system
* Telsa_Open_Frunk.shortcut
  * Wakes the vehicle and opens the frunk
* Telsa_Open_Trunk.shortcut
  * Wakes the vehicle and opens the trunk

