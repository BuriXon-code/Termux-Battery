# Termux-Battery 🔋

## About
Termux-Battery is a Bash script that monitors and displays your device's battery status in Termux. It retrieves battery percentage, temperature, and charging status using `jq` and `termux-battery-status`. The script also supports various options to customize the output, including:
- Adjusting the battery frame color with a 256-color value.
- Centering the output horizontally.
- Disabling ASCII art to show only battery data.
- Emulating battery level, status, and temperature.
- Running in a loop with 0.5-second intervals.

![screenshot](/screenshots/battery.jpg)  

## Installation

### Dependencies
- Termux (or a compatible Bash environment)
- `jq` (for JSON parsing)
- `termux-battery-status` (provided by Termux)

To install the necessary dependency for `jq`, run:
```
pkg install jq
```

### How to Install the Script
1. Clone the repository:
```
git clone https://github.com/BuriXon-code/Termux-Battery
```

2. Navigate to the script directory:
```
cd Termux-Battery
```

3. Make the script executable:
```
chmod +x battery
```

## Usage

### Running the Script
To run the script, execute:
```
./battery
```

The script will display:
- Battery percentage
- Charging status
- Battery temperature (rounded to one decimal place)

### Script Options
- **-center**  
  Centers the output horizontally.

![screenshot](/screenshots/center.jpg)  

- **-color (value)**  
  Sets the color of the battery frame. Accepts a number between 0 and 255 (ANSI 256colors).

![screenshot](/screenshots/color.jpg)  

- **-no-ascii**  
  Displays only battery data without the ASCII art frame.

![screenshot](/screenshots/noascii.jpg)  

- **-loop**  
  Runs the script in an infinite loop with 0.5-second intervals.

![screenshot](/screenshots/battery.jpg)  

- **-level (value)**  
  Emulates a specific battery level. Value must be an integer between 0 and 100.

![screenshot](/screenshots/level.jpg)  

- **-status (value)**  
  Emulates a specific battery status. Valid options: CHARGING, DISCHARGING, FULL.

![screenshot](/screenshots/status.jpg)  

- **-temp (value)**  
  Emulates a specific battery temperature. Value can be a number (integer or decimal).

![screenshot](/screenshots/temp.jpg)  

- **-help**  
  Displays the help message with usage instructions.

![screenshot](/screenshots/help.jpg)  

## Support
### Contact me:
For any issues, suggestions, or questions, reach out via:

- **Email:** support@burixon.com.pl  
- **Contact form:** [Click here](https://burixon.com.pl/kontakt.php)

### Support me:
If you find this script useful, consider supporting my work by making a donation:

[**DONATE HERE**](https://burixon.com.pl/donate/)

Your contributions help in developing new projects and improving existing tools!
