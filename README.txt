messaging_voip.module
--------------------------------------------------------------------------------
This module provides integration of Voip framework with Messaging API.

--------------------------
Installation

1. Extract messaging_voip to your sites/all/modules directory. Make sure you have installed Voip,Voipnumber and Messaging modules.
2. Enable the messaging_voip module in admin/build/modules.

--------------------------
Usage
Go to Messaging settings in admin/messaging/settings


--------------------------
Serve audio from 3rd party

By default audio recordings are copied from 3rd party to local server and served from there. However you can serve audio recordings directly from 3rd party 
server(Twilio) by following this steps:

1. Choose your content type with CallMeField and  go to "display fields".
2. Select "Audio from external URL" as display for your CallMeField.

FileField Sources support

This module also adds new "call me" uploading method for FileField Sources module. Its possible to create one field with multiple uploading choices.
1. Download and install FileField Sources module.
2. Change your CallMe widget to File Upload widget.
3. Under File Sources fieldset you will see various uploading methods (Call Me method is added by this module).
---
The CallMeField module has been originally developed by Tamer Zoubi under the sponsorship of the MIT Center for Future Civic Media (http://civic.mit.edu).




