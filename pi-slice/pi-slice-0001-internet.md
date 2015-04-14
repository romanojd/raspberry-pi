# Pi Slice 01:  Connecting to the Internet

There are two ways to connect to the Internet:  wired and wireless.

## Wired

To make a wired connection to the Internet, just connect a home network cable directly to the network port on the Raspberry Pi.  The Raspberry Pi should automatically be assigned an IP address.

## Wireless

You may not have a wired connection available to you at the location where you setup your Raspberry Pi.  In this case, you will need to make a wireless connection.  You need two things to make a wireless connection:  a wireless USB network adapter and a wireless network to connect to.  Perform the following steps to make the connection.

- Begin with the Raspberry Pi turned off.
- Insert the wireless network adapter into one of the Raspberry Pi's USB ports.
- Turn on the Raspberry Pi and begin XWindows (`startx`)
- From the GUI, open the "Wifi Config" tool by selecting "Menu" -> "Preferences" -> "WiFi Configuration"
- Click on the "Scan" button to open the "Scan results" window and click the "Scan" button to find the available wireless networks.
- Double-click on the network you wish to connect to.  The window will open up showing you the connection options.
- You may need to enter a password in the "PSK" field or a key in the "Key" field.
- Click "Add".
- Back on the "Scan results" window, click the "Close" button.
- You can confirm that the Raspberry Pi is connected to the network when an IP address has been assigned.
- Close the WiFi Config tool by clicking the "X" in the upper right corner.
