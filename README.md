# javafilterpluginforlogstash
This is a filter plugin in Java meant for doing filtration of input stream data in Logstash.
Typically, in real world scenario there is real time continous stream of events flowing in from source upstream into Kafka --> Logstash --> Elastic Search --> Viewed from Kibana.
To test out adding a simple filter in the logstash *.conf file by which it will filter out input data prior to giving out output.
Logstash does --> INPUT -- FILTER -- OUTPUT.

Please follow the Java Plugin Filter implementation documentation:

https://www.elastic.co/guide/en/logstash/current/java-filter-plugin.html

