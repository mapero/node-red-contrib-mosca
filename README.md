# node-red-contrib-mqtt-broker
MQTT Broker server on Node-RED

Because this MQTT broker is implemented by Node.js, you can test MQTT-in and MQTT-out nodes without MQTT environment like Mosquitto.

## Flows
Once you just put this node on Node-RED and hit deploy button, MQTT Broker will run on your Node-RED.

![flows](https://github.com/zuhito/node-red-contrib-mqtt-broker/raw/master/flows.png)

You need to set "localhost" in MQTT-in and MQTT-out properties as follows.
![flows](https://github.com/zuhito/node-red-contrib-mqtt-broker/raw/master/setting.png)

## Install
Run the following npm command in your Node-RED environment.
```
npm install -g node-red-contrib-mqtt-broker
```

## Original project
To register Node-RED library, README.md was added from [node-red-contrib-mosca](https://github.com/mapero/node-red-contrib-mosca) project. The discussion to decide main stream is welcomed.
