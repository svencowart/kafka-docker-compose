# Single Node with Dev Tools
A single node Kafka Cluster with select UI tools designed for development purposes.

## How to enable external clients to connect
If you are trying to connect a client that is outside of this docker network to the broker on this Kafka cluster, then edit your machine's `/etc/hosts` file.  Add the following line to the end of the hosts file `127.0.0.1       broker`.