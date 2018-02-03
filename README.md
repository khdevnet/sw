# Warehouse

Designed and created to store information for large e-commerce organization which produce socks for every one.

# Goals

User have to see a list of all the available products in stock. 
We need to be able to see product information (name, price, quantity) in readable form.
User need to have possibility perform search by product name and change the quantity of the product during the replenishment of the assortment. Users must have access to this application after being authenticated.

# Features
  * [Display available products on warehouse](https://github.com/khdevnet/warehouse/wiki/Display-available-products-on-warehouse)
  * Display dashboard with price statistic, user activities
  * Save user activity history
  * Extend Api for external customers
  * Create online chat bot
  
# Development
### Frameworks & Architecture Styles
  * [Microservice Architecture](https://martinfowler.com/articles/microservices.html)
  * [OAuth 2.0 Authorization](https://tools.ietf.org/html/rfc6749)
  * [Facebook OAuth](https://github.com/khdevnet/warehouse/wiki/Development-Task-Flow)
  * [Kubernetes](https://kubernetes.io/)
  
### Application Architecture
  * [High Level View](https://github.com/khdevnet/warehouse/wiki/High-Level-Architecture-View)
  * [Frontend Component](https://github.com/khdevnet/warehouse-frontend) - provides UI of application to end users
  * [GraphQL Component](https://github.com/khdevnet/warehouse-graphql) - provides an API to interact with Frontend
  * [Products Component](https://github.com/khdevnet/warehouse-products) - provides an API for Products CRUD operations

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
