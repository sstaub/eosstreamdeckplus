# streamdeckplus
Coniguration file for use the ***Stream Deck +*** console with ETC Eos Family consoles.<br>
The file is a starting point for creating your own surfaces depending of your fixtures.<br>
There are two versions, simple and experimental.<br>
The simple version use two separate encoders for fine and course.<br>
The experimental version gives some tricky fine/course/acceleration modes which didn't work proper in the moment,
cause of a bug with import/export. It can solved if you set the current values of the custom variables to the startup value.
- There is no feedback of values possible
- Click on the Encoder gives you the Home value
- Experimental version: Touching on a parameter name (about 1s touch) gives you a yellow frame which indicates special modes
  - Fine mode (16bit parameters)
  - Acceleration mode (8bit parameters) which gives you 4 clicks instead of one. 
- The custom variable ```$(internal:custom_acceleration)``` allows you the set the clicks acceleration global.

Following preparations are necessary
- You need the new Stream Deck +
- You need to download the latest beta version 2.4.0, installed on your computer http://bitfocus.io
- You need an active network connection because EOS don't provide a loopback adapter
- For WLAN you should give a static address instead of the DHCP address of your router
- It use only the generic OSC module not the EOS module
- You must do the right network configuration

Problems
- It is a beta version
- On startup you may rescan for devices
