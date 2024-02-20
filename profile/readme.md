### Merliot: A Distributed, Non-Centralized IoT Platform

Merliot is an innovative IoT platform designed for privacy, scalability, and fault tolerance, written in [Go](go.dev) and [TinyGo](tinygo.org).

**Distributed Architecture:** Merliot employs a distributed architecture where each device operates independently, ensuring scalability and fault tolerance.

**Non-Centralized Control:** Unlike traditional IoT platforms, Merliot offers a non-centralized approach. Each user maintains control over their devices without any intermediary or third-party access to device data.

Curious about Merliot? Try the [Demo](https://www.merliot.io/try-demo) for free.  (An account is required on [Koyeb](koyeb.com)).

Alternatively, you can run the Demo using docker:

```
docker pull ghcr.io/merliot/hub
docker run -p 8000:8000 ghcr.io/merliot/hub
```

Browse to http://\<host\>:8000 to view the hub and configure devices.
