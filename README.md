# (1) Streaming Meetups to IBM Cloudant using Spark
In this notebook we are going to utilize the IBM Apache Spark and IBM Cloudant Bluemix services to process and persist data from the Meetup rsvp stream. On the backend the IBM Apache Spark service will be using the the Spark Kernel. The Spark Kernel provides an interface that allows clients to interact with a Spark Cluster. Clients can send libraries and snippets of code that are interpreted and run against a Spark context. This notebook should be run on IBM Bluemix using the IBM Apache Spark and IBM Cloudant services available in the IBM Bluemix Catalog.
Requirement already satisfied (use --upgrade to upgrade): cloudant in /usr/local/lib/python2.7/dist-packages
Requirement already satisfied (use --upgrade to upgrade): requests-futures==0.9.4 in /usr/local/lib/python2.7/dist-packages (from cloudant)
Requirement already satisfied (use --upgrade to upgrade): requests>=1.2.0 in /usr/lib/python2.7/dist-packages (from requests-futures==0.9.4->cloudant)
Requirement already satisfied (use --upgrade to upgrade): futures>=2.1.3 in /usr/local/lib/python2.7/dist-packages (from requests-futures==0.9.4->cloudant)
Cleaning up...



{u'compact_running': False,
 u'db_name': u'rita_transtats_2014_06',
 u'disk_format_version': 5,
 u'disk_size': 160707408,
 u'doc_count': 502500,
 u'doc_del_count': 0,
 u'instance_start_time': u'0',
 u'other': {u'data_size': 265247850},
 u'purge_seq': 0,
 u'update_seq': u'502516-g1AAAADveJzLYWBgYMlgTmGQT0lKzi9KdUhJMtJLykxPyilN1UvOyS9NScwr0ctLLckBKmRKZEiy____f1YSA-PrcKJ1JTkAyaR6qMZX84nWmMcCJBkagBRQ736w5mgSNR-AaIbYvDgLACDLUQs'}
From the above, we can see the database contains roughly 500,000 documents. We can grab a couple from the database to inspect locally.
