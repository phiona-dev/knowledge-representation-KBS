# Knowledge Representation

A simple Knowledge Base System (KBS) demonstrating object-oriented knowledge representation in Python.

## Overview

This project implements a basic knowledge base for storing and managing person objects, showcasing fundamental concepts of knowledge representation through classes and object storage.

## Features

- **Person Class**: Represents individuals with name and age attributes
- **KnowledgeBase Class**: Manages a collection of Person objects
- **Search Functionality**: Find persons by name within the knowledge base

## Usage

```python
# Create a knowledge base
kb = KnowledgeBase()

# Add persons
kb.add_person(Person("Alice", 30))
kb.add_person(Person("Bob", 25))

# Search for a person
person = kb.find_person_by_name("Alice")
if person:
    print(person)  # Output: Alice, 30 years old
```

## Getting Started

Run the notebook to see the example usage and output:

```bash
jupyter notebook knowledge-representation.ipynb
```

## Requirements

- Python 3.x
- Jupyter Notebook

## License

MIT
