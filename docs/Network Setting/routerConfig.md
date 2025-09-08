# Router Configuration

## Router Device Manual

- Model: X32 PRO
- [锐捷星耀系列 无线路由器 一本通 (V1.9).pdf](https://www.ruijie.com.cn/fw/wd/90525/)

## WiFi Settings

- WIFI SSID (2.4GHz): `ISDN2602_2G`
- WIFI SSID (5GHz): `ISDN2602_5G`
- WIFI Password: `isdn2602@iot`

## Admin Control Panel Access

- Connect your device to WiFi. If the above WiFi SSID is not available, you may need to look for the default one that starts with   `@Ruijie-sXXXX` (Or check the bottom label of the router device)
- Open browser and visit `http://192.168.110.1/` to find the admin control panel
- Login in with admin password `isdn2602@admin`



## DHCP

- DHCP starts from `192.168.110.151` with 104 available
- IP Reserved up to `192.168.110.150`

- For this project 
    * IP reserved for tile host is: `192.168.110.100`
    * IP for main 25 final arena tiles are `192.168.110.101 - 192.168.110.125`