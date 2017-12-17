## Welcome to John Jenkins's GitHub Page
I have many ongoing and past projects stored in my Github repos. I am using github pages to describe and organize the projects.

### ngArcGauge
ngArcGauge is an angularjs directive that is a [d3.js](https://d3js.org/) arc gauge with alot of custom values. The repo readme.md explains how to setup the project.

[ngArcGaugeRepo](https://github.com/jjenksy/ngArcGauge)

### Eureka Server
The Eureka Server is a Spring Boot application with the Netflix OSS Eureka server implementation. [Netflix Eureka Server](https://github.com/Netflix/eureka). There is an implementation on docker hub for this that can be pulled down but it does not work without configuration. So I rolled my own and plublished to docker hub to get the image run docker pull jjenksy/eureka-server. I reccomend port forwarding 9042 to 9042 then any of your Eureka Clients can get service information from Eureka.
