# To-Do Application

## Overview

This is a simple yet powerful To-Do application built with Python. It features both a command-line interface (CLI) and a graphical user interface (GUI), allowing users to manage their tasks efficiently.

## Features

- Add new tasks
- View all tasks
- Edit existing tasks
- Mark tasks as complete
- User-friendly GUI with real-time clock display
- Command-line interface for quick task management

## Files

- `gui.py`: Contains the graphical user interface implementation using PySimpleGUI
- `cli.py`: Implements the command-line interface for the application
- `functions.py`: Houses the core functionality and file operations for the To-Do list

## Requirements

- Python 3.x
- PySimpleGUI (for GUI version)

## Installation

1. Clone this repository or download the source files.
2. Install the required packages:
   ```
   pip install PySimpleGUI
   ```

## Usage

### GUI Version

To run the graphical user interface:

```
python gui.py
```

The GUI provides an intuitive interface for managing your tasks. You can add, edit, and complete tasks using the buttons provided.

### CLI Version

To run the command-line interface:

```
python cli.py
```

Follow the prompts to manage your tasks. Available commands:
- `add`: Add a new task
- `show`: Display all tasks
- `edit`: Modify an existing task
- `complete`: Mark a task as completed
- `exit`: Close the application

## How It Works

The application uses a text file (`todos.txt`) to store tasks. The `functions.py` module handles reading from and writing to this file, ensuring data persistence across sessions.

## Customization

You can customize the appearance of the GUI by modifying the theme in `gui.py`. The current theme is set to "NeonBlue1".

## Contributing

Feel free to fork this project and submit pull requests with any enhancements.
