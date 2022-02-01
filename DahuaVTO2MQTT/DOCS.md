# How to use

To use this add-on, you need to supply the config for your intercom and MQTT gateway

- Requires you to use one of the supported Dahua Intercoms
- Requires you to run a MQTT server


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
