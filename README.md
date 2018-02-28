# nifi-storm-topology

Example Storm topology that uses the NiFiStorm spout.

Requires Java, Maven, Storm, and the latest NiFi with an output port "Data for Storm".

To run:
* mvn clean package
* storm jar target/nifi-storm-topology-1.0-SNAPSHOT.jar org.apache.nifi.storm.NiFiStormTopology
