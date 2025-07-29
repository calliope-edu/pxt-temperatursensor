You will find the English ReadMe at the end of the document.

# DS18B20 Temperatursensor für Calliope mini

## Inhaltsverzeichnis

* [Zusammenfassung](#zusammenfassung)
* [Blöcke](#blöcke)
* [Beispiel](#beispiel)
* [Lizenz](#lizenz)

## Zusammenfassung
DS18B20-Modul, unterstützt die Steuerung über einen 1-Draht-Bus und liest die Temperatur aus.

## Blöcke
### Temperatur auslesen, Rückgabe als Zahl. MakeCode unterstützt keine Fließkommazahlen, daher wird der Wert um das 100-fache verstärkt.
![image](https://github.com/DFRobot/pxt-ds18b20/blob/master/image/number.png)<br>

### Temperatur auslesen, Rückgabe als Zeichenkette (String).
![image](https://github.com/DFRobot/pxt-ds18b20/blob/master/image/string.png)<br>

## Beispiel
Beispiel in JavaScript
```
basic.forever(() => {
serial.writeValue("temp ", DS18B20.Temperature_number(DS18B20.pin.pin0))
basic.pause(1000)
serial.writeLine("temp : " + DS18B20.Temperature_string(DS18B20.pin.pin0))
basic.pause(1000)
})
```
## Lizenz

MIT

Geforkt von https://github.com/mengbishu/pxt-ds18b20


## Supported targets

* for PXT/calliopemini




# DS18B20 Temperature Sensor for Calliope mini 
Forked from https://github.com/mengbishu/pxt-ds18b20

## Table of Contents

* [Summary](#summary)
* [Blocks](#blocks)
* [Example](#example)
* [License](#license)

## Summary
DS18B20 module, support single bus control, and read temperature.

## Blocks
### Read temperature, return a number, makecode do not support floats, so the value is amplifies up to 100 times.
![image](https://github.com/DFRobot/pxt-ds18b20/blob/master/image/number.png)<br>

### Read temperature, return a string.
![image](https://github.com/DFRobot/pxt-ds18b20/blob/master/image/string.png)<br>

## Example
Example for JavaScript
```
basic.forever(() => {
    serial.writeValue("temp ", DS18B20.Temperature_number(DS18B20.pin.pin0))
    basic.pause(1000)
    serial.writeLine("temp : " + DS18B20.Temperature_string(DS18B20.pin.pin0))
    basic.pause(1000)
})
```

## License

MIT


## Supported targets

* for PXT/calliopemini



