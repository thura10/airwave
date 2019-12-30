# airwave
Share Files between iOS and Windows without hassle.

Airwave is a simple electron app to transfer files between iOS and Windows. It is made as simple as I could. It uses node.js, electron, express and multer to handle all this.
[Feel free to donate. I won't cry about it.](https://paypal.me/thurasw)

Download the shortcuts:  


[Send - Over LAN](https://www.icloud.com/shortcuts/e6eba5b155d14377a5382f029d0ad1c1)  
[Receive - Over LAN](https://www.icloud.com/shortcuts/9fda4fe76267411da227c6c711256abf)  
[Send - Using Hotspot](https://www.icloud.com/shortcuts/8503fa691f2f4affbb67e2f705462e87)  
[Receive - Using Hotspot](https://www.icloud.com/shortcuts/35c2c52d681d41c596f5448b1bc1598c)  

# Before you use

1. Every time you update the SSID of Hotspot in config, you must regenerate QR, restart the app and make appropriate changes in the shortcuts.

2. iOS is pretty hesitant to connect to wifi networks without an internet connection so you might wanna go to Control Panel -> Network and Internet -> Network and Sharing Center -> Change adapter settings -> (Your actual Wifi Adapter **not hosted network**) -> Properties -> Sharing -> Allow other network users to connect through ...
This will share the internet from your main WiFi to the hotspot wifi and your phone will connect to the hotspot 2x 3x quicker.

3. This app is made using dark magic and you have to donate before you can use. I know. Very magical. [Here ;)](https://paypal.me/thurasw)

3. On a real note, it's very self-explanatory. Very user-friendly. Just try not to mess up the file format of the config.

To-do:\
Show percentage of file being uploaded\
Authenticate user before accepting uploads\
