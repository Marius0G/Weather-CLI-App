# Weather CLI App

A terminal-based weather application built with Rust at Rust Ip Workshop UPB that displays real-time weather information for multiple cities using a text-based user interface.

## Features

- **Beautiful TUI**: Uses the [ratatui](https://github.com/ratatui-org/ratatui) library to create an interactive terminal interface
- **Real-time Weather Data**: Fetches current weather conditions from the OpenWeatherMap API
- **Multi-city Support**: View weather for multiple cities and switch between them
- **Comprehensive Weather Details**: Displays:
  - Temperature (current, feels like, min/max)
  - Humidity and pressure
  - Wind speed and direction
  - Weather conditions with description
  - Visibility and cloudiness
  - Sunrise and sunset times

## Getting Started

```bash
git clone https://github.com/yourusername/weather-cli-app
cd weather-cli-app
cargo run
```
Note: You'll need to provide your own OpenWeatherMap API key in the Connection struct.
![image](https://github.com/user-attachments/assets/43f77b98-7c35-4c61-9106-8a9641083fe6)
