# Mambo Drone - Line Following Algorithm through Image Processing

## Project Overview

The Mambo Drone Line Following Algorithm project leverages robotics and computer vision to enable a Parrot Mambo Fly mini-drone to autonomously follow a designated path using image processing techniques. This project integrates control systems, sensor fusion, localization, mapping, and navigation to achieve precise line-tracking.

## Control Systems

The control system ensures stable and precise flight, encompassing altitude control, orientation control (roll, pitch, and yaw), and line following control, all critical for maintaining the drone's stability and alignment with the path.

## Sensor Fusion and Kalman Filter

Sensor fusion combines data from the drone's accelerometers, gyroscope, barometer, and optical flow sensor using a Kalman filter algorithm. This provides accurate estimations of the drone's state, ensuring stable flight even with external disturbances.

## Navigation Module

The navigation module processes image data from the downward-facing camera to detect the line and calculate control inputs. It uses image processing techniques like edge detection, color thresholding, and contour analysis to keep the drone on track.

## Conclusion

This project demonstrates the integration of control systems, sensor fusion, localization, mapping, and image processing for autonomous navigation. The Mambo Drone showcases precise line-following, highlighting the potential of robotics and computer vision in various industries.


## References
- [Portfolio](https://sbadiga24.github.io/projects/mambo)
- [OpenCV Documentation](https://opencv.org/documentation/)
- [Mambo Drone SDK](https://developer.parrot.com/docs/piloting/mambo.html)
