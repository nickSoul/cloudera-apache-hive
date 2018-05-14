[toc]
# cloudera-apache-hive
## Objective
 Deploy, Manager and Configure Apache Hive with Cloudera Manager
## Parcel
* Use [apache-hive-2.3.3](http://mirrors.hust.edu.cn/apache/hive/hive-2.3.3/apache-hive-2.3.3-bin.tar.gz) executable binary.
* The define script set HIVE_HOME, HADOOP_HOME to the corresponding parcel root.
## CSD
* Start Script
    * Set HIVE_CONF_DIR to cloudera-scm-agent process' working directory.
    * VM config option
* ConfigWriter
    * Log4j2 Configuration
    * hive-site.xml
## Monitoring
 Base Process Metrics Provided by CDH
## TODO
* Rooling upgrade without downtime(Based on HA)
* Alternative system link
