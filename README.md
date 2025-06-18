Industrial Internet of Things

Smart Irrigation System using Cisco Packet Tracer

Mid-Course Project

L&T EDUTECH
Certificate in industrial IoT Architecture and Applications

By

Amarjit Samal

Electrical and Electronics Engineering ,
Vellore Institute of Technology ,Chennai

amarjitsamal787@gmail.com

1. Aim
To design and simulate a smart irrigation system that monitors soil moisture levels and automatically activates irrigation (sprinklers) only when necessary, thereby optimizing water usage in agricultural fields.

2. Problem Statement
Traditional irrigation systems operate on fixed schedules without considering real-time soil moisture conditions. This results in:
Wastage of water resources.
Poor crop yield due to over-irrigation or under-irrigation. The need is for an intelligent irrigation system that dynamically responds to soil conditions.

3. Scope of the Solution
Real-time monitoring of soil (simulated via water level sensors).
Automatic triggering of sprinklers based on water level threshold.
Visualization and control via IoT dashboard on a smartphone or computer.
Easily scalable for large agricultural deployments.
Fully simulated using Cisco Packet Tracer’s IoT devices and interface.

4. Architecture of the Solution
Diagram Summary :
Two water level monitors simulate soil moisture at two field zones.
A Home Gateway (IoT-enabled router) connects all devices.
Four lawn sprinklers simulate irrigation outputs.
A smartphone accesses the IoT server via Wi-Fi to set conditions and monitor status.
Logic conditions are defined to:
Turn on sprinklers when water level < 5.0 cm (dry soil).
Turn off sprinklers when water level > 5.0 cm (sufficient moisture).
Data Flow:
Sensors → Measure water level.
Gateway → Reads data and applies logic.
Sprinklers → Automatically turned on/off.
Smartphone/Web → Allows manual view and control of system state.

5. Required Components (from Cisco Packet Tracer)
Water Level Monitor - Simulates soil moisture sensors.
Lawn Sprinkler - Simulates irrigation output (on = water released).
Home Gateway - Central IoT gateway that collects data and triggers actuators.
Smartphone  - Used to configure rules and view status via IoT server.
IoT Server Interface - Accessed via browser at http://192.168.25.1 to configure device conditions.
