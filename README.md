# homebridge-gpio-on-switch-bounce

[![Build and Lint](https://github.com/luisgithubbr/homebridge-gpio-on-switch-bounce/actions/workflows/build.yml/badge.svg)](https://github.com/luisgithubbr/homebridge-gpio-on-switch-bounce/actions/workflows/build.yml)

A homebridge plugin for gpio on switch.

## install

Make sure you had installed homebridge first, then run the following command to install `homebridge-gpio-on-switch`.

```
sudo npm install -g homebridge-gpio-on-switch-bounce
```

## config

```json
{
	"accessory": "HomebridgeGpioOnSwitch",
	"name": "switch",
	"pin": 18
}
```
