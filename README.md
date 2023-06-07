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

yolov5
https://blog.csdn.net/qq_40691868/article/details/114379061

torch and torchvision torcharduio match
https://blog.csdn.net/qq_40691868/article/details/114379061
https://blog.csdn.net/jorg_zhao/article/details/106883420

https://blog.csdn.net/shiwanghualuo/article/details/122860521

https://blog.csdn.net/weixin_54721509/article/details/122983561  train
1.conda create -n semi-auto python=3.8
2.No module named 'rospkg
pip install rospkg
3.cv_bridge   ImportError: dynamic module does not define module export function (PyInit_cv_bridge_boost)
https://blog.csdn.net/double_ZZZ/article/details/113254903
https://blog.csdn.net/qq_41426807/article/details/125636175
source install/setup.bash --extend
3.error:cannot declare variable 'g_numpyAllocator' to be of abstract type 'NumpyAllocator'
https://zhuanlan.zhihu.com/p/356441425



depth_segment//semi-goal
1.glog be sure v0.4.0 
1.CMake Error: Could not find cmake module file: /home/mic-730ai/glog/build/CMakeFiles/3.10.2/CMakehttps://github.com/google/glogCompiler.cmake
最后发现问题出在project（）里面不能有空格。。。。。。。。
空格删掉最终cmake …成功
2.opencv3 and opencv_contrib
https://blog.csdn.net/qq_40442753/article/details/110464607


