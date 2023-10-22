
# Robot Patrol Project

This project implements a simple robot patrol algorithm using laser sensors to identify the safest direction to move. The robot will rotate to the most open (safest) area and move in that direction.

![Robot Patrolling](https://github.com/therealnaveenkamal/robot_patrol/assets/80611084/6c3f51bb-299f-4217-99c2-8117ba0654c4)


## Table of Contents

- [Introduction](#introduction)

- [Requirements](#requirements)

- [Installation](#installation)

- [Usage](#usage)

- [Configuration](#configuration)

- [Contributing](#contributing)

- [License](#license)

## Introduction

This project showcases a basic robot patrolling algorithm using laser scans to navigate safely in the environment. The robot will react to obstacles and identify the safest path.

## Requirements

- ROS (Robot Operating System)

- C++ Compiler

- Appropriate Robot Hardware

## Installation

1\. Clone the repository:

   ```
   git clone https://github.com/therealnaveenkamal/robot-patrol.git
   ```

2\. Build the project:

   ```
   cd robot-patrol;
   colcon build
   ```

## Usage

1\. Launch the robot patrol program:

   ```
   ros2 launch robot_patrol start_patrolling.launch.py
   ```

2\. The robot will use laser data to identify the safest direction and patrol accordingly.

3\. You can monitor the robot's behavior in real-time.

## Configuration

You can configure the robot's behavior and parameters by modifying the source code in `patrol.cpp`.

## Contributing

If you'd like to contribute to this project, please follow these guidelines:

1\. Fork the repository.

2\. Create a new branch for your feature: `git checkout -b feature-name`.

3\. Make your changes and commit them: `git commit -m 'Add new feature'`.

4\. Push to the branch: `git push origin feature-name`.

5\. Create a pull request.

We welcome your contributions!

## License

This project was created under the supervision of the team of [The Construct](https://theconstructsim.com/)

## Demonstration Video

Watch the project in action:

https://github.com/therealnaveenkamal/robot_patrol/assets/80611084/557910f7-a641-4fe2-b860-dfb4665e035d
