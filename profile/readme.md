## Merliot: A Private, Non-Centralized IoT Platform

Merliot is an innovative IoT platform designed for privacy, written in [Go](go.dev) and [TinyGo](tinygo.org).

**Non-Centralized Control:** Unlike traditional IoT platforms, Merliot offers a non-centralized approach. Each user maintains control over their devices without any intermediary or third-party access to device data, ensuring privacy.

Curious about Merliot?  Click the button to try the [Merliot Hub](https://github.com/merliot/hub) for Free[^1].

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=docker&image=merliot/hub&name=hub&env[WS_SCHEME]=wss://)

Alternatively, you can try it with using docker:

```
docker pull merliot/hub
docker run -p 80:8000 merliot/hub
```

Browse to http://\<host\> to view the hub and configure devices.

### Supported Targets

Merliot can target several microcontrollers and SBCs:

- [Raspberry PI](https://www.raspberrypi.com/) (not Pico)
- [Arduino Nano rp2040 Connect](https://store-usa.arduino.cc/products/arduino-nano-rp2040-connect)
- [Seeed Wioterminal](https://www.seeedstudio.com/Wio-Terminal-p-4509.html)
- [Adafruit PyPortal](https://www.adafruit.com/product/4116)

### Example Devices

- [Device Hub](https://github.com/merliot/hub)
- [Relay Controller](https://github.com/merliot/relays)
- [Garage Door Opener](https://github.com/merliot/garage)
- [MorningStar Solar Charge Controller](https://github.com/merliot/ps30m) (Modbus)
- [Skeleton Device](https://github.com/merliot/skeleton) (template for new devices)

[^1]: An account is required on [Koyeb](koyeb.com).  Koyeb has a Free tier allowing one free virtual machine.  That's all we need to run Merliot Hub.
