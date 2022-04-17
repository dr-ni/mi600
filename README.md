# mi600
Direct data access bash-script for the solar-inverter bosswerk mi600

This is a simple tool for direct data access from the solar-inverter bosswerk mi600. It can read the actual solar power and the cummulative earned energy at the actual day.

## Requirements

- The curl package must be installed.

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
