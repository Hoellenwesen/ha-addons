# How to use

To use this add-on, you need to supply the config for your intercom and MQTT gateway

- Requires you to use one of the supported Dahua Intercoms
- Requires you to run a local MQTT server


## Configuration

Add-on configuration:

```yaml
vto:
  host: '192.168.1.110'
  ssl: false
  username: 'admin'
  password: 'admin'
mqtt:
  host: core-mosquitto
  port: 1883
  username: 'homeassistant'
  password: 'homeassistant'
  prefix: DahuaVTO
debug: false
```

## Known issues and limitations

- None. Let me know.

## Support

In case you've found a bug, please [open an issue on our GitHub][issue].

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[issue]: https://github.com/troykelly/hassio-addons-dahuavto2mqtt/issues
[source-shield]: https://img.shields.io/badge/version-master-blue.svg
[source]: https://gitlab.com/elad.bar/DahuaVTO2MQTT
[release-shield]: https://img.shields.io/badge/version-v1.0.2-blue.svg
[release]: https://github.com/troykelly/hassio-addons-dahuavto2mqtt/releases/tag/v1.0.2
[original-author]: https://gitlab.com/elad.bar