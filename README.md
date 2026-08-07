Quadruped Robot - Preliminary Mechanical Design
📌 Overview
This project presents the preliminary mechanical design of a simple quadruped (four-legged) robot. The main objective is to understand the basic mechanical principles required to build a stable walking robot rather than developing a fully functional robotic system.

🎯 Objectives
Design a simple robot body and chassis.
Design four robotic legs.
Determine the number of joints and Degrees of Freedom (DOF).
Select suitable servo motors.
Perform a preliminary torque calculation.
Ensure stability by considering the center of gravity.
Propose a walking gait.
Identify expected mechanical challenges.
🛠️ Mechanical Design
Robot Body
Rectangular chassis made of lightweight aluminum or acrylic.
Approximate dimensions:
Length: 30 cm
Width: 18 cm
Height: 10 cm
Battery and electronics are placed at the center to improve stability.
Leg Design
Each leg consists of:

Hip joint
Upper leg
Knee joint
Lower leg
Rubber foot for better grip
⚙️ Degrees of Freedom (DOF)
Each leg has:

1 Hip Joint
1 Knee Joint
Total DOF:

4 Legs × 2 DOF = 8 DOF

🔋 Servo Motor Selection
Servo Motor: MG996R

Features:

Torque: Approximately 11 kg·cm
Operating Voltage: 6V
Affordable and widely used in educational robotics projects.
📐 Preliminary Torque Calculation
Assumptions:

Robot weight = 2 kg
Load per leg = 0.5 kg
Leg length = 0.1 m
Force:

F = 0.5 × 9.81 = 4.9 N

Torque:

Torque = Force × Distance

Torque = 4.9 × 0.1 = 0.49 N·m

Therefore, a servo capable of producing at least 0.5 N·m is recommended.

⚖️ Stability
To improve stability:

Place the battery at the center of the chassis.
Evenly distribute electronic components.
Keep the center of gravity near the middle of the robot.
🚶 Walking Gait
The proposed gait is an Alternating Walk Gait:

Front Right + Rear Left
Front Left + Rear Right
This gait provides good stability and is easy to implement.

⚠️ Expected Mechanical Challenges
Robot vibration during walking.
High power consumption.
Foot slippage on smooth surfaces.
Servo overheating under heavy loads.
Loss of balance if the weight distribution is uneven.


📚 Conclusion
This project introduces a simple preliminary mechanical design for a quadruped robot with eight degrees of freedom. The design focuses on simplicity, stability, and educational value while demonstrating the essential concepts of robotic mechanical engineering
