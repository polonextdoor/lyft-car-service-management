# Lyft Virtual Experience
# Car Service Management Program
The Car Service Management Program is a Python application that helps manage the service requirements for Lyft rental cars based on their engine and battery types. The program uses a flexible and extensible architecture to determine when a car needs service based on different criteria such as mileage, warning indicators, and time.

## Features
* The program supports different types of engines and batteries, each with its own service criteria.

* Service criteria include mileage-based service, warning indicator service, and time-based service.

* Cars are represented as a composition of engine and battery types, allowing easy modification of car components.

* The CarFactory class provides methods to create car instances based on specific engine-battery combinations.

* The application adheres to the Strategy design pattern to encapsulate service criteria and the Factory Method pattern for creating car models.