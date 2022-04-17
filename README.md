# mi600
A bash-script for the solar-inverter bosswerk mi600

This is a simple command-line tool for direct solar data requests from the inverter Bosswerk mi600. It can read the actual solar power and the cumulative daily earned energy.

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

## Use
Start deamon in background:
```
mi600 <hostname | ip> <username> <password> [-t]
```
Option -t: total daily earned energy


https://github.com/dr-ni/mi600
