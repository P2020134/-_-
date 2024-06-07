# Απαλλακτική Εργασία για το μάθημα "Έξυπνα Περιβάλλοντα"
## Από τους φοιτητές
- **Αλέξανδρος Γιανκούλης ΑΜ Π2020134**
- **Φελλαχίδης Γεώργιος ΑΜ Π2020182**

# FireGuard: Fire Detection System Using Arduino

## Table of Contents
1. [Introduction](#introduction)
2. [Components and Technologies](#components-and-technologies)
3. [Data Collection from Sensors](#data-collection-from-sensors)
4. [Intelligence of the System](#intelligence-of-the-system)
5. [Interaction with the Environment](#interaction-with-the-environment)
6. [Evaluation and Effectiveness](#evaluation-and-effectiveness)
7. [Application Limitations](#application-limitations)
8. [Future Prospects](#future-prospects)
9. [Development Methodology](#development-methodology)
10. [User Evaluation Methodology](#user-evaluation-methodology)

## Introduction
Fire is one of the most destructive and concerning phenomena that can affect our homes. According to an article from Reader.gr, nearly 4,000 house fires occur in Greece each year. This number is alarming and underscores the need for effective prevention measures and timely detection.

The proposed fire detection system includes a smoke and temperature sensor connected to an Arduino, which processes the data and triggers an alarm as soon as smoke or a rapid temperature change is detected. Additionally, the device can send notifications to a connected mobile application, allowing users to receive immediate updates regardless of their location.

## Components and Technologies
The fire detection device relies on a series of technological elements and components for its effective operation. The general architecture of the device includes:
- **Arduino**: The heart of the device, processing data from sensors and controlling outputs.
- **Temperature Sensor**: Detects temperature increases that may indicate a fire.
- **Smoke Detector**: Detects the presence of smoke in the air.
- **Buzzer**: Emits a sound to alert users in case of danger.
- **LED**: Provides a visual alert when a fire is detected.
- **LCD Display**: Shows real-time information on sensor status and alerts.
- **Resistors**: Ensure the proper functioning of various electronic components.
- **Push Button**: Used to reset the system or confirm alerts.

## Data Collection from Sensors
The device collects two main types of data from the sensors:
- **Temperature**: Monitored continuously by the temperature sensor. When the temperature exceeds a predefined limit (e.g., 50°C), the system triggers alerts.
- **Smoke**: Detected by the smoke sensor, which can identify the presence of smoke in the air. When smoke levels exceed a set threshold, the system triggers alerts.

## Intelligence of the System
The smart fire detection device combines and analyzes data from the temperature and smoke sensors to provide accurate and reliable alerts:
- **Combining Data Analysis**: The system integrates temperature and smoke data to determine the presence of fire, reducing false positives.

## Interaction with the Environment
The device utilizes information from temperature and smoke sensors to trigger the following:
- **Visual Alerts**: The LED lights up to visually alert users of danger.
- **Auditory Alerts**: The buzzer emits a loud sound to alert users audibly.
- **LCD Display**: Shows specific information such as current temperature, smoke presence, and system status. In case of danger, the screen displays warning messages and user instructions.

## Evaluation and Effectiveness
The effectiveness of the system will be evaluated through the following steps:
- **Real-Scenario Testing**: Testing the device in various fire scenarios with controlled temperature and smoke increases to verify detection accuracy and alert speed.
- **Data Analysis**: Collecting and analyzing data from tests to evaluate detection accuracy, the number of false positives and negatives, and system response.
- **User Feedback**: Gathering feedback from users on their experience, the reliability of alerts, and ease of use.

## Application Limitations
Several limitations must be considered for the application completion:
- **Sensor Accuracy**: Temperature and smoke sensors may have limitations in accuracy and sensitivity.
- **Energy Consumption**: The device may require high energy consumption, especially if battery-operated, which can limit the device's lifespan.
- **Environmental Factors**: Sensor performance may be affected by environmental factors such as humidity, dust, and noise.
- **Hardware Compatibility**: Careful selection and integration of various components are necessary to ensure compatibility and system stability.

## Future Prospects
- **Function Expansion**: Adding additional sensors for detecting other environmental parameters, such as humidity or carbon monoxide.
- **Networking and Integration**: Developing networking capabilities to connect the device with other smart devices and integrate it into smart home systems.
- **Algorithm Improvements**: Enhancing data analysis algorithms for better prediction and detection of fire risks.

## Development Methodology
The methodology for developing FireGuard included:
1. **Conceptualization**: Identifying the need for a fire detection system.
2. **Component Selection**: Choosing appropriate sensors and components.
3. **Circuit Design**: Creating the schematic and layout.
4. **Programming**: Writing code for the Arduino to process sensor data and trigger alerts.
5. **Prototyping**: Building and testing a prototype.
6. **Testing**: Conducting real-scenario tests to evaluate performance.
7. **Iteration**: Refining the design based on test results and feedback.

## User Evaluation Methodology
To evaluate the application from the user's perspective:
1. **Qualitative Research**: Conducting interviews where participants evaluate the prototype/demo.
2. **Technological Limitations**: Identifying potential technological constraints.
3. **Conclusion Formulation**: Summarizing findings and making recommendations.
4. **Future Utilization and Development Prospects**: Assessing potential for future use and improvements.

---

By following this structured approach, FireGuard aims to provide a reliable and effective solution for early fire detection in residential and business environments.
