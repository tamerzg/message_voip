messaging_voip.module
--------------------------------------------------------------------------------
This module provides integration of Voip framework with Messaging API.

--------------------------
Installation

1. Extract messaging_voip to your sites/all/modules directory. Make sure you have installed Voip,Voipnumber and Messaging modules.
2. Enable the messaging_voip module in admin/build/modules.

--------------------------
Usage
1. Go to Messaging settings in admin/messaging/settings
2. Under Default send method you will see 2 new methods which are provided by this module: "Phone call that reads the message text" and 
   "Phone call informing that there's a message"
3. If you select 2nd method be sure to setup "Default Send Method for phone call informing that there's a message", so the full message can be delivered over that
   channel.

Users can set their default methods under their user profile settings.

---
The messaging_voip module has been originally developed by Tamer Zoubi under the sponsorship of the MIT Center for Future Civic Media (http://civic.mit.edu).




