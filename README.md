# sonoff-nodemcu

## Flashing the firmware (https://github.com/espressif/esptool)

```
esptool.py --port <serial-port-of-ESP8266> write_flash -fm qio 0x00000 <nodemcu-firmware>.bin
```

## Loading .lua files to NodeMCU

https://github.com/GeoNomad/LuaLoader

## Building .bin yourself if you dont want to use the one in this repo

https://hub.docker.com/r/marcelstoer/nodemcu-build/
