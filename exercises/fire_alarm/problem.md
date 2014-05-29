__Build a "fire alarm" that sounds when the air temperature is more than 50°C.__

* Attach a temperature sensor TMP36 to **A0**
* Attach a piezo to pin **9**
* Attach an LED to pin **13**
* Attach a button to pin **5**
* When the temperature sensor detects a temperature above 50°C the following should happen:
    * The piezo should sound
    * The LED should flash on and off continuously
* If the temperature drops below 50°C the piezo and LED should switch off
* If the button is pressed the following should happen
    * Piezo and LED should turn off
    * Piezo and LED should not turn on again unless the temperature drops below 50°C

## Docs

- LED - https://github.com/rwaldron/johnny-five/wiki/Led
- Piezo - https://github.com/rwaldron/johnny-five/blob/master/docs/piezo.md
- TMP36 - https://github.com/rwaldron/johnny-five/blob/master/docs/sensor-temperature-tmp36.md
- Button - https://github.com/rwaldron/johnny-five/wiki/Button#usage