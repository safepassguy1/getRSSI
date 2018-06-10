# getRSSI
A bash script that will return the RSSI of a wifi source given the SSID

To run run this scrip make sure the following are installed.<br>
iw<br>
grep<br>
egrep<br>

In the following example the wireless device is  wlan0 the SSID is spap2 and the number of samples to take is 10

```bash
safepassguy1@aspergarria:~/getRSSI wlan0 spap2 10
-42.00
-44.00
-44.00
-45.00
-45.00
-45.00
-44.00
-44.00
-44.00
-45.00
```
