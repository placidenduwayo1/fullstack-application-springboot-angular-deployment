# Docker images of microservices-base application
This git is containing a **docker-compose.yml** file for deploying in docker images all utility services and all business services:
* utility services:
	 * a database service: ***microservices-db***
	 * a confguration server: ***microservices-config-service***
	 * a service of registration of microservices: ***micoservices-registration-service***
	 * a gateway service between backend and the frontend: ***backend-frontend-gateway-service*** 
 
* business microservices (each business microservice is implemented in clean architecture pattern):

	* a microservice of managing employees's addresses: ***clean-archi-business-service-address***
	* a microservice of managing employees: ***clean-archi-business-service-employee***
	* a microservice of managing projects: ***clean-archi-business-service-project***
	* a microservice of managing companies: ***addressesclean-archi-business-service-company***

The backend(a spring boot microservices-base application) and the frontend (angular application) are located on the following git:
- [spring-project-back and angular-project-front](https://gitea.natan.fr/placidenduwayo/fullstack-application-springboot-angular.git)

## Microservices configuration server
All services (utility services and business services) configiration files for config server are located on the following git:
- [services configuration files](https://github.com/placidenduwayo1/fullstack-application-springboot-angular-config-service.git)
