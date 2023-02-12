# Event-Driven Architecture
Distributed asynchronous communication for highly scalable apps

## Components
- **Event**: a message that is sent to notify other components of an occurrence
- **Event generator**: generates events
- **Event processor**: processes events
- **Event channel**: medium where event lies before consumption

## Comparison with SOA
- SOA: Synchronous request/response, technically loosely coupled, functionally tightly coupled.
- EDA: Spatial and temporal decoupling, asynchronous architecture

## Advantages
- **Scalability**: easy to scale instances
- **Extensibility**: easy to add new systems

## Topologies
### Mediator
orchestrates the flow of events
<img width="334" alt="Capture d’écran 2023-02-12 à 18 09 52" src="https://user-images.githubusercontent.com/19282069/218325801-1480fa1b-02ab-45bd-99fc-1d1bb4c0e7ec.png">

### Broker
stores events and routes them to subscribers
<img width="366" alt="image" src="https://user-images.githubusercontent.com/19282069/218325818-48faf59d-efb4-4a75-a0eb-d9270c428b1a.png">