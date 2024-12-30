---
date: 2023-12-15T09:17
draft: false
title: Zigbee
tags:
    - zigbee
    - network
---
> Zigbee is a wireless communication protocol designed for personal area networks and well suited to home automation. It uses a low power, and low bandwidth, mesh network that allows devices that aren’t within direct range of each other to communicate indirectly, via other nodes. Many devices that are permanently powered (not battery powered) will help build the mesh (known as routers), though not all will do this (light bulbs particularly are unlikely to be a router). If you don’t have enough routers, or you locate these poorly, your mesh will be unreliable.

<small>[Tinkerer’s blog](https://blog.ceard.tech/2019/11/zigbee-and-home-assistant)</small>

We can have Zigbee devices interconnected using any compatible specific Zigbee coordinator for these software programs:
- [Zigbee Home Automation (ZHA)](zigbee-home-automation.md) which is more straightforward to implement, basically plug and play,
- Or [Zigbee2MQTT](zigbee2mqtt.md) for a wider array of devices but more technical to implement.

Both are compatible with the now modern Zigbee 3.0 connections.