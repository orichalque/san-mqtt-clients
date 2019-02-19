# Sensor & Actuator Network MQTT Clients

## Installation

Clone this repository and run `mvn package` at root.

## Usage

Run the jar containing the dependencies using `java -jar mqttClients-$version-jar-with-dependencies.jar`.

```
usage: ./client.jar [-a] [-id <id>] [-p <port>] -s <server> [-S] [-t
       <topic> <QoS>]
 -a,--actuator              The client is an actuator, once started, it is
                            going to idle, waiting for broker's messages.
 -id,--identifier <id>      The client identified.
 -p,--port <port>           Specific port, other than 8883.
 -s,--server <server>       URI of the MQTT broker. Default port: 8883
 -S,--sensor                The client is a sensor, once started, the
                            prompt will ask for messages to send to the
                            broker.
 -t,--topic <topic> <QoS>   Topic to subscribe or publish to, and its QoS.

```

## Examples

