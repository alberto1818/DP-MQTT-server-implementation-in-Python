# DP-MQTT-server-implementation-in-Python

## Overview

Publish / Subscribe model communication between broker and one or more clients where a message **published** to a certain _topic_ will be delivered to every client that is **subscribed** to that _topic_

The actions which are used in the MQTT protocol is publishing and subscribing of messages. It is the main core of the our broker.  Server is responsible for receiving messages from IoT devices and sending them back to the message subscribers. The system we gonna build gonna  inherit Netty's easy-to-use, simple, high-performative and safe features, as well as fast development. 
 We are going to provide real-time and reliable messaging by our service to other devices, while only trying  to minimise code and bandwidth. It is suitable for devices with limited hardware resources and the network environment with limited bandwidth. 


## Requirements

```
pip install paho-mqtt
```

## Implementation

Python, paho

## Architecture

python, paho

## Design Patterns

Adapter, Observer, Factory Method
