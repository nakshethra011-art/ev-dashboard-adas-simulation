# ev-dashboard-adas-simulation
An EV Dashboard and ADAS (Advanced Driver Assistance System) simulation project built during my internship at Emertxe Information Technologies. The system uses an STM32F103C8T6 microcontroller with HAL libraries to interface with an ultrasonic sensor for obstacle detection and UART for telemetry communication. Real-time EV data (speed, battery status) and ADAS alerts are extracted via UART and visualized using a Python-based dashboard (ev_dashboard.py), with additional simulation and testing done through PICSimLab.
Tech stack:
 STM32F103C8T6 (HAL-based firmware)
 UART communication
 Ultrasonic sensor (obstacle/distance detection)
 Python (dashboard visualization)
 PICSimLab (simulation environment)
Key features:
 Real-time EV telemetry monitoring
 ADAS-style obstacle detection and alerting
