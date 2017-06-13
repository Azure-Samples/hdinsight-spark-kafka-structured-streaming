---
services: hdinsight
platforms: scala
author: blackmist
---

# Use Spark Structured Streaming with Apache Spark and Kafka on HDInsight

This example contains two Jupyter notebooks that demonstrate the following operations:

* Stream-Tweets-To-Kafka.ipynb: Loads tweets from Twitter into a Kafka database.
* Spark-structured-streaming-from-Kafka.ipynb: Uses Structured Streaming to load tweets stored in Kafka.

Note: This example requires Spark 2.1, which is available in HDInsight 3.6. The Spark and Kafka clusters must also be in the same Azure Virtual Network. To create a resource group containing all the services needed for this example, use the resource manager template in the [Use Spark Structured Streaming with Kafka](http://docs.microsoft.com/azure/hdinsight/hdinsight-apache-kafka-spark-structured-streaming) document.

## Stream-Tweets-To-Kafka

This notebook uses DStream, and it only exists as a convenient way to get tweets into Kafka.

## Spark-structured-streaming-from-Kafka

This notebook uses Structured Streaming to load tweets from Kafka and apply a schema onto the JSON data structure. This allows you to select individual fields from the data.

## Contributing

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
