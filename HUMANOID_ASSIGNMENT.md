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
