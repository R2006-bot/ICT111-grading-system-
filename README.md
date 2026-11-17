# ICT111 Grading System

This repository is for the ICT111 coursework and serves as a simple grading system project for learning Python programming and software development fundamentals.

## Overview

The goal of this project is to build a system that can:

- store student records
- record coursework and assessment marks
- calculate total marks and percentages
- determine pass/fail or grade categories
- display results in a clear and organised format

This project is intended to help strengthen practical programming skills, including data handling, logic implementation, and user-friendly output.

## Features

- Student information management
- Subject/course assessment tracking
- Grade calculation based on marks
- Performance summary and classification
- Simple console-based or file-based interface
- Easy-to-extend structure for future improvements

## Project Structure

```text
ICT111-grading-system/
├── README.md
├── main.py
├── grading_system.py
├── students.py
├── tests/
└── data/
```

> Note: This structure is a recommended project layout and can be adjusted as the project develops.

## Technologies

- Python 3
- Standard library modules
- Optional: CSV/JSON files for saving student data
- Optional: Tkinter or Flask for a graphical/web interface (if extended later)

## Setup

1. Make sure Python 3 is installed on your machine.
2. Clone the repository.
3. Open the project folder in your preferred editor or terminal.
4. Run the program with:

```bash
python main.py
```

## Example Usage

```python
student = {
    "name": "Jane Doe",
    "course": "ICT111",
    "marks": [78, 85, 90]
}
```

The system can then calculate totals, averages, and grade outcomes from the student's assessment records.

## Learning Goals

This project is designed to help develop:

- Python syntax and logic
- data structures and functions
- file handling and persistence
- problem solving in practical applications
- basic software design and documentation

## Future Improvements

- Add a graphical user interface
- Save data in CSV or JSON files
- Support multiple courses and multiple students
- Add automated tests for grading logic
- Improve validation for invalid or missing marks

## License

This project is for academic learning purposes and is not currently intended for commercial use.

## Author

A first-year Data Science student learning Python and software development through the ICT111 course.
