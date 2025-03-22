# Smart-Agriculture-System
# IoT-Based Field Monitoring System

## Project Overview
The **IoT-Based Field Monitoring System** is a smart agriculture solution designed to help farmers efficiently monitor and automate crop irrigation. This system leverages IoT sensors, cloud technology, and mobile applications to provide real-time insights into field conditions.

## Features
- **Real-time Data Monitoring**: Continuously collects data from soil moisture, temperature, and humidity sensors.
- **Automated Irrigation**: Adjusts water supply based on sensor readings to optimize irrigation.
- **Cloud Synchronization**: Uses Firebase to store and synchronize data across devices.
- **Mobile Application**: Android app built with Kotlin for remote access to field data.
- **User Alerts & Notifications**: Sends notifications based on predefined thresholds for soil moisture and weather conditions.

## Technologies Used
- **Hardware**:
  - Raspberry Pi with Grove Pi Plus
  - IoT Sensors (Soil Moisture, Temperature, Humidity)
- **Software**:
  - Python (for Raspberry Pi)
  - Firebase (Cloud Database & Real-time Sync)
  - Kotlin (Android Development)
  - Grove Pi Libraries (Sensor Integration)

## Installation & Setup
### Hardware Setup:
1. Connect the IoT sensors to the Raspberry Pi via the Grove Pi Plus.
2. Ensure all connections are secure and the Raspberry Pi is powered on.

### Software Setup:
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/iot-field-monitoring.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Set up Firebase:
   - Create a Firebase project.
   - Add Firebase Realtime Database and configure authentication.
   - Update Firebase credentials in the project files.
4. Run the IoT data collection script:
   ```sh
   python main.py
   ```
5. Install and run the Android app for remote monitoring.

## Achievements
- Successfully implemented **real-time data synchronization** with Firebase.
- Ensured **system reliability and performance** through optimized sensor data handling.
- Improved irrigation efficiency by automating water supply based on real-time sensor readings.

## Future Enhancements
- Integration with AI-based predictive analytics for better crop management.
- Expansion to support multiple farm locations within a single application.
- Solar-powered system for sustainability and energy efficiency.

## Contributors
- **Your Name** – Developer & Project Lead
- **Team Members (if any)**

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any queries, reach out to **your.email@example.com** or connect via LinkedIn: [Your Profile](https://linkedin.com/in/yourprofile).
