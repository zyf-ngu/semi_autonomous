# semi_autonomous
##Ubuntu中为 GitHub 设置基于 SSH 密钥的身份验证,
https://zhuanlan.zhihu.com/p/377361811
##yolo 
1.conda env semi-auto python=2.7
2.ImportError: No module named em
pip install empy
3.ImportError: No module named yaml
pip install pyyaml
4. error: ‘CV_LOAD_IMAGE_COLOR’ was not declared in this scope
将代码中出现的CV_LOAD_IMAGE_xxxx用对应的flag值代替，同样能解决问题。

   CV_LOAD_IMAGE_UNCHANGED  = -1 ( = cv::IMREAD_UNCHANGED),
   CV_LOAD_IMAGE_GRAYSCALE 	= 0  ( = cv::IMREAD_GRAYSCALE),
   CV_LOAD_IMAGE_COLOR     	= 1  ( = cv::IMREAD_COLOR),
   CV_LOAD_IMAGE_ANYDEPTH   = 2  ( = cv::IMREAD_ANYDEPTH),
   CV_LOAD_IMAGE_ANYCOLOR   = 4
5.Could not find a package configuration file provided by “costmap_converter“ with any of the follow
sudo apt-get install ros-melodic-costmap-converter
6.Could not find a package configuration file provided by "mbf_costmap_core"   with any of the following names
sudo apt-get install ros-melodic-mbf-costmap-core
7.Could not find a package configuration file provided by "mbf_msgs" with any
  of the following names:
8.Could not find libg2o!
sudo apt-get install ros-melodic-libg2o
9.Could not find a package configuration file provided by "catkin_simple"


yolov5_ros
https://github.com/mats-robotics/yolov5_ros

https://blog.csdn.net/weixin_54721509/article/details/122983561  train
1.conda create -n semi-auto python=3.8
2.No module named 'rospkg

