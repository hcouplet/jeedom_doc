This plugin allow to link to Chineese kincony.com relay controlers.
Those are cheap ethernet or wifi controler with digital input.
You can see the different model on : https://www.kincony.com/product/relay-controller

Those can be bought easily on aliexpress.

Setup :
Will assign a fix ip to your device or setup a fixed lease in your DHCP server.
First you need to use VirCom tool to setup your device.
1. Choose the IP (fixed or DHCP)
2. Work Mode : TCP Server
3. Choose a port (ie. 4192)
4. Click modify Settings button
5. power cycle the device.

You can check everything is working fine using the KC868Hx-Debug-Client.exe software.
Enter the ip and port and check relays and input are working correctly.

Now you can go into the plugin and add your device.
Enter the ip and port and select the number of relays and input. (this will auto-create commands)
