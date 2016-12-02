# Replicate Connector for Kafka

Copyright (C) 2016 Dbvisit Software Limited -- Updated 1 December 2016

# 1 Introduction

Replicate Connector for Kafka is a [Kafka Connector](http://kafka.apache.org/090/documentation.html#connect) for loading change records from the REDO logs of an Oracle database, as mined by [Dbvisit Replicate](http://www.dbvisit.com), to Kafka

# 2 Licensing

This software is released under the Apache 2.0 license, a copy of which is located in the LICENSE file.

# 3 Building

You can build the Replicate Connector for Kafka with Maven using the standard lifecycle phases. The Replicate Connector for Kafka requires the [Dbvisit replicate connector library](https://github.com/dbvisitsoftware/replicate-connector-library), build and install it prior to building this connector

```
mvn clean package
```

To build developer documentation run:

```
mvn javadoc:javadoc
```

# 4 Documentation

User documentation for Replicate Connector for Kafka are located [here](http://replicate-connector-for-kafka.readthedocs.io/en/latest/source_connector.html)

# 5 Installation

To install and use the Replicate Connector for Kafka follow the steps outlined in the [quickstart guide](http://replicate-connector-for-kafka.readthedocs.io/en/latest/source_connector.html#quickstart)

# 6 Contributions

Active communities contribute code and we're happy to consider yours. To be involved, please email <a href="mailto:mike.donovan@dbvisit.com">Mike Donovan</a>.
