# 🏠 Esplogger

An ESP32-based weather station that monitors and transmits temperature and pressure data from your garden to your Home Assistant setup. Stay updated on your local weather conditions directly from your smart home system.

## Setup

Clone this repository.

```bash
git clone https://github.com/lewinkoon/homelogger.git
cd homelogger
```

Install python dependencies.

```bash
poetry install
```

Activate virtual environment.

```bash
poetry shell
```

Upload your code to your ESP32 board.

```bash
esphome run main.yaml
```

## Usage

Once set up, your ESP32 weather station will automatically connect to WiFi and transmit temperature and pressure data to Home Assistant. You can view real-time data in the Home Assistant dashboard.
