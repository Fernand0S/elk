# ELK - Elasticsearch, Logstash and Kibana

This is stack ELK running with docker swarm for environment Test, Develop and Production. 

What is the ELK stack?
The ELK stack is an acronym used to describe a stack made up of three popular projects: Elasticsearch, Logstash, and Kibana. Often referred to as Elasticsearch, the ELK stack gives you the ability to aggregate logs from all your systems and applications, analyze those logs, and create visualizations for application and infrastructure monitoring, faster troubleshooting, security analysis, and more.

E = Elasticsearch
Elasticsearch is a distributed search and analytics engine built on top of Apache Lucene. Support for multiple languages ​​and high-performance, schema-less JSON documents makes Elasticsearch an ideal choice for multiple search and log analysis use cases.

L = Logstash
Logstash is an open-source data ingestion tool that allows you to collect data from various sources, transform it, and send it to the desired destination. With pre-built filters and support for 200+ plugins, Logstash allows users to easily ingest data regardless of the source or data type.

K = Kibana
Kibana is a data visualization and exploration tool used for logging and time series analysis, application monitoring, and operational intelligence use cases. It offers powerful and easy-to-use features such as histograms, line charts, pie charts, heatmaps, and built-in geospatial support. Additionally, it provides tight integration with Elasticsearch, a popular search and analytics engine, which makes Kibana the default choice for visualizing data stored in Elasticsearch.

Reset password users stack, access container execute command above:

Example: docker exec -it id.container /bin/bash

- elasticsearch-reset-password --username elastic
- elasticsearch-reset-password --username kibana_system
- elasticsearch-reset-password --username logstash_admin_user

"![1_vZDu4Bwj2GxQh8t1IjDq4w](https://github.com/Fernand0S/elk/assets/32446123/9b7b134d-b81d-41a0-895a-787216d992c3)"

- Elasticsearch - Tools for index 
- Logstash - Tools for collect logs
- Kibana - Visualize and Dashboard Web
