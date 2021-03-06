# Microservices with SpringBoot
This academic project was made in the context of a practical work about Software Architecture.

## Services
This project contains several services:
1. Product Service: A service containing business logic ([Github Repository](https://github.com/Educational-practice/SpringBoot-microservices))
2. Config Service: The single source of configuration for all microservices ([Github Repository](https://github.com/Educational-practice/Springboot-microservices-config))
3. Proxy Service: Responsible for the routing of requests and load balancing ([Github Repository](https://github.com/Educational-practice/Springboot-microservices-proxy))
4. Discovery Service: A global registry where are all microservices are registered, enabling easy discovery and decoupling ([Github Repository](https://github.com/Educational-practice/SpringBoot-microservices-discovery))

## What I used
- Visual Studio Code (With Java Pack extension and Remote SSH Development)
- Google Colab 
  - Everything was configured remotely on linux through SSH
  - Ports were exposed using SSH Reverse tunneling
  - Intrested? You can check the [python package](https://pypi.org/project/colab-ssh/) I developed to accomplish this.

## Screenshot of the service on Eureka
![Screenshot](docs/screenshot.png)

## With the proxy service
![Screenshot](docs/screenshot2.png)

## With two instances of the service "ProductService"
![Screenshot](docs/screenshot3.png)

## Credits
All the credits goes to Houssem Ben Braiek et Hadhemi Jabnoun, two students at INSAT And Ms. Lilia Sfaxi, a professor at INSAT, who rewrote this detailed [tutorial](https://insatunisia.github.io/TP-eServices/tp4/) from which this work was inspired.
