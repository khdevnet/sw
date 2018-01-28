# Warehouse

Designed and created to store information for large e-commerce organization which produce socks for every one.

# Goals

User have to see a list of all the available products in stock. 
We need to be able to see product information (name, price, quantity) in readable form.
User need to have possibility perform search by product name and change the quantity of the product during the replenishment of the assortment. Users must have access to this application after being authenticated.

# Roadmap

* [As a user I want to be able access data in flexible way](https://github.com/khdevnet/warehouse/milestone/1)
* [As a user I want to be able see a list of products](https://github.com/khdevnet/warehouse-products/milestone/1)
* [As a user I want to be able to have access to this application after being authenticated](https://github.com/khdevnet/warehouse/milestone/3)
* [As a user I want to be able to see product information in user friendly way](https://github.com/khdevnet/warehouse/milestone/4)
* [As a user I want to be able host service in kubernetes](https://github.com/khdevnet/warehouse/milestone/5)

# Development
### Process
  * Development Flow
  * Bug Verication Flow
  
### Frameworks & Architecture Styles
  * [Microservice Architecture](https://martinfowler.com/articles/microservices.html)
  * [Onion Architecture](https://dzone.com/articles/onion-architecture-is-interesting)
  * [OAuth 2.0 Authorization](https://tools.ietf.org/html/rfc6749)
  * [EF Code First Migrations](https://msdn.microsoft.com/en-us/library/jj591621(v=vs.113).aspx)
  
### Highlevel Application Architecture
  * [General Architecture View](https://github.com/khdevnet/warehouse-frontend)
  * [Facebook OAuth](https://developers.facebook.com/docs/javascript) - Authorization SDK from Facebook
  * [Frontend Component](https://github.com/khdevnet/warehouse-frontend) - provides UI of application to end users
  * [GraphQL Component](https://github.com/khdevnet/warehouse-graphql) - provides an API to interact with Frontend
  * [Products Component](https://github.com/khdevnet/warehouse-products) - provides an API for Products CRUD operations
  
### Maintenance & Support
  * Infrastructure
  * Deploy Guide
  
### User Documentation
  
![Highlevel Architecture Vision](https://github.com/khdevnet/warehouse/blob/master/docs/HighlevelArchitectureVision.png)

Components

* [Frontend](https://github.com/khdevnet/warehouse-frontend)
* [GraphQL](https://github.com/khdevnet/warehouse-graphql)
* [Products](https://github.com/khdevnet/warehouse-products)
