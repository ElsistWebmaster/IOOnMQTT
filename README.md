# IOOnMQTT
### An IEC61131-3 program that exchanges data by using the MQTT protocol.
#### A ST IEC61131 program.
This program connects to a free broker, publishes the status of a logical input on the "IOCommand" topic. The program subscribes to the same topic so it receives from the broker the state at each variation, the received state commands a logical output. In this way, the input status is reported to the output by comunicating through the broker. So it realizes an example of data exchange between different systems by using a MQTT protocol.