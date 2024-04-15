---
layout: page
title: Sensors
show_sidebar: false
hide_footer: false
hero_height: is-small
# hero_image: /img/team/group/2023_info_day.jpg
gallery: sensors
---



## Data Collection Devices

Relative models and supplementary materials of our platforms and sensor suite are provided in this repository: [[TAIL-Platforms]](https://github.com/TAIL-Robot/TAIL-Platforms/).

### Sensor suit

<!-- To capture visual measurements with different wavelengths, the RGB cameras are placed to form a forward-looking sensor system.

The terrain-looking sensor system uses an RGB-D camera to obtain sufficient ground information.

In addition, LiDAR enables the recognition of the surrounding environment regardless of angle.

Finally, GPS, IMU, and built-in odometry are responsible for the robot's Navigation. -->

<figure>
 <img src="/img/sensorsuit.png" style="width:50%" />
 <figcaption>
Sensors characteristics </figcaption>
</figure>


Each sensor and relative characteristics are represented in this table.
Specially, tail provide the sensor data from wheel(wheel odom, vel, motor rpm and current) and quadruped robots(leg odom, contact and motor status).

<figure>
 <img src="/img/sensors_table.jpg" style="width:50%" />
 <figcaption>
Sensors characteristics </figcaption>
</figure>




### Robots

We utilize wheeled and quadrupedal robots to collect data and set up the compact sensor configuration.
They are rugged enough to traverse through challenging terrains to explore more unstructured areas of an environment. 
<!-- The datset is comprised of video sequences captured from the camera onboard a mobile robot platform. The platform used for data collection is small enough to manuever in cluttered environments, and -->

<figure>
 <img src="/img/travel.jpg" style="width:50%" />
 <figcaption>
Robot platform </figcaption>
</figure>




## Time synchorization

We propose a hardware-synchorizated method for this sensor suite.
<figure>
 <img src="/img/sync.png" style="width:50%" />
 <figcaption>
 Time synchorization
 </figcaption>
</figure>


## Calibration

- Instrinsics of IMU: [Allan Varicance ROS](https://github.com/ori-drs/allan_variance_ros)
- Instrinsics of color cameras: [ROS camera calibration](http://wiki.ros.org/camera_calibration)
- Stereo frame cameras extrinsic: [Stereo camera](https://www.mathworks.com/help/vision/ug/using-the-stereo-camera-calibrator-app.html)
- Camera-IMU extrinsic: [Kalibr](https://github.com/ethz-asl/kalibr)
- Camera-LiDAR extrinsic: [lidar-camera-calibrator](https://www.mathworks.com/help/lidar/ug/get-started-lidar-camera-calibrator.html)
