# Home Assistant Add-on: Dahua VTO to MQTT Gateway

_Sends Dahua VTO events to the MQTT Gateway._


## About

Using [elad-bar's][original-author] Python code this addon simply connects to your intercom and relays events via your MQTT gateway.


## Source

[![Source][source-shield]][source]


## Installation

The installation of this add-on is straightforward and easy to do.

1. Navigate in your Home Assistant frontend to **Supervisor** -> **Add-on Store**.
2. Add a new repository by URL `https://github.com/Hoellenwesen/ha-addons`
3. Find the "DahuaVTO2MQTT" add-on and click it.
4. Click on the "INSTALL" button.

![Supports aarch64 Architecture][aarch64-shield] ![Supports amd64 Architecture][amd64-shield] ![Supports armhf Architecture][armhf-shield] ![Supports armv7 Architecture][armv7-shield] ![Supports i386 Architecture][i386-shield]


## MGTT Events

[List of available MGTT events](https://gitlab.com/elad.bar/DahuaVTO2MQTT/-/blob/master/MQTTEvents.MD)


## Supported Models

[List of supported Dahua devices](https://gitlab.com/elad.bar/DahuaVTO2MQTT/-/blob/master/SupportedModels.md)


## Known issues and limitations

- None. Let me know.


## Support

In case you've found a bug, please [open an issue on our GitHub][issue].


[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[issue]: https://github.com/Hoellenwesen/ha-addons/issues
[source-shield]: https://img.shields.io/badge/version-master-blue.svg
[source]: https://gitlab.com/elad.bar/DahuaVTO2MQTT
[original-author]: https://gitlab.com/elad.bar
