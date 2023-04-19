# The Autonomous Guided Vehicle (AGV) and Autonomous Mobile Robot (AMR)

- AGV stands for Automated Guided Vehicle, and is a mobile robot that transports items or goods from one area to another by following a predetermined path, which is often marked by magnetic tape or wires implanted in the floor. AGVs are often used to automate material handling jobs to boost efficiency in manufacturing, distribution, and warehousing operations.
- AMR stands for Autonomous Mobile Robot, which is a mobile robot that navigates its environment and performs duties using sensors and advanced software rather than pre-programmed paths or physical infrastructure. AMRs are versatile and agile, making them perfect for dynamic environments and tasks that demand regular routing or handling changes. They are utilised in many areas, such as manufacturing, logistics, healthcare, and retail.

![AGV vs AMR](https://aethon.com/wp-content/uploads/2015/04/AMRvs.AGV_.jpg)

## Contents

- [AGV/AMR History](#AGV/AMR-History)
- [AGV/AMR Application](#AGV/AMR-Applications)
- [AGV/AMR Composition](#AGV/AMR-Composition)
  - [Frame](#Frame)
  - [Navigation](#Navigation)
  - [Locomotion](#Locomotion)
  - [Data Collection](#[Data-Collection)
  - [Data Transmission](#Data-Transmission)

## AGV/AMR History

- Automation for material handling and transportation extends back to the early twentieth century. The earliest automated guided vehicles (AGVs) were created in the 1950s and were primarily employed in industrial settings like factories and warehouses. Advances in technology, such as the development of sensors and computer control systems, led to the development of increasingly sophisticated AGVs capable of navigating complicated settings and adapting to changing conditions in the 1980s.

![First AGV](https://www.forkliftaction.com/upload/gallery/3707.jpg?s=1)

- In recent years, there has been increased interest in autonomous mobile robots (AMRs), which are similar to AGVs but have improved sensors and navigation systems that allow them to travel freely throughout a facility without the need for predefined courses or markers. The rise of AMRs is inextricably tied to the advent of Industry 4.0, a movement towards more automation and digitization in manufacturing and other industries. AGVs and AMRs are now employed to improve efficiency and minimise labour costs in a range of environments, including manufacturing plants, warehouses, hospitals, and retail outlets.

|AGV|AMR|
|---|---|
| ![Modern AGV](https://thumbs.dreamstime.com/b/automated-guided-vehicles-agv-forklift-lifting-carton-modern-warehouse-253424837.jpg) | ![Amazon AMR](https://s.yimg.com/uu/api/res/1.2/Lvtw_mfKscRcPEwX3qKGhw--~B/Zmk9ZmlsbDtoPTU1MTt3PTg3NTthcHBpZD15dGFjaHlvbg--/https://media-mbst-pub-ue1.s3.amazonaws.com/creatr-uploaded-images/2022-06/49559fb0-f226-11ec-95ff-01cdb7299c23.cf.jpg) |

## AGV/AMR Application

|Application|Description|Example|
|---|---|---|
|Warehousing and logistics|  Transporting goods from one location to another, reducing the need for manual labor and increasing efficiency | ![warehousing AGV](https://www.bevindustry.com/ext/resources/issues/2021/08-August/Dist_AGVs_Yale-robotic-reach-truck1170x878.jpg?1627558764) |
|Manufacturing|Used in manufacturing facilities to transport raw materials, finished products, and other supplies | ![Manufacturing AGV](https://www.sme.org/globalassets/sme.org/technologies/articles/2018/06---june/dakkota-201802-222-768x432.jpg) |
|Healthcare| Used in healthcare facilities to transport medical supplies and equipment between different departments | ![Medibot](https://m.economictimes.com/thumb/msid-75123099,width-1200,height-900,resizemode-4,imgsize-796189/engineering-professors-pose-with-the-version-two-prototype-of-the-iium-medibot-medical-robot-at-the-international-islamic-university-malaysia-in-gombak-on-the-outskirts-of-kuala-lumpur-.jpg) |

## AGV/AMR Composition

While AGV's and AMR's are similar in design, there a few differences that is key to their functionality and use case

### Frame

AGV

| Types | Description	| Example |
|--|--|--|
| Tuggers | Automated vehicles that are used to tow other carts or trailers | ![Tugger AGV](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fi.ytimg.com%2Fvi%2FbNxsYJ_zxOs%2Fmaxresdefault.jpg&f=1&nofb=1&ipt=359f2c6d292d749d881449b103ce9a7f4b872aec52cf93d15d2333382de7500b&ipo=images) |
| Automated Guided Carts | Used to transport materials from one location to another, with minimal features | ![AGV](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.ui-akMaPHlZZJI4qPbSpOQHaFi%26pid%3DApi&f=1&ipt=fa50df63ccfd0d7d880572ea5a3575cf23e45306a06e8dcda7f5c2935783bf75&ipo=images) |
| Unit Load | Designed to transport large, heavy loads | ![Unit load](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.agvnetwork.com%2Fimages%2Ftypes-agv%2Funit-load%2Funit_load_agv_with_lifting_table.jpg&f=1&nofb=1&ipt=0f52d26d3035a5839847d6757d1fe363916376a938e83f9dab9041358b585609&ipo=images) |
| Pallet Trucks/Forklifts | designed to move pallets and other loads around | ![Pallet/Forklift AGV](https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fwizurai-indonesia.com%2Fwp-content%2Fuploads%2F2021%2F02%2Ftruck-pallet-AGV.png&f=1&nofb=1&ipt=62d30a20632a8ed680535e5761c5e081816677492b9b41230e42755b152a59d6&ipo=images) |

AMR

| Types | Description	| Example |
|--|--|--|
| Carts | Same as AGV but with no need for any sort of guidance | ![AMR](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fvalutrack.com%2Fwp-content%2Fuploads%2F2023%2F04%2FZebra-Fetch-Robotics-Portfolio.jpg&f=1&nofb=1&ipt=c6db3c5259e03b8a6b95fd065fee23800062b17f9f2010e82bb3f531c0cb7050&ipo=images) |
| Cylinder | Used mainly in service and hospitality as a robot server or waiter | ![waiter robot](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fdeliveryrobot.com.au%2Fwp-content%2Fuploads%2F2021%2F07%2Fp22.jpg&f=1&nofb=1&ipt=6f66742f212e1d8ed85c0ede69ebe5915847297f31d24d947f2e969d9ff7b2f1&ipo=images) |

## Navigation

AGVs often use physically marked roads or routes on the ground or other infrastructure, such as magnetic tape, painted lines, QR code stickers, or laser targets.The AGV follows these routes and relies on optical sensors that detect and correct deviations from the path. Onboard sensors on some AGVs may be used to identify obstructions to prevent collisions. AGVs operate best in well-defined environments with established infrastructure, such as factories, warehouses, and airports. While AMRs are built to operate in dynamic contexts with changing infrastructure. It detects its surroundings and determines its location by using natural landmarks. To identify impediments and avoid crashes, they are outfitted with sensors such as cameras, lidar, and ultrasonic sensors. In its navigation system, AMRs commonly use SLAM (Simultaneous Localization and Mapping) algorithms. The robot gathers sensor data from its surroundings and uses it to create an environment map. Simultaneously, it uses that data to estimate its own position on the map.

| Types of Navigation | Video |
|--|--|
| ![AGV Navigation](https://www.agvnetwork.com/images/technology/navigation-systems/AGV_and_AMR_Navigation_Technology.jpg) | [![Watch the video](https://www.youtube.com/embed/JIYOndxW9hc?wmode=transparent)](https://youtu.be/JIYOndxW9hc) |

## Locomotion

| Types | Description	| Example |
|--|--|--|
| Omni wheel | An Omni wheel is a wheel with freewheel rollers on a plane perpendicular to its axis of rotation. | ![Omniwheel](https://upload.wikimedia.org/wikipedia/commons/e/e3/Triple_Rotacaster_commercial_industrial_omni_wheel.jpg) |
| Mecanum | A wheel with rollers attached to its circumference. These rollers are positioned diagonally or at 45-degree angle. | ![Mecanum wheels](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRiMXCXM81_JfQCC-XKEJDlD2vfwveHCn1BvYZB1x-JVzUz8DwGcoyV9CAtFvZLRQg0_Bs&usqp=CAU) |

