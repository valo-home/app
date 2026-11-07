# Valo app

The mobile app for [Valo](https://github.com/valo-home/valo), the open source local smart home hub for Zigbee, MQTT and IP cameras.

> **The work has not started yet.** Valo itself is in early development, before beta. This repository holds the plan and collects ideas.

## Until then

The web interface of the hub is made for phones. Open the address of your Valo in the phone browser and add it to the home screen. Dashboards, devices, cameras with live video, automations and the assistant all work there.

![Valo web interface on a phone: dashboard, camera, device and automation](https://raw.githubusercontent.com/valo-home/valo/main/assets/screenshots/phones.webp)

## Planned

- connection to the hub in the home network, and from outside through a TLS proxy or a tunnel
- dashboards, device control and scenes
- camera video, clips and snapshots
- push notifications for alarms, leaks and camera events, as an alternative to Telegram
- several homes in one app

The app will talk to the same REST API and Socket.IO events as the web interface, no cloud service in between.

## Get involved

Ideas, platform choices and help are welcome in the [issues](https://github.com/valo-home/app/issues). If you build something on the Valo API in the meantime, tell us about it.

## License

Apache License 2.0
