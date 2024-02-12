

# Pomodoro Timer

This Pomodoro Timer is a simple yet effective time management tool to help you focus on your work and study tasks. Built with Python and Tkinter, it features a customizable and easy-to-use graphical user interface.

## Features

- **Customizable Work, Short Break, and Long Break durations**: Set to 25 minutes of work, 5 minutes of short break, and 20 minutes of long break by default.
- **Visual and Textual Countdown**: Shows the remaining time visually on a tomato image and as text.
- **Session Counter**: Marks each completed work session with a checkmark.
- **Color-Coded Sessions**: Work sessions are green, short breaks are pink, and long breaks are red for easy identification.
- **Reset Functionality**: Allows you to reset the timer and session counter at any time.

## How to Use

1. **Start the Timer**: Click on the "Start" button to begin the first Pomodoro (25 minutes of work).
2. **Follow the Timer**: The app will automatically switch between work sessions and breaks, updating the session counter accordingly.
3. **Reset if Needed**: The "Reset" button can be used to start over at any time.

## Setup

To run the Pomodoro Timer, you'll need:
- Python 3.x
- Tkinter installed with Python (usually comes with the standard Python installation)
- `tomato.png` image file placed in the same directory as the script for the timer visualization.

## Running the Application

Open a terminal or command prompt, navigate to the directory containing the script, and run:

```bash
python pomodoro_timer.py
