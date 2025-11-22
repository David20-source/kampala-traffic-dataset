Kampala Smart Traffic Dataset

## Overview
A comprehensive traffic dataset containing 500 observations collected from 15 major roads in Kampala City, Uganda. This dataset is designed for traffic congestion analysis and machine learning applications.

## Dataset Specifications
- **Records**: 500 observations
- **Roads**: 15 major arterial roads
- **Time Period**: Multiple weeks coverage
- **Features**: 13 original features + 4 engineered features

## Features Description

### Temporal Features
- `hour`: Hour of day (0-23)
- `day_of_week`: Day of week (0-6)
- `is_weekend`: Weekend indicator (0/1)

### Spatial Features
- `road_name`: Name of the road segment

### Traffic Flow Metrics
- `traffic_volume`: Number of vehicles per time period
- `avg_speed_kmh`: Average vehicle speed in km/h
- `vehicle_density`: Vehicles per km per lane

### Incident Data
- `incident_flag`: Presence of traffic incident (0/1)
- `incident_type`: Type of incident

### Environmental Factors
- `weather_main`: Weather condition

### Road Infrastructure
- `road_capacity`: Maximum designed vehicle capacity

### Engineered Features
- `rolling_mean_3h`: 3-hour rolling average
- `capacity_utilization`: Volume to capacity ratio
- `time_period`: Time period of day
- `day_type`: Type of day
- `flow_efficiency`: Speed to volume ratio

### Target Variable
- `congestion_level`: Traffic congestion level (Low, Medium, High, Severe)

## Usage
This dataset is ideal for:
- Traffic congestion prediction
- Machine learning classification
- Urban mobility research
- Transportation planning

## Citation
If you use this dataset in your research, please cite:
Kampala Smart Traffic Dataset. (2025). Retrieved from https://github.com/David20-source/kampala-traffic-dataset

text

## License
MIT License

Copyright (c) 2025 Nyanzwengye David, Ssebaggala Edward, Lwanga Charles

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Authors
- Nyanzwengye David
- Ssebaggala Edward
- Lwanga Charles
- Muteesa I Royal University, Department of Information Technology
