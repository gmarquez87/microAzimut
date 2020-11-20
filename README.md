# microAzimut

This repository contains the datasets used by the microAzimut technique [1]. The architectural tactics, architectural patterns and frameworks of the datasets are mentioned below:

**Properties**

*Availability*

- High detection of failed host: This property defines the capability of detect failed hosts in order to a load balancer can stop requests to them.

- Intermittently asynchronous data transmission: Communication property where a message sender does not wait for a response.

- Regular snapshots: Property related to recovering the system from planned host maintenance owing to hardware upgrade, soft reboot, among others.

- Efficient duration of timeouts periods: Property that prevents remote procedure calls from waiting indefinitely for a response.

- High isolation: The property where each microservices is its own encapsulated application.

- Effective load balancing: Efficiently distributing incoming network traffic among groups of backend servers.

- Quick broken state recovery: Capability to restart states when they are broken for a more extended period.

- High control of failure propagation: Property which indicates the capability of isolate failures through a good definition of service boundaries.

- High service monitoring visibility: Property that allows visibility into the health of the microservice architecture.

- Periodic heartbeat signal: Property related to the periodic signal to check the status of services.

- Low application restarting: This property refers to the low rate of restart services when a failure occurs.

- Efficient resources consumption: Property related to the impact on the resources consumption (hardware/software) of a system.

*Scalability*

- Effective technical duplication: This property focuses on the need to execute multiple identical copies of an application behind a load balancer, to improve its capacity and availability.

- High functional decomposition: This property focuses on separating services and data along noun or verb boundaries, allowing segmentation of teams and ownership of code and data.

- Effective data partitioning: This property focuses on grouping related items.

*Interoperability*

- High cooperation among components: Capability of exchange information among services and devices (such as sensors).

- High coordinated orchestration among components: This property points to a control mechanism to coordinate, manage and sequence the invocation of particular components (which could be ignorant of each other).

*Security*

- Strong level of individuals, groups, or systems authorization: Capacity of control users to grant them limited access to platforms systems resources without having to expose their credentials.

- High-security authentication: Capacity of verifying the identity of a person, service or device.

- Effective credentials management: Property related to the management of credentials, making them available to less or high privileged users for authentication to other systems without giving them access to the credentials themselves.

- Effective access control: Property that allows verifying if an entity requesting access to a resource has the necessary rights to do so.

**Microservices tactics**:

- Preventing single dependency	
- Set timeouts	
- Providing fallbacks	
- Self-preservation	
- Asynchronous messaging	
- Ping/Echo	
- Monitor	
- Heartbeat	
- Sanity Checking	
- Transactions	
- Removal from Service	
- State Resynchronization	
- Data Store Separation	
- Build Separation	
- Container Deployment	
- Network Location	
- Balancing Scale	
- Self-description	
- Discover Service	
- Orchestrate	
- Tailor Interface	
- Authenticate Actors	
- Identify Actor	
- Authorize Actor	
- Limit Access	
- Limit Exposure

**Microservices patterns**:

- Circuit Breaker
- API Gateway
- Service Registry
- Result Cache
- Monitoring
- Health Check
- Service Discovery
- Messaging
- Page Cache
- Scalable Store
- Key Value Store
- Load Balancer
- Database is the Service
- Container
- Broker
- Authenticator
- Credential
- Authorization

**Frameworks**:

- DynamoDB (https://aws.amazon.com/es/dynamodb/)
- Netflix Nebula (https://github.com/nebula-plugins)
- Guava (https://github.com/google/guava)
- Netflix Eureka (https://github.com/Netflix/eureka)
- Netflix Zuul (https://github.com/Netflix/zuul)
- Netflix Hystrix (https://github.com/Netflix/Hystrix)
- Zipkin (https://zipkin.io)
- RabbitMQ (https://www.rabbitmq.com)
- Docker (https://www.docker.com)
- Kubernetes (https://kubernetes.io/es/)
- Netflix Ribbon (https://github.com/Netflix/ribbon)
- Netflix Turbine (https://github.com/Netflix/Turbine/wiki)
- Swagger (https://swagger.io)
- Redis (https://redis.io)
- Memcached (https://memcached.org)
- Ehcache (https://www.ehcache.org)
- Apache Zookeeper (https://zookeeper.apache.org)
- Nginx (https://www.nginx.com)
- Papertrail (https://www.papertrail.com)
- Netflix Archaius (https://github.com/Netflix/archaius)
- Apache Cassandra (https://cassandra.apache.org)
- MongoDB (https://www.mongodb.com)
- OAuth (https://oauth.net/2/)
- ActiveMQ (http://activemq.apache.org) 
- Mosquitto (https://mosquitto.org)
- Apache Kafka (https://kafka.apache.org)
- Logstach (https://www.elastic.co/logstash)
- Graylog (https://www.graylog.org/blog)
- Telepresence (https://www.telepresence.io)
- Istio (https://istio.io/latest/)
- Kong (https://konghq.com)
- Claudia (https://github.com/claudiajs/claudia)
- Apache OpenWhisk (https://openwhisk.apache.org)
- Prometheus (https://github.com/prometheus)
- MySQL (https://www.mysql.com)
- PostgresSQL (https://www.postgresql.org)

For a more detailed description of each microservices tactics and microservices pattern, please refer to the following references.

**References**

[1]Márquez, G., Lazo, Y., & Astudillo, H. (2020, March). Evaluating Frameworks Assemblies In Microservices-based Systems Using Imperfect Information. In 2020 IEEE International Conference on Software Architecture Companion (ICSA-C) (pp. 250-257). IEEE. [DOI](https://doi.org/10.1109/ICSA-C50368.2020.00049)

[2]Pereira-Vale, A., Márquez, G., Astudillo, H., & Fernandez, E. B. Security Mechanisms Used in Microservices-Based Systems: A Systematic Mapping. In 2019 XLV Latin American Computing Conference (CLEI) (pp. 01-10). IEEE. [DOI](https://doi.org/10.1109/CLEI47609.2019.235060)

[3]Márquez, G., & Astudillo, H. (2019, September). Identifying availability tactics to support security architectural design of microservice-based systems. In Proceedings of the 13th European Conference on Software Architecture-Volume 2 (pp. 123-129). [DOI](https://doi.org/10.1145/3344948.3344996)

[4]Márquez, G., & Astudillo, H. (2018, December). Actual use of architectural patterns in microservices-based open source projects. In 2018 25th Asia-Pacific Software Engineering Conference (APSEC) (pp. 31-40). IEEE. [DOI](https://doi.org/10.1109/APSEC.2018.00017)

[5]Osses, F., Márquez, G., & Astudillo, H. (2018). An exploratory study of academic architectural tactics and patterns in microservices: A systematic literature review. Avances en Ingenieria de Software a Nivel Iberoamericano, CIbSE 2018.

[6]Márquez, G., Villegas, M. M., & Astudillo, H. (2018, September). A pattern language for scalable microservices-based systems. In Proceedings of the 12th European Conference on Software Architecture: Companion Proceedings (pp. 1-7). [DOI](https://doi.org/10.1145/3241403.3241429)

[7]Márquez, G., Villegas, M. M., & Astudillo, H. (2018, November). An empirical study of scalability frameworks in open source microservices-based systems. In 2018 37th International Conference of the Chilean Computer Science Society (SCCC) (pp. 1-8). IEEE. [DOI](https://doi.org/10.1109/SCCC.2018.8705256)

[8]Taibi, D., Lenarduzzi, V., & Pahl, C. (2018). Architectural patterns for microservices: a systematic mapping study. SCITEPRESS. [URI](http://hdl.handle.net/10863/5599)

[9]Bass, L., Clements, P., & Kazman, R. (2013). Software architecture in practice. Addison-Wesley Professional.

