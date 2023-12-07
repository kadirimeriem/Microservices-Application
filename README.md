# Microservices-Application
The Discovery Service is a special service. Its role is to establish a directory where all instances of microservices are registered. This allows all microservice instances to locate each other for communication. The most widely used Discovery Service is Netflix's Eureka. Once microservice instances are created and launched, they register themselves in this registry. To call a microservice, you simply need to search in this directory of instances exposed by Eureka through a REST API.
1.	Execute the following four files simultaneously:

         •	client

         •	voiture

         •	Eureka

         •	gateway

2.	Pay close attention to localhost links in each file’s Application Properties. There are nearly three localhost references; ensure consistency for seamless communication between client, voiture, Eureka, and gateway components.
