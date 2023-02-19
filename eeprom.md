SPD EEPROM Tool
===============

A simple command line tool for reading and writing AT24/EE1004 DDR4 SPD EEPROMs.

AUR: [spd-eeprom](https://aur.archlinux.org/packages/spd-eeprom)

## Dependencies

```
python3
```

## Usage

### List used DIMM slots

```
sudo ./eeprom.py -l
```

### Read data from SPD EEPROM

```
sudo ./eeprom.py -r -d DIMM -f FILE
```

### Write data to SPD EEPROM

```
sudo ./eeprom.py -w -d DIMM -f FILE
```
