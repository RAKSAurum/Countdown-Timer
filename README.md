# Countdown Timer Application

This is a Python-based countdown timer application using the `Tkinter` library for the GUI and threading to manage background processes. The app allows users to set a countdown timer by selecting hours, minutes, and seconds, and provides functionalities to start, pause, and cancel the timer.

## Features

- **Set Timer**: Allows you to set the countdown timer by choosing hours, minutes, and seconds.
- **Start Timer**: Start the countdown once the time is set.
- **Pause Timer**: Pause the countdown at any moment.
- **Cancel Timer**: Cancel the countdown and close the application.
- **Responsive UI**: The countdown dynamically updates the remaining time on the display.

## Getting Started

### Prerequisites

Ensure you have Python installed. You can download it from [python.org](https://www.python.org/downloads/).

You will also need the following libraries, which are typically included in a standard Python installation:

- `Tkinter`
- `threading`
- `time`

No additional external libraries are required.

### Installation

1. Clone the repository or download the source code.
2. Run the `main.py` file in your terminal or preferred IDE.

```bash
git clone https://github.com/yourusername/countdown-timer.git
cd countdown-timer
python main.py
```

### Running the Application

1. After launching the application, a window will appear with the following options:
   - **Set the timer**: Choose the desired hours, minutes, and seconds from the dropdown menus.
   - **Start button**: Begins the countdown.
   - **Pause button**: Pauses the countdown if necessary.
   - **Cancel button**: Cancels the timer and closes the window.

2. Once the countdown reaches zero, a message box will pop up with the message "Time Over."

## Code Overview

### Files
- **`main.py`**: Contains the logic for the countdown timer application. The `CountDown` class manages all the operations for setting, starting, pausing, and displaying the countdown.

### Main Components

- **Tkinter Widgets**: The application uses various Tkinter widgets including labels, buttons, and comboboxes for user interaction.
- **Threading**: The `threading` module is used to run the countdown function in a separate thread, preventing the application from freezing while counting down.
- **MessageBox**: The `messagebox` is used to show alerts when the countdown finishes or when there's an error.

## Usage

1. Select hours, minutes, and seconds for the countdown using the dropdown.
2. Click **Set** to load the timer.
3. Click **Start** to begin the countdown.
4. You can **Pause** the countdown or cancel it using the **Cancel** button.

### Example

If you want to set a countdown of 2 hours, 30 minutes, and 15 seconds:
- Select `2` for **Hour**, `30` for **Minute**, and `15` for **Second**.
- Click **Set**.
- Click **Start** to begin the countdown.
