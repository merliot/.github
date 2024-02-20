# Merliot

Merliot is a distributed, non-centralized IoT platform written in [Go](go.dev) and [TinyGo](tinygo.org).

**Distributed** as in your devices are independent of everyone elses, making the plaform scalable and fault-tolerant.

**Non-centralized** as in there is no central control; each user's devices are user-controlled.  There is no third party between you and your devices.  And no third-party access to your device data.

Scared?  You can try the [Demo](https://www.merliot.io/try-demo).  It's Free to try, but requires an account on [Koyeb](koyeb.com).

Alternatively, you can run the Demo using docker:

```
docker pull ghcr.io/merliot/hub
docker run -p 8000:8000 ghcr.io/merliot/hub
```

Browse to http://\<host\>:8000 to view the hub and configure devices.
