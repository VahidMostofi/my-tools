## My Tools
A list with brief documentation of the utilities and tools I developed for my personal use. Most of these projects and repos are not clean. Hopefully this could be an attempt to organize them and make the easily reusable in future. 

### Muck Microservice architecture Generator
To generate a system with dynamic number of microservices with any architecture. These repositories are mostly useful for simulation and testings.

It's possible to define a system with any number of microserivces, which anyone could interact with any other (defined in the docker-compose file). Each service is packed in one Docker container and the service specific response times and statistics would be available in Jaeger Open Tracing.

* https://github.com/VahidMostofi/micromuck-nodejs
* https://github.com/VahidMostofi/micromuck-java
* https://github.com/VahidMostofi/micromuck (go)

### Priority Message Queue
An idea to improve total response time by prioritizing slower requests in a system with a central messaging system (RabitMQ).

* https://github.com/VahidMostofi/priority_message_queue

### Jaeger Trace Analyzer
Aggregating and parsing Jaeger traces based on predefined formulas.
* https://github.com/VahidMostofi/jaeger_trace_analyzer

### TCPDUMP Docker Swarm
Docker swarm creates multiple virtual networks, using this tool we can run tcpdump on all of them automatically and get the merged results for further analysis.

* https://github.com/VahidMostofi/jaeger_trace_analyzer

### Bookstore
A simple CRUD microservice application with JWT authentication. Packaged in Docker containers. Easily deployable in Docker-swarm and Kubernetes.

* https://github.com/VahidMostofi/bookstore
