# Ecommerce Application Microservices

Here is the collection of all the microservices I built for an Ecommerce application and their description.

## Product Service

- This is product service, we can add, retrieve, and modify the products based on the need.
- Link to repository [click here](https://github.com/Shubham10845/Prodcut-service)

## User Service 

- This service acts as the user base of the project.
- All the signup, login and logout functionalities are implemented here.
- I have implemented token-based authentication using Spring Security and JWT for authenticating users.
- Link to the repository :- [click here](https://github.com/Shubham10845/user-service)

## Payment Service

- Integrated Stripe payment gateway for payments.
- Link to the repository :- [click here](https://github.com/Shubham10845/payment-service)

## Service Registry

- This acts as a service registry.
- This service maps all the available instances of the registered services, which our API gateway can use to redirect the requests 
  and balance the load.
- Link to the repository :- [click here](https://github.com/Shubham10845/service-registry)

## API Gateway

- Acts as the single entry point for all client requests.
- Routes requests to the appropriate microservices based on URL paths.
- Link to the repository :- [click here](https://github.com/Shubham10845/api-gateway)