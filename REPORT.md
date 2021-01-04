## Lab6 - Microservices

### Accounts service running on port 2222
![img.png](img.png)

### Web service running on port 3333
![img_1.png](img_1.png)


### Eureka server (registration) running on port 1111 with two services registered

![img_2.png](img_2.png)

### Account microservice running on port 4444
![img_3.png](img_3.png)

### Dashboard with the two services registered
![img_4.png](img_4.png)

### What happens when the microservice running on port 2222 is killed? Can the web service provide information about the accounts and why?
Eureka removes the 2222 accounts service
![img_5.png](img_5.png)

Killing the service has no impact on the user because Eureka redirects to the service hosted on port 4444