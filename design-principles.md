# Object-Oriented Programming (OOP) Design Principles

![image](https://github.com/EthanNorton/SWEskills/assets/86625413/3a09226f-83f1-4b9e-b626-28fb419b0069)
- **Potential Workflow** 

## Encapsulation

### Definition
Encapsulation is bundling the data (attributes) and methods (functions) that operate on the data into a single unit or class and restricting access to some of the object's components.

### Key Practices
- Use access specifiers (`private`, `protected`, `public`) to control access to the attributes and methods.
- Provide public getter and setter methods to access and update the private attributes.

# Functional Programming Tools in Python

This section explores essential functional programming constructs in Python, including `lambda`, `map`, `filter`, and `reduce`. Functional programming emphasizes immutability, first-class functions, and declarative code.

### Definition 

Functional programming techniques can lead to more concise, readable, and maintainable code. These techniques are particularly useful when working with collections of data, making it easy to apply transformations or filtering operations in a clean, declarative manner.

## Tools Covered

- **Lambda Functions**: Anonymous functions for short, single-use operations.
- **Map**: Applies a function to every element of an iterable.
- **Filter**: Filters elements in an iterable based on a condition.
- **Reduce**: Reduces an iterable to a single value through a binary operation.
- **List Comprehensions**: A Pythonic way to apply functions to iterables.

### Further Resources
- [Python Official Docs](https://docs.python.org)
- [Real Python Functional Programming Guide](https://realpython.com/python-functional-programming/)
- [Geeks for Geeks Functional Programming](https://www.geeksforgeeks.org/functional-programming-in-python/)

# Magic Methods in Python

Magic methods, also known as **dunder methods**, allow you to define how objects behave with respect to built-in operations such as arithmetic, comparison, string representation, and more.

### Definition

These methods have double underscores before and after their names (e.g., `__init__`, `__str__`, `__add__`). Python calls these methods automatically when performing certain operations on objects, making it possible to customize object behavior in a flexible way.

## Common Magic Methods Covered

- `__init__`: Initializes an object.
- `__str__`: Defines how an object is printed as a string.
- `__repr__`: Provides an official string representation of an object.
- `__add__`: Overloads the `+` operator.
- `__len__`: Defines behavior for the `len()` function.
- `__getitem__`, `__setitem__`: Enables indexing and item assignment.
- `__eq__`: Compares two objects for equality.
- `__call__`: Allows an object to be called like a function.

## Getting Started

To explore these magic methods, define a class and implement any of the above methods. You can run each example in this section by copying the code to a `.py` file and running it.

### Further Resources
- [Python Official Docs on Magic Methods](https://docs.python.org/3/reference/datamodel.html)
- [Real Python: Magic Methods](https://realpython.com/python-magic-methods/)

  
## Operating Systems Principles 

## Refactoring Code

**Topics** 
- https://arxiv.org/pdf/2207.05613

### Definition

### Key Practices

## Abstraction

### Definition
Abstraction involves simplifying complex reality by modeling classes appropriate to the problem and working at the most relevant level of inheritance for a particular aspect of the problem.

### Key Practices
- Use abstract classes and interfaces to define common methods that multiple subclasses can implement.
- Focus on what an object does rather than how it does it.

## Inheritance

### Definition
Inheritance is a mechanism where a new class is derived from an existing class. The new class inherits attributes and methods from the existing class.
![image](https://github.com/EthanNorton/SWEskills/assets/86625413/91c631fd-a6e2-46a6-a67d-83725730bcbf)

### Key Practices
- Use inheritance to promote code reusability and establish a natural hierarchy.
- Override methods in the subclass to provide specific implementations.

## Polymorphism

### Definition
Polymorphism allows objects of different classes to be treated as objects of a common superclass. It is often expressed through method overriding and interface implementation.

### Key Practices
- Use method overriding to allow different classes to provide specific implementations of a method defined in a superclass or interface.
- Leverage dynamic method binding to call the overridden methods at runtime.

## Decorators 

## SOLID Principles

### Single Responsibility Principle (SRP)
A class should have one, and only one, reason to change.

### Open/Closed Principle (OCP)
Software entities should be open for extension but closed for modification.

### Liskov Substitution Principle (LSP)
Subtypes must be substitutable for their base types without altering the correctness of the program.

### Interface Segregation Principle (ISP)
No client should be forced to depend on methods it does not use.

### Dependency Inversion Principle (DIP)
High-level modules should not depend on low-level modules. Both should depend on abstractions.

## Composition over Inheritance

### Definition
Favor composition (having instances of other classes as members) over inheritance (extending other classes) to achieve code reuse and flexibility.

### Key Practices
- Use interfaces and delegate the responsibility to other classes to achieve functionality.
- Avoid deep inheritance hierarchies which can lead to complex and fragile code.

## DRY (Don't Repeat Yourself)

### Definition
Avoid duplication of code by abstracting common functionality and reusing existing code.

### Key Practices
- Refactor common code into reusable methods or classes.
- Use inheritance or composition to avoid code duplication.

## KISS (Keep It Simple, Stupid)

### Definition
Strive for simplicity in design and implementation, avoiding unnecessary complexity.

### Key Practices
- Write clear, concise, and understandable code.
- Avoid over-engineering and focus on solving the problem at hand.

---

# Structuring Code for Good Machine Learning Workflows

## Modular Design
- Break down the workflow into modular components such as data ingestion, preprocessing, model training, evaluation, and deployment.
- Each module should be self-contained and perform a specific task.

## Data Handling
- Efficiently load, preprocess and augment data.
- Implement data versioning to track changes in the datasets used for training and evaluation.

## Feature Engineering
- Develop a pipeline for feature extraction, transformation, and selection.
- Use tools like `sklearn.pipeline` or custom pipelines to automate feature engineering.

## Model Training
- Structure code to support hyperparameter tuning and cross-validation.
- Implement checkpoints to save and resume training.

## Evaluation and Metrics
- Define clear evaluation metrics and implement functions to compute them.
- Use cross-validation and hold-out validation to assess model performance.

## Model Management
- Use version control for models to keep track of different model versions and configurations.
- Implement logging to record training history and model performance.

## Testing and Validation
- Write unit tests and integration tests for data processing functions and model training.
- Ensure reproducibility by setting random seeds and documenting the environment setup.

## Scalability and Performance
- Optimize code for performance, especially for large datasets and complex models.
- Use distributed computing frameworks like Apache Spark for large-scale data processing.

## Deployment
- Develop a strategy for model deployment including model serialization (e.g., using `pickle` or `joblib`), containerization (e.g., Docker), and serving (e.g., Flask, FastAPI).
- Implement monitoring to track model performance and detect drifts in real-time.

## Documentation and Collaboration
- Document code, workflows, and decisions clearly to facilitate collaboration.
- Use tools like Jupyter Notebooks for exploratory data analysis and sharing results.

## Automation and MLOps
- Implement CI/CD pipelines to automate testing, validation, and deployment of ML models.
- Use MLOps tools and frameworks (e.g., MLflow, TFX, Kubeflow) to manage the end-to-end ML lifecycle.

