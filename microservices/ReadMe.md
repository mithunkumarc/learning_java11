spring boot : 2.4.1 : implement  : https://github.com/in28minutes/spring-microservices-v2/tree/main/03.microservices  

spring cloud basics : The Beginner’s Guide To Spring Cloud - Ryan Baxter

      https://www.youtube.com/watch?v=aO3W-lYnw-o


Microservices 
1. architectural style
2. Decomposition of single system into independent running , intercommunicating services.
3. Alternative to monolithic applications
4. has both advantages and disadvantages as do monolithic.



ribbon load balancing: requests among microservice instances  
Eureka: Naming server : registering microservices  
Feign: Easier REST Clients  

visibility and monitering :   
zipkin distributed tracing: tracing request  
netflix api gateway  

fault tolerance : hystrix : if microservice is down : backup plan : message error  


microservice advantages :   
adapt new technology  
dynamic scaling  
faster release cycles  




feign : can be used as restclient : client/consumer side  
ribbon : name(eureka will provide) discovery(helps client to discover service instance) : used for loadbalancing : client /consumer side  
eureka : all apps register in eureka server   
zuul api gateway : common services like authentication, autorization, : intercept all requests  

sleuth : tract request accross different microservices using id, if there is no id, its difficult to debug using logs  
we cant know which request belong to which logs  

learn : https://www.appsdeveloperblog.com/microservices-and-spring-cloud-tutorials-for-beginners/



tools / databases : examples

1. search : elastic search
2. Reivews : mongodb
3. cart : redis
4. shipping : sap
5. customer : relational db
6. payment : upi/paypal/..
