# Star Wars Shop
Designed and created for training purpose in software architecture.
# Goals
User have to see a list of all the available products in stock. 
We need to be able to see product information (name, price, quantity) in readable form.
User need to have possibility perform search by product name and buy any product.
User need to have possibility checkout product and create order. 
Users must have access to this application after being authenticated.

# Start application
1. Clone all projects
  ```
  $ git submodule update --init --recursive
  $ git submodule update --recursive --remote
  ```
2. Run docker compose 
  ```
  $ docker-compose up
  ```


# Features
  * [Display available products in SW store](https://github.com/khdevnet/sw/wiki/Display-available-products-on-warehouse)
  * [Checkout order in SW store](https://github.com/khdevnet/sw/wiki/Display-available-products-on-warehouse)
  * Display dashboard with price statistic, user activities
  * Save user activity history
  * Extend Api for external customers
  * Create online chat bot
  
# Development
### Frameworks & Architecture Styles
  * [Microservice Architecture](https://martinfowler.com/articles/microservices.html)
  * [CQRS Architecture](https://martinfowler.com/bliki/CQRS.html)
  * [Onion Architecture](https://jeffreypalermo.com/2008/07/the-onion-architecture-part-1/)
  * [OAuth 2.0 Authorization](https://tools.ietf.org/html/rfc6749)
  * [Facebook OAuth](https://github.com/khdevnet/warehouse/wiki/Development-Task-Flow)
  * [Kubernetes](https://kubernetes.io/)
  * [Docker](https://www.docker.com/)
  
### Application Architecture
  * [High Level View](https://github.com/khdevnet/warehouse/wiki/High-Level-Architecture-View)
  * [Frontend Component](https://github.com/khdevnet/sw-frontend) - provides UI of application to end users
  * [GraphQL Component](https://github.com/khdevnet/sw-graphql) - provides an API to interact with Frontend
  * [Products Component](https://github.com/khdevnet/sw-products) - provides an API for Products CRUD operations
  * [Checkout Component](https://github.com/khdevnet/sw-checkout) - provides an API for checkout order operations

### Process
  * [Development Flow](https://github.com/khdevnet/warehouse/wiki/Development-Task-Flow)
  * Bug Verification Flow
  
### Continious Integration
  * [Development Pipeline Flow](https://github.com/khdevnet/warehouse/wiki/Development-Pipeline-Flow)
  * [Production Pipeline Flow](https://github.com/khdevnet/warehouse/wiki/Production-Pipeline-Flow)
  
# Maintenance & Support
  * [Environments](https://github.com/khdevnet/warehouse/wiki/Environments)
  * [Kubernetes Debug Commands](https://github.com/khdevnet/warehouse/wiki/Kubernetes-Debug-Commands)
  
# User Documentation
  * Dashboard page
  * Products page
  * Api for external users
