## Merliot: A Distributed, Non-Centralized IoT Platform

Merliot is an innovative IoT platform designed for privacy, scalability, and fault tolerance, written in [Go](go.dev) and [TinyGo](tinygo.org).

**Distributed Architecture:** Merliot employs a distributed architecture where each device operates independently, ensuring scalability and fault tolerance.

**Non-Centralized Control:** Unlike traditional IoT platforms, Merliot offers a non-centralized approach. Each user maintains control over their devices without any intermediary or third-party access to device data, ensuring privacy.

Curious about Merliot? Try the [demo](https://www.merliot.io/try-the-demo) for free[^1].  The demo runs a Merliot [hub](https://github.com/merliot/hub) on the Internet.

Alternatively, you can run the demo using docker:

```
docker pull ghcr.io/merliot/hub
docker run -p 8000:8000 ghcr.io/merliot/hub
```

Browse to http://\<host\>:8000 to view the hub and configure devices.

### Supported Targets

Merliot can target microcontrollers or SBCs:

- [Arduino Nano rp2040 Connect](https://store-usa.arduino.cc/products/arduino-nano-rp2040-connect)
- [Seeed Wioterminal](https://www.seeedstudio.com/Wio-Terminal-p-4509.html)
- [Adafruit PyPortal](https://www.adafruit.com/product/4116)
- [Raspberry PI](https://www.raspberrypi.com/) (not Pico)

### Example Devices

- [Device Hub](https://github.com/merliot/hub)
- [Relay Controller](https://github.com/merliot/relays)
- [Garage Door Opener](https://github.com/merliot/garage)
- [MorningStar Solar Charge Controller](https://github.com/merliot/ps30m)
- [Skeleton Device](https://github.com/merliot/skeleton) (template for new devices)

### Learn More

#### Running
- Run on Docker
- Run on Koyeb
- Run from Source

#### Architecture
- Security



[^1]: An account is required on [Koyeb](koyeb.com).
