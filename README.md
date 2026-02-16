# Student Data Management System

## Overview
A Python application for managing student records using efficient data structures including lists, tuples, sets, comprehensions, and generators.

## Setup Instructions

1. Clone the repository:
```bash
git clone <repo-url>
cd course-7-module-1-python-data-structures-lab
```

2. Install dependencies:
```bash
pipenv install
pipenv shell
```

3. Run tests:
```bash
pytest -x
```

## Features

- **Student Records Management**: Store student data using tuples in lists
- **Filtering**: Use list comprehensions to filter students by major
- **Data Display**: Format and display student information
- **Unique Attributes**: Track unique majors using set comprehensions
- **Memory Efficiency**: Process large datasets using generator expressions

## Usage

Run tests to verify functionality:
```bash
pytest -x
```

## Module Descriptions

- `lib/student_data.py`: Stores student records as tuples
- `lib/filters.py`: Filters students by major using list comprehensions
- `lib/data_processing.py`: Formats and displays student data
- `lib/set_operations.py`: Tracks unique majors using set comprehensions
- `lib/data_generator.py`: Generates students by major using generator expressions

## Data Structures Used

- **Lists**: Store collections of student records
- **Tuples**: Immutable student records (ID, Name, Major)
- **Sets**: Track unique majors efficiently
- **List Comprehensions**: Filter students dynamically
- **Generator Expressions**: Process data with memory efficiency
