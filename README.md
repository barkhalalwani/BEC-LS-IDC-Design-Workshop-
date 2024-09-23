# Geometrical Frame Application
## Overview
The application here aims to enhance understanding of design patterns through the development of a class library that implements business logic for a geometrical frame application. This has been achieved by utilizing optimal design patterns to create a scalable and maintainable architecture.

The application has been built with the consideration of SOLID Programming design principles and usage of design patterns like Builder Pattern and Factory Pattern. The test cases specifically have been written using the Factory Design Pattern.  

### Principles:
- **S**Single Responsibility: Break the code into modules of one responsibility each.
- **O**pen/Closed Principle: Add new functionality in the future without directly modifying our existing code.
- **L**iskov Substitution: Subclasses should be able to be used interchangeably with their superclasses without breaking the functionality of the program.
- **I**nterface Segregation: Client-specific interfaces are better than general-purpose ones. This means that classes should not be forced to depend on interfaces they don’t use. Instead, they should rely on smaller, more specific interfaces.
- **D**ependency Inversion: High-level modules should not rely directly on low-level modules. Instead, both should rely on abstractions (interfaces or abstract classes).

### Design Patterns:
- Builder Pattern: simplifies object creation by separating the construction process from the actual representation.
- Factory Pattern: It defines a factory class to provide an interface to create objects without exposing their concrete implementations to make it more adaptable.

## Project Details:
### Objective
To develop a class library that:
- Allows the creation of a frame that can contain geometrical shapes.
- Implements best practices in design patterns for effective shape creation, operations, and property management.
### Key Features
Frame Specifications:
- Origin at the upper left corner.
- Defined length along the x-axis and width along the y-axis.
- Only one frame can be instantiated at a time.  
### Shape Management:
- Ability to add multiple shapes to the frame, including:
1. Circles (defined by a center and radius).
2. Rectangles (defined by a top left corner and side length).
3. Squares (a specific type of rectangle).
- Ensure that all shapes are contained within frame boundaries.
- Prevent the addition of duplicate shapes.
- The application must allow modifications to the frame's length and width.

## Deliverables
- Unit tests to ensure functionality and reliability.
- Source Code
- Low Level Design 

## Usage
- Instantiate the frame using the provided API.
- Add shapes as per the specifications.
- Modify the frame dimensions if needed.
- Run unit tests to validate the implementation.

## Conclusion
Through this application development, we are able to implement design patterns while contributing to a practical execution. 







