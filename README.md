# Enhanced Alarm Clock

A modern, feature-rich alarm clock web application with a beautiful UI and comprehensive time management features.

![Enhanced Alarm Clock Screenshot](screenshot.png)

## Features

### Alarm System
- Set multiple alarms with hour, minute, and second precision
- Customizable alarm names
- Snooze functionality with adjustable snooze time (1-30 minutes)
- Sound testing capability
- Custom alarm sound support
- Active alarms list with easy removal

### Stopwatch
- Start, stop, and reset functionality
- Lap time recording
- Millisecond precision
- Clean, easy-to-read display
- Lap times history

### World Clock
- Add multiple world clocks
- Support for any timezone
- Easy clock management
- Real-time updates
- Major cities pre-configured
- Custom city and timezone addition

### World Map
- Visual timezone representation (UTC-12 to UTC+14)
- Major city markers with hover information
- Timezone information display
- Interactive map interface
- City timezone detection
- Continent visualization

### Settings
- Dark/Light theme toggle
- Customizable alarm sounds
- Persistent settings using localStorage
- User preferences management
- Modern glass-morphism UI design

## Technologies Used

- HTML5
- CSS3 (with modern features like CSS variables and animations)
- JavaScript (ES6+)
- Tailwind CSS for styling
- Bootstrap Icons for icons
- Google Fonts (Montserrat)
- LocalStorage for data persistence

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/enhanced-alarm-clock.git
cd enhanced-alarm-clock
```

2. Open `main.html` in your web browser:
```bash
# Using Python's built-in server
python -m http.server 8000
# Then open http://localhost:8000 in your browser
```

## Usage

### Setting an Alarm
1. Navigate to the Alarm tab
2. Select the desired hour, minute, and second
3. Enter an optional alarm name
4. Set snooze time (default: 5 minutes)
5. Click "Set Alarm"

### Using the Stopwatch
1. Go to the Stopwatch tab
2. Use Start, Stop, and Reset buttons
3. Record lap times using the Lap button
4. View lap history below the stopwatch

### Adding World Clocks
1. Open the World Clock tab
2. Enter a city name
3. Select the timezone
4. Click "Add Clock"
5. Remove clocks using the X button

### Using the World Map
1. Navigate to the World Map tab
2. Hover over the map to see timezone information
3. View major cities and their timezones
4. See continent boundaries and timezone lines

### Customizing Settings
1. Access the Settings tab
2. Toggle between dark and light themes
3. Change alarm sounds using the file picker
4. Preview selected sounds
5. Settings are automatically saved

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## File Structure

```
enhanced-alarm-clock/
├── main.html          # Main application file
├── README.md          # This file
└── assets/            # Resource files
    ├── sounds/        # Alarm sounds
    └── images/        # Application images
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [Bootstrap Icons](https://icons.getbootstrap.com/) for the icon set
- [Google Fonts](https://fonts.google.com/) for the Montserrat font
- [Blank Audio](https://github.com/anars/blank-audio) for the default alarm sound

## Support

For support, email support@example.com or open an issue in the repository.

## Version History

- 3.0.0
  - Complete UI redesign with glass-morphism
  - Enhanced world map with city markers
  - Improved timezone support
  - Dark/Light theme toggle
  - Custom alarm sound support
  - Persistent settings

- 2.0.0
  - Added world map visualization
  - Improved theme support
  - Enhanced settings management
  - Bug fixes and performance improvements

- 1.0.0
  - Initial release
  - Basic alarm functionality
  - Stopwatch feature
  - World clock support 