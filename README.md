pi-boy
======

##Description
A mimic of the Pip-Boy 3000 from "Fallout: New Vegas" intended for the Raspberry Pi or any other portable linux device. Because this is meant to be the main UI for an entire system, this project may be very dependant on system setup (and hardware for some features, e.g. the planned radio). I will try to modularize as much as possible, so that any unwanted features may be compiled out or replaced easily.
###Window Tree
The Pip-Boy has 3 tabs, each with 5 separate windows.

1. `Stats` - Settings and device information
  1. `Status`- Hardware info **TODO**
    * `SYS` - CPU, RAM, and process information.
    * `BAT` - (if available) Battery information (as Geiger Counter)
    * `HDD` - Filesystem information
  2. `L.A.N./W.A.N.` -  connect to networks via wireless **TODO** 
  3. ``
  4. ``
  5. ``
2. `Items`
  1. ``
  2. ``
  3. ``
  4. ``
  5. ``
3. `Data` - All actual functionality
  1. ``
  2. ``
  3. ``
  4. ``
  5. ``

##Installation
###Dependencies
```
libmpdclient (mpd)
SDL 2
libconfig
```

###Building
**TODO**

##Configuration
**TODO**
