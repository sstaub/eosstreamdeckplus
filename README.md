# streamdeckplus
Coniguration file for use the ***Stream Deck +*** console with ETC Eos Family consoles.<br>
The file is a starting point for creating your own surfaces depending of your fixtures.
- There is no feedback of values possible
- Touching on a parameter name (about 1s touch) gives you a yellow frame which indicates special modes
  - Fine mode (16bit parameters)
  - Acceleration mode (8bit parameters) which gives you 4 clicks instead of one

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
