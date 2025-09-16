# Mobi_robots
## Description
Mobilab robots workspace, containing packages for robotics arms, grippers, and mobile robots.

## ROS 2 info
|Ubuntu|ROS 2 Distro|Gazebo Version|
|:----:|:---------------:|:------------:|
|[24.04](https://ubuntu.com/blog/tag/ubuntu-24-04-lts)|[Jazzy](https://docs.ros.org/en/jazzy/index.html)|[Harmonic](https://gazebosim.org/docs/harmonic/getstarted/)|

## Repository Structure
```tree
mobi_robots/
├── arms/
│   ├── arms/
│   └── grippers/
├── mobile_robots/
└── README.md
```

## Cloning and building
``` bash
mkdir ~/mobi_ws && cd ~/mobi_ws
git clone --recursive https://github.com/MOBILAB-UDESC/mobi_robots.git
rosdep install --from-paths mobi_robots --ignore-src -r -y
colcon build
source install/setup.bash
```

## Robots
### [Arms](https://github.com/MOBILAB-UDESC/arms)
|Robot|Image|Official source|
|:---:|:---:|:-------------:|
|[gen3_lite](https://github.com/MOBILAB-UDESC/arms/tree/main/gen3_lite)|<img src="https://raw.githubusercontent.com/MOBILAB-UDESC/arms/main/gen3_lite/gen3_lite.png" alt="gen3_lite" width="100"/>|[Kinova](https://github.com/Kinovarobotics/ros2_kortex/tree/main)|

### [Grippers](https://github.com/MOBILAB-UDESC/arms/tree/main/grippers)
|Robot|Image|Official source|
|:---:|:---:|:-------------:|
|[kinova_2f_lite](https://github.com/MOBILAB-UDESC/arms/tree/main/gen3_lite)|<img src="https://raw.githubusercontent.com/MOBILAB-UDESC/arms/main/grippers/kinova_2f_lite/kinova_2f_lite.png" alt="kinova_2f_lite" width="150"/>|[Kinova](https://github.com/Kinovarobotics/ros2_kortex/tree/main)|

### [Mobile robots]()
|Robot|Image|Official source|
|:---:|:---:|:-------------:|
|[jackal](https://github.com/MOBILAB-UDESC/mobile_robots/tree/main/jackal)|<img src="https://raw.githubusercontent.com/MOBILAB-UDESC/mobile_robots/main/jackal/jackal.png" alt="jackal" width="150"/>|[Clearpath](https://github.com/jackal)|