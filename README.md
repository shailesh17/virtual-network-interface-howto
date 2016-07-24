# virtual-network-interface-howto

## OSX
### Configuring a static Virtual IP for your machine on your network
In this section, we'll setup a new virtual interface on your machine so other devices or your LAN router on your network can then be configured to use this as first DNS responder

  1. Go to *System Preferences > Network*
  2. Click the plus *+* sign on the bottom left
  3. Select Interface: *Wi-FI*
  4. Set Service Name to something like *My Virtual Wi-Fi*
  5. Select this new Interface and click *Advanced...* on the right pane.
  6. Go to the *TCP/IP* tab and set *Configure IPv4:* to *Using DHCP with manual address*
  5. Enter your desired IP address in the *IPv4 Address:* field. For example use: `10.10.10.101`
  6. Unless you need IPv6, set it to *Off*
  7. Click *Ok* then *Apply*
  8. Now you should see the interface connected, with message: `My Virtual Wi-FI is connected to <SSID> and has the IP address 10.10.10.101.`


## Linux
See https://help.ubuntu.com/lts/serverguide/network-configuration.html
