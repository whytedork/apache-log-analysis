## create a log analysis system for apache web server using elk stack
+ launch ELK Stack (ElasticSearch, Logstash, Kibana) on the top of Docker in same network
+ give the input from log file
+ create a logstash configuration file using grok filter for extracting the data from log file
+ use COMBINEDAPACHELOG pattern for data extraction
+ tranfer the extracted data to elasticsearch(for output)
+ use kibana for log analysis and creating visuals
+ in kibana there are many filters and bucket available ,so we can easily analyse data using them
+ we can also create real time log monitoring system if we give input from apache log file (/var/log/apache2/access.log)
+ in this file as soon as any one hit on your website/server log will be update.
