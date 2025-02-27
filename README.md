# TurtleBot3 Service Task

## Task
Your task is to create a ROS2 service that controls a TurtleBot3 in simulation. The service should accept an integer argument representing the number of seconds the robot should move forward at a constant speed of **1 m/s**.

### Example:
- If the service is called with the argument `5`, the TurtleBot3 should move forward at **1 m/s** for **5 seconds** before stopping.
- If the service is called with `10`, the robot should move forward for **10 seconds** and then stop.

By completing this task, you will:
- Learn how to launch a TurtleBot3 simulation in a 3D environment.
- Understand how to create a ROS2 service.
- Implement a simple motion control service.

## Prerequisites
To complete this task, you need to install TurtleBot3 and set up ROS2. Follow the installation guides based on your ROS2 version:

- **ROS2 Foxy**: [TurtleBot3 Installation for Foxy](https://emanual.robotis.com/docs/en/platform/turtlebot3/quick-start/#ros-2-foxy)
- **ROS2 Humble**: [TurtleBot3 Installation for Humble](https://emanual.robotis.com/docs/en/platform/turtlebot3/quick-start/#ros-2-humble)
- **ROS2 Jazzy**: [TurtleBot3 Installation for Jazzy](https://emanual.robotis.com/docs/en/platform/turtlebot3/quick-start/#ros-2-jazzy)

## Reference Documentation
- [ROS2 Services](https://docs.ros.org/en/foxy/Tutorials/Services/Creating-A-Simple-Service-And-Client-Py.html)
- [TurtleBot3 Official Documentation](https://emanual.robotis.com/docs/en/platform/turtlebot3/overview/)

## Submission
Once you have completed the task, submit your code as a pull request or share a link to your repository.
