# streamdeckplus
Configuration file for use the ***Stream Deck +*** console with ETC Eos Family consoles.<br>
The file is a starting point for creating your own surfaces depending of your fixtures.<br>
There are two versions, simple and extended.<br>
The simple version use two separate encoders for fine and course.<br>
The extended version gives some tricky fine/course/acceleration modes.
- There is no feedback of values possible
- Click on the Encoder gives you the Home value
- Extended version: Touching on a parameter name (about 1s touch) gives you a yellow frame which indicates special modes
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
- 2.4.0 is now a stable version and supports also loopback live
- On startup you may rescan for devices
