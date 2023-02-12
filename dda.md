# Domain-Driven Architecture
Modeling SW to match a domain according to input from domain experts
## DDA Layers
### Application Layer
- ASP.NET Core MVC
- Network
- Commands
- etc...
### Domain Layer
- Entities
- POCO classes
### Infrastructure Layer
- Data persistence infrastructure
- Use of ORM (EF Core)
- etc...

## Terms
- **Domain logic**: purpose of the modeling, the business logic
- **Domain model**: ideas, knowledge, data, metrics, goal
- **Subdomain**: a part of the domain logic
- **Bounded context**: a subdomain that is independent from other subdomains
- **Ubiquitous language**: a language that is used by all stakeholders

## Pros and Cons
### Pros
- As close as possible to user functional map, facilitates communication between **domain experts** and **developers**
- Easy to implement task/activity-oriented user interface
### Cons
- Lot of relationships between entities, performance issues
- Long learning curve