# AsyncAPI plugin for Node-RED

A plugin for generating and configuring nodes for Kafka, MQTT, AMQP, etc. automatically from an AsyncAPI specification.

- [Introduction](#introduction)
- [How to install](#how-to-install)

---

## Introduction

Screenshot of current code:

![screenshot](/images/screenshot.png)

Quick demo recording:

[![demo](https://img.youtube.com/vi/3B4O10V2PA0/0.jpg)](https://www.youtube.com/watch?v=3B4O10V2PA0 "demo")

## How to install

### Installing Node-RED

Plugin support is currently only available in the beta version of Node-RED. If you don't want to wait until it's added to the main release, you can install the beta using:

```
npm install node-red@next
```

### Installing the AsyncAPI plugin

Run the following npm command in your Node-RED user directory (e.g. `~/.node-red`):

```
npm install node-red-contrib-plugin-asyncapi
```

Then restart Node-RED
