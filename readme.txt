application-server1.yml与application-server2.yml实现eurekaserver集群；
    (java -jar eurekaserver-0.0.1-SNAPSHOT.jar --spring.profiles.active=server1;)
    (java -jar eurekaserver-0.0.1-SNAPSHOT.jar --spring.profiles.active=server2;)
在eurekaclent中添加服务地址；