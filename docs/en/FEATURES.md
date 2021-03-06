Supported Features
------
### Event & Condition
* Date
* Time
* WiFi connection
* Cellular Location (based on base station / cellular tower)
* Power status
* Day of week
* Bluetooth device connected
* Connectivity status
* Headset plugged in/out
* Screen on/off
* Calendar event
* (Geo-)Location
* Battery level

### Event
* *Condition* Event
* Any Broadcast/Intent
* Designated SMSs
* Incoming Notifications
* Timer (Delay a while)
* NFC tag scanned
* TCP communication (one round trip)
* Widget (on launcher / desktop / home screen)

### Condition
* Ringer mode

### Operation
* WiFi switch
* Cellular network switch
* Bluetooth switch
* Auto rotation switch
* Sending Broadcast
* Screen brightness
* Ringer mode
* Execute commands
* Control Hotspot switch
* Enable or disable *account synchronization*
* Send network messages
* Send HTTP messages
* Control media player
* Toggle airplane mode
* Send SMS
* Post Notifications
* Set alarm
* Change Event status
* Control volume
* Launch App
* UI mode (e.g. car mode)
* Play media (e.g. music)

### *Dynamics*
* Dynamics is introduced to replace the old "formatting expression"
* In *Operations*, everything like `<<YOUR_DYNAMICS>>` is seen as the *placeholder* which is used to assign *Dynamics*
* In a *Profile*, all *placeholders* are seen as identical, using the same *Dynamics* assignment (if any)
* If a *placeholder* isn't assigned a *Dynamics*, its string literal will be used
* Currently, *Operations* who supports *Dynamics* is the same as the previous ones supporting "formatting expression". However, in theory and plan, all *Operation* which allows the user to input data will support *Dynamics*
