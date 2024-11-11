# FARMBOT

<p align="center">
  <img src="farmbot.svg" alt="FarmBot" width="200"/>
</p>

Farmbot is a ROS2 package that provides a high-level interface to control a robot in a farm environment. The package is designed to be modular and can be easily extended to support new hardware and sensors. The package is built on top of the ROS2 framework.

When said it is modular, it means that the package is divided into several sub-packages, each of which is responsible for a specific task. For example, the `localisation` package is responsible for localising the robot in the farm environment, the `navigation` package is responsible for navigating the robot in the farm environment, and so on.

The cool thing about this package is that any of the sub-packages can be used independently of the others. For example, if you only want to use the `localisation` package, you can do so without having to use the other packages. And in addition, you can substitute any of the sub-packages with your own implementation or other existing implementations as long as they adhere to the interface defined by the package.