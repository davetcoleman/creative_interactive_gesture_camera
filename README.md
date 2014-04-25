creative_interavtice_gesture_camera
===================================

Provides drivers to use creative interactive gesture camera in ROS

## Deps

To use this package in ROS, the DepthSenseSDK for linux needs to be installed. To install a frozen version:

```
roscd creative_interavtice_gesture_camera
sudo sh resources/DepthSenseSDK-1.4.1-1181-amd64-deb.run
```

Or, the latest download can be found here:
http://www.softkinetic.com/fr-be/support/download.aspx?EntryId=517

To download, you will need to create a free account

You will also need to install:
```
sudo apt-get install ros-hydro-libg20 mrpt-libs
```

And:
```
cd ~/catkin_ws/src
git clone git@github.com:RainerKuemmerle/g2o.git
```

## Build