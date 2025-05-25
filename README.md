# Countdown Timer

A simple and intuitive GUI-based countdown timer application built with Python and Tkinter.

## Features

- **User-friendly interface** with drop-down menus for setting time
- **Flexible time setting** - Set hours (0-24), minutes (0-59), and seconds (0-59)
- **Start/Pause functionality** - Control your countdown with dedicated buttons
- **Real-time display** - Watch your countdown update every second
- **Alert notification** - Get notified when the countdown reaches zero
- **Cancel option** - Stop and close the timer at any time

## Requirements

The application requires the following Python modules:

- `Tkinter` - For the graphical user interface
- `threading` - For background timer operations
- `time` - For time calculations and delays

## Installation

1. Clone this repository:
```bash
git clone https://github.com/RAKSAurum/Countdown-Timer.git
cd Countdown-Timer
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

**Note**: Tkinter is typically included with Python installations, so manual installation may not be necessary.

## Usage

1. Run the application:
```bash
python timer.py
```

2. **Set your countdown time**:
   - Use the drop-down menus to select hours, minutes, and seconds
   - Click the "Set" button to confirm your time selection

3. **Control the timer**:
   - Click "Start" to begin the countdown
   - Click "Pause" to temporarily stop the timer
   - Click "Cancel" to stop and close the application

4. **Monitor progress**:
   - Watch the real-time countdown display showing "Time Left: HH: MM: SS"
   - Receive a notification popup when the countdown completes

## File Structure
```txt
countdown-timer/
├── timer.py # Main application file
├── requirements.txt # Required Python packages
└── README.md # Project documentation
```


## How It Works

The application uses a `CountDown` class that manages the timer functionality. Key components include:

- **GUI Setup**: Creates a 564 x 850 pixel window with a black theme
- **Time Selection**: Three drop-down menus for hours, minutes, and seconds
- **Threading**: Uses background threads to run the countdown without freezing the UI
- **Time Calculation**: Converts user input to total seconds and counts down
- **Display Updates**: Updates the timer display every second

## Contributing

Feel free to fork this repository and submit pull requests for any improvements or bug fixes.

## License

This project is open source and available under the [MIT License](LICENSE).
