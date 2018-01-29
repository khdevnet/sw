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
  * [Development Flow](https://github.com/khdevnet/warehouse/wiki/Development-Task-Flow)
  * Bug Verification Flow
  
### Frameworks & Architecture Styles
  * [Microservice Architecture](https://martinfowler.com/articles/microservices.html)
  * [OAuth 2.0 Authorization](https://tools.ietf.org/html/rfc6749)
  * [Facebook OAuth](https://github.com/khdevnet/warehouse/wiki/Development-Task-Flow)
  
### Highlevel Application Architecture
  * [General Architecture View](https://github.com/khdevnet/warehouse/wiki/General-Architecture-View)
  * [Frontend Component](https://github.com/khdevnet/warehouse-frontend) - provides UI of application to end users
  * [GraphQL Component](https://github.com/khdevnet/warehouse-graphql) - provides an API to interact with Frontend
  * [Products Component](https://github.com/khdevnet/warehouse-products) - provides an API for Products CRUD operations
  
### Maintenance & Support
  * Infrastructure
  * Deploy Guide
  
### User Documentation
