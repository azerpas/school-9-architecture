# Software Architecture & Design
- *architecture*: focus on developing the skeleton of software
- *design*: focus on the code level design, funcs, modules, classes, etc.
| Name | Scope | Defines | Creates | Patterns |
| --- | --- | --- | --- | --- |
| Architecture | System | Main properties | High-Level Structure | Microservices, serverless, etc. | 
| Design | Module | Individual properties of a module | Specifications of software artifacts | Creational, structural, behavioral |

## SOLID Principles
### S: Single Responsibility Principle
Each service have 1 objective
### O: Open-Closed Principle
Modules should be independent and expandable
### L: Liskov Substitution Principle
Independent services should be able to communicate with each other
### I: Interface Segregation Principle
SW should be divided into independent modules
### D: Dependency Inversion Principle
High-level modules should not depend on low-level modules

## Other clean code principles
- DRY: Don't Repeat Yourself
- KISS: Keep It Simple, Stupid
- YAGNI: You Ain't Gonna Need It

## 12-Factor App
1. Codebase - One codebase tracked in revision control, many deploys
2. Dependencies - Explicitly declare and isolate dependencies
3. Config - Store config in the environment for deployments
4. Backing services - Treat backing services as attached resources
5. Build, release, run - Strictly separate build and run stages
6. Processes - Execute the app as one or more stateless processes
7. Port binding - Export services via port binding
8. Concurrency - Scale out via the process model
9. Disposability - Maximize robustness with fast startup and graceful shutdown
10. Dev/prod parity - All should be as similar as possible
11. Logs - Treat logs as event streams
12. Admin processes - Kept in source control and packaged with the app