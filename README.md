# Modena Interfaces
ROS 2 interface definitions shared across Modena packages.

This package contains the custom messages, services, and actions used by Modena Robotics software.

It is intended to be used as a common dependency by other Modena ROS 2 packages.

## Features
- Custom ROS 2 messages
- Custom ROS 2 actions

### Current Messages:
- `JogCmd`
- `JogStatus`
- `RobotState`

### Current Actions:
- `MoveJ`
- `MoveL`
- `MoveAbsJ`
- `MoveHome`
- `MoveRest`
- `WaitTime`

## Installation
This package assumes an existing ROS 2 workspace.

Clone the repository into your workspace:

```bash
cd ~/ros2_ws/src
git clone https://github.com/modena-robotics/modena_interfaces.git
```

Build the package:

```bash
cd ~/ros2_ws
colcon build --packages-select modena_interfaces
source install/setup.bash
```

## Used by
- `mr3_mini_driver`
- `modena_teleop`
- `mr3_mini_controller`

## License
This project is licensed under the BSD 3-Clause License.