# (1) Streaming Meetups to IBM Cloudant using Spark
In this notebook we are going to utilize the IBM Apache Spark and IBM Cloudant Bluemix services to process and persist data from the Meetup rsvp stream. On the backend the IBM Apache Spark service will be using the the Spark Kernel. The Spark Kernel provides an interface that allows clients to interact with a Spark Cluster. Clients can send libraries and snippets of code that are interpreted and run against a Spark context. This notebook should be run on IBM Bluemix using the IBM Apache Spark and IBM Cloudant services available in the IBM Bluemix Catalog.
Requirement already satisfied (use --upgrade to upgrade): cloudant in /usr/local/lib/python2.7/dist-packages
Requirement already satisfied (use --upgrade to upgrade): requests-futures==0.9.4 in /usr/local/lib/python2.7/dist-packages (from cloudant)
Requirement already satisfied (use --upgrade to upgrade): requests>=1.2.0 in /usr/lib/python2.7/dist-packages (from requests-futures==0.9.4->cloudant)
Requirement already satisfied (use --upgrade to upgrade): futures>=2.1.3 in /usr/local/lib/python2.7/dist-packages (from requests-futures==0.9.4->cloudant)
Cleaning up...
