# Sridharshini_project
1. Project Overview
The Smart Home Automation System is an IoT-based project designed to integrate appliance control, video doorbell communication, and distributed Bluetooth audio into a unified smart home environment.

The system uses Raspberry Pi and Home Assistant as the central home automation platform, along with custom-designed PCBs and embedded hardware for device control and integration.

The project combines embedded systems, wireless communication, hardware design, and audio-video integration to develop a practical smart home solution.

 2. Objectives
- Develop a centralized home automation system using Raspberry Pi and Home Assistant.
- Enable convenient control and monitoring of connected home appliances.
- Design and integrate custom PCBs for the automation hardware.
- Develop a video doorbell with camera, display, microphone, and speaker integration.
- Implement two-way audio communication between the outdoor doorbell and indoor display.
- Develop a Bluetooth audio amplifier and ceiling speaker system.
- Integrate hardware and software components into a functional smart home platform.

3. Hardware Components

| Component | Application |
| Raspberry Pi 5 | Central home automation server |
| Home Assistant | Appliance control and device management |
| ESP32 / NodeMCU | Embedded appliance-control hardware |
| Relay modules | Switching connected electrical appliances |
| Custom PCB | Hardware integration and circuit implementation |
| Camera module | Video capture for the doorbell |
| ESP32-S3 | Embedded video doorbell and communication functions |
| Microphone | Audio input for two-way communication |
| Audio amplifier | Audio signal amplification |
| Speaker | Indoor communication and ceiling audio playback |
| Bluetooth audio hardware | Wireless audio streaming |


 4. Software and Technologies

- Home Assistant
- Raspberry Pi
- ESP32 and ESP32-S3
- ESPHome
- Embedded C/C++
- Arduino IDE
- YAML configuration
- Wi-Fi communication
- PCB design
- Bluetooth audio integration

5. System Architecture

The project consists of three primary subsystems.

A. Home Automation

Raspberry Pi runs Home Assistant and provides a centralized interface for appliance control and device management.

ESP32-based controllers interface with relay hardware to control connected appliances. Communication between the controllers and Home Assistant enables dashboard-based operation.

B. Smart Video Doorbell

The video doorbell integrates a camera, microphone, speaker, and indoor display.

When the doorbell button is pressed, the system is designed to provide video and audio communication between the outdoor unit and the indoor display.

The system integrates embedded processing, camera interfacing, display control, and audio communication.

C. Bluetooth Ceiling Speaker

A Bluetooth audio amplifier and ceiling speaker system provide wireless audio playback in the home.

The audio subsystem combines amplifier hardware, speakers, and a suitable power supply to support permanent ceiling-mounted audio playback.

Overall System Flow


                 SMART HOME SYSTEM
                         |
          +--------------+--------------+
          |              |              |
          v              v              v
    Home Automation  Video Doorbell  Bluetooth Audio
          |              |              |
          v              v              v
    Raspberry Pi     Camera + Mic    Bluetooth Input
    Home Assistant   Indoor Display        |
          |          + Speaker              v
          v                          Audio Amplifier
    ESP32 Controller                        |
          |                                 v
          v                          Ceiling Speaker
     Relay Modules
          |
          v
    Home Appliances


6. Home Automation Implementation

The home automation subsystem uses Raspberry Pi and Home Assistant to manage connected appliances.

ESP32-based controllers interface with relay modules and physical wall switches. ESPHome provides the firmware configuration for supported controllers.

The system is organized into the following functional blocks:

- Centralized device management using Home Assistant.
- Communication between Home Assistant and ESP32 controllers.
- Relay-based appliance switching.
- Integration of physical wall switches.
- Organization of devices into Home Assistant areas.

7. Video Doorbell Implementation

The video doorbell was designed by integrating embedded hardware and audio-video components.

Main Features

- Camera-based video capture.
- Microphone interfacing for audio input.
- Speaker output for audio playback.
- Indoor display for the doorbell interface.
- Two-way audio communication.
- Button-triggered doorbell operation.

The subsystem demonstrates embedded hardware integration, audio interfacing, camera integration, and communication between indoor and outdoor devices.

8. Bluetooth Ceiling Speaker Implementation

The ceiling speaker subsystem provides wireless audio playback using Bluetooth audio hardware, an amplifier, and ceiling-mounted speakers.

Main Features

- Bluetooth audio connectivity.
- Audio amplifier integration.
- Permanent ceiling speaker installation.
- Dedicated audio hardware and power supply.
- Integration of audio components into the smart home environment.

9. Custom PCB Design

Custom PCB design was incorporated into the home automation hardware to support component integration and system implementation.

The PCB documentation can include:

- Circuit schematics.
- PCB layout files.
- Component list and specifications.
- Connector and GPIO assignments.
- Power distribution details.
- Hardware assembly photographs.

Upload your actual PCB design files and photographs if you want to demonstrate your hardware design skills.

10. Results and Validation

The project integrates home automation, video doorbell functionality, and Bluetooth audio hardware.

Use this section to document the actual results obtained from your implementation.

Suggested evidence includes:

- Raspberry Pi and Home Assistant setup.
- ESP32 controller and relay board photographs.
- Home Assistant dashboard screenshots.
- Custom PCB photographs.
- Indoor and outdoor video doorbell hardware.
- Two-way audio communication tests.
- Bluetooth ceiling speaker test results.

Include only features that you have implemented and tested.

11. Applications

- Smart residential buildings.
- IoT-based appliance control.
- Embedded home automation.
- Smart doorbell and visitor communication systems.
- Wireless audio playback.
- Hardware and software integration projects.

12. Future Enhancements

Potential future improvements include:

- Gesture-based appliance control using an MPU6050 sensor.
- Edge AI-based gesture recognition.
- Energy consumption monitoring.
- Occupancy-based lighting control.
- Intelligent automation based on sensor data.
- Integration with additional smart home devices.

These enhancements are proposed features unless they have already been implemented and validated.

13. Safety Considerations

Electrical appliances may operate at hazardous mains voltages. Relay modules, PCB layouts, wiring, power supplies, and enclosures must be designed for the intended loads and appropriate electrical safety requirements.

Mains-voltage construction and testing should be performed by a qualified person using appropriate isolation and protective measures.

Sensitive configuration information, Wi-Fi credentials, API tokens, and encryption keys must be removed before publishing project files.

14. Conclusion

The Smart Home Automation System demonstrates the integration of IoT, embedded systems, custom hardware, and wireless communication.

By combining Raspberry Pi and Home Assistant-based appliance management with a video doorbell and Bluetooth ceiling speaker system, the project brings multiple electronic subsystems into a unified smart home environment.

The project provides practical experience in embedded development, PCB design, hardware-software integration, communication interfaces, and IoT system implementation.

15. Technical Skills Demonstrated

- Embedded Systems
- Internet of Things (IoT)
- Raspberry Pi
- Home Assistant
- ESP32 Microcontrollers
- ESPHome
- PCB Design
- Hardware-Software Integration
- Audio Interfacing
- Camera and Display Integration
- Wireless Communication

 Author

Project:Smart Home Automation System

Domain: Embedded Systems | IoT | Home Automation | Hardware Design

Platform: Raspberry Pi, Home Assistant, ESP32
