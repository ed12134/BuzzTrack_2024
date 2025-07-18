# BuzzTrack 2024

## Project Overview

**BuzzTrack** is an IoT-based system designed to monitor bee colonies in real-time, addressing challenges in traditional beekeeping such as manual inspections, hive disturbances, and environmental fluctuations. Developed by a team of computer engineering students, the system integrates sensors to track temperature, humidity, hive weight, and bee activity, providing actionable insights to beekeepers via a web application.

## Key Features

- **Environmental Monitoring**:
  - **DHT22 Sensor**: Measures hive temperature (32–36°C optimal) and humidity (50–60% optimal).
  - **CPU Fan**: Automatically activates to regulate hive temperature.

- **Hive Productivity Tracking**:
  - **Load Cell Sensors**: Monitor hive weight (2–3 kg per frame) to assess honey production and colony health.
  - **Reflectance Sensors**: Count bees entering/exiting the hive to analyze foraging activity.

- **Security and Surveillance**:
  - **ESP32 Camera**: Captures images outside the hive every 30 minutes to detect threats (e.g., pests, intruders).

- **Data Visualization**:
  - **Web Application**: Displays real-time data, graphs, and alerts (accessible on desktop/mobile).
  - **SMS Alerts**: Notifies beekeepers of critical changes (e.g., high temperature, weight thresholds).

- **Power Supply**:
  - Solar-powered with a 400 Ah battery backup (84 hours of operation).

## Methodology

- **Research Design**: Mixed-method (qualitative interviews + developmental research).
- **Testing**: Conducted at the National Apiculture Research Training and Development Institute (NARTDI) with 20 participants (beekeepers, researchers, technical experts).
- **Evaluation**:
  - **Technical Feasibility**: Rated "Excellent" for durability (4.13/5), simplicity (4.67/5), and precision (4.0/5).
  - **Usability**: High satisfaction (4.29/5) for effectiveness, efficiency, and user interface.

## Results

- **Effectiveness**: Achieved a 4.21 grand mean rating, confirming reliable monitoring of hive conditions.
- **Cost**: Total project cost: ₱14,215 (including labor).

## Conclusion & Recommendations

BuzzTrack proved viable for enhancing beekeeping through automation, reducing manual labor, and improving hive management. Future recommendations include:

- Adding varroa mite detection via camera alerts.
- Implementing live pollen monitoring.
- Expanding to multiple hive boxes for scalability.
- Resolving PLDT WiFi restrictions with a proxy server.

## Significance

The system supports sustainable apiculture by optimizing productivity, minimizing bee stress, and providing data-driven insights for conservation efforts.

## Tech Stack

Here are the technologies used in the BuzzTrack project:

- **Frontend**: 
  - ![HTML5](https://img.icons8.com/color/48/000000/html-5.png) HTML5
  - ![CSS3](https://img.icons8.com/color/48/000000/css3.png) CSS3
  - ![JavaScript](https://img.icons8.com/color/48/000000/javascript.png) JavaScript
  - ![React](https://img.icons8.com/color/48/000000/react-native.png) React

- **Backend**: 
  - ![Node.js](https://img.icons8.com/color/48/000000/nodejs.png) Node.js
  - ![Express](https://img.icons8.com/color/48/000000/express.png) Express

- **Database**: 
  - ![MySQL](https://img.icons8.com/color/48/000000/mysql.png) MySQL

- **Deployment**: 
  - ![Heroku](https://img.icons8.com/color/48/000000/heroku.png) Heroku

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ed12134/BuzzTrack_2024.git
