# Stratux - Garmin Pilot edition
This is a modified version of Stratux to better work with Garmin Pilot. This is not intended for general use please see: https://github.com/b3nn0/stratux

See https://github.com/b3nn0/stratux/wiki/Developing-Stratux for dev setup.
You can't upload to GIT from the Stratux so this is what I found that works for me the best:
1. Add a Wifi Card to your Dev PC.
2. Create a WiFi hot spot and connect the stratux to it via AP+Client settings
3. Create a topic branch and just check in there.
4. Use Putty to connect to the Stratux from your Dev PC.
5. You can then pull the code down directly from the topic branch onto the Stratux over Wifi.
6. stxstop && git pull && make && make install && systemctl daemon-reload && stxrestart
