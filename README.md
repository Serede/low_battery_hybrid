low_battery_hybrid
==================

Simple bash script to hybrid-sleep the system based on udev power_supply subsystem. Based on NickHu's low_battery_suspend.

*Usage*

`low_battery_hybrid [1-100]`

Takes a percentage which is compared against the current battery percentage.
If the current battery percentage <= provided percentage, then hybrid-sleep the system.
