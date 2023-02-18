# Hopper Robot Q-Learning

This project provides a simulation environment for a Hopper robot in Gazebo using ROS Kinetic, as well as Q-Learning algorithms to train the robot to perform various tasks. The project uses the OpenAI Gym package to create a gym environment for the robot simulation and implements Q-Learning algorithms to train the robot to perform various tasks.

## Installation
### ROS Installation
1. Follow the instructions for installing ROS Kinetic from the official ROS website based on your operating system: http://wiki.ros.org/kinetic/Installation
2. Once ROS is installed, set up your ROS environment by sourcing the setup.bash file:
```bash
source /opt/ros/kinetic/setup.bash
```
### Gazebo Installation
1. Install Gazebo using the following command:
```csharp
sudo apt-get install gazebo9
```
2. Install additional dependencies for Gazebo and ROS integration:
```csharp
sudo apt-get install ros-kinetic-gazebo-ros-pkgs ros-kinetic-gazebo-ros-control
```
### Gym Installation
1. Install the OpenAI Gym package using the following command:
```
pip install gym
```
2. Install additional dependencies required for the Hopper Robot Q-Learning project:
```
pip install numpy
```

## Downloading and Running the Project
1. Clone this repository to your local machine:
```bash
git clone https://github.com/shiivashaakeri/Hopper_Robot_QLeaning.git
```

2. Navigate to the root directory of your ROS workspace:
```bash
cd path/to/simulation_ws
```

3. Build your workspace:
```
catkin_make
```

4. Source the setup.bash file for your workspace:
```
source devel/setup.bash
```
5. Launch the main launch file using roslaunch:
```css
roslaunch my_hopper_training main.launch
```

## Usage

Once the simulation is running, you can use the OpenAI Gym interface to interact with the simulation and train the robot using Q-Learning algorithms. The start_training_v2.py file contains the implementation of the Q-Learning algorithm and can be modified to train the robot for different tasks.
## Acknowledgements
- [ROS and Robotics tutorials](https://www.theconstructsim.com)
- [Reinforcement learning environment for developing AI algorithms](https://gym.openai.com)
- [Gazebo Simulator Tutorials with ROS](https://youtube.com/playlist?list=PLK0b4e05LnzbsYJ5WH-S5td2aclJqpDYo)


