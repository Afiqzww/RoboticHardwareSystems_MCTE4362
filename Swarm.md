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
  - [Locomotion](#Locomotion)
  - [Data Collection](#[Data-Collection)
  - [Data Transmission](#Data-Transmission)


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
- 
| Types | Description	| Example |
|--|--|--|
|Drone| Drones are used as swarm robots due to their mobility and versatility | ![](https://dp9eps5gd5xd0.cloudfront.net/images/Article_Images/ImageForArticle_4(1).jpg) | 

- Ground

| Types | Description	| Example |
|--|--|--|
|Wheeled| Suitable for flat or moderately uneven terrains and can navigate indoor and outdoor environments effectively. | ![-](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.latestgkgs.com%2Frobotarium-3860-a&psig=AOvVaw3eQt36-Zet1DxnzPOkj2OI&ust=1683984431707000&source=images&cd=vfe&ved=0CA4QjRxqFwoTCPjN6bLx7_4CFQAAAAAdAAAAABAD) |
|Insect/Animal|  Inspired by animals or insects, have multiple legs that provide enhanced mobility and maneuverability in complex and challenging terrains. Legged swarm robots can traverse uneven surfaces, climb obstacles, or navigate rough terrains where wheeled robots might struggle. | ![-](https://cdn.sci.news/images/enlarge9/image_10180e-Four-Legged-Robots.jpg) |

### Navigation

