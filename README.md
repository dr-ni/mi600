# mi600

This is a simple bash command-line tool for direct solar data requests to the Bosswerk inverter MI600. It can read the actual solar power and the cumulative daily earned energy.

## Requirements

- curl must be installed.

## Development


Install:
```sh
sudo make install
```

Uninstall:
```sh
sudo make uninstall
```

## Useage
```
mi600 <hostname | ip> <username> <password> [<type>]
```
## Options
Allowed request <type>:
- webdata_sn
- webdata_msvn
- webdata_ssvn
- webdata_pv_type
- webdata_rate_p
- webdata_now_p
- webdata_today_e
- webdata_total_e
- webdata_alarm
- webdata_utime
- cover_mid
- cover_ver
- cover_wmode
- cover_ap_ssid
- cover_ap_ip
- cover_ap_mac
- cover_sta_ssid
- cover_sta_rssi
- cover_sta_ip
- cover_sta_mac
- status_a
- status_b
- status_c


https://github.com/dr-ni/mi600
