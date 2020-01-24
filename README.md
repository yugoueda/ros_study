# ロボットシステム学 課題2
 16C1019 植田祐伍
 
# 実装内容　
　joyコンで亀を操作する

# 動作環境
  ubuntu 18.04
  ROS melodic 1.14.3　
  
# 必要パッケージ
 ros-melodic-joy
 ros-melodic-joystick-driver
 turtesim
 
#動画

#手順

　$roslaunch basic_lecture turtle.launch
 $rosrun joy joy_node _dev_name:="Sony PLAYSTATION(R)3 Controller"
 $rostopic echo /joy
 
