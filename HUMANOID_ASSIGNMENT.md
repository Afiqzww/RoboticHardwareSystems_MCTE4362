# The Humanoid Robot

A humanoid robot is a robot that resembles the human body in shape and structure. These robots are designed to interact with human tools and environments, conduct experiments related to bipedal locomotion, and serve various other purposes. Typically, humanoid robots have a torso, a head, two arms, and two legs, although some may replicate only part of the body, such as the upper half. Some humanoid robots are also equipped with heads designed to replicate human facial features like eyes and mouths. Androids, on the other hand, are a specific type of humanoid robot that are built to aesthetically resemble humans

## Contents

- [History](#History)
- [Composition](#Composition)
  - [Frame](#Frame)
  - [Locomotion](#Locomotion)
  - [Navigation](#Navigation)
  - [Data Collection](#[Data-Collection)
  - [Data Transmission](#Data-Transmission)
  - [Power Management](#Power-Management)

## History

- In the 13th century, a Muslim engineer named Ismail al-Jazari designed various humanoid automata. He created a waitress robot that could dispense drinks

<img src="https://upload.wikimedia.org/wikipedia/commons/7/76/Al-jazari_elephant_clock.png" width="400" height="600">

- During the Renaissance period, there were advancements in automata design. Italian inventor Leonardo da Vinci sketched and conceptualized humanoid robots, including a mechanical knight

<img src="https://media.gq-magazine.co.uk/photos/5d139955d7a70181fcbba917/master/w_1600%2Cc_limit/Robot-Knight-GQ_11Feb16_getty_b.jpg" width="400" height="600">

- 18th and 19th centuries: During this period, inventors and engineers continued to explore the creation of humanoid robots. Jacques de Vaucanson, a French engineer, constructed mechanical automata, including a life-sized flute player and a digesting duck

<img src="https://media.springernature.com/lw685/springer-static/image/chp%3A10.1007%2F978-3-030-32398-1_2/MediaObjects/448627_1_En_2_Fig10_HTML.png" width="400" height="600">

- Pre-Modern Humanoid robots

|Name|Description|Image|
|---|---|---|
|Gakutensoku|Gakutensoku: In 1928, Japanese engineer Makoto Nishimura built Gakutensoku, one of the first modern humanoid robots. It was capable of facial and body movements|<img src="https://upload.wikimedia.org/wikipedia/commons/d/de/Gakutensokuold.jpg">|
|Elektro|Elektro: Created by Westinghouse Electric Corporation in 1939, Elektro was a humanoid robot that could speak, walk, and smoke cigarettes|<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Senator_John_Heinz_History_Center_-_IMG_7802.JPG/1200px-Senator_John_Heinz_History_Center_-_IMG_7802.JPG">|
|Shakey|Shakey: Developed by SRI International in the late 1960s, Shakey was a pioneering robot that could navigate its environment and perform tasks. It utilized artificial intelligence and computer vision|<img src="https://history-computer.com/wp-content/uploads/2021/01/RosenAndShakey1983.webp">|
|WABOT| WABOT series: The WABOT series of robots, developed by Waseda University in Japan starting from the 1970s, aimed to create humanoid robots capable of human-like movements and interactions|<img src="https://www.humanoid.waseda.ac.jp/booklet/photo/WABOT-1-1973.jpg">|
|ASIMO|ASIMO: Honda's Advanced Step in Innovative Mobility (ASIMO) robot was introduced in 2000. ASIMO featured advanced mobility, dexterity, and the ability to recognize human faces and voices|<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0c/Honda_ASIMO_%28ver._2011%29_2011_Tokyo_Motor_Show.jpg/1200px-Honda_ASIMO_%28ver._2011%29_2011_Tokyo_Motor_Show.jpg">|

- In recent years, advancements in robotics have led to the development of various humanoid robots, each with its unique capabilities. Some notable examples include Boston Dynamics' Atlas robot, SoftBank Robotics' Pepper robot, and Hanson Robotics' Sophia robot

|Name|Description|Image|
|---|---|---|
|Atlas|Atlas is a bipedal humanoid robot developed primarily by Boston Dynamics, a robotics company based in the United States. It was created with the support and funding of the U.S. Defense Advanced Research Projects Agency (DARPA) and was initially designed for search and rescue missions|<img src="https://cdn.mos.cms.futurecdn.net/s9sxXfjdJwNhnpAoHgFegF.jpg">|
|Pepper|Pepper was the world’s first social humanoid robot able to recognize faces and basic human emotions. Pepper was optimized for human interaction and is able to engage with people through conversation and his touch screen.|<img src="https://upload.wikimedia.org/wikipedia/commons/a/a1/SoftBank_pepper.JPG">|
|Sophia|Sophia is a social humanoid robot developed by the Hong Kong-based company Hanson Robotics. Sophia is marketed as a "social robot" that can mimic social behavior and induce feelings of love in humans.|<img src="https://upload.wikimedia.org/wikipedia/commons/1/1e/Sophia_at_the_AI_for_Good_Global_Summit_2018_%2827254369347%29_%28cropped%29.jpg" >|

## Composition

![](https://media.springernature.com/lw685/springer-static/image/chp%3A10.1007%2F978-3-030-30036-4_23/MediaObjects/465912_1_En_23_Fig2_HTML.png)

### Frame

Humanoid robots are robots designed to resemble the human body in shape. They typically have a torso, a head, two arms, and two legs, though some may replicate only part of the body, such as from the waist up. Some humanoid robots also feature heads designed to replicate human facial features like eyes and mouths. The body design of modern humanoid robots aims to achieve functionality, interaction with human tools and environments, and, in some cases, an aesthetic resemblance to humans.

![](https://supercarblondie.com/wp-content/uploads/Ameca-humanoid-robot-hero.jpg)

Modern humanoid robots incorporate advanced technological methods for their body design. These methods include manufacturing lightweight/complex materials by 3D printing, generative design, and other processes to replicate bones, muscles, and tendons. By reproducing the human body with such detail, engineers can create robots that have a more human-like appearance and movement capabilities

### Locomotion

Locomotion used in various nature replicated robots are based of legged locomtion in which the kinematics of the legs in this case humanoid is replicated but replaced with electrical and mechanical components.

![](https://pub.mdpi-res.com/micromachines/micromachines-13-01688/article_deploy/html/images/micromachines-13-01688-g001.png?1666431014)

This involves the planning and control of dynamic motions to achieve versatile and complex behaviors. Several methods and approaches have been proposed to address the challenges in locomotion planning and control for legged robots.

![](https://journals.sagepub.com/cms/10.5772/52452/asset/images/large/10.5772_52452-fig1.jpeg)

One approach mentioned in the provided information is the Trajectory Optimization for Walking Robots Plus (TOWR+). TOWR+ is a method for dynamic locomotion planning that utilizes trajectory optimization to generate motions for walking robots. It aims to create versatile locomotion behaviors for humanoid robots in diverse terrains 

![](https://www.researchgate.net/publication/353885579/figure/fig2/AS:1056334304772096@1628861132677/A-The-TOWR-locomotion-planning-algorithm-is-presented-B-Illustrative-examples-of.png)

This process involves inverse kinematics which is the process of computing the joint angles or joint values that correspond to a desired position and orientation of the robot's end effector or body. The purpose of inverse kinematics is to determine the joint configurations required to achieve a specific pose or trajectory in the operational space

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSi0H-duGTjR66yhi3Z-2Dlk3xpCgS_RV6QctlKxVlz9t43ASV8v8TX-PT4dLRrwRv12D0&usqp=CAU)

### Navigation

The complex area of Humanoid robot navigation focuses on the movement in various environments. It involves the combination of Sensors and the development of strategies and techniques to enable smooth and efficient navigation for these robots.

- Sensors

-Laser Range Finders (Lidar): Lidar sensors use laser beams to measure the distance and create a detailed 3D map of the surrounding environment. This information helps robots to detect obstacles, navigate in complex environments, and perform mapping and localization tasks.

-Cameras: Cameras, such as RGB and RGB-D cameras, are widely used in humanoid robots for vision-based navigation. They capture visual information from the environment, enabling the robot to perceive objects, recognize landmarks, and estimate its position and orientation.

-Tactile Sensors: Tactile sensors provide robots with the sense of touch, allowing them to detect contact, pressure, and force exerted on their bodies or end-effectors. By integrating tactile feedback, robots can navigate safely, interact with objects, and respond appropriately in human-robot interaction scenarios.

-Inertial Measurement Units (IMUs): IMUs consist of sensors such as accelerometers, gyroscopes, and magnetometers. They measure the robot's linear acceleration, angular velocity, and magnetic field orientation. IMUs are used for estimating the robot's motion, orientation, and stabilization, which are essential for navigation and control.

-Ultrasonic Sensors: Ultrasonic sensors emit high-frequency sound waves and measure the time it takes for the waves to bounce back after hitting objects. They are used for obstacle detection and proximity sensing, helping robots avoid collisions and navigate in confined spaces.

- Path planning

-Environment Representation: To perform path planning, the robot needs information about its environment. This information can be obtained through various sensors such as lidar, cameras, or depth sensors. The robot constructs a representation of the environment, often in the form of a grid map or a geometric model, which is used for path planning.

Obstacle Detection and Avoidance: Path planning algorithms take into account the presence of obstacles in the environment and generate paths that avoid collisions. The robot uses its sensors to detect obstacles and incorporates this information into the planning process. Techniques like potential fields, rapidly exploring random trees (RRT), or A* search are commonly used for obstacle avoidance and finding collision-free paths.

Path Generation and Optimization: Once the robot has information about the environment and obstacles, it generates a path from the start position to the goal position. This path can be represented as a sequence of waypoints or a continuous trajectory. Path planning algorithms aim to find the optimal or near-optimal path based on certain criteria, such as minimizing distance, energy consumption, or considering dynamic constraints of the robot.

Real-time Adaptation: Path planning for humanoid robots often requires real-time adaptation to dynamic environments. The robot continuously updates its perception of the environment and adjusts its planned path accordingly. This adaptive behavior enables the robot to handle changing obstacles, new information, or unexpected events during navigation.

Integration with Control and Localization: Path planning is closely integrated with robot control and localization. The planned path is used by the robot's control system to generate motion commands for achieving the desired trajectory. Localization techniques, such as simultaneous localization and mapping (SLAM), can provide the robot with accurate position information for effective path planning and execution.

### Data Collection

A humanoid robot should be equipped with the standard sensors any semi/autonomous robot requires for efficient operation, control, function.

- Vision Sensors: Vision plays a crucial role in human-robot interaction, and humanoid robots often utilize vision sensors to perceive their surroundings. These sensors can include cameras, depth sensors (such as time-of-flight or structured light sensors), and stereo vision systems. Vision sensors enable robots to recognize objects, navigate their environment, detect obstacles, and interpret visual cues for interaction.

- Tactile Sensors: Tactile sensors provide robots with the ability to sense and understand physical contact with objects or humans. They can be in the form of arrays or individual sensors distributed across the robot's body or specifically designed for the robot's hands. Tactile sensors use pressure, force, or deformation measurements to determine the tactile feedback. These sensors are valuable for object recognition, grasping, manipulation, and human-robot interaction.

- Inertial Measurement Units (IMUs): IMUs consist of accelerometers, gyroscopes, and sometimes magnetometers. These sensors measure the robot's linear acceleration, angular velocity, and orientation in space. IMUs are essential for balance control, motion tracking, and posture estimation in humanoid robots. They provide information about the robot's position, velocity, and orientation.

- Joint Position and Force Sensors: Humanoid robots often employ joint position sensors (encoders) to measure the angles and positions of their limbs and joints. These sensors provide feedback for precise control of movements. Additionally, force/torque sensors integrated into the joints or end effectors enable the robot to sense external forces and apply appropriate forces during interaction or manipulation tasks.

- Microphones: Sound sensors, such as microphones, enable humanoid robots to perceive and interpret auditory information. By analyzing sounds and speech, robots can engage in verbal communication, recognize voice commands, and interact with humans through speech interfaces.

- Range Sensors: Range sensors, including laser range finders or LiDAR (Light Detection and Ranging) sensors, provide robots with depth information and allow them to perceive the shape and distance of objects in their environment. These sensors are valuable for mapping, localization, and obstacle avoidance.

- Environmental Sensors: Humanoid robots can benefit from additional environmental sensors like temperature sensors, humidity sensors, gas sensors, or ambient light sensors. These sensors enable the robot to gather contextual information about the environment and adapt its behavior accordingly.

### Data Transmission

Humanoid robots need a communication system to transmit and receive data. This system allows the robot to communicate with external devices, such as a central control system or other robots, and exchange information. Common communication interfaces used in humanoid robots include Ethernet, Wi-Fi, Bluetooth, and CAN (Controller Area Network). They also require a network architecture to facilitate communication among their internal components. This architecture may involve a combination of wired and wireless communication protocols mentioned previously.

### Power Management

- Power Source: Humanoid robots are usually powered by rechargeable batteries or external power supplies. The choice of power source depends on factors such as robot size, weight, and operational requirements. Batteries provide mobility and portability, while external power supplies may be used for stationary robots or when a continuous power source is available.

- Power Distribution System: The power distribution system is responsible for routing and regulating the power supply to different components of the humanoid robot. It includes circuitry such as power distribution boards, voltage regulators, and connectors to ensure proper distribution of power to various subsystems.

- Power Monitoring and Management: To optimize power usage and prevent power-related issues, humanoid robots often incorporate power monitoring and management systems. These systems monitor power consumption, battery levels, and charging status to provide feedback on the robot's energy status. They may also implement power-saving strategies, such as sleep modes or dynamic power allocation, to conserve energy and prolong the robot's autonomy.





