# Rockpro64 setup

## Connect the serial console

Does not work on MacOsX. It's just showing funny characters.
You need to connect through a Linux VM.

No drivers are required on Debian.

Connect to the PI-2-bus :
* GND -> pin#6
* RTX -> pin#8
* TXD -> pin#10

And then :
```
screen /dev/ttyUSB0 1500000
```

## Resources

* https://www.pine64.org/rockpro64/
* https://wiki.pine64.org/index.php/ROCKPro64
* https://wiki.pine64.org/index.php/ROCKPro64#Setup_a_serial_console_.28UART.2a9
* https://forum.pine64.org/showthread.php?tid=6387
