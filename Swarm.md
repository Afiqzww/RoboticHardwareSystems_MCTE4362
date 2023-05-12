# Swarm Robots

- Multiple robots wether homogeneous or heterogeneous are adapted to form a swarm of robots in swarm robotics. Because individual robots have processing, communication, and sensory capabilities on-board, they can communicate with one another and react to their surroundings autonomously.
- Individual robots in swarm robotics are often basic and have limited capabilities. When they work together, they can complete complex tasks and demonstrate cognitive behaviour. Swarm robots' collective behaviour derives from interactions between the robots and their surroundings, as well as interactions between the robots themselves.
- Swarm robotics offers a wide range of applications, including search and rescue, environmental monitoring, construction, agriculture, and transportation. Swarm robotics provides advantages such as resilience, flexibility, fault tolerance, and scalability by using the capabilities of several robots working together.

![](https://media.wired.com/photos/59324a2044db296121d6a21b/3:2/w_1280%2Cc_limit/rubenstein1HR-660.jpg)

## Contents

- [Swarm Robot History](#Swarm-Robot-History)
- [Swarm Robot Application](#Swarm-Robot-Applications)
- [Swarm Robot Composition](#Swarm-Robot-Composition)
  - [Frame](#Frame)
  - [Navigation](#Navigation)
  - [Communication](#Communication)
  - [Data Collection](#[Data-Collection)



## Swarm Robot History

- Early Concepts (1980s-1990s): Swarm robotics concept emerges with researchers like Beni and Wang exploring coordination and cooperation among multiple simple robots.
- Artificial Life and Autonomous Robotics (1990s): Influence of artificial life on swarm robotics, studying self-organizing systems inspired by natural phenomena.
- First Swarm Robotics Experiments (early 2000s): Projects like "Swarmanoid" demonstrate coordination of different robot types for complex tasks.
- Swarm Intelligence (early 2000s): Study of collective behavior in decentralized systems influences swarm robotics.
- Advances in Algorithms and Communication (2000s-current): Continuous developments in swarm robotics algorithms and communication techniques for tasks like formation, recognition, transportation, and exploration.
- Real-World Applications: Swarm robotics finds applications in search and rescue, environmental monitoring, agriculture, construction, and transportation, showcasing practical solutions to various challenges.

## Swarm Robot Applications

|Application|Description|Example|
|---|---|---|
|Search and Rescue| Deployed in disaster scenarios to search for survivors in hazardous environments, such as collapsed buildings or debris. They can quickly cover a large area, communicate with each other, and provide real-time data for efficient search and rescue operations. | ![SnR swarm](https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fmedia1.s-nbcnews.com%2Fj%2Fnewscms%2F2014_04%2F138586%2F140124-rescue-robots-flocking-drones-main_3cf3128f7e1d3ca21d307cd526589731.nbcnews-fp-1240-520.jpg&f=1&nofb=1&ipt=8f42cf52c0c56e578cc6228aa451f8e456782e798222b15fd58f92c8c5ad4492&ipo=images)|
|Environmental Monitoring| Used to monitor and collect data in environmental studies. They can collaborate to gather information about air or water quality, collect samples from different locations, and create a comprehensive understanding of the environment. | ![EM swarm](https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Frobohub.org%2Fwp-content%2Fuploads%2F2016%2F10%2F2-Saga-NOLABELS.jpg&f=1&nofb=1&ipt=e5d83d748eb7b81c9168f83ba25365e04088a440e9634e53e3c37f04152f47bb&ipo=images) |
|Agriculture| Assists in agriculture by performing tasks like crop pollination, planting, and harvesting. They can work collaboratively to cover large fields,  | ![Agri swarm](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse3.mm.bing.net%2Fth%3Fid%3DOIP.rOo15x7zaEjURxkI3IE0vQHaEJ%26pid%3DApi&f=1&ipt=ae2d84ea7122ed5b1837b82e66fa02ea4c6679c8a6704f313756444b4848c876&ipo=images) |

## Swarm Robot Composition

Due to the nature of its use designs and use cases vary widely so we will be discussing two types of swarm robots: Aerial and Ground.

### Frame

Normally small scale, low powered robots are used for swarms since the main principal is quantity over quality.

- Aerial

| Types | Description	| Example |
|--|--|--|
|Drone| Drones are used as swarm robots due to their mobility and versatility | ![](https://dp9eps5gd5xd0.cloudfront.net/images/Article_Images/ImageForArticle_4(1).jpg) | 

- Ground

| Types | Description	| Example |
|--|--|--|
|Wheeled| Suitable for flat or moderately uneven terrains and can navigate indoor and outdoor environments effectively. | ![-](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.techexplorist.com%2Fwp-content%2Fuploads%2F2020%2F02%2FSwarming-robot.jpg&f=1&nofb=1&ipt=4b923890e9312cd1109929915ef02fe498a3ab74512695a5e8097d35f14fdbd7&ipo=images) |
|Insect/Animal|  Inspired by animals or insects, have multiple legs that provide enhanced mobility and maneuverability in complex and challenging terrains. Legged swarm robots can traverse uneven surfaces, climb obstacles, or navigate rough terrains where wheeled robots might struggle. | ![-](https://cdn.sci.news/images/enlarge9/image_10180e-Four-Legged-Robots.jpg) |

### Navigation

- Localization is the process of estimating a robot's position and orientation inside its environment. To identify their location, swarm robots can utilise odometry (measuring wheel or leg rotations), inertial sensors (gyroscopes, accelerometers), or external sensors (GPS, beacons, or motion capture systems).
- Mapping entails constructing a model of the environment in which the swarm robots operate. Swarm robots can map their environment using techniques such as simultaneous localization and mapping (SLAM). Mapping allows the robots to have a spatial sense of their surroundings, plan pathways, and avoid obstacles while navigating.
- In swarm robots, collision avoidance is critical for ensuring safe and smooth navigation. To detect and avoid collisions with objects or other swarm members, swarm robots use several techniques such as proximity sensors, vision systems, or communication among robots. Collision avoidance algorithms enable swarm robots to manoeuvre in a coordinated fashion while keeping a safe distance between themselves and the environment.
- Swarm robots can exchange information and interact with one another to coordinate their motions, share maps or paths, and avoid conflicts or collisions. Swarm robots can achieve collective behaviour while travelling in a coordinated manner thanks to communication protocols, consensus algorithms, or decentralised decision-making processes.

### Communication

Over the years various protocols have been developed for various types of swarm robots and tasks. Here are some commonly used protocols:

![](https://www.mdpi.com/applsci/applsci-10-03661/article_deploy/html/images/applsci-10-03661-g006.png)

| Types | Description	| Example |
|--|--|--|
|


### Data Collection

- Enviromental Data: Swarm robots frequently collect data about their surroundings. Temperature, humidity, air quality, radiation levels, and noise levels are examples of such data.
- Sensor Readings: swarm robots are equipped with a variety of sensors. Sensor data such as distance measurements, proximity detection, light intensity, and sound levels are collected. These sensor readings provide essential information on the physical qualities of objects or barriers in the environment, allowing robots to navigate, avoid collisions, and interact efficiently with their surroundings.
- Visual Data: Swarm robots equipped with cameras or vision sensors capture visual data from their environment. This includes images, video streams, or depth maps that provide visual information about the surroundings. 
- Localization and Mapping Data: Swarm robots gather information on their own localization and mapping. Odometry data (wheel or leg rotations), GPS locations, visual landmarks, or environmental mapping information can all be included. 






