# wiz_light
A WiZ Light integration for Home Assistant.

Working features 
 - Brigtness
 - Color (RGB)
 - White Color Temprature
 - On/Off

 Next up:
  - Some improvements and bugfixes to create a more stable integration
  - testing with other hardware -- **Contribution required !!**


## Install for testing 
If you want to try the integration please clone this repo to `<confdir>/custom_components/`.

Run `git clone https://github.com/sbidy/wiz_light` within the `<confdir>/custom_components/`.

You also have to install the `pip install pywizlight` package.

## HA config
To enable the platform integration add 
```
light:
  - platform: wiz_light
    name: <Name of the device>
    ip: <IP of the bulb>
```
