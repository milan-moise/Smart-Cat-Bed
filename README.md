# Smart Cat Heating Bed

## Project Overview
The Smart Cat Heating Bed is an IoT system that monitors temperature inside a cat bed and regulates heating or cooling using a Peltier module. The system uses a Raspberry Pi, DHT11 sensor, relay-controlled Peltier module, LED indicator, and LCD display.

## Features
- Real-time temperature monitoring
- Automatic heating/cooling control
- LCD temperature display
- LED system status indicator
- Modular system design for future ML integration

## Hardware
- Raspberry Pi
- DHT11 Temperature & Humidity Sensor
- Relay Module
- Peltier Module
- LCD Display (I2C)
- LED + resistor
- External power supply for Peltier

## Control Logic
- If temperature < lower threshold → heating ON
- If temperature > upper threshold → cooling ON
- Otherwise → system idle

## Running the Project
```bash
pip install -r requirements.txt
python3 src/main.py
python3 -m src.main

```
cd existing_repo
git remote add origin https://gitlab.oit.duke.edu/mm1247/smart-cat-bed.git
git branch -M main
git push -uf origin main
```

