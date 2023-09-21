# Self-Driving Cars with ROS & Autoware by ApexAI 


## Overview

Self-Driving Cars with ROS and Autoware opensource stack by [Autoware Foundation](https://www.autoware.org/) hosted by [ApexAI](Apex.AI).

The courses are lectured by Autoware foundation members, which includes the following companies and Universities:

- [ADLINK](https://www.adlinktech.com)
- [Apex.AI](https://www.apex.ai/)
- [Autonomous Stuff](https://autonomoustuff.com/)
- [Embotech](http://embotech.com/) 
- [FH Aachen University](https://www.fh-aachen.de/en/) 
- [Graz University of Technology](https://www.tugraz.at/en/home/) 
- [Kalray](http://kalray.eu/) 
- [LG](http://lge.com/) 
- [Open Robotics ](http://openrobotics.org/)
- [Parkopedia](http://parkopedia.com/) 
- [Samsung](https://www.sra.samsung.com/) 
- [StreetScooter](http://streetscooter.com/) 
- [Ternaris](https://ternaris.com/) 
- [Tier IV ](http://tier4.jp/)
- [The Construct](http://www.theconstruct.com)

The course comprises 14 courses with an estimation duration of 14H. 

## Course Contents

- [01 - Development Environment](./01_DevelopmentEnvironment/)
- [02 - ROS2 101](./02_ROS2_101/)
- [03 - ROS Tooling](./03_ROS_Tooling/)
- [04 - Platform](./04_Platform/)
- [05 - Architectures](./05_Architectures/)
- [06 - Autoware 101](./06_Autoware_101/)
- [07 - Object Perception LIDAR](./07_Object_Perception_LIDAR/)
- [08 - Perception Camera](./08_Perception_Camera/)
- [09 - Perception Radar](./09_Perception_Radar/)
- [10 - Localization](./10_Localization/)
- [11 - LGSVL Simulator](./11_LGSVL_Simulator/)
- [12 - Motion Control](./12_Motion_Control/)
- [13 - MARV Data Analytics](./13_MARV_Data_Analytics/)
- [14 - HD Maps](./14_HD_Maps/)

## Requirements

- [KITTI dataset](https://www.cvlibs.net/datasets/kitti/)
- [kitti_ros dataset](https://github.com/AutoLidarPerception/kitti_ros)
- [MARV Robotics - Tool for Large Data Storage, Analysis, Viewing and Testing](https://roscon.ros.org/2016/presentations/MARVRoboticsPangercic.pdf)

## Setup

The entire course resources is over 1GB size, since the Git repository is limited to a maximum of 500 MB, I had to install Git LFS to upload up to 5 GB per file.

This may be interesting either you want to clone or upload the files from a local machine

1. [Install Git LFS](https://docs.github.com/fr/repositories/working-with-files/managing-large-files/installing-git-large-file-storage) on your local machine

```sh
git lfs install
```

2.  Select the file types you'd like Git LFS to manage & track: `.pdf and `.bag` (ROS messages data) 


```sh
git lfs track "*.pdf" "*.bag"
```

```sh
git add .gitattributes
```
3. (Usual) Commit and push to GitHub 

```sh
git add file1.pdf file2.bag
git commit -m "Add new files"
git push origin main
```

## References

- Course hosted by ApexAI
  - https://www.apex.ai/autoware-course
- Course youtube videos: 
  - https://www.youtube.com/playlist?list=PLL57Sz4fhxLpCXgN0lvCF7aHAlRA5FoFr
- Course lectures gitlab: 
  - https://gitlab.com/ApexAI/autowareclass2020/-/tree/master/lectures
- Course Code Sources: 
  - https://gitlab.com/ApexAI/autowareclass2020/-/tree/master
- Issues & Forum: 
  - https://gitlab.com/ApexAI/autowareclass2020/-/issues



