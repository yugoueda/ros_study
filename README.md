# ロボットシステム学 課題2
 16C1019 植田祐伍
 
# 実装内容　
　joyコンで亀を操作する

# 動作環境
  ubuntu 18.04<br>
  ROS melodic 1.14.3　
  
# 必要パッケージ
 ros-melodic-joy<br>
 ros-melodic-joystick-driver<br>
 turtesim<br>
 
# 動画

# 手順
 $roslaunch basic_lecture turtle.launch<br>
 $rosrun joy joy_node _dev_name:="Sony PLAYSTATION(R)3 Controller"<br>
 $rostopic echo /joy<br>
 
