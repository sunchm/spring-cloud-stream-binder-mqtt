== spring-cloud-stream-binder-mqtt
Mqtt binder for spring cloud stream 

=== Usage

//TODO; Don't know how to push my code to maven repository LOL

=== Configuration Options

This section contains the configuration options used by the Apache Kafka binder.

For common configuration options and properties pertaining to binder, see the <<binding-properties,core documentation>>.

spring.cloud.stream.mqtt.binder.url::
location of the mqtt broker(s) (comma-delimited list)
+
Default: `tcp://localhost:1883`.
spring.cloud.stream.mqtt.binder.username::
the username to use when connecting to the broker
+
Default: `guest`.
spring.cloud.stream.mqtt.binder.password::
the password to use when connecting to the broker
+
Default: `guest`.
spring.cloud.stream.mqtt.binder.cleanSession::
whether the client and server should remember state across restarts and reconnects
+
Default: `true`.
spring.cloud.stream.mqtt.binder.connectionTimeout::
the connection timeout in seconds
+
Default: `30`.
spring.cloud.stream.mqtt.binder.keepAliveInterval::
the ping interval in seconds
+
Default: `60`.
spring.cloud.stream.mqtt.binder.persistence::
memory' or 'file'
+
Default: `true`.
spring.cloud.stream.mqtt.binder.persistenceDirectory::
Persistence directory+
Default: `/tmp/paho`.

//TODO update bindings configuration properties
