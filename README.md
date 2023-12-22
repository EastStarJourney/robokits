# roboKits

## Introduction
RoboKits is an innovative project that focuses on abstracting various fundamental motion control systems for robots based on principles of dynamics and kinematics. The project aims to provide a comprehensive set of control components, known as kits, for essential robot behaviors such as grasping, movement, balance, and flexibility. These kits collectively form the RoboKits Motion Control Library, offering a versatile solution for a wide range of robotic motion control applications.

## Components
The project is divided into three main components:

1. Kits Lab: Basic Motion Control Models
The Kits Lab comprises a collection of fundamental motion control models that serve as the building blocks for robot behaviors. These models are designed to be modular and can be easily integrated to create complex motion sequences.

2. Kits Dev: Motion Control Modeling
Kits Dev focuses on motion control modeling, providing tools and frameworks for developers to design and customize motion behaviors for specific robotic applications. This component facilitates the creation of tailored solutions for diverse robotic scenarios.

3. Kits Runtime: Actuators and Execution
Kits Runtime is responsible for the execution of motion control models in real-world scenarios. It includes components for interfacing with actuators and managing the runtime behavior of robots, ensuring seamless translation of motion control models into physical actions.

## Advanced Features
1. Hybrid Control Support
RoboKits supports a variety of hybrid control configurations, including serial, parallel, and mixed structures. This flexibility enables the implementation of diverse and complex control strategies to meet the motion control requirements of humanoid robots in various scenarios.

2. Adaptive Motion Control Learning
Taking inspiration from human locomotion, RoboKits employs a novel "pendulum-like" approach to estimate the target's center of mass, geometric features, and dynamic characteristics. This innovation streamlines the tuning of Model Predictive Control (MPC) parameters for robots with complex structures, providing adaptive learning capabilities for motion control.

3. Vision-Servo Control
In the realm of flexible control, RoboKits introduces a "visual-servo" control mode, simplifying the complexity of robot motion control. This mode leverages visual information to enhance control precision, making it easier to handle intricate movements and tasks.

## Conclusion
RoboKits is a groundbreaking initiative that not only abstracts fundamental motion control systems but also introduces innovative approaches to enhance adaptability and simplify the control complexity of humanoid robots. Whether you are working on grasping, mobility, balancing, or flexibility, RoboKits provides a comprehensive and flexible solution to meet the diverse needs of robotic motion control in various environments.

## License
This project is provided free and open-source under the MIT license. See the licenses folder for more information.
