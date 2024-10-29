# Pamodoro-GUI-application

This is a simple Pomodoro timer application built using Python and the Tkinter library. It helps improve productivity by following the Pomodoro Technique, where users work in intervals (usually 25 minutes) followed by a short break.

## Features

- Start, reset, and automatic cycling of work and break sessions.
- Customizable work, short break, and long break durations.
- Visual timer display with a "tomato" icon.
- Progress indicators after each work session.

## Requirements

- Python 3.x
- Tkinter library (included with most Python installations)

## Setup Instructions

1. **Clone the Repository**: Clone this repository or download the files manually.

   ```bash
   git clone https://github.com/your-username/pomodoro-timer.git
   cd pomodoro-timer
   ```

2. **Add Image File**: Make sure to have an image file named `tomato.png` in the same directory as `main.py`. This image is used as a background icon in the timer display.

3. **Run the Application**: Run the main Python file to start the timer.

   ```bash
   python main.py
   ```

## Usage

1. Click the **Start** button to begin the timer.
2. After a 25-minute work session, the timer will automatically start a 5-minute break.
3. After every 4th session, the timer will initiate a longer 30-minute break.
4. Click the **Reset** button to reset the timer at any time.

## Configuration

You can adjust the durations of the work and break sessions by modifying the following constants in the `main.py` file:

```python
WORK_MIN = 25           # Work session duration in minutes
SHORT_BREAK_MIN = 5      # Short break duration in minutes
LONG_BREAK_MIN = 30      # Long break duration in minutes
```

## Pomodoro Technique

The Pomodoro Technique is a time-management method that uses a timer to break down work into intervals, traditionally 25 minutes in length, separated by short breaks. This helps improve focus and prevents burnout.

## Project Structure

```plaintext
.
├── main.py         # Main Python file with timer logic and UI setup
└── tomato.png      # Icon used in the timer display
```

Enjoy using the Pomodoro Timer to enhance your productivity!
```
