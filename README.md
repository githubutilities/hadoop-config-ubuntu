# Hadoop multi-node config for ubuntu

# Steps

1. hadoop user
2. SSH
3. config `JAVA_HOME`, `HADOOP_HOME`
4. config `hadoop_env.sh` and `*-site.xml`
5. config master and slaves ip addresses using `/etc/hosts`
6. cleanup original data on each server and format NameNode
7. start the deamons using `start-*.sh`

> NOTICE: 
> * names in `slaves` file should be domain names
> * the domain name must not contain `_`!


# Web Interfaces

* NameNode - http://localhost:50070/
* JobTracker - http://localhost:50030/
* TaskTracker - http://localhost:50060/


# Tutorials

* [single-node](http://www.michael-noll.com/tutorials/running-hadoop-on-ubuntu-linux-single-node-cluster/)
* [multi-node](http://www.michael-noll.com/tutorials/running-hadoop-on-ubuntu-linux-multi-node-cluster/)
* [config file simple description](http://www.cnblogs.com/Richardzhu/p/3579851.html)

# Other Solutions(made by Enterprise)

* [hortonworks](http://hortonworks.com/)
* [cloudera - QuickStarts, Cloudera Manager, Cloudera Director](http://www.cloudera.com/)
