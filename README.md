# Sensor Data Analysis

Simple pandas project.

## Installation

```bash
pip install -r requirements.txt     # pip3 if Mac
```

## Usage

```bash
python process_sensor_data.py       # python3 if Mac
```

## Files

- `sensor_data.xlsx`: Input data
- `process_sensor_data.py`: Analysis script
- `sensor_data_analyzed.xlsx`: Output results

## What It Does

1. Loads Excel data
2. Cleans missing values
3. Calculates averages by equipment
4. Flags high temperature readings (>50°C)
5. Exports results as Excel data

## Requirements

- Python 3.7+
- pandas
