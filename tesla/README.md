README
=========

The Tesla shortcuts were created based on the excellent examples shared by u/jn1cks of reddit.com in this post: https://www.reddit.com/r/teslamotors/comments/ahe5be/i_created_a_siri_shortcut_that_wakes_up_my_tesla/. 

In order to utilize these shortcuts you will need to first import and execute the "Generate_Tesla_Token.shortcut" shortcut in order to generate the authorization token. Once that is complete you can import and execute any of the other Tesla shortcuts.

Tesla iOS Shortcut Inventory:

* Generate_Tesla_Token.shortcut
  * Generates an authorization token from the captured Tesla.com credentials
  * NOTE: This shortcut needs to be executed at least every 45 days since the tokens automatically expire
  * RECOMMENDATION: Set a reminder in your favorite calendaring or task app with the "workflow://run-workflow?name=Generate_Tesla_Token" link in the notes section

* Open_Frunk.shortcut
  * Wakes the vehicle (if needed) and opens the frunk

* Open_Trunk.shortcut
  * Wakes the vehicle (if needed) and opens the trunk

* Turn_On_HVAC_Normal.shortcut
  * Wakes the vehicle (if needed), turns on the HVAC system, and sets the temperature to 67 degrees Fahrenheit

* Turn_On_HVAC_Max.shortcut
  * Wakes the vehicle (if needed), turns on the HVAC system, sets the temperature to 82 degrees Fahrenheit, and turns on the driver's seat warmer

* Turn_Off_HVAC.shortcut
  * Wakes the vehicle (if needed) and turns off the HVAC system

* Turn_On_Sentry.shortcut
  * Wakes the vehicle (if needed) and turns on Sentry Mode

* Turn_Off_Sentry.shortcut
  * Wakes the vehicle (if needed) and turns off Sentry Mode

* Set_Charge_Limit.shortcut
  * Wakes the vehicle (if needed) and sets the charge limit to the user-selected percentage.

